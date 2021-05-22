Interview participant: [Int2] 
Interviewed by: Lucian Dragos via Zoom on 21.04.2021 
Transcribed by: Lucian Dragos on 20.05.2021


Interviewer: What is your name and what is your role in your company?

[Int2]: My name is [Int2] and I'm a software developer at [company].

Interviewer: How many years have you worked as a programmer?

[Int2]: About 8.

Interviewer: If you could use your own words, how would you define pair programming?

[Int2]: Two people programming together at the same computer, collaborating, using some method or something for switching roles, or maybe they don't even have to switch. I've used like that, I don't know if it's called pair programming, but more like someone watching to learn, so I guess there can be various degrees of collaboration.

Interviewer: OK, and how about mob programming? How would you define that?

[Int2]: That's several people, I would say at least four working on the same thing at the same computer, at the same time, and taking turns to have the driver role. That’s the person who inputs the texts in our code or whatever you're doing into the computer. And code that gets written needs to go through the driver, but the driver is not supposed to initiate anything on his term, so it's more of a smart input device. That aspect is kind of important.

Interviewer: Can you tell me a summary of your experience with any of the two programming practices?

[Int2]: Yeah, for pair programming I haven't really practiced it that much, if at all I felt a bit uncomfortable because it felt like someone was looking over my shoulder while I was programming. I've done it a bit, not really systematically. With mob programming I attended a seminar with Woody Zuill in 2019. As some going forward from that seminar, we decided to have a serious try in the team using mob programming. So basically, all we did was mob programming for, well, basically until COVID in 2020. That sort of was a bit distracted that a bit and then people sort of yeah, not everyone was very happy with mob programming, so we sort of needed to allow for other ways of working as well. But I feel it was a really good to do it fully for a bit to get the experience from it. Yeah, you learn a lot by doing it.

Interviewer: I'm pretty sure I attended the same seminar with Woody's Zuill in 2019 and I just want to make sure I remember correctly; you had some time just with him afterwards to do a bit of training?

[Int2]: Oh yes, if I remember correctly, there was some sort of general like speech he did in the dining area in the morning I think then then the afternoon we had the more like hands on training only for employees. So that was like we were dividing the groups and I got some task to solve. Well, they're using rather a stricter version of mob programming, where there is only one Navigator as well, so only the Navigator gets to speak. And that's very useful for practicing communication because the Navigator has to communicate clearly what the intention is so that the next navigator can take over without having to start from the beginning.

Interviewer: OK, so you mentioned that your team started using mob programming after that and they you stopped around when the distance work started. But do you know how the rest of your company uses these two practices?

[Int2]: Yes, I know some teams do. At least I don't have like very good information about how much they use it and so on, but I know several other teams that use it more or less. It’s also an interest among new employees as well. I've held a like a mob programming workshop with some new employees and also some people from my company that was procured by [company] recently.

Interviewer: OK, so I'm moving on to the middle section of this interview. I'm talking about the pros and cons of both the methods, kind of putting them in the same boat. Did you see any changes in the efficiency of programming after adapting any of the two practices? And by efficiency here I mean the amount of OK code per resources used.

[Int2]: Yes, absolutely, I will answer that in terms of mob programming because I don't really know about pair programming. After a bit of learning how to do things and I think the quality of the code and the like efficiency, as you say improved. Also, the output, we did some like basic measuring of a number of issues completed so that was the positive effect on efficiency.

Interviewer: Some researchers say that it’s usually not worth to do pair or mob programming in terms of the amount of code produced when comparing to the amount of code produced by coding alone, do you think that using these two practices have more advantages, which out scale the efficiency decrease?

[Int2]: I think amount of code is kind of a poor measurement, because there are many other important factors like quality, number of bugs produced, number of bottlenecks that you have to consider and so on. I'm sure that there are so many factors some people like might not work well together, and then of course the efficiency will be lower. But for people who liked mob programming and so want to do it, I think there is a real potential for increased efficiency.

