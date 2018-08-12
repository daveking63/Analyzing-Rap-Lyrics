# Analyzing-Rap-Lyrics
A summary of an earlier 3 parts series analyzing the evolution of rap lyrics with Python NLP and Topic Modeling

<h2>Introduction</h3>

This repository highlights the work done on an earlier (2016) three part series focused on exploring and analyzing the evolution of rap lyrics from 1980 to December 2015. The series was originally found at <a href='http://Dataffiti.com'>Dataffiti.com</a>.  For convenience  I made PDF copies of the 3 parts and placed them in this repository.

<h3>Summary of Series</h3>

The series is based a corpus of songs created by first constructing a list of song titles from the Billboard (BB) weekly Top 15 Hot Rap Songs for the years of interest and then using an API from ChartLyrics.com to extract the associated lyrics from their archive of songs. In cases where the lyrics were either missing or in error, the lyrics were supplemented with those from Genius.com.

This analysis followed in the footsteps of a variety of earlier studies including:

<ul>
<li>Mauch et al.’s (2015) study of the audio evolution of popular music from 1960-2010</li>
<li>Thompson’s (2015) study of the lyric evolution of popular music from 1960-2010.</li>
<li>Sterckx’ (2013) analysis of the Million Song Dataset.
<li>Fell and Sporleder’s (2014) lyrics-based analysis and classification of music.</li>
</ul>

The major question to be answered was, "How have Rap lyric evolved overtime?" To answer this general question, the series focused on three major types of analysis. In each case the basic idea was to determine whether there were differences among the lyrics and whether the differences varied systematically over time. Include among the types of analysis were:

<ol>
<li>NLP text analysis -- an analysis of the lexicon, grammatical structure, and rhyming structure</li>
<li>Topic mining based on an algorithm known as Non-negative Matrix Factorization -- an analysis of the major underlying themes and topics in the corpus</li>
<li>Classification -- an analysis aimed at determining whether the lyrics could be subsetted into a collection of differentiated classes based on the "style" of the lyrics.</li>
</ol>

It took ~50 pages of analysis and discussion to answer the major questions. If you're interested take a look.

<h3>What's New Here</h3>

So what's left. First, the original presentation didn't include the underlying code or data set.  Those will be provided here shortly. Second, the analysis stopped at 2015.  In the near future, I plan to add 2016-2018 and re-run some of the more interesting analyses.
This time I'll do it in an iPython Notebook and shorten the overall discussion considerably.

(To be continued)
