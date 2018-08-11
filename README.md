# Analyzing-Rap-Lyrics
A summary of an earlier 3 parts series analyzing the evolution of rap lyrics with Python NLP and Topic Modeling

<h2>Introduction</h3>

This repository highlights the work done on an earlier (2016) three part series focused on exploring and analyzing the evolution of rap lyrics from 1980 to December 2015. The series is found at:

<ul>
<li><a href='http://dataffiti.com/2016/01/17/analyzing-rap-lyrics-part-1-of-3-creating-a-corpus/'>Analyzing Rap Lyrics – Part 1 of 3: Creating a Corpus</a></li><br>
<li><a href='http://dataffiti.com/2016/03/09/analyzing-rap-lyrics-part-2-preparing-cleaning-and-exploring-rap-lyrics/'> Analyzing Rap Lyrics – Part 2: Preparing, Cleaning, and Exploring Rap Lyrics</a></li><br>
<li><a href='http://dataffiti.com/2016/06/20/long-time-between-posts/'>Analyzing Rap Lyrics – Part 3: Analytical Results and Implications</a></li><br>
</ul>

<h3>Summary of Series</h3>

The series is based a corpus of songs created by first constructing a list of song titles from the Billboard (BB) weekly Top 15 Hot Rap Songs for the years of interest and then using an API from ChartLyrics.com to extract the associated lyrics from their archive of songs. In cases where the lyrics were either missing or in error, the lyrics were supplemented with those from Genius.com.

This analysis followed in the footsteps of a variety of earlier studies including:

<ul>
<li>Mauch et al.’s (2015) study of the audio evolution of popular music from 1960-2010</li><br>
<li>Thompson’s (2015) study of the lyric evolution of popular music from 1960-2010.</li><br>
<li>Sterckx’ (2013) analysis of the Million Song Dataset.
<li>Fell and Sporleder’s (2014) lyrics-based analysis and classification of music.</li><br>
</ul>

In particular, the analysis in the series followed 3 major strains:

<ol>
<li>Traditional NLP text analysis</li><br>
<li>Topic mining based on an algorithm known as Non-negative Matrix Factorization</li><br>
<li>Classification based on the underlying <i>style</i> of a lyric</li><br>
</ol>

<h3>What's New</h3>

The primary addition made by this repository is the inclusion of the underlying code and data sets that we not included in the original analysis.

(To be continued)
