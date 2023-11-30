# Anon-Amen
Anonymous Shipping Configuration 


How It Works

Two classes of people: "Forwarders" and "Buyers". 

Forwarders: Profit seeking individuals located in each country and major city.  They will have their own system for receiving packages and should be comfortable using their own address or PO Box.  The forwarder will sign up on Anon Amen and put in a zip code for Buyers to locate. 

Buyers: Want a packaged shipped without revealing personal information. Creates an account on Anon Amen.  Finds a Forwarder that is geographically close and willing to accept the package on mutually agreed terms. Buyers are willing to pay a premium, determined by the forwarder, to have package shipped in a private manner. 



Order of Operations:  

1. Forwarder signs up on website. Lists zip code and advertisement. Advertisement includes any limits and disclaimers. Forwarder deposits Monero into custodial wallet.

2. Buyer goes on website and finds a forwarder geographically close to them. Creates an account. Hits a button to initiate trade with Forwarder. Once the forwarder accepts “initiate trade”, a webpage for that trade is created that allows for input data and chat is now allowed. Chat should only be allowed after trade begins to ensure any conversation between forwarder and buyer is retained.

3. In the chat the forwarder and buyer should decide how the package should be picked up.  Does the buyer want to meet in public, a specific address (parking lot, cafe), delivered to his address by the forwarder, or to pick up at the forwarders address?

4. After that determination is made, the buyer will input how much the package is worth into the field.

5. Next the forwarder will input their percentage take of the package. (ie 10 percent of 1.2 xmr).

6. Notifications are sent to each “Do you accept the terms of the trade” if:
The forwarder’s wallet has monero greater than or equal to the agreed upon package worth (1.2 xmr)
The buyer’s wallet has monero greater than or equal to the agreed upon forwarder’s take (.12 xmr)

7. If either of the wallets don’t have a sufficient balance, a notification is sent requiring the forwarder or buyer to deposit more monero. Up until this point the trade can be canceled by either party. 

8. If both parties are able to accept, monero is taken out of the forwarder’s wallet the (1.2xmr) And monero is taken out of buyer’s wallet (.12 xmr), both of which go into a wallet controlled by website admin.

9. Forwarder gives buyer specific instructions for sending package. (name, street, city, zipcode) 

10. Buyer has package shipped to forwarder’s address. Buyer inputs tracking code (requirement). 

11. Forwarder receives package and delivers the package in agreed upon way.

12. Forwarder declares “transaction complete”. Buyer hits “transaction complete”.

13. Forwarder is given back full collateral and agreed upon premium (1.2 + .12 = 1.32 xmr)


Requirements to Mitigate Scamming 

The following should be written clearly and acknowledged by both Forwarder and Buyer for each trade:

1. The website chat must be used for all communication. Chat’s cannot go into session, telegram, or other mediums so that all messages are can be seen by an administrator in the event of a dispute.  If a chat goes into a telegram there is no way to verify it was official communication between both parties.

2. All shipments must have tracking.  This is the only to prevent a vector of scamming from the forwarder (claiming it never arrived) and the buyer (claiming the item was shipped but was not).



Weaknesses and Scammer Attack Vectors   

1. Forwarder liability:  A buyer sends something very illegal (weapons, meth, fentanyl, heroin) to a forwarder’s house or PO Box. If the box is searched by federal agents, USPS inspectors, or customs the forwarder might have to talk to police.  This is the biggest concern, and will inhibit some people from signing up as a forwarder.

Mitigation: Very careful packaging should be used at all times. Package forwarders have some protection under US laws – only private companies and US Customs may open up the package for suspecting something suspicious, USPS needs a search warrant.  Additionally, if something illegal was found, to confirm the identity police normally ask the person listed on the address to come in and claim package. In every instance the forwarder should not claim. Lastly, Forwarders are profit seeking individuals.  This is a major risk taken. Forwarders can ask what is in the package prior to shipment. Should be charging high amounts, which will allow some forwarders to do this full time.  

