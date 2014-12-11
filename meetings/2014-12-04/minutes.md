# December 04, 2014  

## Attendees
Chris Williams (CW)  
Bert Belder (BB)  
Chris Saint-Amant (CS)  
Cian O'Maiden (CO)  
Danese Cooper (DC)  
Erik Toth (ET)  
Issac Roth (IR)  
Kevin Decker (KD)  
Scott Hammond (SH)  
Todd Moore (TM)  
Dan Shaw (DS)  
Isaac Schlueter (IS)  
TJ Fontaine (TF)  
Trevor Norris (TN)  
Gianugo Rabellino (GR)  
Mark Carrol (MC)  
Manish ?


## Public Recap  

### Trademark and Website WG (Scott Hammond)
**SH:** Some overlap with compliance group. Recommend not to share the trademark yet until certification is fleshed out. Want to hear from the community as to how people would like to use the trademark. WG discussed liberal or “stingy” use of trademark. No resolution but will discuss further, however discussion resulted in possible multi-mark solution, one representing API compliance or certification. Agreed *TM* will setup conversation with trademark attorney. *DS* will research current usage of trademark. Discussed modifying current website to downplay Joyent and expand content such as ads or meetup information. Also discussed establishment and enforcement of policy (ET: website content?) guidelines. Followup meeting to be scheduled.  

### Advisory Board WG (Dan Shaw)
**CS:** Set 2 main objectives: 1) replace existing Advisory Board through transparent, public process and 2) refine scope of AB responsibilities. Expect that scope will be reduced over time. Reiterate 4 groups: core team, Joyent as steward, Advisory Board and user community. Responsibilities do not include technical direction. Support community growth aside from technical contributions. TC owns governance model but AB provides feedback on governance in regard to non-technical areas. Proposed AB selection process includes criteria for core team members, but still requires refinement. Major goal is to improve representation from broader community of Node.js members. Users who want to have input into technical direction should defer to TC, not Advisory Board. Open questions: 1) Scope of responsibilities between TC and AB, 2) Joyent’s role on AB
**DS:** Will be meeting again before the holiday’s to move discussion forward.  

### Technical Committee/Governance WG (Isaac Schlueter)
**IS:** Discussed proposed changes. *TJ* opposed to voting mechanism, preferring consensus. Concerned the edge cases result in bullying of minority. Danese suggested Apache model. Four participants in favor of voting, but no resolution reached. Back and forth on contribution policy and participants. Isaac in favor of open/open, Bert suggested TC vote for commit bit. TC has ownership of governance, so can be changed but with strict consensus. Also has chat history from conversation.  
**TF:** Erik proposed strawman to adopt in short-term to iterate. He conducts meetings as Danese describes, so next WG conversation will reflect that more clearly and will look into Apache process.  
**SH:** Please keep to quick summary.  

### Compliance/Certification WG (Dan Shaw)
**DS:** Meeting just happened so still compiling notes. Identified potential strategies at varying levels of effort. One is to define Node.js API compliance test suite vs. create canonical JS implementation that every entity should use to be “Node.js Compliant.” Approaches aren’t mutually exclusive and could be combined. Coordination needs to happen between trademark group and possibly new ™ aside from Node.js for use by companies to indicate their compliance. Indemnification of party providing compliance will be policed by market, not policing body. Input from Danese on the history of Java as an example, and during that process Sun tried to oppress ecosystem, creating tension. Worked to fix collaboration instead of improving technology. Should compel complying companies to publish compliance test data. Open questions include ownership, technical problems including targeting/tracking Node.js now or in the future? Action item is to review IronRuby and IronPython community for examples.  


## Review of Action Items (Chris Williams, et. al.)  

### GitHub Process (TJ Fontaine)  
No additional updates.

### Code of Conduct WG (Todd Moore)
**TM:** No bandwidth to run this WG.  
**TF:** Would be happy to drive this WG.  
**TM:** We need to schedule meetings, pulling together existing proposal. Start limited and as expand if necessary. Looking to other examples and organizations to lay groundwork.  

### Trademark and Website WG (Scott Hammond)
No additional updates.  

### Advisory Board WG (Dan Shaw)
No additional updates.  

