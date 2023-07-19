# How-I-Hacked-My-College-Website
Welcome Hackers!
Let see How I hacked my college website......

Note: Before starting the hunt on the website, I’ve not taken the permission from the required authorities. I know it is wrong but I do. Please do not hunt, if you do not have any permission. I am not responsible to any of your actions.

Target : https://payment.*****.ac.in

RECON : Here I gather all information of the target https://*****.ac.in ---- Info like Sub-Domain enumeration, Directory Search, Wayback URLs, IP addresses, Nameserver & Mailserver.

Think Whaattt!!! In the first phase of hacking, I got the URL which have .zip file & It is very intresting.

But But But My college use a Firewall :  The site https://payment.*****.ac.in is behind ModSecurity (SpiderLabs) WAF.
So now I search on google that "How to bypass ModSecurity WAF" & watch some videos on Youtube for the same. And I got one blog, where I learned that how to bypass WAF.

I can't show that how I bypass WAF, because it is still vulnerable.....

Now I'm able to download that .zip file : payment.*****.ac.in.zip
![image](https://github.com/MrKeral/How-I-Hacked-My-College-Website/assets/82687464/2aa778ea-7aef-453e-a871-60aef706a0db) 

While reading every file, there is three files(ccavRequestHandler.php, ccavResponsetHandler.php, config.php) where I got the username & password of the database. Oviously PHPMYADMIN.
![image](https://github.com/MrKeral/How-I-Hacked-My-College-Website/assets/82687464/b0f8f179-e95c-4ce7-8849-9832e96134ef)

And here information disclouser is also done, becuse I got some mail IDs of payment department employees.
![image](https://github.com/MrKeral/How-I-Hacked-My-College-Website/assets/82687464/5db493dc-debb-4960-b7f0-2d5352ba159a)

Now I stop hunting beacuse I got critical information. So now I reported to HoD & Dean of my college..

That's all...

