# Assignment9

For week 9, I had nothing but problems because my GCP SDK wasn't configuring on my sytem. It installed and ran up until this bit of code: $ gcloud beta compute firewall-rules create mhn-allow-admin --direction=INGRESS --priority=1000 --network=default --action=ALLOW --rules=tcp:3000,tcp:10000 --source-ranges=0.0.0.0/0 --target-tags=mhn-admin

where it would crash. And crash. and crash. I asked my instructors for help, TAs for help, I searched the internet for help, but nothing. It just keeps crashing. 

Also for Milestone 0 in the lab, it just wasn't listening. Despite what everybody did, the nc -l command just wasn't working for me. I don't know what's wrong. 

So I wasn't able to advance on this project for 2 weeks. I was told to just give up and let you all at CodePath know what is going on. 