Interviewer: My next two questions you already kind of mentioned them, but the first one of them was if you have seen a difference in the number of errors and defects in the resulting code.

[Int2]: I haven't looked at real measurements, but my general sort of feeling is that there were less bugs. because everyone was sort of active during the whole process from start to deployment.

Interviewer: There's one point that was raised by a previous interview that I had, which was the inclusion of code review in the process of programming and not having to do it again afterwards. What do you think about this?

[Int2]: In general, when we mob program use mob programming, we didn't do like an actual code review as we would normally do, we would like maybe we would do like just look at the code we I would do a pull request and then look at the code in in Bitbucket just to like assigned to check like you would do on your own when you're programming so that everything looks OK. And once everyone thought it looked OK, we were done. So no like formal review like we would normally do. And I think there might be, and I can feel that too as a disadvantage because you don't get to sit down like all by yourself to look at the code so some people have, I know I've embraced that thing, so that could be an issue as well because you don't have time to sort of reflect on it.

Interviewer: You also said before that it really depends on the people that are part of the mob, but do you think these practices can increase the feeling of teamwork and camaraderie?

[Int2]: Yeah, yes, that's one of the strong points of mob programming, I think, because you get to know your teammates better both competence wise and like personally as well like you hear their kids in the background, we sort of get a bit more insight into their lives and how they think. That's definitely improved over like working on your own and maybe having some meetings every now and then because you're working together all the time.

Interviewer: OK, uhm, so we've mostly talked about the positive aspects of it, but do you think there are some tradeoffs of or straight up disadvantages of any of these two practices?

[Int2]: Yes, I'm again answering for mob programming, depending on your personality, you might have an easier or harder time sort of adapting the mob programming because you have to be comfortable with other people looking at you, typing gold and so on. I guess that is one aspect that made one team member that we had sort of not be part of the mob for this because that was when we were practicing this sort of code kata thing, where there is one driver and one navigator, so the Navigator will, like all eyes on the Navigator, has to sort of bring things forward, and that was it can be a bit too much pressure. Sometimes you have to be attentive to how people react to things and it's so helpful to do little reviews. We had these daily review or retros or why they might call it at the end of every day we talk about like how did it go today with more program? What can we improve? And so on.
So that could be disadvantages if people, do not like it simply, and that's OK. And for simpler tasks, it may feel like that it’s an overkill to have many people doing a very simple thing. But then again, there is kind of a rule for mob programming that if you feel you are not contributing and you are not learning, then it's OK to exit the mob. I think that's quite a good rule, so one advantage with the mob is there is that there is sort of a redundancy. If someone wants to have to like see through their kids to go to the toilet or whatever, it's fine because they can leave and they can come back and sort of listen for a bit, then they will hopefully get into what the mob is doing. 
And there are some like technical issues that could be hard to solve. One thing like when we had prior to COVID, we had this big screen and we even had a specific mob computer that we were using, so that the person would sit down with that computer, and everyone would see it on the big screen. Then there were some challenges getting back to work in a remote setting. But I think, yeah, you can have a good solution like, but you probably need to try different ones to have something that suits most people.

Interviewer: I would like to, even though you said you don't have much experience with pair programming, I just want to hear your opinion over the question of do you think the two developers involved in pair programming should be around the same level or do you think there's a higher benefit for having them at different competence levels?

[Int2]: Umm, I think there can be both pending on what the purpose of the power programming is, or like the level of collaboration that I mentioned earlier. I guess you can pair program with the explicit intention of teaching someone. I've done that but personally I think that’s a bit uncomfortable, I don't know, having someone look while programming that way when you're only two people, it's sort of (…) But it's like personally I would prefer to have program with someone approximately on the same level, because then you can move forward as fast as you would like mostly. But yeah, when I say at the same level, I mean perhaps like general experience with programming rather than experience with the specific thing you're doing, so you don't have to explain like very many things, because then like I think our program is not very efficient. I think it depends on the purpose of the pair programming.

