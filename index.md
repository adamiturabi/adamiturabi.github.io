---
title: "Adami Turabi"
author: "adami.turabi [at] protonmail [dot] com"
output:
  bookdown::gitbook:
    split_by: "none"
    self_contained: yes
    pandoc_args: ["--lua-filter=trn.lua"]
    keep_md: yes
    css: mystyle.css
    config:
      toc:
        collapse: section
        scroll_highlight: yes
        before: null
        after: null
      toolbar:
        position: fixed
      edit : null
      download: null
      search: yes
      fontsettings:
        theme: white
        family: sans
        size: 2
      sharing:
        facebook: yes
        github: no
        twitter: yes
        linkedin: yes
        weibo: no
        instapaper: no
        vk: no
        all: ['facebook', 'twitter', 'linkedin', 'weibo', 'instapaper']
      info: yes
---
[بسم الله الرحمن الرحيم]{.ar}

[الحمد لله والصلاة والسلام على نبينا محمد. أما بعد:]{.ar}

# Articles

+ [Rules for writing hamza in the Arabic script](https://adamiturabi.github.io/hamza-rules/)
+ [Classification of Arabic nouns and their use as qualitative nouns](https://adamiturabi.github.io/noun-class-nahw-wafi/)
+ [Using pandoc lua filters to input and romanize Arabic in Rmarkdown documents](https://adamiturabi.github.io/rmd-arabic-romaniz/)
+ [A consistent romanization scheme for Arabic, Classical Persian, and Urdu](https://adamiturabi.github.io/romanization-scheme/)
+ [A disambiguating diacritical scheme for Classical Persian and Urdu vowels in the Arabic script](https://adamiturabi.github.io/urdu-diacritics/)
+ [Setting up scanned PDFs for printing](https://github.com/adamiturabi/print-scanned-books)