### Technical Committee/Governance WG (Isaac Schlueter)
**IS:** Only additional comment is that feeling like there is much focus on minor details. Voting has been pragmatic in the past and vote happened because group decided it was best way forward. Bikeshedding over voting, but agree that TC owns process so voting could be added later. Confusion/lack of alignment: in principle is the TC the committers or could there be TC members who are not GH committers, etc? Could be value in having someone such as community manager, TC39 member, V8 team member on TC as example of non-committers who could add value. Also, should a LARGE group of committers, so having all committers be on TC might become untenable: committer group much larger than TC.  
**TF:** Agreed we want involvement from V8 or other external technical people. People who make decision must be internal/committers. Not opposed to non-technical decision makers, however example given in meeting (Isaac continue to have commit bit due to ownership/ knowledge of subsystem). More discussion around structure of getting people the commit bit.  
**IS:** People want to contribute without getting involved in TC or help make decisions. Benefit of open/open is that barrier(?) can be removed.  
**TN:** Doesn’t want anyone NOT writing or maintaining code making decision on technical direction. They should not be helping make decisions.  
**CS:** Not a matter of telling, but guiding direction is a matter of leadership; committing code or otherwise.  
**TN:** Concern that non-technical contributors have little accountability because that can’t own the implementation.  
**IS (?):** Makes sense to have more committers than TC. At least want insight and guidance from non-committers. Should be more committers than TC members; will mandate better documentation and communication.  
**TN:** Don’t care how many people have commit bit. Who signs off on important patches? Domain experts like Fedor should sign off? What is the process behind deciding and landing on patches.  
**IS:** As long as TC owns release process risk of mayhem is low. Patches can be reverted.  
**DC:** You’re talking about lazy consensus. Assumed that all patches can be reverted.  
**TF:** We’re talking more about workflow than changing how Node fundamentally works. Mechanism is that subsystem experts can integrate change. Anyone can review any pull request and after a while team can delegate trust to participants and ultimately even though they didn’t have a commit bit, could be brought in based on decision of the current committers.  
**CW:** Checkpoint.  
**SH:** Sounds like group agrees on consensus model. Let’s agree on big stuff and refine.  
**IS:** Important thing is to establish something and change as necessary.  
**CS:** It’s important to think of TC as leadership. Commit bit doesn’t make you a great leader, so keep in mind when choosing TC participants: may not be actively writing Node.js code. Leaders maybe be needed to execute against roadmap.  
**CW:** Will continue discussion in WG.  
**BB:** Should add *TN *to WG  


### Compliance/Certification WG (Dan Shaw)
No additional updates  


## New Business  

### io.js Fork (Scott Hammond)
**SH:** Want to understand fork intent, philosophy and relationship to Node.js.  
**IS:** io.js was Fedor feeling frustrated that node-foward/node was kept private (potentially due to risk of lawsuit), so name was changed and repo opened. Community rallied around it. Intent is same as node-forward to iterate on problems and solutions, ultimately merging back with joyent/node. Success depends on progress in AB and WGs and no hostility involved. Fork of joyent/node in same way as isaacs/node  
**IR:** Sugar-coating. Undertone is that node-forward was altruistic, io.js has feeling of being subversive. People on AB were involved in node-forward but have less impact on io.js.  
**IS:** Disagree. node-forward was not strictly about technical progress, but organizational progress.  
**IR:** node-forward was created consensus-seeking, but io.js was unilateral. It colored the perception of the community.  
**IS:** That’s describing *IS*, *BB*, and *IR* feeling, but the community doesn’t see it that way. Same people, same committee, same process, aims and objectives. Not every journalist is telling that story, but that it’s hostile. Not everyone involved in io.js is hostile. Conversation was started in August and now it’s December with little progress, understandably.  
**DC:** Keep in mind Joyent leadership changed.  
**SH:** I needed to build trust.  
**IS:** The community actively did not trust joyent prior to *SH* arrival. Joyent position was: no changes. Not putting it on *SH*.  
**SH:** Patience appreciated.  
**IR:** Agreed that external perception may not have changed much. Pointing out that io.js is driven by people not at this meeting and has life of it’s own. More divergent faction than we’ve had yet and increases pressure to come up with solution that works for everybody.  
**IS:** Unilateral move by Fedor and would have advised him against.  
**DS:** Look at the AB as here to protect business value of Node, but io.js release pent up need of people who want to contribute to contribute. Should be wake-up call to AB to accelerate and merge streams.  
**IS:** A little bit of fire under us to deliver on promise of AB. Don’t think we need to change course at this time due to io.js. Looks better for Joyent if it were able to be called “node.” io.js TC needs to come to shared understanding of messaging. No known disagreement with this sentiment amongst io.js. Should the diverge it’s not optimal.  
**TM:** That would be bad for everyone, we should converge.  
**CS:** Perception is very different from what *IS* described is the internal sentiment. Don’t see any help from the io.js side so mitigate perception issues as pertaining to Wired article. io.js should articulate path to re-merging, including expectations of Joyent. Be clear of road toward reconciliation, if that’s the true intent and desire. Possibly identifying it as an interim effort.  
**IS:** There a couple non-temporary ways to collaborate: 1) Move code/binary kernel to io.js, with node wrapping io.js, 2) pull patches from io.js. These are non-hostile and non-competitive. Premature to commit to saying it’s temporary.  
**TM:** We are making good progress; what is it that makes it possible to bring the forks back together again.  
**CS:** Saying a long-term divergence is possible is difficult reconcile with AB. What’s rationale should issues get resolved.  
**IS:** This is *if* the issues can’t be resolved.  
**CS:** This needs to be clarified with general public that a long-term fork is only possible if issues aren’t reconciled.  
**IS:** Preparing a message to clarify. There are multiple options, but don’t think anyone prefers a name change. Everyone already says “Node”. Having to say JS on the server other than Node is damaging and competition will be damaging. Could be a symbiotic relationship, but too early to tell. If issues can be resolved no reason for io.js to continue to exist.  
**CS:** Good to hear and want to ensure that explanation is crisp to community.  
**IS:** To be clear, I’m annoyed Fedor did this unilaterally. Agree that continuing to call it io.js is non-optimal. Would have been ideal to announce with publication of fork.  
**DS:** IS covered the io.js messaging, but there’s a need for the AB to respond.  
**DC:** A unified message from AB is necessary.  
**DS:** Should message that the needs have been identified and we’re accelerating work toward resolving issues.  
**CS:** Could the two groups put out messaging together showing unity?  
**SH:** The reason behind the AB was to address conflicts head-on. We are all better off getting a slice of watermelon vs a whole grape, so we need to align around what we want Node to be. This includes community, healthy ecosystem etc. Obvious contention but this group was formed to figure it out. Sounds like resolution or progress wasn’t quick enough. Are we still interested in resolving these issues and is it still the correct course of action to prevent forking and bifurcation of the community? I feel like we finally reached a point where we were establishing trust and I’m committed to this path recognizing there is more to do here. Would like to see a true io.js messsage.  
**IS:** What’s happening on social media is the community rushing to fill a vacuum.  
**IR:** *SH* is coming from a position of thinking Joyent is in charge.  
**IS:** I’m in the middle of multiple groups so a unique position. io.js needs to put together messaging and say what’s actually going on. A joint message is a bad idea. It makes it seem that io.js is connected with the AB. Part of motivation for io.js was for TC to do things that was not beholden to Joyent. If it appears otherwise it could be disruptive to community, some of whom don’t trust Joyent. Should say that core contributors are still working with Joyent to come to resolution. Also saying that io.js is working in public with goal to rejoin with Joyent.  
**TM:** AB should say we’re working and committed to same goals as io.js and willing to work together with them.  
**SH:** I have reached out to Fedor to understand. Have not heard back, but would like conversation with him. Not an issue of me feeling I’m in charge, but instead having a consistent message that we are working with community and what we’re doing is in the best interest of the direction of the project.  


