---
layout: post
title: Security through elimination is not secure enough
date: 2020-03-03 13:32:20 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: mac.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [security]
---
## Security through elimination is not secure enough
With the current day and age being almost completely data-driven, security is a word that has been common. Though, I think its real meaning being not so common yet. Some recent news that was heard recently were as follows:

Case 1:

>[https://entrackr.com/2020/03/why-is-paytm-flagging-teamviewer-zoom-apps-as-threat/](https://entrackr.com/2020/03/why-is-paytm-flagging-teamviewer-zoom-apps-as-threat/)

"If your smartphone has remote desktop apps like TeamViewer, AnyDesk and Zoom installed then you will not be able to use the online payment app: Paytm."

>"While the SoftBank-backed firm has been asking users to uninstall the aforementioned apps on the pretext of security threats, its own mobile application is notorious for collecting all kinds of “confidential data” from its users. When a user installs the Paytm app and agrees to its terms and condition, it gets access to the user’s phone status and identity, permission to read sensitive log data, modify or delete the content of users USB storage, record audio, track location and read calendar events, among others."

I use Zoom on a near regular basis and so do many other people. Security is not a problem because of VC apps, it is a problem of the current era and the mindset that banning pen drives is a "security" feature. What is the solution to people answering phishing calls? Banning the call feature of the phone?

Case 2

>[https://timesofindia.indiatimes.com/business/india-business/no-support-for-win-7-but-most-atms-yet-to-upgrade/articleshow/74291769.cms](https://timesofindia.indiatimes.com/business/india-business/no-support-for-win-7-but-most-atms-yet-to-upgrade/articleshow/74291769.cms)

>"According to industry sources, many banks have not yet discussed an upgrade with their management service providers although an RBI circular in June 2018 mandated using supported versions of operating systems in ATMs. Given that the Indian banking industry has deployed over 2 lakh ATMs, the cost of an upgrade is expected to run into hundreds of crores."

The logic given in most cases is, the ATMS's are not connected to the internet hence "security" is not a risk to them. Then card up-gradation happens, like a band-aid on a stab wound, and the world continues happily. Some get skimmed right at the financial centre of this country and everybody thinks, may he was not "secure" enough.

Case 3

>[https://www.sixthtone.com/news/1002770/how-hackers-take-abandoned-chinese-uber-accounts-for-a-wild-ride](https://www.sixthtone.com/news/1002770/how-hackers-take-abandoned-chinese-uber-accounts-for-a-wild-ride)

>"If a person’s Uber account was charged for multiple rides in such a short period of time in a bizarre location, why didn’t Uber warn its user or just suspend the account?"

This article is two years old, but such instances happen even today. It took a company like Uber two years to listen to consumers on reports of account takeover. Uber did not acknowledge that a 4 digit OTP was just not large enough! A close friend of mine just faced this 6 months back and reported it, as there was a random person in Bangalore taking a one-time airport trip from an account with saved card details. The friend never saw the deducted Rs 2500 despite argument. The worst part? The friend had two factors enabled [which means a change can only happen if a second unique code like an OTP is provided] on the app, and yet a hacker was able to change the email and phone number with zero intimation to the friend. The friend had to cancel the card reissue another one. Uber blamed the friend for not being "secure" enough.

[On a side note, how costly is Bangalore, that the poor person thought it was easier to just hack a bloody uber account to take a trip to the airport]

Case 4

>[https://gizmodo.com/anyone-can-look-at-millions-of-americans-medical-images-1838178643](https://gizmodo.com/anyone-can-look-at-millions-of-americans-medical-images-1838178643)

>"It turns out that anyone with basic computing skills and an internet connection can access millions of private medical images and data—such as MRIs, X-rays, and CT scans—as well as a buffet of valuable private info, according to a disturbing report from ProPublica."

Recently, a cousin of mine went into a coma and died months later. While the family was grieving and hoping, I was checking his brain scans for signs of life. Somehow got an unauthenticated link [doesn't need any password to view] to check the same from one of the leading hospitals in Kolkata, India. There were certain links to the left like "Check all patients info", and "edit patient info". Guess what the MRI software that provided the software to the hospital did not give them an authentication module. Essentially anyone in the world could see who all were the patients in the hospital and modify to the heart's content. I reported the same to the hospital and the vulnerability still exists.

Being in technology services and product side for six years now, I have heard insane ways to put security in place, starting from banning Google, to using archaic VPN software that disable the internet on the person's working machine. The only thing this does is support stupidity and block knowledge and progress. I get that updating platforms is costly and simply a far less economical option for the businesses and behemoths. It is easier to blame the bloody consumer. But in this day and age, if you are dealing with sensitive data, you better bloody pony up and invest, else go sell bananas.

On a lighter note: listen to your consumers, they might point symptoms that don't make sense, but they might just point you to the problem. 500-mile email

