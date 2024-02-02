rat\_deep\_learning\_phenotyping
================
AUTOR NAME
2024-02-02

<!-- Short Description  -->

On this proyect, we aim to develop an IA that can extract the stadistics
of phenotype or animal pose behaviour per amount of time given a rat
video.

*Updated on 2024-02-02 14:21:18*

<!-- README.md is generated from README.Rmd. Please edit that file -->

## Table of contents

  - [General info](#general-info)
      - [Analyses](#Analyses)
          - [To do list](#to-do-list)
              - [Contact](#contact)

## General info

Originaly developed for the Neuroscience Investigation Center (CIN) of
the University of Costa Rica (UCR). The idea of this proyect is to
create an IA that can help ease the data analisys of rats behavior,
particulary by using videos.

The proyect built proposal idea is divided in three different steps:

1.  Develop an IA capable of defining the animal on every video frame.
    For this step we’ll be using tools like:
    [DeepLabCut](http://www.mackenziemathislab.org/deeplabcut) and
    [Sleap](https://sleap.ai/).
2.  Classify the rat’s phenotype to determine it’s behaviour (ex:
    grooming). For this step we’ll be using:
    [deepOF](https://deepof.readthedocs.io/en/latest/index.html)
3.  Asocciate the phenotype per second so it can be determied the
    pocentage of each rat’s behaviour at the video, therefore be able to
    do stadistics based on the information

## Analysis

  - Efficiency

Before jumping into any conclusion, there’s the need to test the
efficiency levels of the IA. In order to do so, we’re making 3
comparisons:

1.  DeepLabCut vs Sleap: Both packages were designned to distiguish and
    follow the animal body through the video.
2.  Rat vs Mouse: There are models to identify mouses using said
    libraries, yet not with rats. So we’re going to test out those
    models with rats vs our own.
3.  Git alreadytrained IA vs our own IA: we don’t want to engage with
    only one dataset, knowing that it may make out IA good at it but not
    so good at tracking and classifing rat phenotype behavior with other
    datasets.

Depending on the results we shall continue with the most efficient one.

## In progress

  - First step of the built process

## To-do list

  - Finish the second and third steps of the proyect built process
  - Make the comparisons between the IA’s and determine the most
    efficient one
  - Conclusions and analysis of the IA development with the CIN rats
    videos

## Status

Project is: *in progress*

## Contact

Created by [Autor name](website_URL)
