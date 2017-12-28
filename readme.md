## Political Data Science

I 2008 lancerede Google sin service Google Flu Trends, der gjorde Google i stand til at forudsige influenza-udbrud flere uger før nationale sundhedsmyndigheder var i stand til at identificere samme udbrud. Google Flu Trends er et eksempel på, hvordan data science kan bruges til at få værdifulde indsigter fra data, der kan danne baggrund for politisk handling.  

Data science er en videnskab såvel som en kunst, hvor formålet er at ekstrahere viden og indsigter fra data. Processen består både i at hente, transformere, visualisere og analysere data – ofte med redskaber, som ikke indgår i den almindelige politologiske værktøjskasse. Formålet med kurset er at klæde de studerende på til selv at give sig i kast med nogle af de metoder og værktøjer, som er nybrud i politologien, fx i forbindelse med et speciale. 

Centrale emner i kurset vil være: 
1. 	Hente data: Skaffe data fra alsidige datakilder såsom med scraping og API’er
2.	Præ-processering: Gøre data tidy og klar til analyse ved transformation af data
3.	Visualisering: Præsentere data på en intuitiv og appetitvækkende facon
4.	Statistisk læring: Klassificere og forudsige om data ved brug af især superviseret maskinlæring, såsom Random Forest og Gradient Boosted Trees

Kurset vil indeholde en blanding af teori og redskaber, og den tekniske del af kurset vil foregå i R. 

Teorien vil blandt andet omfatte forskelle mellem kausalestimation og prædiktion, centrale koncepter i maskinlæring samt refleksioner om data science, herunder hvorfor Google har valgt at nedlægge Google Flu Trends. En del af eksemplerne i kurset vil tage udgangspunkt i mit eget speciale, hvor jeg anvendte maskinlæring til at forudsige og målrette tiltag imod uddannelsesfrafald på Professionshøjskolen Metropol. 

Redskaberne i kurset vil blandt andet være centrale R-pakker såsom dplyr, ggplot2 og magrittr. I kurset stiftes også bekendtskab med at hente data ved at benytte API’er.   

Kurset kan både stå alene og supplere kurset *Videregående kvantitative metoder i studiet af politisk adfærd*.


## Lektionsplan

*Her følger en tentativ lektionsplan.*

