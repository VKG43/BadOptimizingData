# BadOptimizingData

## Introduction and Motivation
This project seeks to create a framework where disparate, time-correlated data sources are combined to create an optimizable and not quite random set. 

In one of my other projects I have found myself trying to code optimizers from scratch and the existing sources (Machine Learning Mastery) while educationally useful tend to use mathematically simple optimizer data such as: $$z=x^{2}+y^{2}$$ which while usable tend to make the process of finding the derivatives too easy. 

As such, this project is how I personally made data that, while practically useless, presents a more interesting optimization challenge. 

## Process
I selected two of the datasets on the wonderful Alan Turing institute's TCPD datasets (https://github.com/alan-turing-institute/TCPD). In my case I took homeruns in the American Baseball League and the flow of the Nile river at Aswan. Both of these datasets were reduced to range from 1901-1970.

## Nile Data
The data for the Nile flow volume looked like: 
![niledata](/Images/Nile.png)

## Baseball Data
The data for the American Baseball League looked like:
![baseball data](/Images/Baseball.png)

## Combined 3d plot
Combined over time the data looks like:
![combined data](/Images/Baseball-Nile.png)
This data does exactly what I want it to as it is very messy but still represents an optimizable shape. There is a clear(ish) optimized point at 800 Flow and 1900 Year. 
