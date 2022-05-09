# Use Case 1: End User leans on their endpoint protection software as he experiences a phishing attack, malware is prevented.

## Description

Of note – but very much going on in the background - as Bob turns on his computer, Bob’s endpoint protection software starts up and checks for any new updates from the software manufacturer. A small set of signatures have been published overnight. Unknown to Bob, the signatures are installed in the background, ensuring that Bob’s computer is protected from the latest known malware attacks. The software also checks in with Bob’s corporate network asking a similar question, “Are there any new blocks we need to know about?” the software asks the corporate library of rules. No new rules are downloaded as no filters, blocks, proxy rules or firewall rules have been created in the last 16 hours.

Our story continues with Bob - He is eager to follow up on a project so he does not notice that the “from” name is "Alice", but it is not displaying as it typically would. He clicks anyways, as he is looking forward to the next step in a project.

Bob opens the e-mail to see “I found this link that I think will help us with our project, talk soon” – followed by a URL.

Of course Bob clicks the link, and this is what we call a phishing – or in the case of a specific user, a focused “spear phishing” attack.

The web site Bob accesses contains a zero-day cyber vulnerability. Bob did not catch it, his e-mail system’s filter did not, and now Bob’s endpoint software has to take over.

The link that Bob clicked opened up a few interesting tidbits, but it did not seem very apropos to Bob and Alice’s project. He ignored the rest of the site, realizing – too late – that this sounded like one of those examples from his security awareness training. “I probably should not have clicked that,” Bob thought. He looked again at the tempting e-mail and saw that while it had Alice’s first name, it did not include a last name. And he hovered his mouse over the URL and realized, “...not a good site... uhoh.”

Bob hasn’t seen anything else strange, he only clicked a link and realized quickly that it was off topic – he closed the screen so fast, at this point Bob’s fears dwell and he goes about his coffee – and his day.

In the background, however, the damage was done in a split second. Bob’s computer saw Bob click a link

- he initiated it, and Bob’s computer’s policies allow him to install software. The software installed itself and after setting a timer to “go off” in 4 hours, the bad program went dormant.

Malware was installed immediately as Bob clicked the URL – it all happened as the web page loaded.
Bob’s endpoint protection software scanned the new program that was downloaded in the background

- the software scans all files coming and going on Bob’s computer.

When the new program starts to run, the virus software compares the digital signature, the certificate used to sign it, and the name, size and date on the program to its database of known malware attacks.

The new program does not match the database. The endpoint software flags it as a new, unsafe program.

Many people in Bob’s company are business and mission focused – they are not savvy IT people. Because alerts have created a lot of extra calls and support costs, this security event – unknown software – does not pop up on Bob’s computer.

Instead the endpoint software sends an alert to the corporate logging tools.
