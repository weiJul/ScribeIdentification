# Implementing Neural Nets For Scribe Identification

This repo is about my master thesis.

## Problem

Scribe identification that is the complex task of locating the corresponding scribe
of a manuscript, is a time-consuming endeavor for paleographers and codicologists,
which can therefore only take place on a limited scale.

## Solution

AI support could make the assignment of scribes faster and more comprehensive in the future.
The objective of my thesis was to reduce time-consuming repetitive palaeographical tasks sparing time then
available for scientific analyses. In addition, this new structure of automated support
potentially allows significantly more comprehensive investigations including more
samples.

## Technical approach

The used models were AlexNet, Half DeepWriter and DeepWriter
which have already been used for scribe identification. The neural networks were
trained on the historic manuscripts to recognize seven individual scribes. The trained
networks were then tested on unseen, new codices in order to investigate their
transvere learning abilities.

Masked grayscale images were found to produce significantly more reliable results than RGB images. Since AlexNet achieved the best results in scribe classification on the [Database](https://phaidra.fhstp.ac.at/view/o:4631), it was used for the following experiments. For individual classes of certain books, accuracies of up to __0,98__ based on line level could be achieved. In further experiments the CNN could be improved by implementing a Reject Option in order to produce more stable results.

## More informaiton

Website:
[https://jweissma.pages.gitlab.rlp.net/MA_Website/](https://jweissma.pages.gitlab.rlp.net/MA_Website/)

Code on Gitlab:
[https://gitlab.rlp.net/jweissma/ma-repo/-/tree/main/experiments](https://gitlab.rlp.net/jweissma/ma-repo/-/tree/main/experiments)

Database:
[https://phaidra.fhstp.ac.at/view/o:4631](https://phaidra.fhstp.ac.at/view/o:4631)


## Cite

@mastersthesis{mastersthesis,
author       = {Wei{\ss}mann, Julius},
title        = {Maschinelles Lernen zur Untersuchung von Schreiberhänden des Klosterneuburger Skriptoriums im letzten Drittel des 12. Jahrhunderts},
school       = {Johannes Gutenberg-Universität Mainz},
year         = 2021,
address      = {Offenbach},
month        = 12,
}

## Licence

CC BY 2.0

---


    (\
    \'\
     \'\     __________  
     / '|   ()__________)
     \ '/    \ ~~~~~~~~ \
       \       \~~~hl.Leo\
      (==)      \_________\
      (__)      ()__________)
      
      
