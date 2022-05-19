# Security-notes
Just passed Network+ so unto the Security+. This will be my notes for the test, mainly based of the Professor Messer's videos, but there might be bits and peices of information that I compiled from elsewhere.

## 1.0 Treats, attacks and Vulnerbilities (24% of the exam)
* 1.1 [Phishing](https://github.com/HiroNewf/Security-notes/blob/main/README.md#phishing)
* 1.1 [Impersonation](https://github.com/HiroNewf/Security-notes/blob/main/README.md#impersonation)
* 1.1 [Dumpster Diving](https://github.com/HiroNewf/Security-notes/blob/main/README.md#dumpster-diving)
* 1.1 [Shoulder Surfing](https://github.com/HiroNewf/Security-notes/blob/main/README.md#shoulder-surfing)
* 1.1 [Hoaxes](https://github.com/HiroNewf/Security-notes/blob/main/README.md#hoaxes)
* 1.1 [Watering Hole Attacks](https://github.com/HiroNewf/Security-notes/blob/main/README.md#watering-hole-attacks)
* 1.1 [Spam](https://github.com/HiroNewf/Security-notes/blob/main/README.md#spam)
* 1.1 [Influence Campaigns](https://github.com/HiroNewf/Security-notes/blob/main/README.md#influence-campaigns)
* 1.1 [Other Social Engineering Attacks](https://github.com/HiroNewf/Security-notes/blob/main/README.md#other-social-engineering-attacks)
* 1.1 [Principles of Social Engineering](https://github.com/HiroNewf/Security-notes/blob/main/README.md#principles-of-social-engineering)
* 1.2 [An Overview of Malware](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#an-overview-of-malware)
* 1.2 [Viruses and Worms](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#viruses-and-worms)
* 1.2 [Ransomware and Crypto-malware](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#ransomware-and-crypto-malware)
## 2.0 Architecture and Design (21% of the exam)
## 3.0 Implementation (25% of the exam)
## 4.0 Operations and Incident Response (16% of the exam)
## 5.0 Governance, Risk, and Compliance (14% of the exam) 

# 1.0 
## [Phishing](https://www.youtube.com/watch?v=0Tr8avVrzLA&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=2&ab_channel=ProfessorMesser)
- Trying to get you to click an email link
    - Social engineering and spoofing
- Pretending to be someone they are not
- Check the URL, it’s going to be different than the official site (Probably only a one character difference though)
    - The screen presented is also likely to be a bit off, wrong font, messed up graphics, incorrect spelling, ect
- Try to get you to react to a fake situation (need to change password, need to pay a bill, got hacked and need to resolve the issue, ect)
- Pharming is attacking a whole group of people at once
    - Usually when they are able to take control of a whole DNS server or fine vulnerable websites
    - Redirect you from the official website to the fake one
    - Hard to prevent this from happening and notice that something is wrong
        - Even anti-malware has trouble recognizing this
- Vishing
    - Phishing over a voice call
    - Often spoof a caller ID to act like they are someone trust worthy
    - Try to get you to give up personal information
- Smishing
    - Phishing over SMS / text message
- Find the best way to Phish
    - Reconnaissance
        - Social media
    - Make a believable pretext off of this information
- Very directed attacks like this are called Spear phishing
    - When the attack goes after someone who has a lot of money or a lot of information (like a CEO) is called Whaling
## [Impersonation](https://www.youtube.com/watch?v=hIUr86pysb4&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=3&ab_channel=ProfessorMesser)
- Often starts with a pretext
    - An actor and a story that is trying to be as believable as possible
- Pretending to be someone you are not
    - Usually picks who to impersonate based on info they gathered from reconnaissance
    - Try to get you to trust them
    - Try to get you to to act on what they say (make you think they are of higher rank than you)
    - Act friendly to try and make you feel conformable
- Now it is time to elicit information
    - Email addresses, passwords, ect
    - Commonly done with Vishing
- Identity fraud
    - They may be after your personal information
    - Credit Card fraud
    - Bank fraud
    - Loan fraud (opens loans in your name)
    - Governance benefits or Tax fraud
- Avoiding this
    - Never volunteer your information to people
        - They tech support does not need to know your password
    - Dont over give information, they probably dont need to know that much information
    - Verify who you are talking too and that they can have access to sensitive data
## [Dumpster Diving](https://www.youtube.com/watch?v=h0UfLMy_Fq0&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=4&ab_channel=ProfessorMesser)

- A way of gathering important information about a target (reconnaissance)
    - Phone numbers, addresses, names, ect
- Generally legal in the US but that varies from place to place
- To prevent this use a fence and lock
    - Shred important documents and destroy used tech products

## [Shoulder Surfing](https://www.youtube.com/watch?v=mQH5x559kD4&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=5&ab_channel=ProfessorMesser)

- You may have important things on your computer
    - Attackers can look over your shoulder and get some of this information
- Can do this from afar with binoculars
- Be aware of your surroundings to try and prevent this
    - Could use privacy filters
        - Blocks the view of anyone that is not right in front of the computer
    - Keep your monitor out of the site of others if possible

## [Hoaxes](https://www.youtube.com/watch?v=9fXbXQ-pnsY&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=6&ab_channel=ProfessorMesser)

- Situation that seems real, but does not really exist
    - Can take many different forms
        - Fake viruses
        - Email
        - Phone
        - ect
- Wastes time and resources
- Tend to try and get money from you (through gift cards mostly often)
- De-hoaxing
    - Trust no one
    - Cross reference
    - Use a spam filter
    - If it is too good to be true, then it probably is

## [Watering Hole Attacks](https://www.youtube.com/watch?v=uBoVWqkfZjk&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=7&ab_channel=ProfessorMesser)

- Instead of attacking your target directly, you attack a third party and hope to use that third party to then infect your real target
    - Usually done when your target has too high of security for you to directly breech
    - This third party is the watering hole
- Takes a bit of research in order to find the right third party to attack
- Often effects everyone who goes to this third party site or service even though the attacker is only looking to effect one organization
- Make sure your systems are well secured to protect against this
    - A layered defense / defense in depth
    - Firewalls and IPS
## [Spam](https://www.youtube.com/watch?v=5zYJwdEOQ0M&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=8&ab_channel=ProfessorMesser)

- Unsolicited Messages
- SPIM = Span over Instant Messaging
- Many types of spam both malicious and non malicious, both cause issues
    - Security concerns, resource utilization, storage costs, ect
- Blocking spam
    - Mail gateways
        - Your spam filtering that is on site or cloud based
        - Has an allowed list
            - Requires a lot of maintenance
        - Block anythings that doesn’t comply with the RFC’s
        - Can perform a reverse DNS to check IP’s
        - Tarpitting
            - Slows down the mail server to make the process of sending and receiving mail take time
            - Can deter spam
        - Filtering based on the recipient and filter out invalid recipient

## [Influence Campaigns](https://www.youtube.com/watch?v=nH-qEY9h83E&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=9&ab_channel=ProfessorMesser)

- Hacking public opinion
    - Influence campaigns and opinions
    - Spend a lot of advertising money
- Usually starts with fake accounts
    - They make content on many different sites
    - Then the message gets amplified the message
    - Real people start to talk about it
    - The media picks it up and the story gets even bigger
- The military could sometimes do this to effect other countries and how they work and think
    - Cyber-warfare
    - Influence elections, news and more

## [Other Social Engineering Attacks](https://www.youtube.com/watch?v=trAs7C5h1BU&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=10&ab_channel=ProfessorMesser)

- Tailgating
    - Gain access to a building that you should not have access too by following an official person in
    - Pretend to be a third party with a legitimate reason
    - Maybe carry something with you so your hands are not free and often someone will hold the door open for you
    - Make sure you have a policy for visitors
    - Make it so only one person can enter at a time
        - Mantrap or other
- Invoice scams
    - Starts with a bit of spear phishing
        - Attacker knows who pays the bills and sends a bill to that person in attempts to get money
        - Often for products that you are in fact using and the email can look pretty legit
        - Might also have a link to pay so they can get even more info
- Credential harvesting
    - Gain access to usernames and passwords on your local PC
    - Trying to find everyplace where these login credentials are stored and get them so they can use them for themselves
        - Runs a script on the computer (usually sent via an email)
        - User can be none the wiser

## [Principles of Social engineering](https://www.youtube.com/watch?v=ndwCR1kYz5M&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=11&ab_channel=ProfessorMesser)

- Constantly changing attack
- May involve many people and organizations to make things more believable
- More automated and using open source intelligence
- Authority
    - Act like they are in charge and have a high rank
- Intimation
    - If you dont help things will go bad
- Social proof
    - Convince someone this is what is normally happens
- Scarcity
    - Limited amount of time so it must happen now
- Urgency
    - Needs to happens quickly
    - dont think, just act
- Familiarity / liking
    - Someone you know, act all friendly and talk as if they know you
    - We have common friends (could name drop)
- Trust
    - Say they are from IT
    - Say there are here to help, ect
## [An Overview of Malware](https://www.youtube.com/watch?v=GrdOpFFGxD0&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=12&ab_channel=ProfessorMesser)

- Malicious software
- Gathering information
    - Keystrokes
    - Passwords
    - ect
- Make your computer controlled by someone else
    - Become a bot likely as part of a botnet
- Show advertisement to make tons of money
- Viruses and worms
    - Encrypt your data and demand payment
- The malware can keep growing and installing more and more
- Preventing this
    - Dont click links in emails
    - Dont click web page pop ups
    - Dont go to un-trusted sites
    - Patch vulnerabilities

## [Viruses and Worms](https://www.youtube.com/watch?v=L7cwUYl8gYo&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=13&ab_channel=ProfessorMesser)

- Virus
    - Malware that can reproduce itself
        - Via the file system or network
    - Needs the user to execute a program to run
    - Can delete files, encrypt data, advertise and more
    - Anti-virus software is decent at preventing this
        - Make sure to keep it up to date
    - Program Viruses
        - Part of the application
        - Opening the application launches the virus as well
    - Boot sector viruses
        - In the boot sector of the storage device
        - Launches when you launch the OS
    - Script viruses
        - In the OS or browser
    - Macro viruses
        - Common in Microsoft Windows
        - A lot like script viruses
    - File-less virus
        - Never installs or saves itself as a file
        - Good at avoiding detection via anti-virus software
        - Operates in the memory (RAM)
        - Commonly starts via a link
            - Downloads and runs a flash or java file (or other)
            - Launches Powershell and downloads payload into the RAM
- Worms
    - Malware the self replicates
        - Launches and moves from system to system without users doing anything
    - Takes advantage of vulnerabilities in networking and computer systems
        - Can infect millions of systems
    - Firewalls and IPS can help to stop this from happening and spreading

## [Ransomware and Crypto-malware](https://www.youtube.com/watch?v=HszU4nEAlFc&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=14&ab_channel=ProfessorMesser)

- Ransomware
    - Your data is valuable to you
        - Company data is even more valuable and important
    - How much would you pay to regain access to it?
    - Claiming they encrypted/took your data and requiring you to pay to get it back is ransomware
        - Payment often in bitcoin
    - They could claim to be someone they are not, like the CIA
- Cyrpto-malware
    - New gen of ransomware
    - Actually locking your data behind an encryption
        - Send them money and you will get the key to decrypt the data
- Protecting yourself against it
    - Have a good backup
    - Offline backup or offsite backup is best
    - Keep patches up to date
        - Keep applications up to date as well
        - Everything up to date
