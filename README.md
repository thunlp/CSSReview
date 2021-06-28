# Papers in CSS

CSS: Computational Social Science

Contributed by Huimin Chen, Cheng Yang, Xuanming Zhang



## Introduction

Computational Social Science (CSS) is a fast-emerging field, striving to address socical science problems with the assistance of computational methods. This repo contains the list of all relavant papers surveyed in our paper [**From Symbols to Embeddings: A Tale of Two Representations in Computational Social Science**](). Specifically, the structure of this paperlist is organized as three parts: [Table of Content for Text](#contenttext), [Table of Content for Network](#contentnetwork) and [Table of Content for Research Domains](#applications).

Note that we established the paperlist by investigating on more than 400 top-cited articles from 6 representative publications over ten years. These publications include three prestigious multidisciplinary academic journals, namely ***Nature***, ***Science*** and ***PNAS***, and three top conferences in computer science strongly related to CSS, namely ***ACL***, ***WWW*** and ***KDD***.

Corrections and suggestions are welcomed!



## [Table of Content for Text](#contenttext)
<table>
  <tr><td colspan="2"><a href="#symbol-rep-text">1. Symbol-based representation</a></td></tr>
  <tr>
    <td rowspan="3">&emsp;<a href="#symbol-word">1.1 Word</a></td>
    <td><a href="#symbol-word-freq">1.1.1 Frequency-based</a></td>
  </tr>
  <tr>
    <td><a href="#symbol-word-feature">1.1.2 Feature-based</a></td>
  </tr>
  <tr>
    <td><a href="#symbol-word-network">1.1.3 Network-based</a></td>
  </tr>
  <tr>
    <td rowspan="2">&emsp;<a href="#symbol-sentence">1.2 Sentence</a></td>
    <td><a href="#symbol-sent-freq">1.2.1 Frequency-based</a></td>
  </tr>
  <tr>
    <td><a href="#symbol-sent-feature">1.2.2 Feature-based</a></td>
  </tr>
  <tr><td colspan="2"><a href="#emb-rep-text">2. Embedding-based representation</a></td></tr>
  <tr>
    <td>&emsp;<a href="#emb-word">2.1 Word</a></td>
    <td><a href="#emb-word-embedding">2.1.1 Word Embeding-based</a></td>
  </tr>
  <tr>
    <td rowspan="2">&emsp;<a href="#emb-sentence">2.2 Sentence</a></td>
    <td><a href="#emb-sent-topic">2.2.1 Topic Model-based</a></td>
  </tr>
  <tr>
    <td><a href="#emb-sent-neural">2.2.2 Neural-based</a></td>
  </tr>
</table>


## [Table of Content for Network](#contentnetwork)
<table>
  <tr><td colspan="2"><a href="#symbol-rep-network">1. Symbol-based representation</a></td></tr>
  <tr>
    <td rowspan="4">&emsp;<a href="#symbol-node">1.1 Node</a></td>
    <td><a href="#symbol-node-stat">1.1.1 Node & Edge-based Statistics</a></td>
  </tr>
  <tr>
    <td><a href="#symbol-node-centrality">1.1.2 Centrality-based</a></td>
  </tr>
  <tr>
    <td><a href="#symbol-node-index">1.1.3 Designed Index</a></td>
  </tr>
  <tr>
    <td><a href="#symbol-node-prob">1.1.4 Probablistic Model</a></td>
  </tr>
  <tr>
    <td rowspan="2">&emsp;<a href="#symbol-subgraph">1.2 Subgraph</a></td>
    <td><a href="#symbol-subgraph-motif">1.2.1 Motif-based statistics/coefficients/index</a></td>
  </tr>
  <tr>
    <td><a href="#symbol-subgraph-cluster">1.2.2 Cluster-based statistics/coefficients/index</a></td>
  </tr>
  <tr><td colspan="2"><a href="#emb-rep-network">2. Embedding-based representation</a></td></tr>
  <tr>
    <td rowspan="2">&emsp;<a href="#emb-node">2.1 Node & Subgraph</a></td>
    <td><a href="#emb-node-MF">2.1.1 Matrix Factorization</a></td>
  </tr>
  <tr>
    <td><a href="#emb-node-neural">2.1.2 Neural-based</a></td>
  </tr>
</table>


## [Table of Content for Research Domains](#contentapplications)
<table>
  <tr>
    <td><a href="#sociology">1. Sociology</a></td>
    <td><a href="#anthropology">2. Anthropology</a></td>
	</tr>
  <tr>
    <td><a href="#psychology">3. Psychology</a></td>
    <td><a href="#politics">4. Politics</a></td>
	</tr>
  <tr>
    <td><a href="#economics">5. Economics</a></td>
    <td><a href="#linguistics">6. Linguistics</a></td>
	</tr>
  <tr>
    <td><a href="#communication">7. Communication</a></td>
    <td><a href="#geography">8. Geography</a></td>
	</tr>
  <tr>
    <td colspan='2'><a href="#environment">9. Environment</a></td>
	</tr>
</table>


## [Text](#contenttext)
### [Symbol-based representation](#contenttext)
#### [Word](#contenttext)
##### [Frequency-based](#contenttext)

1. **Ontogeny and phylogeny of language.** PNAS 110.16 (2013). [paper](https://www.pnas.org/content/110/16/6324.short)

   *Charles Yang*.

2. **Quantitative analysis of culture using millions of digitized books.** *Science* 331.6014 (2011). [paper](https://science.sciencemag.org/content/331/6014/176.abstract)

   *Jean-Baptiste Michel et al.*

3. **Aspirational pursuit of mates in online dating markets.** *Science Advances* 4.8 (2018). [paper](https://advances.sciencemag.org/content/4/8/eaap9815.short)

   *Elizabeth E Bruch and MEJ Newman.*

4. **What does Congress want from the National Science Foundation? A content analysis of remarks from 1995 to 2018.** Science Advances 6.33 (2020). [paper](https://advances.sciencemag.org/content/6/33/eaaz6300?utm_campaign=SciAdvances&utm_source=Contractor&utm_medium=Twitter)

   *A Lupia, S Soroka, and A Beatty.*

5. **The public and legislative impact of hyperconcentrated topic news.** Science Advances 5.8 (2019). [paper](https://advances.sciencemag.org/content/5/8/eaat8296.abstract)

   *Karthik Sheshadri and Munindar P Singh.*

6. **Diurnal and seasonal mood vary with work, sleep, and daylength across diverse cultures.** Science 333.6051 (2011). [paper](https://science.sciencemag.org/content/333/6051/1878/)

   *Scott A Golder and Michael W Macy.*

7. **Quantifying the relationship between financial news and the stock market.** Scientific Reports 3.1 (2013). [paper](https://www.nature.com/articles/srep03578)

   *Merve Alanyali, Helen Susannah Moat, and Tobias Preis.*

##### [Feature-based](#contenttext)

1. **Human language reveals a universal positivity bias.** PNAS 112.8 (2015). [paper](https://www.pnas.org/content/112/8/2389.short)

   *Peter Sheridan Dodds et al.*

2. **Natural speech reveals the semantic maps that tile human cerebral cortex.** Nature 532.7600 (2016). [paper](https://www.nature.com/articles/nature17637?affid=143731&device=desktop&os=Unknown%20OS&browser=Safari)

   *Alexander G Huth et al.*

##### [Network-based](#contenttext)

1. **Bots increase exposure to negative and inflammatory content in online social systems.** PNAS 115.49 (2018). [paper](https://www.pnas.org/content/115/49/12435.short)

   *Massimo Stella, Emilio Ferrara, and Manlio De Domenico.*

2. **Algorithms in the historical emergence of word senses.** PNAS 115.10 (2018). [paper](https://www.pnas.org/content/115/10/2323.short)

   *Christian Ramiro et al.*

3. **Emotion semantics show both cultural variation and universal structure.** Science 366.6472 (2019). [paper](https://science.sciencemag.org/content/366/6472/1517.abstract)

   *Joshua Conrad Jackson et al.*

4. **Lexical shifts, substantive changes, and continuity in State of the Union discourse, 1790–2014.** PNAS 112.35 (2015). [paper](https://www.pnas.org/content/112/35/10837.short)

   *Alix Rule, Jean-Philippe Cointet, and Peter S Bearman.*

5. **Validation of Twitter opinion trends with national polling aggregates: Hillary Clinton vs Donald Trump.** Scientific Reports 8.1 (2018). [paper](https://www.nature.com/articles/s41598-018-26951-y)

   *Alexandre Bovet, Flaviano Morone, and Herna ́n A Makse.*

   

#### [Sentence](#contenttext)
##### [Frequency-based](#contenttext)

1. **Patterns of text reuse in a scientific corpus.** PNAS 112.1 (2015). [paper](https://www.pnas.org/content/112/1/25.short)

   *Daniel T Citron and Paul Ginsparg.*

2. **Facebook language predicts depression in medical records.** PNAS 115.44 (2018). [paper](https://www.pnas.org/content/115/44/11203?utm_source=yxnews&utm_medium=mobile)

   *Johannes C Eichstaedt et al.*

3. **Elusive consensus: Polarization in elite communication on the COVID-19 pandemic.** Science Advances 6.28 (2020). [paper](https://advances.sciencemag.org/content/6/28/eabc2717.abstract)

   *Jon Green et al.*

4. **Exposure to ideologically diverse news and opinion on Facebook.** Science 348.6239 (2015). [paper](https://science.sciencemag.org/content/348/6239/1130.abstract)

   *Eytan Bakshy, Solomon Messing, and Lada A Adamic.*

5. **Word lengths are optimized for efficient communication.** PNAS 108.9 (2011). [paper](https://www.pnas.org/content/108/9/3526.short)

   *Steven T Piantadosi, Harry Tily, and Edward Gibson.*

##### [Feature-based](#contenttext)

1. **Large-scale evidence of dependency length minimization in 37 languages.** PNAS 112.33 (2015). [paper](https://www.pnas.org/content/112/33/10336.short)

   *Richard Futrell, Kyle Mahowald, and Edward Gibson.*

2. **Examining long-term trends in politics and culture through language of political leaders and cultural institutions.** PNAS 116.9 (2019). [paper](https://www.pnas.org/content/116/9/3476.short)

   *Kayla N Jordan et al.*

3. **Happiness and the patterns of life: A study of geolocated tweets.** *Scientific Reports* 3.1 (2013). [paper](https://www.nature.com/articles/srep02625)

   *Morgan R Frank et al.*

4. **Rapid assessment of disaster damage using social media activity.** *Science Advances* 2.3 (2016). [paper](https://advances.sciencemag.org/content/2/3/e1500779.short)

   *Yury Kryvasheyeu et al.*

5. **The civilizing process in London’s Old Bailey.** PNAS 111.26 (2014). [paper](https://www.pnas.org/content/111/26/9419.short)

   *Sara Klingenstein, Tim Hitchcock, and Simon DeDeo.*

6. **The incidence and role of negative citations in science.** PNAS 112.45 (2015). [paper](https://www.pnas.org/content/112/45/13823.short)

   *Christian Catalini, Nicola Lacetera, and Alexander Oettl.*

7. **The narrative arc: Revealing core narrative structures through text analysis.** *Science Advances* 6.32 (2020). [paper](https://advances.sciencemag.org/content/6/32/eaba2196.abstract)

   *Ryan L Boyd, Kate G Blackburn, and James W Pennebaker.*

8. **Quantitative patterns of stylistic influence in the evolution of literature.** PNAS 109.20 (2012). [paper](https://www.pnas.org/content/109/20/7682.short)

   *James M Hughes et al.*

9. **Experimental evidence of massive-scale emotional contagion through social networks.** PNAS 111.24 (2014). [paper](https://www.pnas.org/content/111/24/8788.short)

   *Adam DI Kramer, Jamie E Guillory, and Jeffrey T Hancock.*

10. **Emotion shapes the diffusion of moralized content in social networks. ** PNAS 114.28 (2017). [paper](https://www.pnas.org/content/114/28/7313.short)

    *William J Brady et al.*

11. **Distress and rumor exposure on social media during a campus lockdown.** PNAS 114.44 (2017). [paper](https://www.pnas.org/content/114/44/11663?tab=related&utm_source=TrendMD&utm_medium=cpc&utm_campaign=Proc_Natl_Acad_Sci_U_S_A_TrendMD_0)

    Nickolas M Jones et al.

12. **Bots increase exposure to negative and inflammatory content in online social systems.** PNAS 115.49 (2018). [paper](https://www.pnas.org/content/115/49/12435.short)

    *Massimo Stella, Emilio Ferrara, and Manlio De Domenico.*

13. **Echo chambers: Emotional contagion and group polarization on facebook.** *Scientific Reports* 6.1 (2016). [paper](https://www.nature.com/articles/srep37825)

    *Michela Del Vicario et al.*

14. **Validation of Twitter opinion trends with national polling aggregates: Hillary Clinton vs Donald Trump.** Scientific Reports 8.1 (2018). [paper](https://www.nature.com/articles/s41598-018-26951-y)

    *Alexandre Bovet, Flaviano Morone, and Herna ́n A Makse.*

15. **Content-based features predict social media influence operations.** *Science Advances* 6.30 (2020). [paper](https://advances.sciencemag.org/content/6/30/eabb5824?utm_source=TrendMD&utm_medium=cpc&utm_campaign=TrendMD_1)

    *Meysam Alizadeh et al.*

16. **What does Congress want from the National Science Foundation? A content analysis of remarks from 1995 to 2018.** Science Advances 6.33 (2020). [paper][https://advances.sciencemag.org/content/6/33/eaaz6300?utm_campaign=SciAdvances&utm_source=Contractor&utm_medium=Twitter]

    *A Lupia, S Soroka, and A Beatty.*

    

### [Embedding-based representation](#contenttext)
#### [Word](#contenttext)
##### [Word Embedding-based](#contenttext)

1. **Word embeddings quantify 100 years of gender and ethnic stereotypes. ** PNAS 115.16 (2018). [paper][https://www.pnas.org/content/115/16/E3635.short]

   *Nikhil Garg et al.*

2. **Semantics derived automatically from language corpora contain human-like biases. ** *Science* 356.6334 (2017). [paper][https://science.sciencemag.org/content/356/6334/183.abstract]

   *Aylin Caliskan, Joanna J Bryson, and Arvind Narayanan.*

3. **Parents mention sons more often than daughters on social media. ** PNAS 116.6 (2019). [paper](https://www.pnas.org/content/116/6/2039.short)

   *Elizaveta Sivak and Ivan Smirnov.*

   

#### [Sentence](#contenttext)
##### [Topic Model-based](#contenttext)

1. **Measuring discursive influence across scholarship. ** PNAS 115.13 (2018). [paper][https://www.pnas.org/content/115/13/3308.short]

   *Aaron Gerow et al.*

2. **What does Congress want from the National Science Foundation? A content analysis of remarks from 1995 to 2018.** Science Advances 6.33 (2020). [paper](https://advances.sciencemag.org/content/6/33/eaaz6300?utm_campaign=SciAdvances&utm_source=Contractor&utm_medium=Twitter)

   *A Lupia, S Soroka, and A Beatty.*

3. **Race, religion and the city: twitter word frequency patterns reveal dominant demographic dimensions in the United States.** *Palgrave Communications* 2.1 (2016). [paper][https://www.nature.com/articles/palcomms201610]

   *Eszter Boka ́nyi et al.*

4. **Network structure and influence of the climate change counter-movement.** *Nature Climate Change* 6.4 (2016). [paper][https://www.nature.com/articles/nclimate2875]

   *Justin Farrell.*

5. **Predicting the birth of a spoken word. ** PNAS 112.41 (2015). [paper][https://www.pnas.org/content/112/41/12663.short]

   *Brandon C Roy et al.*

6. **Quantifying the semantics of search behavior before stock market moves. ** PNAS 111.32 (2014). [paper][https://www.pnas.org/content/111/32/11600.short]

   *C. Curme et al.*

7. **Corporate funding and ideological polarization about climate change. ** PNAS 113.1 (2016). [paper][https://www.pnas.org/content/113/1/92.short]

   Justin Farrell.

8. **Estimating geographic subjective well-being from Twitter: A comparison of dictionary and data-driven language methods. ** PNAS 117.19 (2020). [paper][https://www.pnas.org/content/117/19/10165.short]

   *Kokil Jaidka et al.*

9. **Facebook language predicts depression in medical records.** PNAS 115.44 (2018). [paper](https://www.pnas.org/content/115/44/11203?utm_source=yxnews&utm_medium=mobile)

   *Johannes C Eichstaedt et al.*

##### [Neural-based](#contenttext)

1. **The public and legislative impact of hyperconcentrated topic news.** Science Advances 5.8 (2019). [paper](https://advances.sciencemag.org/content/5/8/eaat8296.abstract)

   *Karthik Sheshadri and Munindar P Singh.*

2. **Restoration of fragmentary Babylonian texts using recurrent neural networks. ** PNAS 117.37 (2020). [paper][https://www.pnas.org/content/117/37/22743.short]

   *Ethan Fetaya et al.*

3. **Universals of word order reflect optimization of grammars for efficient communication. ** PNAS 117.5 (2020). [paper][https://www.pnas.org/content/117/5/2347.short]

   *Michael Hahn, Dan Jurafsky, and Richard Futrell.*

4. **Moralization in social networks and the emergence of violence during protests.** *Nature Human Behaviour* 2.6 (2018). [paper][https://www.nature.com/articles/s41562-018-0353-0]

   *Marlon Mooijman et al.*



## [Network](#contentnetwork)
### [Symbol-based representation](#contentnetwork)
#### [Node](#contentnetwork)
##### [Node & Edge-based Statistics](#contentnetwork)
##### [Centrality-based](#contentnetwork)
##### [Designed Index](#contentnetwork)
##### [Probablitic Model](#contentnetwork)
#### [Subgraph](#contentnetwork)
##### [Motif-based statistics/coefficients/index](#contentnetwork)
##### [Cluster-based statistics/coefficients/index](#contentnetwork)
### [Embedding-based representation](#contentnetwork)
#### [Node & Subgraph](#contentnetwork)
##### [Matrix Factorization](#contentnetwork)
##### [Neural-based](#contentnetwork)



## [Applications](#contentapplications)
### [Sociology](#contentapplications)
### [Anthropology](#contentapplications)
### [Psychology](#contentapplications)
### [Politics](#contentapplications)
### [Economics](#contentapplications)
### [Linguistics](#contentapplications)
### [Communication](#contentapplications)
### [Geography](#contentapplications)
### [Environment](#contentapplications)
