I'm a mathematics and CS student (bachelor's), interested in applied math and related areas.
In my repositories you will find all sorts of interesting projects and implementations I've been working on.

## Overview of my projects

### Finance related

#### Deep Q-Learning

Construction of general Deep Q-Learning pipeline with OOP. I first test the pipeline on synthetic data (generated from stochastic processes) and then implement it on real data (daily stock returns for various US equities) and conclude it to standard allocation principles (eg. equal weights or buy-and-hold strategies).
https://github.com/tobiasocula/Q-Learning-Implementations

#### Portfolio-allocation comparison

In this repository I test out different investment strategies on a wide basket of US equities, like sharpe-optimalization, market-cap adjusted weights and so on. I then form a conclusion whether a sophisticated strategy for choosing weights outperforms more simple strategies on a consistent basis.
https://github.com/tobiasocula/portfolio-allocation-comparison

#### Option market simulator

Implementation of a non-real time option market simulator. It uses a Hawkes-process to simulate and model order-arriving waiting times and trade volumes, paired with sophisticated formulas to determine which contracts receive active trading activity.
It also includes a streamlit-appliation where one can visualize the statistics of a certain run, by plotting distribution of order volume across quotes and different contracts.
https://github.com/tobiasocula/Options-market-simulator

#### (Another) Portfolio-allocation comparison

Similar to the one before, but now I test out multiple strategies on a broader universe of assets, being mostly equity ETFs and precious metals.
This project also implements other weight-allocation strategies I've come across during my research about this topic, and goes in more depth by also performing full parameter optimalization grids and more sophisticated stress tests.
https://github.com/tobiasocula/YetAnotherFinanceProject

### Other

#### Weather model simulation using HMM

Small implementation of the Hidden-Markov-Model applied to a simulated weather system, with a few states and transitions. The goal of this project was primarily to learn about the topic, but I also wanted to see how well it performs on this artificial example.
https://github.com/tobiasocula/Weather-HMM

#### Implementation of Expectation-Maximalization algorithm

This project is fully for educational purposes, and I don't perform any actual research. I wanted to learn about the EM-algorithm, thus I have implemented the most simple case I could come across.
https://github.com/tobiasocula/simple-EM-coinflip-implementation