Nr    	|	Indhold													|	Litteratur 																	| DataCamp 																		 								| Supplerende |
--------|-----------------------------------------------------------|-------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|-------------|
1		|	Intro til kurset og R									|  	[Leeper (2016)](https://github.com/leeper/Rcourse/raw/gh-pages/Intro2R/Intro2R.pdf), </br> [R4DS: kap 1](http://r4ds.had.co.nz/introduction.html), </br>  [Healy (2017): kap 1-3](http://plain-text.co/plain-person-text.pdf) | [Introduction to R](https://www.datacamp.com/courses/free-introduction-to-r) | [Imai (2016): kap 1](http://assets.press.princeton.edu/chapters/s11025.pdf), </br>  [CS: RStudio IDE](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf), </br>  [CS: Base R](http://github.com/rstudio/cheatsheets/raw/master/base-r.pdf)
2		|	R workshop I: </br> Explore								|	[R4DS: kap 2-6](http://r4ds.had.co.nz/explore-intro.html), </br>  [CS: Transformation](https://github.com/rstudio/cheatsheets/raw/master/data-transformation.pdf) | [Introduction to the Tidyverse](https://www.datacamp.com/courses/introduction-to-the-tidyverse) | [Zhang (2017)](https://github.com/underthecurve/r-data-cleaning-tricks/raw/master/R-datacleaning-tricks.pdf), </br>  [Wickham (2014)](https://www.jstatsoft.org/article/view/v059i10/v59i10.pdf), </br>  [Risdal (2016)](https://www.kaggle.com/mrisdal/exploring-survival-on-the-titanic)
3		|	R workshop II: </br> Import, tidy, transform			|	[R4DS: kap 9-13](http://r4ds.had.co.nz/wrangle-intro.html), </br>  [CS: Data import](https://github.com/rstudio/cheatsheets/raw/master/data-import.pdf) | [Cleaning Data in R](https://www.datacamp.com/courses/cleaning-data-in-r), </br>  [Data Manipulation in R with dplyr](https://www.datacamp.com/courses/dplyr-data-manipulation-r-tutorial), </br>  [Joining Data in R with dplyr](https://www.datacamp.com/courses/joining-data-in-r-with-dplyr) | [R4DS: kap 14-16](http://r4ds.had.co.nz/strings.html), </br>  [Spachtholz (2017)](https://www.kaggle.com/philippsp/exploratory-analysis-zillow)
4		|	R workshop III:	</br> Programmering & Git				| 	[R4DS: kap 17-19](http://r4ds.had.co.nz/program-intro.html), </br> [van Strien (2016)](https://programminghistorian.org/lessons/getting-started-with-github-desktop) | [Intermediate R](https://www.datacamp.com/courses/intermediate-r) | [R4DS: kap 20-21](http://r4ds.had.co.nz/vectors.html), </br> [CS: Apply](https://github.com/rstudio/cheatsheets/raw/master/purrr.pdf), </br> [CS: Advanced R](https://www.rstudio.com/resources/cheatsheets/)
5		|	Web scraping & API										|	[]
6		|	Tekst som data											|	[Grimmer & Stewart (2013](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/F7AAC8B2909441603FEB25C156448F20/S1047198700013401a.pdf/text_as_data_the_promise_and_pitfalls_of_automatic_content_analysis_methods_for_political_texts.pdf), </br> [R4DS: kap 14](http://r4ds.had.co.nz/strings.html), </br> [Wickham (2010)](https://journal.r-project.org/archive/2010-2/RJournal_2010-2_Wickham.pdf), </br> [TRinker's R blog (2013)](https://trinkerrstuff.wordpress.com/2013/09/15/paste-paste0-and-sprintf-2/), </br> [CS: Strings](https://github.com/rstudio/cheatsheets/raw/master/strings.pdf) | [Sentiment Analysis in R: The Tidy Way](https://www.datacamp.com/courses/sentiment-analysis-in-r-the-tidy-way) | [King et al. (2013)](https://gking.harvard.edu/files/censored.pdf), </br> [Benoit & Nulty (2016)](https://cran.r-project.org/web/packages/quanteda/vignettes/quickstart.html), </br> [CS: quanteda](https://github.com/rstudio/cheatsheets/raw/master/quanteda.pdf)
7		|	Visualisering											|	[R4DS: kap 3](http://r4ds.had.co.nz/data-visualisation.html), </br> [DVSS: "Before you begin"](http://socviz.co/index.html#install), </br> [DVSS: kap 3 + 8](http://socviz.co/makeplot.html#makeplot), </br> [CS: Visualisation](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf) | [Data Visualization in R](https://www.datacamp.com/courses/data-visualization-in-r) | [FiveThirtyEight (2016)](http://fivethirtyeight.com/features/how-we-charted-trumps-fall-from-grace-in-hip-hop), </br> [DVSS: kap 2](http://socviz.co/lookatdata.html#lookatdata), </br> [Schwabish (2014)](http://pubs.aeaweb.org/doi/pdfplus/10.1257/jep.28.1.209)
8		|	GIS & spatiale data										|	[] | 
9		|	Estimation & prædiktion									|	[ISL: kap 1](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Seventh%20Printing.pdf), </br> [ISL: kap 2 afs 2.1-2.2](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Seventh%20Printing.pdf), </br> [Bach & Svejgaard (2017): kap 1 afs 1.2, kap 3 afs 3.1-3.2](https://drive.google.com/file/d/1vWEeoSFuKMLg-KRnD88AZdUk_bn5Cmoi/view?usp=sharing), </br> [Varian (2014)](http://pubs.aeaweb.org/doi/pdfplus/10.1257/jep.28.2.3), </br> [Hofman et al. (2017)](http://science.sciencemag.org/content/sci/355/6324/486.full.pdf), </br> [Kleinberg et al. (2015)](https://www.cs.cornell.edu/home/kleinber/aer15-prediction.pdf) | [Supervised Learning in R: Classification](https://www.datacamp.com/courses/supervised-learning-in-r-classification) | [Mullainathan & Spiess (2017)](http://pubs.aeaweb.org/doi/pdfplus/10.1257/jep.31.2.87), </br> [Choi & Varian (2009)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.549.7927&rep=rep1&type=pdf), </br> [Breiman et al. (2001)](https://projecteuclid.org/download/pdf_1/euclid.ss/1009213726)
10		|	Superviseret læring I 									|	
11		|	Superviseret læring II									|
12		|	Usuperviseret læring									|
13		|	Refleksioner data science								|
14		|	Opsamling og eksamen									|







## Undervisningsmateriale
Kursets litteratur vil hovedsageligt bestå af kapitler fra lærebøger samt artikler. Særligt vil følgende to lærebøger stå centralt: 

- James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). *An introduction to statistical learning* (Vol. 112). New York: Springer.
- Wickam, Hadley & Grolemund, Garrett (2016). *R for Data Science*. O’Reilly Media. 

En del af litteraturen vil desuden udgøres af dokumentationen for anvendte pakker i R mv. 

Kursusmaterialet vil desuden bestå af online-ressourcer fra [DataCamp](https://www.datacamp.com). 






### Obligatorisk litteratur



### Supplerende pensum 

#### Litteratur 
- Risdal, M. (2016). *Exploring the Titanic Dataset*. Kaggle. [Link](https://www.kaggle.com/mrisdal/exploring-survival-on-the-titanic). 


### Kurser på DataCamp
#### Anbefalede kurser
- [Introduction to R&ast;](https://www.datacamp.com/courses/free-introduction-to-r) 
- [Introduction to the Tidyverse](https://www.datacamp.com/courses/introduction-to-the-tidyverse) 
- [Cleaning data in R&ast;](https://www.datacamp.com/courses/cleaning-data-in-r)
- [Data Manipulation in R with dplyr&ast;](https://www.datacamp.com/courses/dplyr-data-manipulation-r-tutorial)
- [Joining Data in R with dplyr&ast;](https://www.datacamp.com/courses/joining-data-in-r-with-dplyr) 
- [Intermediate R&ast;](https://www.datacamp.com/courses/intermediate-r)
-
- [Sentiment Analysis in R: The Tidy Way](https://www.datacamp.com/courses/sentiment-analysis-in-r-the-tidy-way) 
- [Data Visualization in R](https://www.datacamp.com/courses/data-visualization-in-r)
-
- [Supervised Learning in R: Classification](https://www.datacamp.com/courses/supervised-learning-in-r-classification) 
- [Supervised Learning in R: Regression](https://www.datacamp.com/courses/supervised-learning-in-r-regression)
- [Machine Learning Toolbox&ast;](https://www.datacamp.com/courses/machine-learning-toolbox)
- [Unsupervised Learning in R&ast;](https://www.datacamp.com/courses/unsupervised-learning-in-r)
- 
- [Exploratory Data Analysis&ast;](https://www.datacamp.com/courses/exploratory-data-analysis)




#### Supplerende kurser
- [Importing data in R (part 1)&ast;](https://www.datacamp.com/courses/importing-data-in-r-part-1)
- [Importing data in R (part 2)](https://www.datacamp.com/courses/importing-data-in-r-part-2)
- [Introduction to Git for Data Science](https://www.datacamp.com/courses/introduction-to-git-for-data-science)
- [Intermediate R - practice](https://www.datacamp.com/courses/intermediate-r-practice)
- [Writing functions in R](https://www.datacamp.com/courses/writing-functions-in-r)
- [Text Mining: Bag of Words](https://www.datacamp.com/courses/intro-to-text-mining-bag-of-words)
- [String Manipulation in R with stringr](https://www.datacamp.com/courses/string-manipulation-in-r-with-stringr)
- [Data Visualization with ggplot2 (part 1)](https://www.datacamp.com/courses/data-visualization-with-ggplot2-1)
- [Data Visualization with ggplot2 (part 2)](https://www.datacamp.com/courses/data-visualization-with-ggplot2-2)
- [Data Visualization with ggplot2 (part 3)](https://www.datacamp.com/courses/data-visualization-with-ggplot2-part-3)


&ast; kurserne markeret med stjerne udgør de 23 kurser i DataCamp's eget career track "Data Scientist with R"



<!-- 


	RESTERENDE LITTERATUR:

	- Huang, D. & Gonzalez, I. (2017). Software Carpentry: Version Control with Git. https://swcarpentry.github.io/git-novice/





--> 



## Målbeskrivelse
Kursets målsætning er at klæde den studerende på til at kunne: 

- Håndtere og transformere data i R
- Forklare væsensforskellene mellem kausalestimation og prædiktion
- Forklare centrale maskinlæringskoncepter 
- Formulere og designe et prædiktionsproblem 
- Anvende fagets metoder på et selvvalgt emne


## Anbefalede faglige forudsætninger
Det forudsættes, at man har gennemført de obligatoriske metodekurser på bacheloruddannelsen i statskundskab, eller tilsvarende. 

Det er ikke en forudsætning at have kendskab til R i forvejen, men det er en forudsætning at have mod på at arbejde i R. 


## Fagets underviser

Faget undervises af cand.scient.pol Jesper Svejgaard Jensen. 


## Undervisningsform
Undervisningen består af holdundervisning, hvor pensum bliver gennemgået. Indholdet i undervisningen vil både blive formidlet med slides samt eksempler i R. 


## Tilmelding
Sker via selvbetjeningen på KUnet. 


## Eksamen

Point
- 7,5 ECTS

Prøveform
- Eksamen består af en selvstændig seminaropgave i form af en kvantitativ analyse af data. Opgaven kan være en ny problemstilling eller et replikationsstudium med afsæt i et eksisterende studium. <!-- Inspiration til data kan findes i [dette datasæt](https://github.com/erikgahner/PolData) over politologiske datasæt. -->

Krav til indstilling til eksamen
- En betingelse for at bestå seminarer er, at den studerende har deltaget aktivt i seminaret, dels gennem tilstedeværelse i minimum 75% af undervisningen og dels gennem aktiv deltagelse

Bedømmelsesform og censur
- Opgaven bedømmes på 7-trinsskalaen uden ekstern censur 


## Kriterier for bedømmelse

Karakter | Beskrivelse 
----- | --------------------
12 | Karakteren 12 gives for den fremragende præstation, dvs. hvor den studerende med ingen eller få og uvæsentlige mangler og på selvstændig og overbevisende måde er i stand til at indfri målbeskrivelsen for udbuddet.
07 | Karakteren 7 gives for den gode præstation, dvs. hvor den studerende, om end med adskillige mangler, på sikker vis er i stand til at indfri målbeskrivelsen for udbuddet.
02 | Karakteren 02 gives for den tilstrækkelige præstation, dvs. den minimalt acceptable præstation, hvor den studerende kun usikkert, mangelfuldt og/​​eller uselvstændigt er i stand til at indfri målbeskrivelsen for udbuddet.


## Arbejdsbelastning
28 timers holdundervisning.  
















