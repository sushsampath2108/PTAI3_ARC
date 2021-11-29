The Abstraction and Reasoning Corpus Assignment (ARC)

This repository contains four patterns taken from ARC, whose logic has been written in python language to produce its relative output

There is a directory data/training_PTAI: contains four task files which consists of data for training and test. The data from training has been used to bring a logic behind patterns.
The logic produced is applied to test input to give its respective output
The tasks are stored in JSON format. Each task JSON file contains a dictionary with two fields:

    train: demonstration input/output pairs. It consists of 2 or 3 pairs
    test: test input/output pairs. It consists of typically 1 pair.

A "pair" is a dictionary with two fields:

    "input": the input "grid" for the pair.
    "output": the output "grid" for the pair.

The input and output are printed like this for every train and test data
![image](https://user-images.githubusercontent.com/94651788/143934306-e4075db2-fdcf-4282-9ba8-e5fcc684503f.png)
