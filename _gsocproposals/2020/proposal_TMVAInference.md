---
title: TMVA Deep Learning Developments - Inference
layout: gsoc_proposal
project: TMVA
year: 2020
organization:
  - CERN
  - OProject
---

# Description

Toolkit for Multivariate Analysis [(TMVA)](http://root.cern/tmva) is a multi-purpose machine learning toolkit integrated into the [ROOT](http://root.cern) scientific software framework, used in many particle physics data analysis and applications. We provide in TMVA the functionality for building deep neural networks including fully connected, convolutional and recurrent layers. 
This project will focus on development of some deep learning operators such as layer concatenation or merging that will allow the build of more complex networks such as ResNet within TMVA and with the aim to provide a fast inference engine. 


## Task ideas and expected results
 * Support for concatenation and addition of layers
 * Integration with existing inference library 

## Expected Results:
 * Production ready inference engine for Resnet like neural network completed with example tests and documentation

## Requirements 
Strong C++ skills, solid knowledge of deep learning, familiarity with GPUs

## Mentors
  * [Lorenzo Moneta](mailto:Lorenzo.Moneta@cern.ch)
  * [Sitong An](mailto:s.an@cern.ch)

Please DO NOT contact mentors directly by email, and instead please send project inquiries to MLSFT-GSOC@cern.ch with Project Title in the subject and relevant mentors will get in touch with you. 

## Links
  * [http://root.cern/tmva](http://root.cern/tmva)
  * [TMVA source code](https://github.com/root-project/root/tree/master/tmva)

