# Security+ Notes
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
* 1.2 [Trojan and RATs](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#trojan-and-rats)
* 1.2 [Rootkits](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#rootkits)
* 1.2 [Spyware](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#spyware)
* 1.2 [Bots and Botnets](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#bots-and-botnets)
* 1.2 [Logic Bombs](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#logic-bombs)
* 1.2 [Password Attacks](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#password-attacks)
* 1.2 [Physical Attacks](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#physical-attacks)
* 1.2 [Adversarial Artificial Intelligence](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#adversarial-artificial-intelligence)
* 1.2 [Supply Chain Attacks](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#supply-chain-attacks)
* 1.2 [Cloud-based vs On-premises Attacks](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#cloud-based-vs-on-premises-attacks)
* 1.2 [Cryptographic Attacks](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#cryptographic-attacks)
* 1.3 [Privilege Escalation](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#privilege-escalation)
* 1.3 [Cross-site Scripting](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#cross-site-scripting)
* 1.3 [Injection Attacks](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#injection-attacks)
* 1.3 [Buffer Overflows](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#buffer-overflows)
* 1.3 [Replay Attacks](https://github.com/HiroNewf/Security-Plus-Notes/blob/main/README.md#replay-attacks)
* 1.3 [Request Forgeries](https://github.com/HiroNewf/Security-Plus-Notes#request-forgeries)
* 1.3 [Driver Manipulation](https://github.com/HiroNewf/Security-Plus-Notes#driver-manipulation)
* 1.3 [SSL Stripping](https://github.com/HiroNewf/Security-Plus-Notes#ssl-stripping-http-downgrade)
* 1.3 [Race Conditions](https://github.com/HiroNewf/Security-Plus-Notes#race-conditions)
* 1.3 [Other Application Attacks](https://github.com/HiroNewf/Security-Plus-Notes#other-application-attacks)
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
## [Trojan and RATs](https://www.youtube.com/watch?v=yhhEOseCOzg&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=15&ab_channel=ProfessorMesser)

- Trojan
    - Software pretends to be something else (something normal and safe)
        - Looks nonthreatening to you and your anti virus software
            - Can even disable your anti virus software at times
    - Doesn’t really try to duplicate
    - Now it has free reign
        - Can install more malware or install backdoors
- PUP (Potentially Unwanted Program)
    - Could be downloaded by the Trojan
    - May cause performance issues but not necessarily malicious
        - Displays adds, redirecting your web searches, ect
    - Can be identified by anti virus software quite easily
- Backdoors
    - Why go through normal authentication methods when you can go through the backdoor?
        - An easy way to get into your system
    - Often placed on your systems via malware
        - Malware can use the backdoors that other malware created to make it easier to get into your system
    - Some “trusted” software have backdoors as well as part of the app (this is not good)
- RATs (Remote Access Trojans)
    - The ultimate backdoor
        - Admin/root control over a device and OS
            - Things like key logging
            - Screen recording
            - Copying files
            - Installing more malware
            - ect
    - Malware installs it
- Preventing these
    - Dont click unknown links
    - Keep an anti virus software running
    - Keep backups of files

## [Rootkits](https://www.youtube.com/watch?v=X9x2UzzXP8w&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=16&ab_channel=ProfessorMesser)

- Originated from Unix/Linux
- Modifies the core system files
    - The kernel files
- Can be invisible to the OS and anti virus software
- Zeus/Zbot
    - Combined rootkit and other malware
    - Famous for cleaning out bank accounts
    - Almost impossible to delete the malware
- Some software programs can look for and remove certain types of rootkits
    - Secure Boot with UEFI prevents rootkits on modern systems

## [Spyware](https://www.youtube.com/watch?v=jaZZaghcNOs&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=17&ab_channel=ProfessorMesser)

- Adware
    - Ads everywhere on your computer
    - Causes performance issues on your device and network
    - Sometimes installed accidentally
    - Watch out for software that claims it can remove adware
        - But it itself might be adware or other malware
- Spyware
    - Malware that spies on you
        - Advertising, identity theft, affiliate fraud, ect
        - Browser monitoring, keyloggers, ect
    - Often installed via a Trojan horse
- Adware and spyware can make the attacker a ton of money
- Protecting against it
    - Have an up to date anti virus software
    - Know what you are installing and make sure you trust it
    - Keep file backups as the adware and spyware is hard to remove from a system

## [Bots and Botnets](https://www.youtube.com/watch?v=CHrES3Swpw4&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=18&ab_channel=ProfessorMesser)

- Bots
    - An infected computer that is a bot for someone else
        - Installed via a Trojan horse, vulnerability, alongside a another software program, ect
- Botnet
    - A group of bots
    - Just sits around until the Command and Control (C&C) server tells them to do something
    - All of systems can cause many problems like DDoS attacks
        - Can proxy spam, network traffic, be rented out, ect
- Stopping them
    - Prevent them from installed in the first place
        - OS and application patches
        - Anti virus software
    - Using an on demand network scan can find existing infections
    - C&C Can be block at the firewall if you know what to look for

## [Logic Bombs](https://www.youtube.com/watch?v=javj1IqXKW0&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=19&ab_channel=ProfessorMesser)

- Waits for a certain event to be triggered and then activates
    - Occurs when a date and time is reached
    - Occurs when a certain user event takes place
- Hard to identify and hard to recover
    - Many delete themselves once they execute
- Preventing them
    - Formal change control process
        - Know when things are being modified
    - Automated monitoring
        - Host based intrusion detection, Tripwire, ect
    - Constant auditing
        - Admins can go around other systems so auditing is good to keep track of what they and other users are doing
## [Password attacks](https://www.youtube.com/watch?v=hNhak8IilrA&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=20&ab_channel=ProfessorMesser)

- Plaintext passwords
    - Stored in a readable format
    - This is a terrible idea (dont use apps that do this)
- Hashing a password
    - Input your password and pick which hash type to use
        - Get a random series of numbers and letters in return
        - Inputting this password will always give you the same hash but it is very hard to get the password from the hash itself (other than brute force)
- Spraying attacks
    - Avoids locking the account by trying so many passwords
    - Use the most common passwords and moves on if this does not work
        - No alarms, alerts, or lockouts
- Brute Force
    - Trying every single possible password (or hash)
    - Takes a lot of time and a lot of compute power
    - Hard to do online as their is often delays and lockouts
        - But it is possible offline with hashes
- Dictionary attacks
    - Use the most common words to try and find the correct password
    - There are many different wordlists that can be broken down by native language, line of work, hobbies, etc that can be useful if you know things about your target and their life
    - Can substitute letters like replacing 0 with O and replacing 2 with @
    - Takes some time but not nearly as long as brute force attacks
- Rainbow tables
    - An optimized pre-built set of hashes
    - Easy and quick to search through
        - Almost instantly
    - Need different tables for different hashing methods
- Adding salt
    - Random data added to a password BEFORE it is hashed
    - Every user gets their own random salt data
    - Rainbow tables will not work against this
        - Slows down the brute force process

## [Physical Attacks](https://www.youtube.com/watch?v=efOGCvcfJl4&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=21&ab_channel=ProfessorMesser)

- Malicious USB cable
    - Looks like normal but has additional electronics inside
    - Could tell OS that it is a HID and be able to type things
        - Gain control of your system and install malware and the likes
    - Dont plug in random cables
- Malicious Flash Drive
    - Like the USB cable it has additional electronics inside that cause issues to your PC
    - Could act as a HID like the USB cable
        - Like in USB drop attacks with the Rubber Ducky
    - Files in the drive could also infect your system
        - If you open this picture a program runs, etc
    - Could act as a boot device or Ethernet adapter
- Skimming
    - Stealing credit card information usually during a normal transaction
        - Copying magnetic stripe or the info written on the card
    - Requires extra hardware on the scanners
        - Could also have a camera to learn your PIN
- Card Cloning
    - Get card details from a skimmer and then make an exact duplicate
    - Commonly used with magnetic stripe cards
        - The chips cant be cloned
    - Can also happen with gift cards

## [Adversarial Artificial Intelligence](https://www.youtube.com/watch?v=aXZ-BF8Ot-o&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=22&ab_channel=ProfessorMesser)

- Machine Learning
    - Computers are getting smarter
        - Find data patterns and improve predictions
    - Requires and ton of data and compute power
    - It is used everyday
        - Spam filter that recognizes spam
        - Ads recommended based on your search history and other data
        - etc
- Poisoning the training data
    - Confuses the AI with fake info
    - Make the AI act how you want based on the info you sent to it
- Evasion attacks
    - AI is only as good as the training
    - Attackers can change their approach to try and get around the machine learning
    - An attacker may be able to extract the data from a AI that used real world information to be trained
- Securing the learning algorithms
    - Make sure learning data is legitimate
    - Keep it up to date with the latest information
    - Use the attackers methods to make sure your system is no vulnerable

## [Supply Chain Attacks](https://www.youtube.com/watch?v=cOnjqpw5rXM&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=23&ab_channel=ProfessorMesser)

- Many moving parts in the supply chain
    - If one is attacked it can effect the others (the entire chain in some cases)
- People tend to trust the supplies even though they could have been attacked
- Supply chain security
    - Make sure what you are installing is trust worthy
    - Limit the number of vendors you work with
    - Have good policies and procedures (make sure your suppliers do the same)

## [Cloud-based vs On-premises attacks](https://www.youtube.com/watch?v=u_Ta0rVTL_g&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=25&ab_channel=ProfessorMesser)

- Attacks can happen anywhere
- Cloud security
    - Everything is centralized
    - Cheaper
    - No physical access
    - Third party does have access though
    - Large scale security that may be better than what you can do
    - Need to make sure your users are following the best practices
    - Limited downtime due to more redundancy and high quality products
    - Easy to change and update things
        - May be limited on what you can do with the data though
- On-premises security
    - On site and more costly
    - Full control of everything
    - On site team makes things more secure (hire the right people)
    - No need to call out to a third party
    - Take be time consuming and not instantaneous

## [Cryptographic Attacks](https://www.youtube.com/watch?v=u_Ta0rVTL_g&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=25&ab_channel=ProfessorMesser)

- Encrypted data sent to another person may not be secure the whole way to its destination
- Finding ways to undo security during the transfer process
    - implementation is often the problem
- Birthday attack
    - Hash collision is when you have two very different plaintexts that both create the same hash
        - Should not happen
    - Attacker tries to find the other plaintexts the matches a certain hash
        - Can be prevented by increasing the has output size
- Collisions
    - Hashes are supposed to be a unique value and it is quite bad when they are not
- Downgrade attack
    - Instead of using a good encryption you use something that is not that great
        - Force system to downgrade security
    - Sit in the middle and influence the encryption choice between two systems
        - Man in the middle attack may be used for this
## [Privilege Escalation](https://www.youtube.com/watch?v=ksjU3Iu195Q&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=26&ab_channel=ProfessorMesser)

- Gain high access to a system
    - Admin or root access from a normal users access
- Or just gaining access another user of the same level account
- Tend to be patch quickly
    - Keep anti virus up to date
- Data Execution prevention
    - Only allows applications to run in certain areas of memory
- Randomize where stuff is stored in memory to keep people from find the same data over multiple systems

## [Cross-site Scripting](https://www.youtube.com/watch?v=CyI0XF2xFg8&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=27&ab_channel=ProfessorMesser)

- aka XSS
    - Originally a browser vulnerability that allowed info from on site to be shared with another
- Common web app vulnerabilities
    - Takes advantage of the trust a user has for a site
- Uses JavaScript
- Non-persistent XSS attack
    - A site that allows scripts to run in user input
    - Attacker needs the user to click a link to start this attack (usually an email link)
    - Can get a lot of useful information from the victims machine
- Persistent XSS attack
    - Attacker posts a message to a social network (or other) that has the malicious payload
    - Everyone who reads the post gets the script
    - Many different targets, can spread quickly
- Tokens should have a limited amount of time and should NOT last forever
    - If they last forever you can get around the need to login
- Protecting against it
    - Be careful when clicking links
    - Could disable JavaScript entirely (but not very practical)
    - Keep your browser up to date
    - Devs should make sure that their input fields are validated

## [Injection Attacks](https://www.youtube.com/watch?v=e4KUdwh8rGo&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=28&ab_channel=ProfessorMesser)

- Code Injection
    - Attacker puts their own code into a data stream
    - HTML, SQL, XML, ect
- SQL injection
    - The most common relational database management system language
    - Your site should not allow this, but some do
- XML Injection
    - XML is common for transferring data between devices
    - Modifying the XML requests
        - This should not be possible
- LDAP injection
    - Has useful information stored in it
    - Modify the requests to get what you want
- DLL Injection
    - Inject code into an application and make the application execute the code
    - Runs as part of the normal process by attaching itself to a normal process

## [Buffer Overflows](https://www.youtube.com/watch?v=szTG9w3jImA&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=29&ab_channel=ProfessorMesser)

- When one section of memory can overwrite another section of memory
    - Takes advantage of poor programming
- Hard to find and take advantage of
- A good buffer overflow for an attacker is one that can be replicated and is easy to control

## [Replay Attacks](https://www.youtube.com/watch?v=jHydDY7wQJg&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=30&ab_channel=ProfessorMesser)

- Useful information is often transmitted over the network
    - Hackers can take advantage of this
- Needs to gather the data
    - Network tap, ARP poisoning, malware victim, etc
    - Get session IDs, credentials, etc
- If an attacker takes this gathered information and replays it through the network like it was coming from you than this is a replay attack
    - Replay attack can happen a long time after the gathering of the data
        - Does not involve the original user
    - Pretend you are the normal user sending normal data
- Session Hijack
    - The attacker gains access to the session ID
    - Can pose as the victim without login details needed
    - Get the session ID from wireshark or kismet
        - Or cross-site scripting
    - These headers or cookies need to then be modified
- Preventing them
    - Encrypting the information can stop this from being and issue as even if the attackers receives the data they cannot unencrypt it
        - Salting and peppering the data also helps
    - Make sure to secure the cookies!
        - They hold information like session management, session IDs, personalization, etc
## [Request Forgeries](https://www.youtube.com/watch?v=fmtqMzP7aXI&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=31&ab_channel=ProfessorMesser)

- Cross-site requests
    - Common and legitimate
    - Loading information from other sites (YouTube, twitter, etc)
    - Browser directs the page to find the right data
        - Most of these requests are unauthenticated
        - Client side code
            - Graphics and texts
                - HTML JavaScript
            - Server side code
                - Performs requests
                    - HTML PHP
    - One-click attack / session riding / client side request forgery (XSRF. CSRF)
        - Takes advantages of the trust a site has for the browser
            - Attacker gets access to your accounts via your browser which already has all the info needed
        - Web servers need to put techniques to prevent this
            - Cryptographic tokens or the likes
    - Server side request forgery (SSRF)
        - Sends requests to a web server and the web server performs the request on the behalf of the attacker
            - Allows lots of access that they should not have
        - Needs a vulnerable application running on the web server
            - Caused by bad programming
            - Rare but critical vulnerabilities

## [Driver Manipulation](https://www.youtube.com/watch?v=0EI0Rs1QAes&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=32&ab_channel=ProfessorMesser)

- Traditional anti virus software is good a stopping know vulnerabilities
- There are still ways to get into the system though
    - Unknown attacks (zero-day attacks), new and different attacks
- Attack with the drivers for your system
    - The drivers are trusted by the system already
        - So you can get a lot of information by infecting them
            - Keyloggers, video footage, audio, etc
- Shimming
    - Fit between two objects
    - OS have shims as well
        - Run applications as if they are running in a different OS
            - has a cache to store this information
        - This can be taken advantage of by hackers and place malware here
- Refactoring
    - A different program each time its downloaded
        - Will not match any signatures as it is always different
    - Make the malware look different than it is
    - Hard to detect with signature based detection

## [SSL Stripping (HTTP downgrade)](https://www.youtube.com/watch?v=H1QM6G4Zmos&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=33&ab_channel=ProfessorMesser)

- Combines an on-path attack with a downgrade attack
    - Hard to implement but has big rewards
    - See all of the data flow
    - A man in the middle attack
        - Proxy server
        - Arp spoofing
        - Rogue hotspot
        - etc
    - Looks normal from the victims machine
- SSL is depreciated
    - TSL 1.0 and 1.1 are also depreciated
    - TSL 1.2 and 1.3 are the latest standards
- Avoiding this
    - Use HTTPS and dont allow downgrades

## [Race Conditions](https://www.youtube.com/watch?v=zg_kTCOcinQ&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=34&ab_channel=ProfessorMesser)

- Problems can occur if multiple things happens at the exact same time and you were ready for that
- Time-of-check to time-of-use attack (TOCTOU)
    - Checking for things to occur on the system and making changing while knowing that other things may be going on behind the system
    - Like performing two bank transactions at nearly the same time
        - Could lead to duplicating some of the money and causing issues

## [Other Application Attacks](https://www.youtube.com/watch?v=Qobt7mkZk2A&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=35&ab_channel=ProfessorMesser)

- Memory vulnerabilities
    - Memory Leaks
        - Unused memory is not properly released
        - Application continues to use more and more of the memory until it is all gone
            - System or application crashes | DoS
    - NULL pointer dereference
        - Make a system direct to a null portion of memory where nothing exists instead of the correct data
            - Applications crash, debug info, DoS
    - Integer overflow
        - Large number is placed into a smaller section of memory making said memory overflow
            - Can be repeatable
- Directory transversal
    - Read areas of a server that they should not have access to
        - Bad OS or bad software program
        - May be able to backwards through the file systems to the C drive
- Improper Error handling
    - Errors happens
    - Massages should have just enough information
        - Some tell you too much and this is bad
    - Easy to fix as long as you have control of the application
- Improper input handling
    - All input could be malicious so check it all
    - Dont allow code input like SQL injections
    - Hard for attackers to find these but once they do it can be very bad
- API attacks
    - Manipulating the application programming interference
    - Look for vulnerabilities in the new communication path
        - Exposing data, intercepting communications, more access, DoS, etc
- Resource exhaustion
    - Specialized DoS
    - May use a very small compressed file and that is a HUGE uncompressed file (zip bomb)
        - Anti viruses can detect these
    - DHCP starvation
        - Flooding the network with many new fake devices
        - Make the DHCP server run out of addresses
            - Switch configs can limit the number of requests allowed
