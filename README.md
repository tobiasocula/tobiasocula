I'm a mathematics and CS student (bachelor's), interested in applied math and related areas.
In my repositories you will find all sorts of interesting projects and implementations I've been working on.

## Overview of my projects

Below are some small research projects I've undertaken myself of which I'm most proud and which I think are the most interesting.

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

Small implementation of the Hidden-Markov-Model applied to a simulated weather system, with a few states and transitions. The goal of this project was primarily to learn about the topic, but I also wanted to see how well it performs on this artificial example. I explore both the discrete version, as the version with continuous observation values.
https://github.com/tobiasocula/Weather-HMM

#### Mechanics simulation

Here I use elementary differential geometry and principles from mechanics to design a playground for objects to roll from physical surfaces and produce some cool effects.
https://github.com/tobiasocula/Mechanics-Simulations


