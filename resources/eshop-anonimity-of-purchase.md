## Protecting Your Customers Anonymity

Ethereum is currently an open ledger: all transaction are auditable by anyone. As a result, using the same Ethereum address for all your purchases binds your identity to what you bought.
So what? You might think. It's perfectly fine for the world to know you just got the latest pair of Bose earbuds! Sure, but what about a bulked-purchase of sprays for [halitosis](https://en.wikipedia.org/wiki/Bad_breath)? Or worse, industrial-grade adult gadgets? 

In an era where customer data regulation is lagging behind Facebook's infamous tracking practices, it probably makes sense to offer your clients the means to be incognito if they choose to.

The good news is that, on Ethereum, you can offer them a solid level of privacy by giving them the right guidance.

### What Protection Do We Want To Offer?

Let's make the following assumption: you want whatever happens in your eShop to stays in your eShop. No one (except the law enforcement provided with a search warrant) is supposed to know, or guess, what was bought. 

If the above satisfies your definition of customer privacy, let's get to it: the following will demonstrate how to enable it in your eShop.

### Protection At The Network Level

As you probably know, the internet was not built with anonymity in mind, and it's pretty trivial to infer someone's identity based on their IP address. 

An IP address can be viewed as open data: it transits through your ISP and all switches all the way to the destination server. For instance, your ISP could log timestamps of packets sent and associate them with withdrawal exchange timestamps. 

**Solution**: utilize a VPN or Tor to mask your IP, particularly during a withdrawal. 

The order contain information that can associate your deposit with withdrawal. The safest measure is to delete it after the withdrawal is finished. In the event that you allow someone to review your exchanges, you should keep the order which can be used a proof of purchase in case of dispute. 

Make sure you delete any cookies related to your eShop before utilizing a VPN or Tor, otherwise the cookies will enable the eShop to associate the different IP addresses you've been using with the same user. A recommended method to do this is to utilize another personality (browser, wallet, IP) for the assets of your new location. 

Using an open RPC with each of your wallets enables to infer a connection between your addresses, so if you utilize a similar IP or API token for all your online identities. That scenario could occur with Metamask if you use it for every of your addresses, since Metamask uses the same API token for every one of your requests.

Please bear in mind: the above suggestions are meant for optimal security, they wouldn't be necessary in most scenarios.

### Protection At The Chain Level

As a blockchain, Ethereum establishes total transaction ordering, which enables anyone to know exactly what transaction happened before the next.
When it comes to purchasing, total ordering enables anyone to correlate transactions with a fair level of accuracy.

For instance: if a deposit and a withdrawal have been made at close intervals, chances are they belong to the same person, it is therefore good practice to wait at least twenty-four hours between a deposit and an interval.
 
If there is a batch of deposits from one address, and then a batch of the same size of withdrawals to a single address, they are very likely connected. If you need to make multiple withdrawals, try to spread them out and withdraw to addresses not linked with each other.

In the context of an eShop, than means spacing orders and using different addresses.

Tools like Tornado.cash will help you add a strong layer of anonymity in the purchasing process. 

Let's be entirely honest, the above recommendations are an absolute overkill if your intention is just to acquire items to spice your couple life. Our point was simply to help anyone willing to setup an Ethereum eShop an all their prospective clients evade the all pervasive eye of Big Brother. 

