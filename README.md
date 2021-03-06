labic-parse-facebook
==================

------------------
Purpose:
------------------
This script was created to parse parse the files with statistics generated by Netvizz(https://apps.facebook.com/netvizz/) and exported in the csv format.

------------------
Requirements:
------------------
* Linux;
* Python 3.3;
* Facebook profile with the Netvizz app.

------------------
Usage:
------------------
* Download the files on this page, using the download button on the bar in the right side;
* Using netvizz, choose the option "Page Data";
* Choose the number of posts to export and if by page only or by page and users;
* When Netvizz finishes(may take a long time), download the "tsv stat file" and the "tsv comments file";
* Rename them to "stats.tab" and "comments.tab", respectively;
* Put the files creatd by Netvizz and scripts on the same folder;
* Call the script on a shell in this folder with the command below:

```
python3.3 parse_facebook.py
```

* A "Results" folder will be created with the results.

More detailed instructions, with examples(in portuguese):
http://www.labic.net/blog-2/pesquisa/nar-um-script-para-analisar-a-semantica-e-a-movimentacao-interativa-nas-fanpages-do-facebook/


------------------
Results
------------------
When the script is done running the results will be in the 'RESULTS'. The files created will be in two folders:
COMMENTS and POSTS

------------------
BETA
------------------
This script is in Beta stage, which means it may contain errors or inaccurate results. Feel free(and please do so!) to report any bugs you find. 

