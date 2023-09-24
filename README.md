projekt_3.py: třetí projekt do Engeto Online Python Akademie autor: Adéla Pečená email: adela.pecena@email.cz discord: Adéla Pečená#5431

""" projekt_3.py: třetí projekt do Engeto Online Python Akademie 
author: Adéla Pečená 
email: adela.pecena@email.cz 
discord: Adéla Pečená#5431 """

Tento projekt Vám umožní scrapovat výsledky voleb Českého parlamentu z roku 2017. Zdrojovou adresu URL tohoto projektu naleznete zde: https://volby.cz/pls/ps2017nss/ps3?xjazyk=CZ

Knihovny:
List knihoven třetích stran které jsou potřeba k provozu tohoto projektu najdete ve složce "requirements.txt"

Spuštění projektu "Elections Scraper":
Ke spuštění projektu Elections Scraper (main.py) budete potřebovat dva argumenty:

URL požadované obce ("Výběr okrsku")
Název souboru;
Výsledky budou staženy a uloženy do souboru .csv

Příklad:
Elections Scraper Vám získá výsledky voleb z kraje Příbram

První argument: https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=2&xnumnuts=2111
Druhý argument: pribram_vysledky
The program will notify you once the process is finished:

Process is now done!

Your file pribram_vysledky.csv is ready for checking.

Thank you for using the Elections Scraper app!

Příklad exportu:

ID	Name	Registered voters	Envelopes	Valid Votes	Občanská demokratická strana	Řád národa - Vlastenecká unie	CESTA ODPOVĚDNÉ SPOLEČNOSTI	Česká str.sociálně demokrat.	Radostné Česko
									
529672	Bezděkov pod Třemšínem	134	105	103	12	0	0	10	0
									
564559	Bohostice	167	108	108	12	0	0	9	0
									
539953	Bohutín	1 417	925	920	93	1	2	50	0
									
539970	Borotice	302	202	202	18	1	0	20	0
									
539988	Bratkovice	252	167	166	29	0	0	11	0
									
540013	Březnice	2 841	1 612	1 605	142	1	0	157	5
									
540021	Buková u Příbramě	283	206	206	22	0	0	0
