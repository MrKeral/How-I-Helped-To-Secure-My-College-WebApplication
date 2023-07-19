# How-I-Hacked-My-College-Website
**Welcome!!!**

Let see how I found Critical information on my college website's subdomain.

Note: Before I begin, I want to admit that I made a mistake by not seeking permission from the right people before checking out the website. It's not okay, and I strongly advise against trying anything like this without permission. My story is just to show the importance of reporting vulnerabilities responsibly and being ethical online.

Target: https://payment.*****.ac.in

Phase 1 - Gathering Information: First, I looked into the website (https://*****.ac.in) to learn more about it. I checked out things like sub-domains, directories, old URLs, and some other details like IP addresses and mail servers.

Interesting Find: During my exploration, I found a link to a file with a .zip extension. It caught my attention, and I wanted to see what was inside.

Challenge - Dealing with a Firewall: The website https://payment.*****.ac.in had a security system called ModSecurity (SpiderLabs) WAF (Web Application Firewall). It meant I couldn't access some parts of the site. To get around this, I looked up how to bypass it on Google and watched some YouTube videos. I found a blog post that helped me bypass the WAF.

Being Responsible: I won't explain how I bypassed the WAF here because it's still a vulnerable spot on the website.

Phase 2 - Downloading the .zip File: With the WAF bypassed, I was able to download the mysterious .zip file called payment.*****.ac.in.zip.

Surprising Discoveries: Inside the .zip file, I found three files - ccavRequestHandler.php, ccavResponsetHandler.php, and config.php. These files had sensitive information like usernames and passwords for the PHPMYADMIN database. I also came across some email addresses of employees in the payment department.

Stopping the Hunt: At this point, I realized I had found critical information and decided not to continue. It was essential to do the right thing.

Doing the Responsible Thing: I reported my findings to the Head of the Department (HoD) and the Dean of my college so they could take appropriate action.

Conclusion: My story reminds us all about the importance of being ethical and responsible online. Unauthorized hacking is not only wrong but also illegal. Always ask for permission before testing security, and if you find any issues, report them to the right people. Together, we can make the internet safer for everyone.
