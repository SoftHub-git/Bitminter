# BitMinter

![image](https://user-images.githubusercontent.com/73274922/236248552-dc0c6e73-3e1c-472c-9943-d73e288b2fa4.png)

## About 

Want a miner that runs at a hash rate of just 1.0% that of a modern ASIC miner? Well this is not that miner. This is a miner that runs at a hash rate of _less than_ 0.1% that of a modern ASIC miner!

Bitminter Mining Pool is one of the oldest mining pools. The software started operating in 2011 with the main goal of making Bitcoin mining easier. The brand is owned and operated by the Norwegian company Aesir Financial AS. According to information provided by the company, its client base is 450,000 people. The program has won the hearts of users with its time-tested reliability and simple operation. It has everything you need to make mining easy and win high payouts for your investors.

## Bitminter Rewards
The software uses a scoring system to split payouts. Mining shifts are divided into 10 categories. A new shift begins when 1/10 of the current mining difficulty is overcome or a new block is found. Payouts are based on a 1 Terrahash ratio and are added to your account. Bitminter is one of the first in the industry. This allowed the software to gather a team of experienced miners around its site.

The platform allows you to mine both bitcoins and registered coins. The payout threshold for bitcoin is low. It is only 0.01 bitcoin. The software allows you to set the minimum payment amount to the wallet. Upon reaching the specified number, funds are automatically transferred to your account. Miners with significant hashing power can request a manual payout for amounts below the minimum automatic payout.

Bitminter differs from other mining pools in that it allows you to create your account only using public IDs, Gmail or other accounts. You will not be able to register through the social networks Facebook and Twitter. They are not supported by the software. But this approach scares off users who are not ready to share their personal data with the pool owners.

## Concise interface
Bitminter uses artificial intelligence to predict the needs of traders. This cuts down on the time spent looking for different features and capabilities. The platform has a clear interface and can work with GPUs. It is simple and easy to navigate in the software settings, look for the necessary functions, create tasks.

## Supports various hardware
Bitminter is compatible with a variety of hardware. The application can work with ASIC chips and graphics cards. It is well compatible with external ASIC devices like Chili, Butterfly Labs Block Erupter USB, Antminer U1 / U2, and Red / Blue Fury.

## Application for computers
The Bitminter client is available for Linux, Windows and Mac OS X operating systems. It is based on the Java Network Launch Protocol and does not require installation. The program has a simple and intuitive interface. To work, the user needs to register in the mining pool on the website. And then configure your ASIC hardware.

The Bitminters website impresses with its simplicity. It looks primitive compared to other mining pools. But at the same time, it displays up-to-date operational statistics about rewards, successes, shifts, as well as an API service. Work is registered in shifts. Shifts are usually divided into groups of 10. A new shift begins when 1/10 of a block is completed or a new block is won. 99% of all mining income is paid to clients.

## Why

Learning. I wanted to peel back the covers on Bitcoin and pool based mining, and also try my hand at a larger Clojure project along the way. 

## Core features: 
 - [X] Clojure (so pretty cool) 
 - [X] Slow 
 - [X] Costs more to run than it will ever make back in bitcoin
 - [X] Includes 2 pretty solid tests
 - [X] Peeled back the covers a bit on how Bitcoin works

##  Intallation & Operation

Wanna run it?  
    
Leningen should be used to run the repl and resolve the deps. 

    cd bitminer/
    lein repl 
    > (start-supervisor) 


Then it's a waiting game. Shortly before the heat death of the universe you should be able to nab a share.


[0] Based on miners (as of this 2017) operating in the TH/s range, and my current i7, being run inside of a vm, using only a few cores, being in the KH/s range. 