2. Ways to Scam the Forwarder: Forwarder must deposit what the package is worth in Monero. This is to deter the Forwarder from walking away with the package.  Let’s say the package is worth 5 xmr. The buyer, though required to have tracking on the package, could send a package to the forwarder’s house as agreed upon. Since they know where the package is being shipped to, they could steal it before the forwarder can retrieve it. This would be difficult to do if the package was sent to a PO Box or an apartment, but is doable if delivered to a physical home address. The buyer would also know approximately when the package is being delivered (because of required tracking).  If the Buyer was successful at this, and the forwarder made no disclaimer that they were not responsible for lost or stolen packages, in the event of a dispute the arbiter would most likely side with the Buyer who would receive the 1.2 xmr in collateral.

Mitigation: This would be extremely difficult to pull off as a scammer and probably would only happen to the forwarder once.  Forwarder can prevent this either using a PO Box that only he/she can access, or ensure they will be around when the package is delivered. 

3. Ways to Scam the Buyer: If the buyer undervalues the package, this gives the ability for the forwarder to take the package and delete their account (package is worth 5 xmr but the buyer inputs 1.2 xmr). Additionally, a package forwarder may open the package (suspecting it might contain something illegal) and dispute the transaction.  As a business they must be told that to comply with local laws and regulations – which in this case would permit them the collateral back and keep the illegal items.

Mitigation: This mistake is completely on the buyer, if you undervalue a package you are undervaluing the insurance. Most buyers will overvalue their packages to give them cushion. And if forwarders are opening up their buyers’ packages in search for illegal items, this would enter into their ratings and deter further business.

4. Package delivery weaknesses:

A. The package was delivered to forwarder. Depending on how the buyer and forwarder set up the exchange, there could be many attack vectors during the package drop-off. For example, if they decide to have a public meet up spot with no cameras and the forwarder says the package was dropped at the agreed upon location (public park, parking spot, specific geo location) but the buyer says the package was never there, what happens? 

A. There are many ways for to scam the forwarder and buyer in package delivery hand-offs (which could get pretty complicated depending on the buyer’s requests). Forwarders must take pictures/videos of delivery as a precaution. If the forwarder proves with pictures that the package was dropped at the exact location and agreed upon time, then the dispute would side with the forwarder.  If the forwarder can’t provide photos but the advertisement specifically protects him/her against this, the dispute would go with the forwarder, else to the Buyer.

B. Package is delivered to forwarder.  Forwarder opens it and sees 5 jars of raw organic honey.  Forwarder empties 5 jars of raw organic honey and replaces it with the equivalent amount in watered down honey from Walmart.  Package is sealed again and exchanged with buyer in agreed upon way. Buyer opens package when he gets home. He then tastes the honey and realizes its not what he ordered.


B. This is why the forwarder is not paid until the buyer finalizes transaction. In this case the buyer can reach out to the vendor and verify that something was switched in the package.  The buyer disputes the transaction and the arbiter gets evidence from the vendor. If its a reputable vendor or website it will be much easier to verify that the forwarder was malicious.  But in the cases that the website is not well-known or the vendor has a short history, the decision will be more difficult. Also if the forwarder puts a disclaimer in the advertisement saying he or she is not responsible for damaged or wrong shipments, the arbiter would be forced to side with the forwarder; however the buyer will be allowed to put the evidence of fraud and downgrade his rating for others to see. 
 

C. Package is delivered to forwarder and then given to buyer in agreed upon way.  Buyer opens up the package that contains 5 boxes of premium loose-leaf tea.  Buyer colludes with vendor (or his the vendor himself), and disputes the transaction saying the tea delivered is fake (sends picture of replaced fake tea) and not what he ordered.  In the dispute he will say he contacted the vendor and the “vendor” confirms 5 boxes of premium loose-leaf tea was shipped. The website arbiter will contact the vendor to verify if the package was altered by the forwarder. What happens? 

C.  The only way the Forwarder could protect himself would be to say that he is not responsible for wrong shipments in the advertisement. If the malicious buyer went as far to give him a bad review because the scam did not work, the forwarder shouldn’t have many of these kinds of attacks in his review ratings. 



