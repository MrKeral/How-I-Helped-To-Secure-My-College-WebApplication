# How-I-Helped-To-Secure-My-College-WebApplication
<h2>Welcome!!!</h2>

<h3><b>Let see how I uncovered critical information on my college web application.</b></h3>

Note: Before I begin, I want to admit that I made a mistake by not seeking permission from the right people before checking out the website. It's not okay, and I strongly advise against trying anything like this without permission. My story is just to show the importance of reporting vulnerabilities responsibly and being ethical online.

<h3>Target: https://payment.*****.ac.in</h3>

<b>Phase 1- Gathering Information:</b>  First, I looked into the website (https://*****.ac.in) to learn more about it. I checked out things like sub-domains, directories, wayback URLs, and some other details like IP addresses and mail servers.

<b>Interesting Find:</b> During my exploration, I found a link to a file with a .zip extension. It caught my attention, and I wanted to see what was inside.

<b>Challenge - Dealing with a Firewall:</b> The website https://payment.*****.ac.in had a security system called ModSecurity (SpiderLabs) WAF (Web Application Firewall). It meant I couldn't access some parts of the site. To get around this, I looked up how to bypass it on Google and watched some YouTube videos. I found a blog post that helped me bypass the WAF.

<b>Being Responsible:</b> I won't explain how I bypassed the WAF here because it's still a vulnerable spot on the website.

<b>Phase 2 - Downloading the .zip File:</b> With the WAF bypassed, I was able to download the mysterious .zip file called payment.*****.ac.in.zip.
![image](https://github.com/MrKeral/How-I-Hacked-My-College-Website/assets/82687464/c159083d-5b54-4472-a23e-8274386acda0)


<b>Surprising Discoveries:</b> Inside the .zip file, I found three files - ccavRequestHandler.php, ccavResponsetHandler.php, and config.php. These files had sensitive information like usernames and passwords for the PHPMYADMIN database. 
![image](https://github.com/MrKeral/How-I-Hacked-My-College-Website/assets/82687464/54ced9fc-b5e9-4c1f-86be-c84da6f65f61)

I also came across some email addresses of employees in the payment department.
![image](https://github.com/MrKeral/How-I-Hacked-My-College-Website/assets/82687464/9816c388-9ede-4f42-805a-3c1ae282829b)


<b>Stopping the Hunt:</b> At this point, I realized I had found critical information and decided not to continue. It was essential to do the right thing.

<b>Doing the Responsible Thing:</b> I reported my findings to the Head of the Department (HoD) and the Dean of my department so they could take appropriate action.

<b>Conclusion:</b> My story reminds us all about the importance of being ethical and responsible online. Unauthorized hacking is not only wrong but also illegal. Always ask for permission before testing security, and if you find any issues, report them to the right people. Together, we can make the internet safer for everyone.
