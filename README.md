# Dynamic_Systems_Fingerprint_Model
UNAM-TICs-Dynamic Systems "Proyect"

____
## Table of Contents
* [Proyect Overview](#Proyect_Overview)
* [Introduction](#Introduction)
* [Formulas](#Formulas)
* [Justification](#Justification)
* [Hypothesis](#Hypothesis)
* [General_Objectives](#General_Objectives_(our_Research_Questions))
* [Specific_Objectives](#Specific_Objectives)
* [Technologies](#Technologies)
* [Packages](#Packages)
* [Setup](#Setup)
* [References](#References)
* [Team_Members](#Team_Members)
* [License](#License)


____
# Proyect_Overview
This project aims to develop a model for fingerprint formation. 

![Alt text](https://github.com/JZRodriguez/fingerprints_project/blob/main/Fingerprints%20patterns%202.jpg 'Fingerprints')

# Introduction
## What are fingerprints?
Fingerprints are skin patterns with friction ridges. Our fingers, palms and soles are characterized by ridges (hills) and valleys (furrows). Their formation occurs during fetal development, beginning at approximately the 10th week of gestation, being completed by the 17th week, and remaining throughout life.

## What are the patterns of fingerprints?
There are three basic patterns of fingerprints:
* Whorls: Most complex, and contain central pocket, double loop, and accidental
* Loops: Radial or  ulnar, depending on wheter direction of slope of pattern is towars inner arm bone (radius) or outer arm bone (ulna)
* Arches: Can be plain or tented

![Alt text](https://github.com/JZRodriguez/fingerprints_project/blob/main/Fingerprints%20pattern.jpg 'Types of patterns')



# Formulas

![Alt text](https://github.com/JZRodriguez/fingerprints_project/blob/main/Formula1.jpg 'Formula 1')

![Alt text](https://github.com/JZRodriguez/fingerprints_project/blob/main/Formula2.jpg 'Formula 2')

![Alt text](https://github.com/JZRodriguez/fingerprints_project/blob/main/Formula3.jpg 'Formula 3')


# Justification
### Why is it going to be done?
The biggest inspiration for this proyect comes from the work of Patterns in Nature by Alan Turing.  stripes zebras,coats of cats ,leoards and cheetahs are surprisingly unique ,what makes stripes a tool for identify one animal from the rest ,Fingerprints are like our stripes , Turing’s theory was elegant and simple: any repeating natural pattern could be created by the interaction of two things — molecules, cells, whatever — with particular characteristics. Through a mathematical principle he called ‘reaction–diffusion’, these two components would spontaneously self-organise into spots, stripes, rings, swirls or dappled blobs.
"https://ideas.ted.com/how-the-zebra-got-its-stripes-with-alan-turing/"

###Limitations
physics and mathematical theory of embriology deals with higly complex dynamics systems ,some of them non-linear,its important to mention that we do not pretend to model the actual physical process of ridges formation(fingerprints),However ,the paper that we are analizing gives an alternative aproach,it takes the principal properties ,that we will list below ,to replicate the fingerprint formation during embiological process through ,multivariable calculus tools ,vectors spaces,and numerical methods .
### Goals
*  Tweak the  initial conditions to find those who generate the 3 principal patterns inf fingerprints classification  
* Quantify those parameters and analize them  
* Like any other Dynamic System,main goal is to be able to predict fingerprint form at any given point of time in the formation
* Find critical points,linear stability ,convergence points ,Limit cycles ,Local ,Global Bifurcation

* Study the model as a System and not as a simple ecuation
* Create our final report of findings
* And the funny  part  ,create our own fingerprints


### How is it going to be done?
Compute a fingerprint formation model published in the scientific journal EUROPHYSICS LETTERS, "DOI: 10.1209/epl/i2004-10161-2" to generate fingerprints from initial parameters inserted by the user.


____
# Hypothesis

Given that no person has the same attributes than another person, the expected result is that no two fingerprints analyzed will be the same.


# General_Objectives_(our_Research_Questions)
Fingerprints Growth formation pattern is dicted by highly complex interactions of múltiple inicial contions, listed  below. The main goal is to compute the discret ecuation of the paper "" published by , this we Home will allow us to create fingerprints give a range of viable inicial contions 
This will also help analyze possible pattern designs and classify the characteristhics that define certain fingerprints. While we want to be able to create or own fingerprints, this could also help model fingerprints using existing data.


# Specific_Objectives
* Create a set of functions to model fingerprints given certain characteristics
* Using real data, model the fingerprints with the given information of the person  
* Analize the patterns that are shown to us
* Declare standards for certain forms of fingerprints
* Be able to create fingerprints

![Alt text](https://github.com/JZRodriguez/fingerprints_project/blob/main/Fingerprints%20examples.jpg 'Fingerprint models')

___
# Technologies

* Python          version: 3.8  
* Linux Ubuntu    64-bit
* Linux Arch      64-bit
* Github          https://www.github.com
* Windows 10      64-bit
* Jupyter lab     3.2.9

___
# Packages<br>
* Pandas     version 1.4.1
* Matplotlib version:3.2.2  
* Numpy      version:1.21.5  
* Linux console

___
# Setup

___
# References
Europhys. Lett., 68 (1), pp. 141–146 (2004)
DOI: 10.1209/epl/i2004-10161-2


Dubey, Deepika. Fingerprints; 30 May 2018.


___
# Team_Members

* Luis Aarón Nieto Cruz.
* Jadiel Zúñiga Rodriguez.
* Miguel Ángel Zamorano Presa.

# License
Copyright © 2022 <mikezpresa@gmail.com,zujadiel@gmail.com,aaronnicruz@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


