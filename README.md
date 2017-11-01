# Week9CodePath
Week9 Assignment for Codepath

Three honey pots were deployed, but 2 seemed to have some issues with each kind of honeypot I tried deploying on it.

Over 3000 attacks occured, almost 100 of which were from Honeypot 3 and the rest all came from 1. No matter which type of deployment I used, honeypot 2 attracted no one.

I didn't notice anything that specifically said malware on its protocol or the like. A lot of pcap, some SipSession and SipCall, smbd, and a RtpUdStream.

Countries that I saw committing the attacks seemed to come from a number of nations so far as I could tell from the flags. A lot of Ireland, some UK, France, Canada, Brazil, Germany, South Korea, and the US. There were a few China and Russia every now and then, but not as many as the others I listed. Every now and then though, there wasn't a flag on the attack to show what nation the attack came from, which means either someone has covered their tracks somewhat well or maybe there was a bug in detecting how to catch them.

Primary issue at first was somewhat getting everything started and put together. The instructions didn't mention needing to set up the API credentials to work with the Cloud to get everything working.

I messed up a couple of times in trying to get the project created and working, so I ended up using the browser shell in the dashboard for the cloud.

Whichever honeypot I tried setting up for honeypot 2 seemed to have some weird issue or another in regards to a package's previous version being installed or ommitted. nmap didn't seem to work on any version of 2 I used.

I first tried using Rhasberry Phi Dionaea with honeypot 2. Then elastichoney. Then snort. Honeypot 1 had Ubuntu Dionaea with HTTP, which everyone seems to enjoy visiting and attacking. Honeypot 3 used regular Ubuntu Dionaea.

Best question I have regarding all this is if the attackers got anything from the honeypots or managed to avoid them. Or better yet why France seems to enjoy attacking what seemed like a bit more often than the others. 
