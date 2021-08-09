---
layout: default
slideId: Key-Security
title: Key Security
parent: Owning and Storing Atomic NFTs
nav_order: 1
---

# Key Security
{: .fs-9 }

<br>
One of the primary reasons blockchain systems have received widespread attention has been their ability to provide secure networks without trusting a central entity. Despite this, there are some limitations of the blockchain approach, and understanding them is key to properly deploying new products and solutions.

## MANAGING YOUR KEYS


### INDIVIDUAL ACCOUNT COMPROMISE

<br>
IN THE PAST, AN 8 DIGIT PASSWORD WAS NEARLY IMPOSSIBLE TO CRACK, BUT IN 2020, IT’S NOT ONLY POSSIBLE - IT’S EASY.
{: .text-blue-000 }

Staying safe online is about more than just a strong secret key. Avoiding illegal torrents and other un-verified downloads is a good place to start, but when it comes to corporate e-governance, things get even more complicated. Software review, careful audits, and change management should all be high priorities for any decentralized projects. Storing private keys in a publicly accessible place can introduce a crime of opportunity when not already present.

In addition, a weak quality password could make it possible for any computer with a modern video card to crack your password. The problem is made worse by the existence of inexpensive, on-demand processing, for example, through a traditional cloud provider. Finally, ensuring your source of entropy/randomness was sufficient during account creation may not be something the end-user has control over, however, this can be a major weakness after keys were already thought to have been secured.

Aside from actual wallets being hacked, there is always the risk that a developer’s Github account could be compromised, in which case a bad actor could add malicious code into the client software for the blockchain network. In the past, bad actors have gone as far as to join the development communities for modules which were used in other software, such as the cryptographic libraries used in the Bitcoin client, and sought to create security loopholes by pushing malicious code to those dependencies.

- While core blockchain code doesn't often malfunction, wallet and client software is an easy target for many hackers. It's important to always verify that the wallet software you are downloading matches the publisher's hash. Most the iOS and Google Play app stores do this automatically, but we must be particularly careful with desktop applications.
{: .text-purple-000}
### CRYPTOCURRENCY WALLETS

<br>
- IT’S IMPORTANT TO HAVE THE RIGHT TOOL FOR THE JOB.
{: .text-blue-000 }


Although the software we use to manage cryptocurrencies is called a “wallet”, no actual value is held in the wallet itself. Instead, it is a management interface for interacting with your private keys and blockchain networks. Modern cryptocurrency wallets are more like a chequebook, which doesn’t hold any actual assets directly, but can sign them to another person. Because balances are tracked by the blockchain itself, cryptocurrency wallets mainly automate the process of signing cryptographic messages and broadcasting them to peer nodes in the network.