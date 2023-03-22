# IR Systems based on Indri 5.18
In this project, I used the toolkit of Indri Project to build a retrieval system and implemented several different retrieval methods, including Okapi TF-IDF, maximum likelihood estimates with Laplace smoothing only, Jelinek-Mercer smoothing, and some of my ideas to improve one of the above three IR models. I ran all four retrieval models and then evaluate them. After all of these, I will make an analysis of the advantage and disadvantage of all these four retrieval models.

# Guide

* Download the Indri 5.18 (https://www.lemurproject.org/indri.php#download) and be sure to install gcc@6 first, then configure and make it.
* Prepare your corpus (Here I'm using TREC Web Corpus : WT10g.). 
* Put the corpus folder and indri folder in the same layer of main folder.
* Command `./main/run.sh` will help you build and index and evaluation result.
