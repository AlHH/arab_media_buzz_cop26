# arab_media_buzz_cop26
## Data related to a corpus of Arabic articles on climate change and energy transition, collected via BuzzSumo 2021-10-07 to 2021-12-06

### Background

This repository gives access to data used for an article investigating which themes and perspectives regarding climate change and the green shift caught the greatest attention among Arabic-speaking social media users around the 26th Conference of the Parties (COP26) to the United Nations Framework Convention on Climate Change held in Glasgow, Scotland from October 31st to November 12th, 2021.

A corpus of media reports was created covering a two-month period from October 7 to December 6, 2021 — that is, roughly the three weeks leading up to COP26, the two weeks of the conference, and the three weeks after. This timeframe ensured the capture of potential pre-conference anticipation and post-conference stock-taking.

### Collection Method

The research utilized BuzzSumo.com, a web-based media monitoring tool that claims to offer “the world’s largest index of social engagement data,” to identify the most shared articles in Arabic on topics related to climate change and the green shift. Arabic search terms were used to ensure a focus on content produced by and targeted at Arab audiences. BuzzSumo collects data from major social networks; for this research, Facebook and Twitter were the most relevant. The tool allows searching for web content using keywords, domains, hashtags etc. and provides various statistics and features related to the content. For this study, automated daily queries were run for the two months, October 7 – December 6, 2021, using the following Arabic search terms:

تغير المناخ (climate change), الاحتباس الحراري (global warming), الاحترار OR احترار (global warming), التحول الأخضر (green shift), الطاقة المتجددة (renewable energy), COP26 [in Arabic text], مياه OR المياه OR الماء (water).

‘Water’ was included since access to sufficient and clean water has consistently been shown to be the main environmental concern in the region.

The daily queries run over the study period returned 10 top links per day and search term (if any), i.e. links to web content featuring the search term, and the number of shares, likes, or comments (‘engagement’) on social media platforms for each of these. A total of 2471 links were thus collected and imported into a spreadsheet. Most of these pointed to articles published by online newspapers and television news sites.

### Selection

In a second step, all articles that elicited at least 1,000 shares or ‘engagements’ on a given day were selected, as an indicator of their popularity and influence. After weeding out duplicates and false positives, a total of 168 articles were thus obtained to constitute the corpus to be analysed in detail. All these were manually downloaded and transferred to a full-text database for further analysis.

### Structure

The repository contains a comma-separated file (BuzzSumo_Arab_Climate_Buzz_COP26_Over1000.csv) giving BuzzSumo’s engagement index, the headline and full text of the article, summary notes, the type of source where the article was published, and an automatic translation by Google Translate (or in some cases, the English original where the Arabic was a translation of that). Note that Google’s translations have not been quality-checked; they are provided only as a help to those who do not read Arabic.

### CC-BY-NC-SA 4.0 license

The file(s) in this repository are made available under the CC-BY-NC-SA 4.0 license (Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International).

This license requires that reusers give credit to the creator (‘me’). It allows reusers to distribute, remix, adapt, and build upon the material in any medium or format, for noncommercial purposes only. If others modify or adapt the material, they must license the modified material under identical terms.

- ![](https://chooser-beta.creativecommons.org/img/cc-by.21b728bb.svg)**BY:** Credit must be given to me, the creator.
- ![](https://chooser-beta.creativecommons.org/img/cc-nc.218f18fc.svg)**NC:** Only noncommercial use of your work is permitted. Noncommercial means not primarily intended for or directed towards commercial advantage or monetary compensation.
- ![](https://chooser-beta.creativecommons.org/img/cc-sa.d1572b71.svg)**SA:** Adaptations must be shared under the same terms.

See the full license deed [here](https://github.com/AlHH/arab_media_buzz_cop26/raw/main/LICENSE.md).
