## exerciseminimilism
A small, single html file and browser local storage solution for tracking 7 fixed sets of daily exercises from one week to the next.

## Goals
The idea is that the simplicity reduces all friction to allow you get started on the exercises each day and continue the program long-term.

## Features
It will only ever show today's workout and the previous workout's weight. There is no other history, trending or reporting possible. 

It has no configuration interface in order to keep it simple. Edit the html file source in order to set your exercises. Only the previous weight is tracked to allow setting of the next weight.

Includes a very simple built-in timer for tracking rest periods. You can change the sound by inserting a different base64 encoded wav.

## Data storage
There is no save or undo button. Saving is instant any time data is input into the weight column. 

If you want to delete the data, just delete the local storage keys from an f12 browser debug session. 

There is no data syncing built in, so all data is tied to the browser that is used.

## Compatibility
It should work in any modern browser, and render equally well on desktop or mobile.

## Hosting and Demo
You can either run the raw html file from your local filesystem, put it on a server you contol, or even fork the project and use githack as a way to access it e.g. [This demo github file permalink with github replaced with githack in the url](https://raw.githack.com/bmtwl/exerciseminimilism/13d4ee27deb21004f30bae70ad48dcb0efdf18a6/exercises.html) (Githack caches files for a year, so using permalinks is good to make sure you always have the revision of exercises.html that you want).

## Web refernces and discussions
This project his the front page of Hacker News for a few days and generated some interesting discussion: https://news.ycombinator.com/item?id=42526769

It also has a (likely AI generated) youtube podcast: https://www.youtube.com/watch?v=Z1sNO2TDcGc

There is a Japanese language article here: https://biggo.jp/news/202412280715_minimalist-exercise-tracker-sparks-debate

## Alternative visions
@chase-west has a version of this project that separates out the css and audio data here: https://github.com/chase-west/exerciseminimilism
