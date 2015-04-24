# Joyent Node.js Advisory Board Meeting Minutes - January 29, 2015

## Attendees
Chris Williams (CW)
Erik Toth (ET)
Todd Moore (TM)
Kevin Decker (KD)
Cian O'Maiden (CO)
Issac Roth (IR)
Scott Hammond (SH)
Danese Cooper (DC)
TJ Fontaine (TF)
Dan Shaw (DS)
Jim Zemlin (JZ)
Bert Belder (BB)
Isaac Schlueter (IS)
Chris Saint-Amant (CS)


## Public Recap

### Review Previous Meeting Minutes (CW)
[2014-01-14 Meeting Minutes](https://github.com/joyent/nodejs-advisory-board/blob/779fb1076ae9e47f8dcdc03de31cde5a11018451/meetings/2015-01-14/minutes.md)


### Review of Open Action Items (CW, et. al.)
**TF:** 0.10.36/0.11.15 was released. 0.11.16 out Tuesday or Wednesday next week.
**TF:** NodeSummit WG to meet Monday before NodeSummit (“Day Zero”)
**DS:** Is there a public way to track Technical WG progress?
**TF:** Going to open invite to AB members. If there are proposed community members, they would be added as well as a dial-in for others. Will be boardroom setting for next meeting.
**SH:** Does that makes sense to post on Node.js website?
**TF:** Depends on what’s covered. If it’s a WG not sure if it would be public as _result_ of WG is generally what’s made public. There are key people that need to be there, however. Assume public output would be notes/minutes from WG meeting.



### Open Public Discussion
No topics raised.


## New Business (Private)

### Review of Open Action Items (CW, et. al.)



### Review Status of NodeSummit (DS)

```
At a high level, there is time reserved toward the end of the day at around 4pm PT through the end of the day for Foundation announcement(s) and sessions. We also have space reserved on Monday, Day Zero, in a board room setting for an open board room session.

Day 0 (2/9): Board Room space available to host AB or Foundation board
Day 1 (2/10): 4:25-end Allocated to foundation activities
Day 2 (2/11): 4:40-end Available as needed. Usually allocated to a forward looking session.

Photo of board room: https://www.dropbox.com/s/3jd9sbo75ib3gce/IMG_2209.JPG?dl=0
```
**DS:** TJ discussed boardroom on Monday and there’s also room available for non-TC activity. Will provide a photo of space to set expectations of the venue/accommodations. Not a lot of space for spectators and probably max ~20 people. Will be cozy. Additionally, main days (Tuesday and Wednesday) around 4pm the schedule has allocated space for any announcements and flexibility. Space can be filled if no announcements are prepared. Second day is allocated for looking toward future of Node.js.
**SH:** Previously we discussed to technical session: 1 closed and 1 open.
**TF:** That’s what I was anticipating. Not intended to be public but an internal WG conversation.
**IS:** Yeah, we’re not ready for that.
**DC:** I was asked to form a panel to discuss.
**IR:** If we had a public meeting it would be io.js and Node.js would have to meet at least once prior to then.
**DS:** I would like to see these groups aligned before NodeSummit. If we align _at_ NodeSummit it’s too late in the game.
**IS:** Don’t want to do that negotiation at NodeSummit.
**IR:** People expect to see what’s happening.
**IS:** I agree that 3 months is excessive. we have a private meeting beforehand in the io.js and node-forward meetings so we can make sure everyone is on the same page.
**IR:** The suggestion was that there was _no_ public session.
**IS:** Want people to feel like we’re at least be open with them.
**IR:** We need something technical public that day.
**IS:** that is a good goal, but not sure exactly what that looks like. Scott where are you with being able to talk about a foundation. The last thing I want to do is have a talk about things and then bite our tongues about the foundation.
**SH:** Our target is still to publicly announce with timing being day one, going public that morning.
**DS:** Day 1 is Tuesday.
**SH:** Public announcement that morning and that afternoon we have that hour slot during the day to walk through more details in the public forum, backing up from that have the initial group signed up for the first part of the working group. Enough time for people’s PR machines to warm up. I think we have some pre-briefings this coming week, that is the track/process we are tracking on. Things look ok for hitting that. I’d like to get a session this week with team from IO and give them an update for what we are doing just make sure they know what is happening and agreement for everyone from that group.
**IS:** The best folks are probably IS, BB, and Mikeal Rogers.
**SH:** Fedor seems to be an important person we will get the meeting scheduled this week. Lets make sure anyone writing code is included, asked about TN specifically SH to take point for that. Would like AB members to segue recommendations/output from WG to foundation. If each can make a slide from each WG about the purpose and output in how they have helped in the advisory and recommendations. Fold it in so we can have a meaningful and productive presentation of how the AB has helped.
**DS:** We’ve talked around bringing io.js and node.js, but in the formation of foundation, how important is io.js to the future?
**SH:** My _sense_ is that is has been run around the ideals as described by Bert initially. I think a lot of what io.js represents is an important part of what the foundation represents and is an implementation of what the community wants to see, so it’s important. The ideals align (community, transparent, process), so it’s the next logical progression. Core team has been doing some of that, but perhaps not as much as io.js, but we’re aligned on those objectives. A part where there has been a difference in opinion is the tension between experimenting with latest tech vs delivering quality, production-grade system. An important topic will be how we can accomplish both. Every engineering team I’ve been a part of has had that, and there has to be a way to accommodate experimentation, so how do you weave that into your stable release cadence?
**IS:** I have an answer to that. (to be continued…)
**SH:** There’s a tension there that _has_ to be resolved. Another tension that needs to be addressed is around balancing date-driven deliverables vs functionality-driven, vs quality-driven. I think there’s a process for that in Node.js, but I don’t know how that’s addressed in io.js. We need to listen to, and learn from, the community.
**DC:** I think this is part of why they want the panel they wanted (NodeSummit).
**IS:** In particular the Node.js/io.js community has found an answer to some of these problems. Re: experimental vs prod grade, the answer was unstable and stable release trains. That was difficult to manage once the project reached a certain size. As a result stable trails experimental in certain areas, make it _less_ stable. In io.js this is just becoming a real issue. Started by calling it “unstable” and now getting to a stable and supported v8.
**IS:** We hope between their bleeding edge and unstable, we also can use that same process, we are keeping a bleeding edge following the bleeding edge of V8. A Stable with a v8 that is somewhere between stable and unstable and legacy builds.
**SH:** So 3 release trains.
**IS:** As far as being driven by the 3 priorities (date, quality,features) , you need to balance all 3 at all times. There’s a lot of value to be had in regular, stable releases. Even if it’s just doc updates, the train goes regularly. Balancing functionality with quality, we focus on quality full-time. Also embrace semver as the community. Also, the TC/WG model is similar as AB and it’s working well.
**TM:** One issues is that for those trying to follow along face incompatibilities between forks.
**TF:** Good point. Back to the original question is that the idea of the foundation is the future of node. If/when the 2 project reconcile, there’s a world there multiple distributions exist; hence the compliance/compatibility mark. While there’s a moment today, it will most likely happen in the future. The foundation is there to pave the way forward to handle that gracefully.
**IS:** It’s also a reaction to community needs.
**TM:** We need both bleeding edge and control over compatible releases, so users can have certainty and predictability.
**TF:** We’d have something more akin to the linux kernel with pristine upstream and multiple channels allowing to experimentation and different levels of expected quality.
**IS:** We’re talking a little cross-purpose. There are other forks, but node and io are fundamentally the same people and code. Foundation will benefit from getting those people doing the work back under the node umbrella and having the added institutional experience of those people focused in one place.
**TM:** I think we are saying the same,
**IS:** It is an open source acqui-hire
**TM:** The notion still may exist that we’ll have a bleeding edge as things come back together.
**IS:** Chris Dickinson came up with a good 3-prong release train. Essentially, follow what Chrome does.
**TM:** Yeah, that’s a decent model.
**DS:** Having that participation from google is something we haven’t had before, now they are showing up that we have io.js and it is phenomenal.
**IS:** They’re interested in Chrome, but the Angular, V8 and Chrome are aligned on the future of node and web browsers. e.g. the streams WG is trying to get closer to the other stream WG, etc.
**DS:** I would love to see those efforts accelerate. Should be a foundational part of the foundation and not an afterthought. If we have a reset and restart this process, it would be detrimental losing the effort put into making AB and WG meaningful.
**SH:** re: merger idea, you want to find things that work well and double-down; shedding things that don’t work well. That’s something that needs to be talked through so it’s not a hard reset. The easy part here is that the majority people are working on both.
**IS:** Actually, it’s a minority as there are more people contributing to io that haven’t contributed to node before.
**SH:** Great, then let’s energize the community to continue to grow participants.
**JZ:** Getting the io.js folks back into the node community will generate a lot of excitement. Strong excitement to get both parties unified.
**CW:** As an outside observer, my biggest concern is that it’s discussed a reconciliation and that not enough groundwork has been laid to really effectively get this done prior to NodeSummit.
**IS:** Two things need to happen: IP into Foundation and keeping Governance successes of io.js (without hard reset). Will be blocker for new community members if that doesn’t happen. Have discussed with io.js core team (being careful to keep it from public sphere). I don’t know if everyone is completely on board with reconciliation. There are a lot of hard feelings on a personal level between past and present participant. It can be overcome, just needs to be acknowledged that it’s a problem that needs to be overcome. The details of what that negotiation looks like is pretty straightforward. Not controversial, just need to get to the point of discussing it publicly.
**CW:** I was more referencing the broader community outside from tight-knit TC.
**IS:** Less discussion there. Still frustration regarding lack-of diversity. There’s a lot of community members excited about the new brand, but the thing to keep in mind is that we’re hearing from the top 0.1% of node users, the majority waiting it out to see where the chips land. That’s where the majority of node developers really are. The biggest users are at large enterprises, so it’s hard to get too much of a read from those folks based on a few dozen people on GitHub, but we’re trying to push at those edges. The outreach that I’ve done to companies that use node reveal that they don’t care.
**JZ:** The key is that if the 2 communities unify everyone will come along. Everyone can be reached wil a well-funded jointly-maintained foundation.
**IS:** It’s the continuation of the process, so for most people they never left. Is there anyone that want to add more color.
**IR:** On the user side we’re hearing feedback about it being confusing as to where the multiple project fit. Whatever strategies are decided for branching, etc, they need to be documented and published.
**TM:** Many groups inspect the OSS they’re using and they don’t like their teams running out to use something that has not been vetted, so they ask their devs to not use io.js. There has been some high-level user concern.
**IS:** Shift in branding cause anxiety, so the fix will be to bring the brand together.
**DC:** Tim O’reilly asked me if Node.js was dying.
**CW:** The main root of my question is that the cat is out of the bag wrt forking, so are there people who vehemently oppose reintegration for the codebases.
**TF:** We need to be prepared for that, but the foundation needs to solidify what it means to be node-compatible. The foundation needs to be bigger than this moment.
**CW:** Totally agree. Are there things that can be done to prepare _now_ to anticipate and address this, preventing a problem.
**BB:** There are more people working on io.js and it works. in practical terms people using io.js are concerned that if they go back to Node.js will it still be the same-old Node.js. What you could do is get the two teams talking and working together to instill confidence that coming together won’t be a setback.
**IS:** The message needs to be one of continuity and that the future is Better Together™. We’re currently limited WRT what can be discussed with community members to start to test the waters.
**SH:** Would be good to discuss the specific examples of what’s working for each group, so why don’t we adopt and go for the agreed upon items.
**BB:** The goal is good, but the way it’s expressed is bad. Most folks really feel that io.js is doing way better than node.js, so it would be better to say: “we’ll take the io.js model, but these things need more discussion.”
**IS:** This is why you have marketers. Saying the right things, just using the wrong words. Have to be sensitive to the fact that people may emotionally react.
**TM:** We’ve used an FAQ to do this in past. Need to agree on phrasing, terminology, and tone.
**DS:** Would we be comfortable having io.js TC members involved in that? Since they haven’t seen the inner workings would like to see them engaged early.
**IS:** Would be great to get FAQ in front of Mikeal and Rod Vagg.
**CW:** Joyent should make the announcement, but should we provide an allowance to include more people in this discussion prior to the announcement.
**TM:** Since we’re informing more people next week, can we discuss with more people.
**CW:** Open up discussion in a controlled way.
**JZ:** Can’t we do this/hash it out next week.
**SH:** Yeah, we’re in agreement, so let’s have a session next week with an expanded group.
**TM:** Can you set up FAQ WG
**JW:** Yes, but it needs to have both TCs come together.


## New Action Items
**SH:** Session with representatives from io.js to discuss announcement. Include: IS, BB, and Mikeal Rogers; maybe Fedor.  (This turned into two discussions with io TC during the week prior to NodeSummit.)
**All WG Leaders:** Send detailed recommendations/output from each WG to SH to ensure it becomes input into the initial foundation.
**JZ (et al):** Produce and wordsmith FAQ.
**JZ:** Schedule session between io.js TC members and AB members.



## Next Meeting
Please join our next meeting, Monday Feb 9, 2015 at 2:00 PM PST / 5:00 PM EST connection information is available at [http://nodeadvisoryboard.com](http://nodeadvisoryboard.com).