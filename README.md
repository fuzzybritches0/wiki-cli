# wiki-cli

Download all Wikipedia articles (text-only) and use them offline. The compressed multi-stream database with the corresponding compressed index file will be downloaded, first, if missing. The two files will remain compressed. Searched for indexed lists and pages will be stored in cache for faster future access.

```
# Enter search term as the first argument. If more than one entry exists, an indexed list is shown.
$  wiki-cli "Alfred J. Kwak"
0. Alfred J. Kwak
1. Alfred J. Kwak (TV series)
Repeat the last command and choose the entry by index as the second argument. The corresponding page then will be shown.
$ wiki-cli "Alfred J. Kwak" 0
<page>
<title>Alfred J. Kwak</title>
<ns>0</ns>
<id>1027434</id>
<revision>
<id>1229614831</id>
<parentid>1229156578</parentid>
<timestamp>2024-06-17T19:44:39Z</timestamp>
<contributor> ...
```
