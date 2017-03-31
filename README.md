#  Naive Bayes Reuters

This is a simple example on how to implement and use Naive Bayes on Spark using the popular Reuters 21578 dataset.

## Requirements

GravityLabs Goose (use this fork to be compatible with Scala 2.10):
    
    $ git clone http://github.com/Chimpler/goose
    $ mvn install

## Setup

    $ ./download_reuters.sh
    
## Running Classification

    $ sbt run 

## Examples

    http://www.coinflation.com/coins/1942-1945-Silver-War-Nickel-Value.html => gold
    http://www.businessweek.com/news/2014-06-10/china-using-dubai-style-fake-islands-to-reshape-south-china-sea => ship
    http://en.wikipedia.org/wiki/Soybean => grain
    http://en.wikipedia.org/wiki/Whole_wheat_bread => grain
    http://en.wiktionary.org/wiki/cow => livestock
