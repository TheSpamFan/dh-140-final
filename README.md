# dh-140-final
Digital Humanities 140 Final Project 

**Project Overview**    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In the genres of hip-hop and rap, Eminem is a rapper whose clever and technical delivery of provocative lyrics has made him famous among the general public. While his lyrical skills are undisputed, it is the raw emotions contained within that truly allows him to stand-out among his peers. Eminem frequently tackles dark subjects, such as domestic violence, drug addiction, murder, and rape while also exploring more vulnerable topics such as mental illness and fatherhood. My project explores how these intense subjects are presented by performing sentiment analysis on Eminem's discography across his albums. Utilizing the VADER analyzer from *nltk*'s sentiment module, this paper will be used to uncover the emotional trends, patterns, and themes present in his works. More specifically, this project seeks to answer the question:  
- How does the sentiment in Eminem's lyrics reflect the themes of struggle and resilience across his albums?  

**Repository Contents**
- lyrics_line.txt  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Contains the dictionary containing the raw text of the lyrics of every song. Is in the format:  
{ album_name: { song_name: {'lyrics': string_of_lyrics}, ... } ... }
- lyrics_line_dud.txt  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Empty txt file used when executing the data collection from JupyterHub's server
- final_project.ipynb  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The notebook containing my final project. The narrative, analysis, code, and visualizations are all contained within. 
- requirements.txt  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Contains the imported libraries needed to run my notebooks code. 

**Binder Badge**  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TheSpamFan/dh-140-final.git/HEAD)

**Blog Link**
[![Quarto](https://img.shields.io/badge/Visit%20Blog-Quarto-green)](https://thespamfan.github.io/dh-140-blog/posts/final_blog.html)