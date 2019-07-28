# Code.fun.do-2019
# Incorporating Blockchain Technology in Election Process
## Motivation

In today’s digital world it has become difficult for people to trust any centralised system, the current election mechanisms in all parts of the world are one of them as cries of EVMs getting hacked have become a regular scene. There are several other issues which remain to be answered such as that of people not residing in their voting constituency being robbed of their vote. The blockchain technology has the ability to answer these questions and here we present you our idea on the same.

## Idea

We plan to build and deploy a blockchain for secure transfer of votes, develop a website which verifies the voter using face recognition apart from using the traditional user id and password. Each user will be allotted a small amount of ether which can be used just once to give the vote.Each new vote will only be added and stored in the blockchain only after it is approved by the other servers.

## Benefits

* Decentralised and secure system
* Users can vote from all parts of the world irrespective 
* After casting their vote , users can tally their votes with the actually given vote in the system using a unique code for each user.
* The party wouldn’t  be able to know which citizen voted for which party or not.
* Many parties will spend a lot to hack the system.However the accountability will be maintained because of immutable ledger.

## Challenges

* Any information system that collects data from multiple systems should have policies and procedures defined to prevent the identity of election mechanism from being disclosed to any outside parties, or the public, without consent. A permissioned blockchain is best suited because electional information such as voter records are confidential.

* Initially, we were planning to use the Hyperledger Fabric, but it's not compatible with the Azure Blockchain Workbench. Hence, we will be using the Ethereum based implementation for the purpose of this hackathon. Ethereum uses Proof of Stake consensus and is permissioned blockchain.
* The speed and effectiveness with which blockchain networks can execute peer-to-peer transactions comes at a high aggregate cost, which is greater for some types of blockchain than others. This inefficiency arises because each node performs the same tasks as every other node on its own copy of the data in an attempt to be the first to find a solution. 

## Frameworks Required

### For creating a Decentralized network - Microsoft Azure Blockchain.
* Ethereum will be used.
* Node.js will be used to provide UI and an interface to the blockchain.
* Jquery, Bootstrap will be used for frontend.
* We will use truffle, ganache, meta-mask and web3-js.

## Team - KGPwale
Indian Institute of Technology, Kharagpur

 * Shubhesh Anand
 * Debajit Chakraborty
 * Naman Paharia