### Non-Corporate Ownership (Issac Roth)
**IR:** Is Joyent open to the idea of putting the website and trademark into non-corporate ownership? The fact this hasn’t been addressed is coming up as a reason why the AB is a stalling tactic or way to retain control rather than moving to true community governance. Resolution on this issue will build confidence from community.  
**SH:** Trying to create a vibrant ecosystem for everyone. Trying to build point of view around foundations and what it looks like. Is there an effective model to do that? Hopefully has been consistent around messaging, actions, business model and product strategy as a mechanism to build trust. Try to build right governance model to give control to technical group and remain committed. Looking at foundation yields unanimous advice that the contention needs to be fixed and project healthy BEFORE moving to foundation, and as such has been working under that mode. That approach afford time to continue to learn pros and cons for different constituents. I am at a point where I am open to that and I’m committed to doing what’s right for Node. Gathered info from IBM and Linux foundation, Apache model or rolling own for flexibility. Ask that everyone understand objective. Has anxiety around foundation, particularly from cloud experience and snuffing out of small vendors. Impacted people see some foundations as serving only interests of large companies. What we do has to make sense for everyone on AB, but also everyone who ISN’T on AB. Want to do right thing for Node but needs to understand tradeoffs of Node, but also tradeoffs for Joyent. Accountable to board of directors, too, so time is needed to evaluate. Not opposed to it, but in fact open to it. Just want to find model that foster vibrant open ecosystem and passionate developers. Actively investigating to understand.  



## Summary (Erik Toth)  


## Action Items  

### AB Position on io.js
Will be drafted by SH.  
**SH:** Should be hosted on Node.js.  
**CS:** Should be reviewed by AB.  
**IS:** More important for io.js to clarify and AB announcement should be short and sweet.  

### CoC WG
TF will setup kickoff meeting and drive this WG.  




# Next Meeting  

[https://global.gotomeeting.com/join/273347861](https://global.gotomeeting.com/join/273347861) or please dial-in in using your telephone.  

```
United States: +1 (626) 521-0010
Austria: +43 (0) 7 2088 1033
Belgium: +32 (0) 28 08 4296
Canada: +1 (647) 497-9371
Denmark: +45 (0) 69 91 89 21
Finland: +358 (0) 942 41 5770
France: +33 (0) 170 950 585
Germany: +49 (0) 692 5736 7205
Ireland: +353 (0) 19 030 050
Italy: +39 0 693 38 75 50
Netherlands: +31 (0) 208 080 208
New Zealand: +64 (0) 9 925 0481
Norway: +47 21 04 29 12
Spain: +34 911 82 9890
Sweden: +46 (0) 852 500 179
Switzerland: +41 (0) 435 0167 65
United Kingdom: +44 (0) 330 221 0096  

Access Code: 273-347-861
Audio PIN: Shown after joining the meeting  

Meeting ID: 273-347-861  

```  
