---
layout: default
img: bitcoin.png
category: Services
title: Bitcoin Payment Channels
description: |
---
  We're currently developing an amazing project as our final career project: a software that allows offchain Bitcoin Payment Channels so we can increase Bitcoin transaction throughput and improve Bitcoin scalability.

  The idea is to allow nodes running our software create payment channels between them so that they can pay to each other with Bitcoin-valid transactions that aren't sent to the blockchain (despite they are valid) until the channel is closed. This way, just the channel opening and close transactions would appear in the blockchain but thousands of transactions can happen between the parties meanwhile.

  To implement the idea, we have to deal with game theory, Python 3.6 and low-level understanding of the Bitcoin transaction.

  You can checkout how the repo grows and the project goes here:  
  [https://github.com/uab-projects/btc-payment-channels](https://github.com/uab-projects/btc-payment-channels)
