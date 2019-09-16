[Reddit Link](https://www.reddit.com/r/privacy/comments/3tz3ph/blocking_most_advertising_servers_via_factory/)

Blocking most Advertising servers via factory router firmware.
I have been using open source firmwares on my routers for at least 10 years, but for many people, this is not an option.

With Open Source firmwares like OpenWRT and DD-WRT there is different ways to configure ad blocking, but your choices might be limited with closed source router firmware.

The list of servers below are a list I put together based on multiple lists I have found on the internet, I took only the domain name of the ones that I found to do the most traffic, by adding this list to Block URL settings of your factory router traffic should stop most of the marketing servers and 3rd party servers.

I am putting together the instructions for each manufacturer and will be adding it to the list.

Bad news, you will need to copy/paste each one of the servers below to the list. The Factory firmware's don’t have a way to import this list.

I am adding 2 different list, one if your router has a 10 URL limit, and a second one if your router does not have a limit on how many URL’s you can block.

If your router has a low limit on how many URL’s you can block, I would suggest adding this 10 servers only:
```
doubleclick.com     
doubleclick.net     
googleadservices.com
googlesyndication.com
google-analytics.com
omniture.com      
intellitxt.com      
quantserve.com   
2o7.net 
207.net 
```

If your router has a low limit on how many URL’s you can block, I would suggest adding this 25 servers only:
```
doubleclick.com     
doubleclick.net     
googleadservices.com
googlesyndication.com
google-analytics.com
omniture.com      
intellitxt.com      
quantserve.com   
2o7.net 
207.net
adbrite.com
admob.com
advertising.com
foxnetworks.com
gravity.com
hitbox.com
nielsen-online.com
quantcast.com
scorecardresearch.com
esomniture.com
atwola.com
channelintelligence.com
aquantive.com
adthis.com
247realmedia.com
```

If your router does not have a limit on how many URL’s you can block, I would suggest adding the 80 servers below.
```
adsense.com
adblade.com
207.net             
247realmedia.com     
2mdn.net             
2o7.net             
33across.com
abmr.net             
adbrite.com         
adbureau.net           
adchemy.com         
addthis.com           
addthisedge.com       
admeld.com           
admob.com           
adsonar.com           
advertising.com 
afy11.net           
aquantive.com         
atdmt.com               
atwola.com           
channelintelligence.com
cmcore.com           
coremetrics.com        
crowdscience.com       
decdna.net           
decideinteractive.com
doubleclick.com     
doubleclick.net     
esomniture.com       
fimserve.com         
flingwebads.com     
foxnetworks.com     
googleadservices.com
googlesyndication.com
google-analytics.com
gravity.com         
hitbox.com           
imiclk.com           
imrworldwide.com     
insightexpress.com     
insightexpressai.com
intellitxt.com           
invitemedia.com                  
leadback.com         
lindwd.net
mookie1.com         
myads.com           
netconversions.com   
nexac.com             
nextaction.net         
nielsen-online.com   
offermatica.com     
omniture.com         
omtrdc.net           
pm14.com             
quantcast.com       
quantserve.com       
realmedia.com       
revsci.net           
rightmedia.com       
rmxads.com             
ru4.com             
rubiconproject.com   
samsungadhub.com
scorecardresearch.com
sharethis.com
shopthetv.com
acoda.net           
targetingmarketplace.com
themig.com   
trendnetcloud.com
yieldmanager.com      
yieldmanager.net       
yldmgrimg.net
youknowbest.com    
yumenetworks.com
```