# Joyent Node.js Advisory Board Meeting Minutes - March 23, 2015

## Attendees
Chris Williams (CW)  
Erik Toth (ET)  
Mike Dolan (MD)  
Scott Hammond (SH)  
Issac Roth (IR)  
Isaac Schlueter (IS)
Dan Shaw (DS)  
Bert Belder (BB)  
TJ Fontaine (TF)  
Danese Cooper (DC)  
Gianugo Rabellino (GR)  
Todd Moore (TM)  
Jim Zemlin (JZ)  
Scott Nicholas (SN)  
Kevin Decker (KD)  

## Previous Attendees
Cian O’Maidin (CO)  
Trevor Norris (TN)  
Chris Saint-Amant (CS)



## Public Recap

### Review Previous Meeting Minutes (CW)
[2015-03-09 Meeting Minutes](https://github.com/joyent/nodejs-advisory-board/blob/fbaaaf3c16b8d43bfe3f6af463a8e3fb345fb5b5/meetings/2015-03-09/minutes.md)  

### Review of Open Action Items (CW, et. al.)  
**MD:** Have taken io.js governance documents and reviewed them, looking to ways to incorporate. Typically will set up TSC Charter, TSC Policy, and Project Lifecycle documents. Took template from previous project and integrated io.js proposal to bring it into existing framework, so organized differently from source docs. Also, items were added that were not addressed under io.js docs, such as community docs. Ready to publish for public comment on GitHub. Not just me, but many people have contributed, so thanks.  

### Open Public Discussion
**Travis:** Points from previous meeting WRT marketing are correct. Was difficult to find information about what’s going on. Would be nice to see something this fundamentally important more easy to find.  
**CW:** Definitely agree and are working toward that. Any suggestions as to how to improve?  
**Travis:** Would be easier to find on the Node.js website. You have to dig to find it and if this is the future direction it should be featured more prominently.  
**TF:** We can definitely put it on the homepage and the site is open to contributions from the community.  
**Nathan:** Homepage seems to have out-of-date list to meeting notes. Maybe the process of posting or linking to notes needs to be automated.  
**TF:** We can look into that. Right now the site is auto-generated but some parts are still manual.  
**Nathan:** As someone who writes Node.js exclusively it’s important for me to know what’s happening and unfortunately Google is the best place to find what I need.  
**DC:** Agreed. We can do better.  
**DS:** We’ve been looking for more people to engage with the Community WG. If Travis and Nathan are interested, would love to have them get involved.  
**BB:** Maybe we should get rid of the private section of the meeting, or minimize it.  
**DS:** I support that, too.  
**Nathan:** The way to bring things to the AB was an email address deep in the charter. It might be good to surface that.  
**CW:** The GH repo was another avenue to provide feedback.  
**TM:** Should we be doing something on twitter, too?  
**Nathan:** Sure.  
**SH:** We can tweet when new notes are posted, etc.  


## New Business (Private)

### Review of Open Action Items (CW, et. al.)  

### Reconciliation Status
**TF:** Looking to get feedback from AB on documents that were emailed earlier, prior to releasing to public.  
**BB:** There will be more input from TF, James Snell, etc but overall happy with progress that’s been made over the last 2 weeks.  
**TM:** Thumbs is from IBM.  
**GR:** Yep, we like it was well.  
**MD:** Things have moved along over the last couple weeks, and not time to start thinking about things that not sure people have thought about: schedule, lifecycle, beyond next 6 months onto those who drive it 10+ years. Trying to get as much framework in place as possible. Need developer process for meetings, agenda, technology, etc. That won’t necessarily go in these docs and will let the developer community define.  
**TM:** In terms of support infra, did you have any discussions on how repos will operate, infra for team communication, etc. or is what we’re doing (GitHub) adequate? Could GitHub provide any additional support?  
**MD:** Have not discussed yet as we’ve focused on governance. Some teams don’t use GitHub so we’ve setup infra for them.  
**TM:** It’s been raised to me that some groups do this differently, so merely asking.  
**TF:** Some of this came up during the development of the provided documents, but we’re really trying to leave some of these decisions open for TSC and related projects to decide. Not all tools or infra may be applicable to all related projects.  
**TM:** If you need the board’s help, there needs to be a mechanism for making that request.  
**MD:** The chair of the TSC would be a board Director, so that person would raise these issues to the board for consideration.  
**BB:** We’ve mostly been discussing governance, so more technical items (CI, for example) need to be figured out. We’re pushing the boundaries of GitHub a little bit.  
**TF:** Yes, what has worked well for the core team may not be necessary for other projects. We would enable our own process internally potentially without making it public.  
**JZ:** I have a staff that is more than happy to help tooling discussions.  
**MD:** Many use git, jira, etc.
**JZ:** This community needs to balance velocity from GitHub...  
**MD:** Yep, I changed references to git, as that may be more flexible for teams.  
**DC:** Were there conversations WRT trademarks, etc?  
**DS:** We had conversation but wasn’t actually in the proposed docs.  
**BB:** io.js doesn’t really have a board so effectively TC controlled everything, but makes sense to keep those concerns separate.  

### Non-Node-Core/Incubation Projects (BB)
**BB:** MD proposed project lifecycle, including new projects with representation on TSC. This translates to things like libuv, http parser, and some node modules and we might want to accommodate these types of projects, growing the possible contributor base. socket.io, for example, may want a foundation for themselves. It doesn’t make sense to give _every_ one of these projects a seat on the TC, but could we accommodate them anyway? How might that work?  
**DC:** There’s a ton of infra in Apache for this type of thing to ensure projects like this aren’t dropped and abandoned. The process for incubation needs to be well-defined.  
**GR:** Going back to my Apache experience, I would suggest that it would be best to incubate the incubation. Wait until those projects come in and then think about it, but I don’t think there will be a big influx from day one. There will be a lot of resources necessary to support this and we don’t yet have those resources.  
**TF:** We just want to know if we have the ability make this available to the community. For example, could I get non-profit status by joining such that I can accept donations, etc? Doing it under the Node umbrella would be beneficial for them.  
**DC:** You do want to be able to be that umbrella.  
**MD:** What TJ sent out earlier is the project lifecycle document and sets a lot of this up from previous attempts. We have a general construct, but needs this group’s input to shape it appropriately for Node.js.
**DC:** We’re saying, don’t write it yet, but instead wait until you have one to define what the process is.  
**GR:** Don’t do anything to preclude getting there, but it’s not a priority right now.  
**JZ:** Definitely, please at least check it out.  
**DC:** I did read it but I saw a couple “and then a miracle occurred” items. Don’t over-define it yet.  
**TF:** We are at that point right now, however, WRT libuv and http parser.  
**BB:** It’s obvious that http parser must be in the foundation. WRT libuv, it makes sense as well.  
**IS:** Its reasonable that you go have those conversations.  
**BB:** Yeah, we want to share with libuv what they would get out of participating.  
**TM:** There’s another goal: we don’t want them to be a single-maintainer project forever. We want to support them as much as we can. The question is: should they get a seat on the TC? We don’t want them to feel second-class, but will it scale?  
**BB:** For these projects it makes sense to give them seats, but would a project like Hapi hypothetically get a seat or would there be 2 TCs, etc?  
**DC:** There are already extensible bits to the Apache org.  
**MD:** These are living documents, so it’s expected that they will be updated and revised over time. We plan to make sufficient investment that it will scale appropriately. If you want innovation you want it in the foundation, not outside, so you need to demonstrate value in participating in the foundation.  

### Discontinue Private Meeting (BB)
**BB:** Previously, there was some contention and we wanted to speak frankly. Now, this is info that everyone is interested in and there’s no reason to stay private. I think most of the topic happen on the public side, and could decide on the spot whether or not there are items worth discussing privately.  
**CW:** I agree. In terms of outbound channels, I’d like to help drive more attention to this. If we’re going to go longer than 15 minutes we need to be more intentional. Can we use the Node.js twitter account to publicize this?  
**TF:** Yep.  
**CW:** DS, I’d like to work with you and what the Community WG is doing.  
**DC:** The public side will need to be managed carefully to keep things moving.
**BB:** Maybe we can have an IRC back channel for asking questions.  
**TF:** I agree, especially since we can’t always depend on GoToMeeting.  
**CW:** We could do IRC, Slack…  
**TF:** We need to support as many people as possible.  
**IS:** You need a dedicated advocate in whatever tool you have (IRC, slack, etc) to help manage the conversation.  
**CW:** Is that a moderator, or an advocate separate/disjoint from moderator?  
**IS:** A good moderator could possibly be both, but would be more effective that person is a distinct role.  
**DC:** Wikipedia, for example, has 3 people managing this process.  
**TF:** I’m not sure we’ll have the same visibility as Wikipedia.  
**CW:** For next meeting we’ll do 45 public, 15 private. Who will be public-side advocate? Also, advocate must have traceback to conversation, not an advocate for themselves. Will schedule meetings on Monday afternoons through May.  

If you are interested in participating in API Compliance next steps please sign up for our kick off meeting: https://doodle.com/xr6farvn35cx6sg7  


## New Action Items
- Make NAB information more visible on Node.js website (TF)  
- Post draft governance documents to website/GitHub (MD, TF)  
- Direct io.js participants to draft documents and promote review and discussion. (BB)  
- Schedule 45 min public, 15 min private for upcoming meetings. (CW)  
- Promotion of upcoming meetings. (CW, DS)  
- Identify IRC advocate. (CW, et al)  



## Next Meeting
Please join our next meeting, TBD at https://global.gotomeeting.com/join/524998381 or please dial-in in using your telephone.  


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
