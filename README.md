# Language Course Scraper

I'm hoping to learn Vietnamese, and to help me do that I have recently subscribed to an online language course. I paid for access to the course, but I'm not entirely satisfied with how the course is laid out. There are audio lessons that are only accessible through the course's website, which make it difficult to listen to while I go for a run.

This repository is not to be used as a public scraping tool, but to serve as an example of my Python ability and my solving personal problems with code.

## The Goal

This paid course has ~150 lessons. I would like to write a script that will go through the site, downloads the contents of each lesson, and stores them locally so that I can access them however I would like.

## Course Structure

Each lesson has the following content I would like to procure:

* Difficulty rating
* 20-minute audio clip
* Dialogue/Reading list & Audio Clip
* Practice phrases & Audio Clip
* Vocabulary list & Audio Clip
* Accompanying PDF with extra exercises

## Storage

For practicality, I will store the contents in a MySQL server, with references to all the accompanying files.