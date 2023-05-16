# GLAB-908.13.1-CICDSecurity

## "The One with CI/CD Security: A Friends-Inspired Tech Chat"



*Bob:* (sipping coffee) Ah, nothing like a hot cup of coffee to take the edge off a long day of deploying code, am I right, John?

*John:* (smirking) You bet, Bob. And nothing like a break from constantly worrying about whether you DevOps guys are going to inadvertently expose our company to some disastrous security breach.


*Bob:* (laughing) Oh, come on, John. You know we take security seriously. But, you have to admit, the whole CI/CD process is pretty amazing. I mean, we push out new features and bug fixes faster than Joey can devour a pizza.

*John:* (chuckling) Sure, but sometimes it feels like you're more concerned with speed than making sure our systems are safe. Remember that time you pushed a new release and accidentally exposed our API keys? That was like Ross's "pivot" moment but for our company.


*Bob:* (grinning) Yeah, that was an "oops" moment for sure. But, hey, at least we learned from it. Now, we use secret management tools to avoid such fiascos. Speaking of which, how's your team handling the ever-growing list of security threats?

*John:* (rolling eyes) Oh, you know, it's just another day in paradise. It's like trying to keep Chandler away from sarcasm – nearly impossible. But seriously, we do our best to stay ahead of the game, constantly updating our security policies and monitoring for any suspicious activity.


*Bob:* (nodding) Yeah, I hear you. But, you know, if you guys could maybe ease up on the security alerts every time we try to deploy something, that'd be great. It's like having Janice in our ear all day – "Oh. My. God!"

*John:* (laughing) Okay, okay, I get it. But you have to understand, we're just trying to make sure everything is locked down tight. It's kind of our job, after all. Though, I must say, your team has been doing a better job at incorporating security checks into your CI/CD pipeline lately.


*Bob:* (smirking) Well, thank you. It's almost like we realized that working together makes both of our lives easier. Crazy concept, huh? It's like when Ross and Rachel finally got on a break… I mean, together. They just needed to communicate better.

*John:* (smiling) True that, my friend. So, here's to better communication and collaboration between our teams. May our systems be as secure as Monica's secret closet – which, by the way, still amazes me.


*Bob:* (raising his coffee cup) Cheers to that! And may our deployment process be as smooth as Ross's overuse of hair gel.

*John:* (laughing) Alright, alright. Let's not get too carried away. But in all seriousness, it's been great seeing our teams work more closely together. It's almost like when the whole gang pitched in to help Ross move his new couch up the stairs.


*Bob:* (grinning) Yeah, and we all know how that ended. But hey, at least we're trying, right?

*John:* Absolutely. And with a bit of effort, we'll make sure our company's security and deployment process will be there for us… (singing) when the rain starts to pour!


*Bob:* (joining in) Like we've been there before!

Both: (laughing and clinking coffee cups) Cheers!

As they continue their conversation, Bob and John find humor and camaraderie in their shared experiences, realizing that collaboration and communication are essential for ensuring the best possible security and efficiency in their company's operations.

## To dos for Learners

Please match the ci/cd security issues for each case here

### Issues

- Third-party library vulnerability
- Exposed sensitive information
- Malicious code injection
- Source code repository compromise
- Missed security vulnerability

### Cases

- Developers add a new third-party library to the codebase without reviewing its security vulnerabilities
The library contains a critical security flaw, which the developer is unaware of
The library is deployed to the production environment through the CI/CD pipeline
Potential consequences: attackers could exploit the vulnerability to gain unauthorized access to the system, execute arbitrary code, or steal sensitive data

- A DevOps engineer mistakenly exposes an API key or a password while configuring a service account
The sensitive information gets committed to the source code repository
The code is deployed to the production environment through the CI/CD pipeline
Potential consequences: attackers could use the exposed information to gain unauthorized access to the system or steal sensitive data

- A QA engineer misses a critical security vulnerability while testing the code
The vulnerability goes unnoticed until the code is deployed to the production environment through the CI/CD pipeline
The vulnerability could allow attackers to bypass authentication, access sensitive data, or execute arbitrary code
Potential consequences: attackers could gain unauthorized access to the system, steal sensitive data, or execute arbitrary code

- A developer commits code to the source code repository that contains a backdoor or a malicious code snippet
The code gets deployed to the production environment through the CI/CD pipeline
The backdoor remains undetected for a long time
Potential consequences: attackers could gain unauthorized access to the system, steal sensitive data, or execute arbitrary code

- An attacker successfully injects a malicious code snippet into the source code repository through a phishing attack or a social engineering tactic
The code gets deployed to the production environment through the CI/CD pipeline
The attacker gains access to sensitive data or takes control of the system
Potential consequences: attackers could steal sensitive data, execute arbitrary code, or cause disruption to the system