Interviewer: I'm I'm not going to go into more details about pair programming since you had more experience with Mob programming, but when it comes to mob you mentioned for pair that you usually feel uncomfortable when you observed and your work is observed, do you think there's a risk of people being feeling this like nervousness when they do mob programming, and they have the role of navigators sometimes? Like when they are in charge of the conversation.

[Int2]: Yes, definitely. It all depends on personalities; you have to be like ask them all you have to be attentive to what people think and how they how they would like things to work. The way we did most mob programming was not with us this designated Navigator, so everyone except the driver were navigators. You don't have to feel like pinpointed or anything, but then there is the problem that maybe many people like to talk very much. So, you have to regulate yourself. Some people need to push themselves to talk more, and some people might need to push themselves to talk less. So it's kind of a social practice or training in a way. That's why it's important to have an open conversation in routine so you can actually you dare say maybe you should talk a bit less without the other people being offended way.

Interviewer: Do you think there's a risk of the team members slacking off or like not fully participating in the process? And if so, what would you do to avoid this or stop it?

[Int2]: Yes, I guess there is a risk, but like the rule I mentioned earlier, if you feel you're not contributing or not learning, it's OK to exit mobs, so maybe they should exit the mob. With the app, if you're rotating the Navigator, or the driver, reasonably often like 5 or 10 minutes, it's kind of hard to slack off as well. You need know what's happening, because otherwise when you're driving, and you won't know anything. And then there's also some practice, even if it's not a rule that if someone hasn't spoken for maybe 10 minutes. Someone will ask them: “are you following”? But yeah, I guess that could be a risk that's part of the I guess the social exercise.

Interviewer: Some experts suggest the use of a facilitator. How important do you think this role is? Or would you prefer a self-managed team when it comes to mob programming.

[Int2]: I guess it's all about need, if the team is starting out with mob programming, it's I don't think we had like in designated facility would say when we started, but we had these, like regular little retros, and maybe the Scrum Masters would have acted a bit like a facilitator, but I definitely think it can be valuable, like at least starting out to have someone that sort of watches a bit more what's happening and maybe sort of raised things that they noted sometime.

Interviewer: So now I have the last section which is kind of trying to compare the two programming practices. What characteristic of a project would make you decide to use mob programming? If you had like, let's assume you had a flexible team who could do either a mob or pair programming or just individual? What part of a project would make you say, oh, this is really good fit for mob programming.

[Int2]: I would say things that involve sort of a bit of exploration or doing new things like implementing a new service, deciding on an architecture, things that are not boilerplate or mundane word. I think those things would be especially suited. When there is like a big difference in knowledge within the team, that might also be a good way to transfer knowledge.

Interviewer: Do you think there are any long-term benefits from adopting group programming which is either pair or mob but by long term I mean not just for the team itself, but maybe also for the developers once they move on to a different team.

[Int2]: Yes, as I said, it's kind of a social exercise, so I think you really improve your communication skills, especially when you're in the role of the navigator, we need to communicate effectively so that everyone understands. As well, we need to adapt your instructions depending on the driver we've had like drivers who are not programmers, then you have to be really specific. And in terms of knowledge as well, I think because if you've been in that like model in a team that were practicing only mob programming, you would have sort of a very even level of knowledge within the team. I think it will improve the like the general knowledge of the systems for like other programming.

Interviewer: OK, and you mentioned that you had some issues when the work situation moved to remote work, do you think these programming practices can be adapted and used for remote work, and if so, how would you adapt them?

[Int2]: Yes, I definitely think yeah, we did continue like even after that and there are a big really great number of tools for working remotely in different ways, sharing screens and so on. Switching from navigator like Command line tool with a timer and then we would just write “mob next” it would say who the next driver was, and it would commit and push the code. So, the next person could just do “mob start” and have the code and everything. And there are more tools appearing now for like IntelliJ has some sort of “code with me” plugin and so on. I think there are more tools coming as well, so yes, I think you can have a really efficient mob, even remotely.
