# Introduction

+ Desiging, managing and deploying a security plan is complex task
+ Organization under pressure of third party authorities, clients, stakeholders, users, ...
+ They manage to do vulnberability scan, PenTest, Compliance policies, deploy security devices and so one but They failed eventually
+ Why plans often fails? what is missing? who is the bad guy?
+ Security plans should be viewed by the theat itself but most of the time we organizations exclude this issue and this leads to misunderstanding an biased view and false sense of security
+ Does a threat know about existance of a security plan? for sure
+ Why theats still are successful even if we have security plans? To answer this we must understand the theart to develope the security plans and defenses
+ Definition of threat.
+ Threat is potential attack performed by threat actor
+ Threat actors are inteligent people who have TTPs
+ To understand threats and defend agains them properly we must understand their TTPs
+ We must shift from mindset of "Vulnerable" or "Not-Vulnerable" to understand threat actions This will improve out secuity posture and it helps us defend better againsthem even zero-day attacks
+ Why do threats succed? Isn't identifications and mitigation of vulnerabilities enough?
+ Threat actor's attacks are not simply running an exploit of traditional security testing. They are inteligent people who know there are edr, anti-virus, security defenses, pentest, vulnerability assessment
+ Threat actors do not always fireup scan > discover vulnerability > expliot. They look at the targets and see what it presents and use their weakness and my not use items discovered by security tools
+ Threat actor may gain access, establish C2, persist, situational awareness and ... Defenders often look for prevention not detectoin they have so many logs sometimes
+ Organizations always misses a key piece and it's understanding TTPs of threat actors
+ Scenarios: Threat actors find out phishing is their desired approach, Phishing > gain access > establish C2> situational awareness, lateral movement, ...
+ Is this reasonable? Were opportunities presented to detect and prevent? Could your security programs prevent, detect and respond this threat? sure? is it verified? if so how?
+ Should we blame end-user for this scenario? all security controls hinge on end user? so that user could do those things too so who we should blame now? user's job is to click don't blame them
+ Why is this scenario successful
	+ users are blamed for clicking
	+ poilicies, measures and compliances are minimum not enough
	+ Log everything because of "better safe than sorry" we don't know what to look for
	+ Patch, patch, patch. Threats not always use exploits, it just reduce attack surface
	+ Our security tools will save us, should not rely on the tools, hammer and nails won't build house for us on their own
+ How to solve?
	+ Through Red Team. it is inspired by military operations
	+ Just studying threats tactics and techniques won't help we should experience them
	+ it may named by threat/adversory / simulation/emulation
+ RedTem is the process of using Tactics, Techniques and procedures to emulate
+ A real world scenario with the goal of measuring people, process and technology to defend and environemnt
+ Assumptions and biased vision results in failure, RedTeam use unbiased mindset to measure gap between "what is" and "What should be"
+ Systems processes and technologies built by skilled people but this makes assumptions and biased and boxed in vision to them.
+ To overcome this we should take it in an unbiased way with no assumptions and redteam solves this from threat point of view with no assumptions
+ Some readtem scenarios:
	+ Tabletop Exercises: Disccusions about "what if" statements with no technical testing
	+ Physical attacks: Attack to physical resources to show attack path to physical assets
	+ Human Attacks: Attacks that aim humans like social engineering
	+ Cyber Exercies: A Red vs Blue cyber exercise with them goal of evaluating staff and security operation defenses. It can be an offensive scenario to a full red vs blue wargame
	+ Full-scale Cyber Operation: Most realistic attack combined of previous forms that aim people, physical assets and technical issues and evaluating security operation defenses and staff
+ Redteam does not focus on just finding weaknesses and vulnerabilites it focues on using them to their final goal. finding vulnerabiliites are not a goal but a mean. This is crucial distinguisher for redteam
+ Redteamers may find vulnerability and offer mitigation but it's not the redteams goal. The goal is a wide piucture of the organization to measure and avaluate the security defenses and people and test MTTD(Mean-Time to detect) and MTTR(Mean-Time to recover) These are issues that can not be achived through traditional threat inteligence or security testings
+ RedTems goals: Measuring and challenging defenses of and organization for example an engagement of stealing critical data starts:
	+ A targeted phishing attack test users wilingness to participate in attack (people)
	+ The payload test network and host security defences to against delivery and execution of malware (technology)
	+ In case of triggering a defensive control it test defenders action in indentifying responding and stopping the attack (process)
+ Red Team focus on testing and measuing security operations on a whole and not just technical aspects (people, technologt, process)
+ Training or Measuing defensive and security operations: (we don't rise to the level of our expectation. we fall to the level of our training)
+ Redtem focuses on training defenders like a maneuver. course, typical educations are valuable but not enough. they should be challenged in reality before getting compromised. training them with just courses and without having a real experience is fooling them.
+ For example a threat like wannacry which used eternalblue vulnerability to propagate and compromise. a RedTeam could have easiliy find this scenario that over smb protocol it can propagate
+ RedTeams are used to meaure the effectiveness of people, process and technology used to defend a network, train or measure a blue team(defensive security operations) and test and understand specific threats and threat scanarios
+ RedTeam is an independant group made of skilled people whose goals are to measure security defenses and they operatre based on specific ROE (Rules of Engagements) which describe how they should operate
+ Why independent? because internal orgs have biased an assumptions which leads to misunderstanding and it's better to look at org from outher view and with no assumptions and in an unbiased way. this could be consultant outer org or a part of the organization which are independent of the main org.
+ What is difference between redteam and attackers? RedTeams do real world attacks and provide reports and do risk assessments. Organizations that do redteam effectively don't need to wai to learn from real cyber attacks and compromises. The mindset through redteams can break common assumptions and false sense of security and will help orgs to develop highly effective security solutions
+ Redteams are effective but challenging in practice. we should obey the ROE and boundaries defined. and the output may not be much more than a pentest result and vulberability assessment tool. the redteamers should think on how to use them for theier benefits with threat actors point of view.
+ An unbiased redteam will cover thegap between "What is" and "What should be".
+ Consider this scenario
	+ an org says 5 poeple have access to accounting area. we should take it as what should be which make perfect unbiased assumption and realize difference between "what is" and "what should be"
	+ For example 20 people have admin access to acounting area (this is "what is")
	+ 5 people should have access to accounting area(This is "what should be")

## Red Team in Security Testing

+ **Vulnerability assessment**
	+ identify vulnerabilities and patch them
	+ it does not prevent attacks just reduces attack surface
	+ focus on identify and protect
	+ wide range of area but less depth
	+ Redteamers may use them
	+ Attack path validation

+ **Penetation Testing**
	+ identify vulnerabilieis and exploit them to show the risks and offer mitigation
	+ does not prevent the attacks completely but it detects and prevent attack paths
	+ focus on identify, protect, detect and a bit of respond
	+ a bith more depth than vulnerability assessment
	+ Redteamers may use it
	+ flaw identification

+ **Red Team**
	+ Use tactics, Techniques and procedures of threat actors
	+ measure and evaluate poeple, technology and processess of orgs
	+ focus on identify, protect, detect, respond, recover
	+ Measure security operations as a whole
	+ more depth 

Check NIST guidlines for cyber security frameworks homeworks



