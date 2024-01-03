# Search-Engine
A cute lil' search engine :)
This was a project given out by EECS 485 @ University of Michigan, and therefore can't be shown publicly (without me getting a strongly worded email). Please refer to this readme for further information.

This project has 3 essential parts: An inverted index pipeline, a back-end "index server" used to calculate search results, and a front-end "search server" which shows the results and gets user input.

## Inverted index
The inverted index is a 4-stage pipelined map-reduce program which is fed the raw html of pages and assigns the tf-idf score for each term in the input. It's designed to be run a single time with a shell script and later used by the engine to rank pages using the PageRank algorithm.

## Index server
The index server consists

## Search server
