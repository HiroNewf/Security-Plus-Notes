# Security-notes
Just passed Network+ so unto the Security+. This will be my notes for the test, mainly based of the Professor Messer's videos, but there might be bits and peices of information that I compiled from elsewhere.

## 1.0 Treats, attacks and Vulnerbilities (24% of the exam)
* 1.1 [Phishing](https://github.com/HiroNewf/Security-notes/blob/main/README.md#phishing)
* 1.1 [Impersonation](https://github.com/HiroNewf/Security-notes/blob/main/README.md#impersonation)
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
