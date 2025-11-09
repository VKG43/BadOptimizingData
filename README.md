# BadOptimizingData

## Introduction and Motivation
This project seeks to create a framework where in disparate, time-correlated data sources are combined to create an optimizable and not quite random set. 

In one of my other projects I have found myself trying to code optimziers from scratch and the existing soruces (Machine Learning Mastery) while educationally useful tend to use mathimatically simple optimizer data such as: $z=x^{2}+y^{2}$ which while usable tend to make the process of finding the derivitves too easy. 

As such, this project is how I personally made data that, while practically useless, presents a more interesting optimization challenge. 

## Process
To begin I wanted to combine 2 dataources that were time series data. The data I ended up using as an example has the three dimensions of date (as an integer from 0=starting date to n where each step _t_ is the time step of the underlying data (in this case years and days)

The first data source was taking publically avalible data of soybean yields from 1981 to 2016 (https://doi.pangaea.de/10.1594/PANGAEA.909132) to produce a [35, 2] dataframe. 

I then combined this data with the volume of the nile river at Aswan (https://github.com/alan-turing-institute/TCPD/tree/master/datasets/nile).
