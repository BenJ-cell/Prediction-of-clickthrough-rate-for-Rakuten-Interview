# Prediction-of-clickthrough-rate-for-Rakuten-Interview

Rakuten Advertising is informed of a new auction for an ad placement for an 
user along with information on him/her. Those ads can lead to 
a bigger exposure and therefore a new chance to contract a sale with users. 
But those ad placements have 
a price so we need to carefully value themso we make a profit out of them.
• Purpose:Optimize ad placements for Rakuten on the internet.
• Where and when:During auctions in which Rakuten Advertising and its
competitors are involved.
• What: One auction = one ad placement for one user at one given moment.
• Time to propose a price: 100 millisecondsto give a maximum amountto pay for 
the ad placement called bid response secretto other competitors(sealed auction).
• Who getsthe ad placement: The participant who proposed the highest priced and
paid for it. The others pay 0.
So in order to give a coherent price of those ad placements using users'infomation a
nd their contexts, we must estimate the potential clickthrough rate (CTR) of the 
impression (ie: the probability they will click on the ad). This 
must be done beforewe informthe auction of the price we arewilling to offer to 
display the banner.
To compute our CTR estimation, we have user-related information 
(e.g. time since last visit on an advertiser’s website, number of banners already displ
ayed to that user), and context-related information (e.g. format of the 
ad placement, domain of the web page on which it is to be displayed).
