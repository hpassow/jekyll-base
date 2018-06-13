---
layout: post
title:  "Netlify Exercises"
date:   2018-06-13 01:15:27
categories: Netlify
---

<b>Most Favorite</b>  
Respond to 50+ support requests via email or chat most days - I did this at GoDaddy with no issues.  
Engage multiple users at once via chat to answer their questions and troubleshoot problems - As above.  
Help train and onboard new support teammates - I really enjoy getting new people up to speed.    
Spot trends across many cases to improve Netlify's product and service. - This is oddly something I'm fairly good at doing.  I'm fairly good at noticing trends.  
Help manage communications during a service outage - After time with Charles Schwab when we really WERE losing millions of dollars a second if something was down, I've got the ability to keep a pretty cool head in a crisis. ;)  
  
<b>Least Favorite</b>  
Work with prospective customers to explain our service and the pricing model - too close to "sales", and I'm rubbish at sales.  
Respond to Netlify customers on Twitter - I don't like Twitter.  I can't explain it.  It's just a thing.  
Deliver a talk to many people you don't know at a conference or meetup - See also: introvert  
Dig through server logs to troubleshoot a customer's website behavior - I can do it.  "vi /var/log/httpd/error_log" and I are old friends.  But it's not my favorite thing in the world to comb through.  
Find and recruit teammates for the Support team - I'm happy to train people, but I'm not naturally outgoing enough to be a recruiter.  
<br><br><br>
_What is your favorite thing about providing technical support?_  

My favorite thing about providing technical support is when someone has been extremely frustrated with something and then getting them to that "aha!" moment where they understand what the issue is.  It's incredibly rewarding to see that lightbulb go off and someone truly grok what's happening.

<br><br><br>

_What did you think of our service during the time you used it?  Provide either some constructive criticism or some points that impressed you.  Be honest!  “It sucked” isn’t a wrong answer unless you don’t elaborate and provide some constructive criticism ;)
Talk about how you made your site and why you chose the tools you did.  Briefly explain a challenge you experienced in setting up this site and how you solved it._

I found Netlify to be super easy to use.  I started out doing web sites in vim/Notepad and my current site is WordPress.  I haven't really done a good deal in between, and I haven't had need to play with anything more technical on the web development front.  I was really impressed with how super easy it was to deploy.  

I chose Jekyll because it was highly rated.  Knowing I don't know a good deal about how this is deployed, something highly rated will generally tend to have fewer bugs on the whole.  The only problem I encountered during setup was with that, not with Netlify.  I was mostly making it too hard on myself.  I didn't realize that regular HTML code would work, and I was having issues with formatting and line breaks.  *Sheepish look* That was solved with Google.

I also had to stop myself from changing the theme around too much and customizing the site.  It's an aesthetics thing.

<br><br><br>

<i>Provide a link to documentation for a technical/developer-focused product, which you think are well done, and briefly explain why you think they are well done.</i>

Easy.  <a href="http://developer.mailchimp.com/documentation/mailchimp/">http://developer.mailchimp.com/documentation/mailchimp/</a> - seriously, MailChimp should be the guiding star of all documentation everywhere.  If they've documented it, it's there.  If they haven't documented it, it might also be there.  Beautifully laid out, tons of information, and not at all counter-intuitive.

<br><br><br>

<i>Why do you think SSL/HTTPS is important?</i>

SSL/HTTPS is important because we're seeing more and more compromises, and more people working on open wifi networks that are now more widely available (and doing so without a VPN).  Without an SSL, anyone can intercept that traffic that you're sending with your passwords, bank information, credit card number, etc.  

<br><br><br>

<i>Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users.</i>

I ran in to this a good deal during my time at GoDaddy.  The major challenges that I encountered during DNS configuration were usually a misunderstanding of how to properly configure A and CNAME records.  That's pretty quickly solved with DIG.  While "technically" DNS propagation can take 24-48 hours, that would be exceedingly unlikely.  As a general rule, it's almost instantaneous. 

SPF <i>could</i> be tricky, but that was solved by depreciation.  The only other real major issue I encountered was people not registering their name servers with the registrar.  That's an issue in GoDaddy, true, but at least in Google Domains, it's pretty quick and easy.  I tend to believe it's more that GoDaddy's DNS configuration tool isn't as straightforward about that as some others, but I only have extensive experience in their systems.

<br><br><br>

<i>A customer writes in saying their “site won’t build”.  Compose: your best short (2-paragraph) customer-facing answer, without any additional data, that could be useful in the generic case, but would also lead to a customer providing a more actionable response.</i>

Hello ($CustomerName),

I understand your site won't build.  I apologize for the frustration.  Let's get you back on track.  First and foremost, make sure that your site will build locally.  If so, double check the package versions in the <a href="https://www.netlify.com/docs/build-settings/">Build Settings</a> we are using match yours.  

The most common build errors are listed in the link below:<br>
<a href="https://www.netlify.com/docs/build-gotchas/">Build Gotchas</a><br>

If you are still experiencing errors, please respond with the exact error message and the steps you are taking to receive that message, and I'll be happy to assist you further.

Thank you,
Heather Passow
Netlify Support

<br><br><br>

<i>(optional/bonus) Can you set up a redirect from “/netlify/anything” to https://www.google.com/search?q=anything ?  </i>  
Yes, I can.  

And, while I was tempted to just leave it at that, <a href="https://netlify.theroadiswide.com/netlify/timesscar">https://netlify.theroadiswide.com/netlify/timesscar</a> is what you're looking for.  It's random, but it's what was on the playlist when I was doing this section.

<br><br><br>

<i>(optional/bonus) Could you give us a suggestion to improve this test or the job posting?</i>

Well, the previous question could just be answered with a yes or no.  You might want to try reformatting it to "Please demonstrate a redirect..."
