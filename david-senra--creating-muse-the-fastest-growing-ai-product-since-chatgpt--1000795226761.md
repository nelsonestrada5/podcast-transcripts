---
podcast: David Senra
episode: Creating Muse: The Fastest-Growing AI Product Since ChatGPT | Alexandr Wang, Meta
host: David Senra
transcript_id: 1000795226761
published_at: 2026-10-11
source_url: https://spoken.md/podcast/david-senra-1836497887
---

**David Senra** (0:03)
Tell me the history of Muse.

**Alexandr Wang** (0:04)
The first thing to start with is probably like what our vision was when we started Meta Superintelligence Labs. And when we started it, Mark published this memo that myself and Nat Friedman and a bunch of others like worked together with him closely on called personal superintelligence. And the whole idea was like, how do we make AI, how do we build powerful AI that actually makes all of our lives better? How do we build something that actually lifts the human experience, broadly speaking? In that memo, we spoke to a bunch of the ideas and we basically alluded to I think a lot of what Muse has ultimately become. But we were gesturing at it very, very early. This was in June 2025
Before really agents had happened in any meaningful way. In the summer of 2025, AI was just in a totally different spot. But that's what we wanted to build towards. That was the mission of MSL and that was really where we wanted to take everything. Then we just got to work building models because the end-to-end process of developing any of these frontier models is many, many, many months. You have to go through, you have to build your entire stack, you have to produce the datasets, you have to pre-train the model, then you have to do pro-train the model, you have to build a little stack for that. It's a very lengthy end-to-end process.
I mean, kind of this whole production line. At the start of this year, you know, Opus 4.5 obviously, like, really caused many people, including us, to sort of like see what the future of agents could be or was, and really brought the sort of, like, potential of agents to the foreground. And OpenClaw was happening at the start of the year. Nat Friedman, who, you know, I worked closely with, was, I think, the first person within MSL to work with OpenClaw and try OpenClaw.
He had an experience I would describe as somewhere between terrifying and euphoric. Like, I think he really, like, I think, went all in. He trusted entirely. You know, he's told some of these stories that he had, like, a Stripe Sessions interview where he talked about some of this, or, you know, he told his OpenClaw that he wanted to drink more water. And then, you know, his OpenClaw would, like, watch him in security footage to make sure they were drinking water and tell him, good job. And he had, like, many, many crazy stories like this. And it also makes you realize, like, oh, there's something quite, quite magical about what's happening here. And I remember one of the things that Nat told me, and this is one of the things I remember the most, is he said, I think there really is something here.
And, I don't know, like, early adopter Nat Friedman is, like, a pretty good indicator, because he was one of the first customers of Stripe back in the day, and then was really early on a lot of open-source developer stuff. And he also, you know, helped create GitHub Copilot and many other things. So, that was, like, a clear signal. It was like, okay, there's clearly something pretty magical about personal agents, generally speaking. But, you know, when you actually kind of trust the personal agent and really bring it into your life, it is the ability to do so many things. And after hearing all of these crazy stories, I started using it very deeply. You know, I think for many weeks, I think both of us were sort of like every spare moment, we would just spend talking to our open claws and, like, you know, you know, really immersing ourselves in, like, what personal agents could be.

**David Senra** (3:34)
What was your initial reaction before your terror?

**Alexandr Wang** (3:38)
Nat, at the time, he had this, he had built this prompt to do this, like, basically, like, full psychoanalysis of yourself. There were, like, multiple waves of, like, deep psychological probing. He basically wrote this prompt for you to use in open claw. And I think that was, like, one of the very first things I did with my own open claw. It was maybe the equivalent of, like, three years of therapy, all, you know, compressed into this one moment.

**David Senra** (4:04)
Wait, I'm curious, why, when you get your first shot at open claw, this is one of the first things you do?

**Alexandr Wang** (4:09)
You know, I downloaded it, I installed it, and then Nat was like, oh, you should do this. I was like next to him. He was like, okay, I'll just do the thing you're telling me to do, and then...

**David Senra** (4:18)
Okay.

**Alexandr Wang** (4:19)
And then, you know, this crazy experience.

**David Senra** (4:21)
Well, say more about the crazy experience, though.

**Alexandr Wang** (4:23)
Oh, well, it was just, like, very intense. I mean, it was like, again, it was like three years of therapy, because it was just, like, successive rounds of, like, deep psychological probing, because it had other information about me. It had, you know, access to my email and access to a bunch of my photos, and, like, it could, like, go and look up other information and sort of pull it all together. I was very vulnerable through that process. This was in February.
Both of us, I think, had come to this, like, joint conclusion that this is clearly, like, you know, there's clearly something really special happening here. And we both wrote memos at that time. I wrote a memo about, and both of these we, you know, kind of, like, sent up through the Meta board, because it's, you know, for whatever reason it's board season. I wrote a memo about how I felt that in many ways this was, like, the final consumer product and that the super agent was something that was, like, as far as consumer products went, like, a clear end point in many ways. And then he wrote one called, he wrote actually two, which had very memorable names, the Clause, the Law, and Trust is a Must, which ultimately defined a lot of the core of how we built these products. So we came to this conclusion, this was in February. There was something very important here.
And then we built, you know, our teams, we built a prototype within, like, a week, maybe two weeks, and demoed it to the board. Like, it was this, like, very fast cycle. And many of the decisions that made its way into the final Muse product were present in the first prototype. The JollyBot was there, you know, the early version of the Muse Charm was in that first, of that very first meeting. Not all of the ideas and not all of the tabs were there, but a lot of them were present. Then from there, you know, obviously, that was February, we launched the product seven months later, was like the really, really hard process of taking this, you know, prototype where it, like, sometimes worked and was magical, but most of the time didn't work and would constantly break. And like going from there to something that would be highly reliable, like, you know, kind of like a beautiful crafted consumer product that we felt confident as a contribution to the consumer world. And that was like this very lengthy and quite painful process.

**David Senra** (6:44)
Before we get there, I want to go back to the idea that you wrote the prototype, you guys created the prototype in like one to two weeks. You showed to the board, what's Mark's role in all this?

**Alexandr Wang** (6:53)
He was like experiencing the sort of like euphoria slash terror of the product at the same time as all of us. I think he's talked about this in various interviews, but like I think he used it for a bunch of things around the home and he was using it with his kids and he used it in his MMA training, like he had it watch videos of himself doing MMA training and like we would give him tips on like how to improve. There were like some staff meetings. And by the way, like, you know, this kind of became a thing for much of the Meta team was like having these, having a staff meeting and saying like, what were the crazy experiences that you had with your agent? Again, this was back in February. It's very interesting to kind of think back to this whole cycle because obviously the open cloth phenomena, it peaked and then disappeared. Yeah, there were, you know, it didn't, it didn't persist. And I think a lot of people kind of had this experience, which was, it was just like, you'd have these magic moments, but for the most part didn't like work that well. And there were all these problems and then, you know, it just kind of like died down. And so part of, I think the building the product, a lot of the focus of the product was just like, how do you make this into an actual reliable consumer experience that you feel comfortable putting in front of over time billions of people, and you can feel confident that like most of those people have an amazing experience.

**David Senra** (8:21)
Why were you able to do that and the developers of OpenClaw were not?

**Alexandr Wang** (8:24)
Well, first of all, I think we respect Peter Steinberger and everyone who's contributed to OpenClaw immensely. Like I think Peter is definitely a visionary. I think whatever happened in his beautiful brain that created OpenClaw is magical. And I think maybe the unglamorous part of what made Muse so magical was just really grinding out and sanding out all of the details to make the combined model plus product experience really amazing. And we did many, many iterations on the model itself. We aimed the overall model roadmap towards building towards personal superintelligence, broadly speaking, but certainly personal agents as like...

**David Senra** (9:10)
Say more about that and how that differentiates between your other competitors.

**Alexandr Wang** (9:14)
Yeah, well, this is kind of...

**David Senra** (9:15)
That's actually really interesting.

**Alexandr Wang** (9:16)
Yeah, it's actually useful to go back to the moment because if you go back to the start of the year, February, Opus and Claude were way ahead in coding, way ahead of anyone else, and they were exploding. It was the beginning of the sort of entropic takeover in the full industry. It was a very scary moment, I think, generally speaking, where it's like, oh, wow, they're so ahead on coding, and then obviously they had Mythos, and they had this clear lead. I think the conventional wisdom in the industry was that coding agents were the only form factor that mattered, or maybe the only technology that mattered, or the only capability that mattered for advanced AI.
There's this incredible force in the industry to just go and crowd that use case and compete with Anthropic on coding agents. Because of our experiences and our conviction that I think formed around this idea of personal agents and the sort of taking a step back, I think the reason why we did personal superintelligence in the first place was that it was also what we believed Meta was uniquely positioned to do, and we can talk more about that. But I think because of that...

**David Senra** (10:24)
Well, let's talk about that now. Okay. We'll just do the weave.

**Alexandr Wang** (10:26)
I think one of the first things I told Mark, even before the whole Scale and Meta deal happened and everything, one of the first things I told him was, I think Meta is actually a really special company if we have AGI or ASI or whatever you want to call it, because part of the promise of AI is that for all of us, we have a mix of things that we want to do and things that we have to do.
The promise of AGI is that we're going to spend almost none of the time doing things that we have to do, because the AIs will start doing a lot of that for us, and we can spend all of our time on things that we want to do. And for me, Meta's products represent the things that we all want to do. Like my use of Instagram or WhatsApp or Facebook, like these are products that represent what I, you know, I follow my interests, I follow my hobbies, I follow people that I like, my friends and the people I care about. Like the product span of Meta encapsulates the sort of like what we want to spend our times doing sort of realm. I think on a long arc, Meta is an incredible winner through all this. That's like one of the first things that I believed about Meta and super intelligence. And then ultimately a lot of those ideas made its way into this concept of personal super intelligence. You know, you can kind of look at it a few ways. One is what's the heritage of the company? The heritage of Meta is connecting people with their friends and family, helping them discover their interests. These are things that are very human. And then there's also the sort of like, you can take the business lens, which is Meta has distribution to 3.5 billion people using the apps every day.
And the natural area where Meta was going to be successful is consumer AI.

**David Senra** (12:18)
It's not work, it's not coding, it's personal.

**Alexandr Wang** (12:20)
Yeah, exactly. So, personal agents and personal AI and consumer AI, broadly speaking, were always the zones where we always felt that Meta was going to be able to do something very special.
So that brings us to, okay, early 2026

**David Senra** (12:38)
Now you have the prototype, you have the buy-in, everybody knows, Mark's on board, and now you're doing the seven months of the difficult work of refining this product.

**Alexandr Wang** (12:47)
Yes.
There was kind of this specter, which was like, oh, personal agents, like they came and went.
And we always felt that it was because, you know, the experience wasn't perfect, it wasn't polished yet, you know, all that kind of stuff. But like, we knew that that was something that we had to like think about as, you know, as we were developing this product. We focused our model development roadmap, the top focus, one of the top focuses was towards building on personal agents. And we had like these long spreadsheets of hundreds or even thousands of different, not thousands, but more than a hundred like specific behaviors and capabilities that we knew the model needed to have to be able to build the ideal personal agent. Like it was very, very meticulous. And then over time, we built evals for all of those. We figured out how to train the model to be really, really good at every single one of those things. And we have these reviews where we like look at that spreadsheet and we figure out the things that we're bad at and make sure that we're improving on them. That we did this like very meticulous process to slowly just keep improving and sanding out all the edges of the model so that it could power the product.

**David Senra** (13:54)
Is that really the culture of Meta too? This like constant like sanding of the products?

**Alexandr Wang** (13:59)
Yeah, a lot of the culture of Meta is like once you know what you're measuring, there's very talented people and you can optimize for those things, you can sand out all the details, you can make those things amazing. I think in the sort of like pre-AI consumer product era, like a lot of this was around how do you optimize your conversion, how do you optimize the referral rates, how do you optimize like every part of the onboarding flow, like how do you make all that stuff just perfect? Then I think the AI era, I think a lot of that, especially for Muse has been in the form of sanding out every detail of the model to be perfect for the product.

**David Senra** (14:34)
I want to tell you about the presenting sponsor of this podcast, Ramp. I have been reading a lot about SpaceX lately. SpaceX is one of the most valuable businesses in the world, and one of the main themes in the history of SpaceX is constantly attacking and questioning your cost. Ramp helps many of the most innovative businesses in the world do exactly that. The median company running on Ramp cuts their expenses by 5%, and one thing SpaceX has demonstrated is that a religious dedication to controlling costs can help actually increase revenue because you can pursue opportunities you couldn't otherwise, and we see that in the Ramp data too. The median company running on Ramp also grows their revenue by 16%. So when you're running your business on Ramp and your competitors are not, you have a massive competitive advantage that compounds over time. Ramp is the only platform designed to make your finance team faster and happier. Many of the top founders and CEOs I know run their business on Ramp. I run my business on Ramp and you should too. Go to ramp.com to learn how to help your business save time, save money, and grow revenue. That is ramp.com. Deal is how the best founders turn the world into their talent pool. I've been studying how history's greatest founders operate for a decade. And one thing they all have in common is they understand that recruiting and hiring the very best talent is your most important priority. A players recognize other A players, which is why top companies like Ramp, Shopify, Eleven Labs, Uber, and DoorDash all use Deal. Many of the top founders I know have personally invested in Deal after using their product. And what they discovered is that Deal is the best company in the world at building infrastructure for global hiring. Deal will help your business hire, pay, and manage any worker anywhere in the world so you can retain the best talent anywhere and spend the rest of your time focusing on what you do best, delivering value to your customers. The founder of Eleven Labs has a great description of the value Deal can give your company. He said, We built Eleven Labs to break down language and communication barriers. With Deal enabling us to hire and support exceptional talent anywhere, we can accelerate our innovation and bring more voices, stories, and ideas to every corner of the world. Deal is trusted by over 40,000 companies and growing fast. Learn how they can help your business by going to deal.com/senra.
That is deal.com/senra.
Did you see this profile that's written on Zuck in Colossus written by Jeremy Stern?

**Alexandr Wang** (16:57)
I saw it, if I'm being honest, it was like too long didn't read.

**David Senra** (17:00)
It's 15,000 words. I just had Jeremy in the podcast. He's my favorite.

**Alexandr Wang** (17:04)
Which I saw. I saw that.

**David Senra** (17:06)
Yeah. I think he's writing the best profiles on entrepreneurs and investors in the world right now. I think he's literally the best in the world the way he does. But in that, Zuck says, he was talking about the advantage that he has relative to, I think, Elon and Sam Altman. And he's like, listen, my skill set is very unsexy, but I'm really good at building teams and then just improving a product slowly over a long period of time. And relative to Elon and Sam Altman and others, it's like I'm not going to lose control of my company and I don't need to raise any more money. And so I can just do this for an excessively long period of time. That section of the profile is popping in my mind when you're talking about this seven month stretch of trying to refine and build Muse.

**Alexandr Wang** (17:44)
I think that's exactly right. Like I think that it took immense patience. I mean, seven months, like, you know, maybe it doesn't sound like that long, but AI is like fierce.

**David Senra** (17:54)
Seven months in AI time.

**Alexandr Wang** (17:55)
Seven months in AI time, which may be like a decade and like non AI time. And I think it for all of us, but I really give Mark a lot of credit for this. Like it took a lot of patience and restraint and a lot of trust in the process. And like, you can go back and look at the, you know, what Mark said in earnings calls for this entire period from February through September. And he will allude to the fact that we were building personal agents. I mean, we weren't really trying to hide it. Like we were building personal agents and we were talking about it, but I think, you know, there's a lot of doubt in the company for that entire period. Like people, obviously the, one of the dominant Wall Street narratives is like, oh my gosh, Meta is just burning all this money. Like, are they even going to pull anything off in AI?

**David Senra** (18:43)
It's more than that. It's like, Zuck cannot win AI. It said over and over again for a long period of time. And again, going back to Jeremy Stern's profile on him, he then off the record starts talking to his competitors, including one former researcher that is now at a competitor that used to work with Zuck, and is now at another lab.
And he goes, I don't want to have to compete with him because Mark's like the, I think the line is, Mark is the fucking Terminator. And it was like, he just does, will not stop. And he's like, then he talks about one of the superpowers that he's never happy with the state of the product, so he always wants to constantly prove it, but he's not an asshole. Like, he's not, you know, he's definitely a dictator, but like, he's not, you know, rude and like, kind of will destroy the chemistry of a team. He actually talks about in the piece that team cohesion is excessively important to him.

**Alexandr Wang** (19:30)
I think that's all right. I think one of the magical things about Muse was that we really like took quite a bit of time to sweat all the details before ultimately coming out with the product. Because I think that the personal agents was one of these product areas that kind of rested on a knife's edge, which is if it can reliably deliver these magical experiences, it has the potential to be one of the greatest consumer products ever. But you're dealing with models, you're dealing with something non-deterministic, you're dealing with agents, they can break, they can be unreliable. If people have these unreliable experiences, they think it's trash. It was one of these things where getting to the product to a point of quality and value such that it resonated with so many of the people who downloaded and used it.

**David Senra** (20:15)
I want to talk more about this process. I'm curious how much resources, how big the team, how many people are working on it. Do you guys have any data on like, okay, I'm using Muse, nine great experiences, two inconsistent or shitty experiences, and then I churn out? Do you have any information on this?

**Alexandr Wang** (20:31)
You can see this from a lot of the other agent products at the start of the year. Almost everyone churned out of those, and it's because they were unreliable. We did a lot of user testing of Muse. We did many, many rounds of new people trying to download it, and use it from scratch, and just seeing what that experience was like. A huge part of the premise of Muse, and I think what's really landed is that it is a different thing from what most people have experienced with consumer AI. It is not a chat bot, it is an agent, and it can do agent things for you.
I think to a developer, this is kind of like old news because they've had to download agents and have been using them for a while, but for most people, just even that graduation process, it needs to be explained and it needs to be on boarded on a very thoughtful way. And then for sure, we definitely have seen like when, because we've done tests with like different versions of the model and various model versions and continuously do those A-B tests. The product experience is very, very sensitive to model quality. It's very sensitive to how reliably the models can undergo these tasks, how reliably they communicate with the user about them, how reliably they check back with the user, if there's things that they require guidance on.

**David Senra** (21:54)
But how did you know it was ready to be released?

**Alexandr Wang** (21:57)
Part of it was pretty numerical, which is like we had set, go back to that spreadsheet of 100 plus things, we had set for each of those rows what threshold is launch blocking and above what threshold is good.
We had many checkpoints that were like green on 80 of the rows, but red on 20 of the rows, we knew that wasn't good enough. And we had our first model checkpoint, which was green across the board, which was a specially trained version of Muse Spark 1.3. So there was like the very numerical part of it. And then there was just the experiential part, which is we tried the model. We could tell that it was a lot better than anything we had iterated with before.

**David Senra** (22:38)
So going back to that seven month period you were talking about, how many people were working on the product?

**Alexandr Wang** (22:41)
Between the model work and the product work, like under 200 people total, which I guess sounds like a lot, but in big company land, it's actually a lot smaller.

**David Senra** (22:52)
It's not very many.

**Alexandr Wang** (22:53)
It was kind of cool looking back on this and thinking about it is like, we knew this was going to be the most important product that, and the whole executive team, everyone knew that this was probably going to be one of the most important products that Meta would ship this year, but we had the restraint organizationally, I think, to make sure that like it was a really small focused team working on it, and that it didn't balloon to this like, oh, you have like, you know, huge swaths of the company working on it, because we knew it was a single work of art, like it required strong point of view and strong focus to like pull that through into one beautiful experience.

**David Senra** (23:32)
Say more about this. Why did you just call it like a single piece of art and then you need a single perspective or point of view?

**Alexandr Wang** (23:38)
I think one criticism of products that come from larger organizations, and I think this is even now starting to plague a lot of the AI labs, is that they become this Frankenstein, almost like Kronenberg amalgamation of a bunch of different people's points of view and visions and beliefs. And it's sort of like PM Hell in some sense, where every PM has a thing that they're trying to get into the product and jam into the product, and then all of that blends together into this smoothie almost. People feel it as users and consumers. You can feel when a product is just like, it feels like lots of different people worked on it, and there were clearly different people who were gold differently, so they just kind of jammed it all together. Muse had to be the exact opposite, which is like, there's one clear point of view.
There is one cohesive experience that we're trying to deliver to the world.

**David Senra** (24:43)
I love that you said that, and it just happens to be pure coincidence.
I don't know when this is going to come out, but we're recording this on the 15th anniversary of Steve Jobs' death. And when you think of somebody like a pro, consumer products that had a single point of view, you obviously think of Steve first. I've read every single book on Steve and the history of Apple, and I've done like, I don't know, 15 or 20 episodes on him for my other podcast founders. But one of my favorite lines to describe Steve's impact was, it says that Apple is just Steve Jobs with 10,000 lives. The products are to his taste, his perspective, his point of view. What he wanted to see in the world is exactly what the end user got.

**Alexandr Wang** (25:19)
In Muse's case, like Nat Friedman deserves a lot of credit. Like his taste and sensibilities ultimately dictate and shaped what that product became.

**David Senra** (25:27)
Do you talk about how many people are using Muse? Are you guys talking about this publicly or no?

**Alexandr Wang** (25:31)
We have said millions, and then I have retweeted other people who have shown graphs where we would imply that Muse is the fastest growing consumer app of all time. Consumer AI app of all time.

**David Senra** (25:48)
So you won't say a number though?

**Alexandr Wang** (25:49)
We've said millions, yeah.

**David Senra** (25:50)
Well, millions could be hundreds of millions. Also millions, so you're just not adding the beginning to that. I want to go into like, you've been kind of going like, and I mean this in a loving way, like unhinged on X.
So you talk about, is this like marketing strategy? What is going on? I feel like there's a distinct difference in your public tweeting since Muse launch. What are you doing?

**Alexandr Wang** (26:14)
There's a few pieces of what's happening here.

**David Senra** (26:16)
This has got to be more fun than Scale AI. When you were building Scale AI, it has to be. We'll talk about that later, but it has to be.

**Alexandr Wang** (26:21)
The past few weeks have been some of my most fun building. Yeah, certainly in my career. And I think there's a few things happening. So one is, it felt important that we figured out a way to make Muse break through. It's a pretty torrential, going back to this, like a torrential stream of updates. It's like, for most people, there's just constantly being like kind of bombarded with new AI products and startups and releases and things and models. And here's another model and here's another product and here's another feature. And it's just like this torrential stream. We had actually meeting, large meetings, where we talked about this as a team. It was like, we need to break through. And obviously like Meta, we have lots of distribution. Like we can make sure everyone knows about it, but that's not enough to make it break through in an interesting cultural or fascinating way for the world to kind of like, you know, pay attention to. I separately in my life have happened to have met and become friends with like, memers.
And I have these, I affectionately call them my schizo friends, but people who like, literally they spend all their day thinking about memes on the internet and understanding that.

**David Senra** (27:38)
I have people that are obsessive muse, and they're also obsessed with your X feed, and they're convinced that you have like, a hundred muses coming up with memes to meme you. It's not that you just have a collection of schizophrenic friends that are terminally online.

**Alexandr Wang** (27:53)
The X feed, just for Wordsworth is like, literally every one of those tweets I write, there were like, a few, quite a period where I was like, it was like really hard for me to pay attention to meetings because I would just like, think of a meme. And I'd be like, oh god, I have to get this out. And I would like, it was like moments of inspiration. There was like, I was with one of my, like I was trying to have like dinner with one of my coworkers. And then during the dinner, I was like, wait, wait, I figured it out. And then I posted a different meme. It was like, it was almost, I almost felt like I was like an engineer solving bugs again, because it was like, you know, you could tell when something was going to click. But yeah, so one thing is we wanted to break through. Another thing that like, I just thought was important is like, how do we make Meta cool again? Because like, for whatever reason, despite having like these incredible pieces of cultural software like Instagram and Facebook historically, Meta was not cool for a while. And so I wanted to make Meta cool and interesting and kind of like funny. And then the unhingedness was something that happened kind of like naturally over time. When Muse first came out, I was just like mostly focused on promoting all the interesting use cases that I saw. I was like retweeting like tens of interesting use cases that I saw of people using Muse. And then at some point, it was like because I was just like tweeting so much, there were like a few tweets where I was just like, didn't think that much about it and just said, fuck it, post. And then some of those tweets like did really well.

**David Senra** (29:24)
Have you seen this like time spent thinking about it and then banger?

**Alexandr Wang** (29:28)
You've seen that? I haven't seen it, but I agree with that. That's like, I just, some of these names I didn't spend that much time on. I like tweeted them. I didn't even check my phone for a few hours and I was like, oh wow, that one went really well. And then I kind of like remembered something about the internet, which it wasn't super intentional, but I remembered like the internet rewards risk and it rewards like surprise and like things that like people don't expect. And so then I just kind of like went off. A lot of my coworkers, I think, were somewhat surprised at something that Nat said for the whole week when I was posting on the meetings. He was like, you know, I thought we would learn, he said this like in a bunch of meetings, he was like, I thought we were gonna learn a lot about, you know, Muse users and like how people were using Muse, but actually like we're just learning a lot about Alex's mind.
It was a lot of fun. I felt like I was drawing on all of my internet knowledge for years and years and years to like pull into those moments. And I think it actually, you know, I don't know, we have the tracking and it's like hard to tell, but I actually think it actually genuinely made an impact on growth, which is kind of hilarious.

**David Senra** (30:34)
I definitely think it did.
I can't stop hearing about it. So, and all the people I'm hearing about it from also downloaded the app and are now using it. Go back to what you were saying that it's like, hey, we have distribution, but that doesn't mean that we can make something that people are going to come back to and actually sticky. So like, how did you do this with Muse?

**Alexandr Wang** (30:49)
I think it was like, how do you make this into, how do we make this breakthrough as a product? And I think there were like a few parts of that. But I think one is, how do you get people to imagine the experience? Like, how do you get someone to a wow moment with the product as early as possible? And this product, I think, naturally lends itself to that because I think, you know, it's like, it's AI, it can do a lot. It can, there's like, if someone has never used an AI agent, there's a lot that it can do that will surprise you. So that I think was a big part of it. I think another part of it was like, how do you harness all of those stories of people having these wow moments and like use those to help make the product sing and make the product fly?

**David Senra** (31:33)
How are you using the stories though? Because you guys aren't running ads for Muse, are you?

**Alexandr Wang** (31:36)
We ran a few ads. I mean, honestly, like, I think at first it was just the fact that I would retweet so many of them. Like I was just, anytime I saw someone do something interesting about Muse, I was like, quote tweet.

**David Senra** (31:47)
I couldn't understand why both Anthropic and OpenAI's ads are so bad. Because remember, Anthropic was doing this huge outdoor campaign, and it's all about them. And same thing with ChatGPT, it's like they'd have the icon, which I don't even think people recognize as a logo, and it'd just say Codex and just be two people sitting at a desk. I'm like, what the fuck does this mean? Where it's like, you have all these use cases. All you have to do, your ad is to show the benefit of your product. That's it.
You have millions of them. Run those ads. It's so elementary, but it's interesting that people make this mistake over and over again.

**Alexandr Wang** (32:20)
Yeah, I think one thing that we came back to a lot in both Building Muse, as well as just building stuff in general at Meta, was just like, why would someone care?

**David Senra** (32:29)
They don't care about you or your company. They care about everybody's self-interested. This is like, there's this very old book. It's called Scientific Advertising. It was written in the early 1900s.
It was so valuable that the guy that made the most money as an advertising agency founder in the 1920s and 30s, it was written by this guy Claude Hopkins. He was this best copywriter. He's like, these are all the ideas, how I'm making this money. I'm putting this manuscript in a safe for 20 years, right? But essentially, it's not about advertising. It's about human nature, which doesn't change. And his whole point was just like, your ads are about you, your ads are about your product, your ads are like, hey, I have this thing, buy. People don't care about that. They're self-interested. And if you just, all you have to do is just do the trick of what this does for you. And you just lead with that. And there's people that took that idea, those ideas were written in the early 1900s, and went on to build massive companies, advertising agency founders, from the 50s, 60s, 70s, and even to this day.

**Alexandr Wang** (33:20)
Yeah, 100%.
I think there are a few insights, let's say. First is, most people in the world, they don't give a shit about, like, OpenAI or the research or these other companies or the research or even us or our research or whatever. They care about, like, what it can do for them. We had this gift of the mascot, which was the little jolly guy.
I remember the tweet where I realized, I was like, oh, wow, this is mileage. Because basically, I was driving into work and while I was on the way, I, like, generated a version of the guy holding a briefcase and I tweeted, MFW, I go to work on Monday. I remember thinking, like, this is, like, one of my best tweets in a while. And then I kind of realized, like, you can put him into a lot of situations. One thing I, like, kind of realized as we were going through that process was, like, how do you create surprising moments that are very different from any other marketing that you've seen of, like, a product? I don't, like, really remember the last time someone, like, you know, leaned into racy memes to, like, market a product. I don't actually know if it's been done before, but I kind of, like, realized, like, oh, wow, this is, like, a thing that we can do with this little guy. And that's something that, like, is interesting. That's something that, like, drives intrigue to, like, the average person.

**David Senra** (34:38)
Okay, but that might get them, raise awareness, might even get them to download the app. But then, how do you get them to stay engaged once the app is on their phone?

**Alexandr Wang** (34:47)
There's a cycle that people who really love the app, and we even, like, we back in February had, which is you try to give it a little thing, and it does it, and you're like, oh, wow, it did that. And then you try to give it a little bit, something, like, a little bit more, and then it does it. And you're like, oh, wow, it can do that. It could do that first thing, it could do the second thing, and then you give it, like, a little bit bigger of a problem. And it's kind of this, like, trust fall almost that you have with an AI agent, which is at first you, like, don't really trust it, but you're, like, kind of intrigued, so you're gonna give it a little bit nibble, and then you give it, like, something a little bigger and something a little bigger and something a little bigger. Certainly, like, when I talk to, like, college students or whatever, like, some of the ways that people use AI, it's like a full trust fall. They just, like, are recording voice notes and brain dumping to the AI, and they send it and they just trust the AI to, like, organize all the thoughts and give them, like, clear plans and think clear things to do, et cetera.
I think for the successful uses of Muse, it really is like getting them onto this trust fall process of using it for slightly bigger and bigger and bigger things and then having it work every one of those times.

**David Senra** (35:59)
I found one of my all-time favorite quotes when I was reading the book Zero to One. The quote says, The single most powerful pattern I have noticed is that successful people find value in unexpected places and they do this by thinking about business from first principles instead of formulas. That is exactly what AppLovin has done with their advertising platform. AppLovin connects you with over a billion potential new customers in mobile games. AppLovin allows you to capture undivided attention. AppLovin ads are full screen videos that are watched for an average of 35 seconds. That is retention that blows other ad platforms out of the water. And you can launch on AppLovin in minutes. You set the goal and AppLovin achieves it. No complex setup, no expertise needed. And AppLovin scales quickly. They can put your ads in front of over a billion potential customers. Other businesses have seen immediate results, scale to hundreds of thousands of dollars of spend per day and increase their revenue by millions. So you want to get started quickly before all of your competitors are on AppLovin. And you can do that by going to applovin.com. That's applovin.com.
I wonder how much of this is actually driven by word of mouth. So obviously talking to you, I was going to have to download the app no matter what. But what really piqued my interest is a friend of mine was sending me screenshots of how he was using Muse. So like when you download it, it doesn't really tell you like too much of like what you can do. It's kind of like open ended, like a, you know, like a open text box.
But a friend of mine, he's running like a hundred billion dollar company. He left his ID on a flex jet. And then he went through and he's like, well, I want to tell Muse I don't want to be involved in this process at all. You have to figure out how to get the ID, like go pick up the idea, this is where it's at, and then this is where I'm at, and then figure out all the steps along the way. And it like arranged the courier, went there, got to his security, his office somehow, and got upstairs to his office. Like, and it was like, holy shit, this is the best marketing. It's just three or four screenshots of Muse going back and forth, and him saying, I don't want to be involved. I have to do everything, and him figuring it out on the way.

**Alexandr Wang** (37:59)
You know, this is actually one of the things about, I don't know how, it was like somewhat intentional, but definitely like modern product marketing is like very screenshot driven. Like I think to have a modern consumer product, like it has to work on the screenshot. Like the screenshot has to fly, so to speak, either through like group chats or word of mouth or like online. And I think that's been a big part of it. This wasn't intentional or engineered, but I think the fact that we had the little guy in the screenshot is like was a big deal. Because I think having Jolly or whoever your Muse is like in the screenshot immediately communicates. This is a Muse screenshot. It's just like the best marketing you could possibly have.

**David Senra** (38:43)
So are you on your Muse like all day long? Like what is your own personal usage?

**Alexandr Wang** (38:47)
I mostly like set up a lot of workflows using it. And then I guess my meetings a lot of the time, but so in practice, like I think in my job, quote unquote, I'm supposed to like pay attention and be pretty present and interact with people. I set up a bunch of workflows and like kind of treat it as like a second brain.

**David Senra** (39:07)
Yeah, you said that in the post that you wrote and it was like really short and I think I saw last time it was like five and a half million views so far, but you said, I love how you described Muse. Like, well, if everyone had a second mind beyond their own.

**Alexandr Wang** (39:19)
I think this is, philosophically speaking, one of the most interesting questions about like, what does it mean to be human when you have like powerful AI and what is that relationship like and how exactly does that look? And different people have different takes on what exactly that looks like. I think the sort of like fear cases, obviously that AI is above us and that we're just sort of like doing what they do and there's like other worlds where that relationship is different.

**David Senra** (39:47)
Before you go on, what is your own personal view of that?

**Alexandr Wang** (39:49)
I really believe in Muse. I believe in the personal agent as like a long-term form factor of just it is human nature to have wants and desires and dreams. And I think like AI and personal agents like Muse will be the mechanism and the bridge that enables us to accomplish those things and continue accomplishing them. And then like humans will dream bigger and bigger and bigger and bigger. Kids will dream of like having their own star systems or whatever, and like Muse will help them do that. There's this thing that like Bezos wrote in like, I think it was one of his shareholder letters, which is like the beautiful thing about consumers is that they're like always beautifully unhappy or something like that, or like beautifully unsatisfied with the options they have. That is like one modality of our relationship with AI. I think that there's other modalities. Like I think that AI will start doing more and more of the scientific discovery process.
I think AIs will start inserting more and more into various parts of the economy. But I do believe in this modality, in this like form factor long-term of everyone having an AI that supports them and what they want.

**David Senra** (40:57)
So you see AI is kind of like removing all like the clutch of life, right? The stuff that we don't want to do. I think in the piece you said something like the world is full of like gatekeepers and obstacles and like Muse can get around this for you without spending any more of your time so you can actually focus on stuff you want to do.

**Alexandr Wang** (41:12)
I think Muse can give everyone the adulthood they dreamed of in childhood. Everyone, when they're kids, they have like big ideas and big dreams. And when they like imagine their life and they sort of like, you know, play it out, they imagine this life where they can like be an astronaut or they can save the planet or they change the world or whatever it might be. It's like a big, they think big.
And then for, you know, a variety of reasons, by the time people finish school, they enter the workforce, by the time they get to their, you know, have been in a job for a while, it's that like all that hope and ambition and ability to dream has been sucked out of them.

**David Senra** (41:56)
No, it's been beaten out of them. Their life has beaten out of them.

**Alexandr Wang** (42:01)
I think as adults, I don't think we like, just like appreciate the degree to which we're all zombies.
We lost our agency and we lost our, I think ambition is really a good word for it. One of the promises of AI broadly speaking, and I think through products like Muse, is to keep it going from when you're a kid. Like you're a kid, you have big dreams, use AI, help make those things happen. Then like dream bigger, make those things happen. Dream bigger, make those things happen. And kind of like experience this like escalator of agency, an increase in agency throughout your life versus a sort of like you have lots of agency and then it gets like crushed.

**David Senra** (42:39)
You know what I was thinking of when you were speaking just now, you mentioned earlier this experience that you and Nat Friedman went through where you had this like disturbing psychological audit and like coming in waves from this AI. It's like, yeah, what if we had that, but it's like the opposite of what you're saying. It's like actually gave you more self-confidence, like gave you understanding like the world is malleable. And if you push on it hard enough, you go after it with enough energy and drive, you can actually change it around you.

**Alexandr Wang** (43:02)
Yeah, I think this is something that like certainly the most impressive entrepreneurs exhibit, which is like, I think they like dream big, they accomplish that and they dream bigger. And then maybe they work on that for like a decade, but then like, you know, if they accomplish that, then they dream bigger. Like Elon is obviously a great example of this.
I think Mark is a great example of this. I think, but I think a lot of like the iconic entrepreneurs, this is like, like kind of like their lived experience. And I think there's a version of that that should be true for every person. And I think what's kind of like tragic is, I think for most people, you have like big dreams, big ideas, you enter the corporate workforce, you're, you kind of become a zombie. Maybe at some point you want to go tackle your dreams, but then it's like really, really hard because you have all these commitments, you maybe have a family, maybe whatever it is, it's just like, it's almost, you become trapped in the sort of like zombie hood.

**David Senra** (44:00)
There's one more thing on Muse before I want to get to Scale AI and like the partnership that you do, that you did with Meta and making that decision. But in this essay that you wrote, it's like short post that you wrote, I love what you said, you said, the world until now has been shaped by the small number of fanatics who have somehow found a way to make their wants real, but we've never seen humanity with every single person's agency fully switched on.

**Alexandr Wang** (44:22)
I think the promise of this world that I'm describing, where every single person has this agency increased throughout their lifetime, and they have the ability to accomplish their wants and their dreams, I think that world looks crazy in a very good way. I think it will be very interesting, it'll be artistic and cool, and you'll go into different pockets of the world, and it will be very diverse, that will be insane to think about what exactly that looks like, where literally billions of people have, all of a sudden, because of abundant intelligence, the resources to make incredible things happen.
I think that's part of the promise. I think in my head, it's almost like the Rick and Morty interdimensional cable, but just somehow manifested into reality for humans. It could just be really awesome.

**David Senra** (45:15)
So I keep hearing this line from that show where it's like, the universe eats smart people.
Okay, so I want to go back. What I'm personally curious about is, you found Scale AI, you're running Scale AI, and then one day Mark Zuckerberg reaches out and says, hey, I assume he says, hey, I want to talk. Can you tell me about this?

**Alexandr Wang** (45:36)
Yeah, I think the exact message was something like, hey, do you have time for a call?

**David Senra** (45:40)
Did you have a relationship with Mark previously? Did you spend any time with him? Like what's the background there?

**Alexandr Wang** (45:44)
I have a friend who, this guy, Alex Schultz, who I've known actually for many, many years, from when Scale was maybe a year old, I met him in San Francisco. He's currently the Chief Data Officer at Meta, but was a long time Meta Executive Lieutenant. And he introduced me to Mark, I want to say in about like, I think it was 2021 or 2022 to talk about AI, because I think at that time, Mark was getting a lot more interested in AI, Scale, we were doing a lot of stuff in AI.
My memory is that I think it took like, one year to schedule that first meeting. Like from the intro to the meeting being scheduled, I think it was like a full year.

**David Senra** (46:24)
Why?

**Alexandr Wang** (46:25)
Mark obviously has like an insane calendar and like has like a bajillion different things to deal with. And he's also very good at prioritization. Like he will spend a lot of time on the things that are really, really important. In some ways, like too much time on the things that are like really, really important. The only way he will do that and like be a good dad and be a good partner and all this other stuff is to just like ruthlessly prioritize.
I had spoken to him a few times kind of after that and had gotten his advice as a founder to get advice from, you know, Mark Zuckerberg, obviously like a really big deal.
And I actually remember at that time, like he wrote these like, like I would ask him a question on WhatsApp and then he would write these like really long responses. And I was really confused. I was like, how does he have time to write these like really long responses? But now I realize he like, is just like really fast and rigorous at writing to like a lot of WhatsApp messages. He'll like write a very rigorous, like long response very quickly. It's like a very impressive skill of his.

**David Senra** (47:24)
Gives you a sneak peek into what's going on in his mind.

**Alexandr Wang** (47:26)
Yeah, it's like, yeah, there's racing. Meta was an important customer of Scale. And I would say like prior to this instance, maybe we spoke once every like six months or so. Maybe that was like the cadence of our interactions.
And then, yeah, I think he had called. And I think it was actually like not obvious at first what the like end point was going to be. Because the first conversation was just like, you know, this was after Llama 4 And it was kind of just like asking, what do you think we should be doing?

**David Senra** (48:00)
Why is that an important point? That this conversation is happening after Llama 4?

**Alexandr Wang** (48:04)
Llama 4 was not on the trajectory that Meta wanted as a company. It definitely was like, I think internally speaking, a disappointment. It was also at a time where AI was clearly becoming just like increasingly, increasingly important. It was clear that AI was going to be like really critical to the future of Meta. So yeah, the first few conversations we spoke on the phone and he was just sort of asking for advice on like, what do you think we should be doing? What do you think we should be focused on?

**David Senra** (48:29)
This is what I've heard about him privately, that he has this insane, it's not a board of directors like a Meta board, although there's some people on the board that he also does this with, but he's got this group of world-class entrepreneurs on him, and I've spoken to some of them like, you don't understand, he asks for advice constantly. He's like hitting us up, he's like, here's what's going on in my life, I read the work, what would you do? And he'll do that over and over and over again.

**Alexandr Wang** (48:51)
I think this is quite an impressive trait. Yes. Because it takes humility obviously, continue doing that even after all the incredible things that he's been able to accomplish. I mean, the whole timeline from when he first reached out to when we announced the deal was like five, six weeks. Like it was like pretty quick.

**David Senra** (49:11)
Another thing that world-class entrepreneurs have in common, we had Jonathan Morales, the founder of Grok on this podcast. The first time we ever spoke publicly about the $20 billion deal he did with NVIDIA was on the show. And he's like, from the time first call from Jensen to the monies in my bank account was three weeks.

**Alexandr Wang** (49:27)
Yeah, that's amazing.
I just had lots of ideas on like what I would be doing if I were in his shoes, on like how I would be thinking about Meta's AI strategy. One of the first things I said was what I said earlier, which is like, hey, I actually think because Meta is like heritage-wide focused on things that people want to do, is actually one of the most specially placed companies with this incredible shift AI. I like had lots and lots of ideas that I sort of sent his way. And then, that was kind of this like conversation happening in parallel with this like, oh yeah, maybe we should potentially consider if there's a way to work together.

**David Senra** (50:04)
So, when he says that, what do you think? Because this is not predictable to you?

**Alexandr Wang** (50:09)
Not predictable, no. The whole thing was like, it was like a really crazy sequence. At the time, I was just like, oh, that's nice, but like there's no way that.

**David Senra** (50:18)
But you know what that means when they say that, right?

**Alexandr Wang** (50:20)
They don't want to buy you.

**David Senra** (50:22)
It's always the same thing, but they say, it's like, oh, we got to find a way to work together.

**Alexandr Wang** (50:25)
Yeah, I don't think I'd had that kind of coaching at the time.
One thing that I explicitly felt at the time was like, yeah, it probably doesn't make that much sense even. I think I personally was like, yeah, maybe he's teasing it or throwing it out there, but it doesn't even make that much sense.

**David Senra** (50:45)
Why wouldn't you think it makes sense?

**Alexandr Wang** (50:47)
I mean, obviously, a deal ended up happening.

**David Senra** (50:50)
So, what do I know? No, but back then, we know what happened, but I'm very curious to your thinking as you're experiencing this.
The fact that you said, oh, yeah, you said this was like, that doesn't make sense. Why wouldn't it make sense?

**Alexandr Wang** (51:01)
Taking a step back, obviously, the iconic meta acquisitions have been Instagram and WhatsApp, and these were like very clear product logic-driven decisions.
Scale is like a deep enterprise, government sales, like an entirely different kind of business from Meta. And so the logic that I had thought at the time would have made sense is if Meta wanted to get into those things, then I think maybe that's the industrial logic that would have made sense. But this wasn't that, because I think Mark clearly was predominantly interested in getting the Llama program and his overall AI program.

**David Senra** (51:47)
He wanted talent.

**Alexandr Wang** (51:48)
Yeah, he wanted talent. It was kind of shrouded and unclear the whole time, a lot of the way.

**David Senra** (51:53)
When did it become clear? After the money hit the account.

**Alexandr Wang** (51:58)
When we started talking numbers, I was like, oh, wow, okay, all right. That's when things became more clear.

**David Senra** (52:06)
At first, you're like, oh, this doesn't make sense. Then you guys keep talking, and then how fast did he convince you, this is a good path for you?

**Alexandr Wang** (52:13)
There was a part of it which was like, wow, this is a really fascinating deal construct. We ultimately landed on this deal where Meta invested, owns 49 percent of Scale, Scale continues, myself and a few people joined Meta.
What I was incredulous about at the time was like, it's such a weird deal, but is one that I think genuinely was like this very interesting win, win, win, win, so to speak. There's a win for the shareholders of Scale because all shareholders of Scale got a great deal, benefited a lot. Scale continues and I truly believe the best days of Scale are ahead of it.

**David Senra** (52:56)
My question to you is like, or what I'm personally interested in is like, okay, is this, he can explain this to you, and you come around to that perspective in one phone call? Is this like, wait, wait, Mark, I got to think this is so fucking crazy. I got to think about this for a few days, like explain this process as much as you can.

**Alexandr Wang** (53:14)
Many weeks of being like, this is insane, is this even real? Does this make any sense?
If it does make sense, like, how do I feel about it? The predominant emotion was more like, this is kind of insane. And then as I thought more about like, oh, I actually have to make a decision of whether or not I do this. That was in and of itself. There were like a lot of like conversations there with the people at Scale, with our investors. Like there were a lot of interesting conversations in that, on that side. I mean, it's obviously like really hard to like, let go of or give up your baby.

**David Senra** (53:49)
You worked on Scale for how long? How many years?

**Alexandr Wang** (53:51)
Yeah, nine years from founding until the...

**David Senra** (53:53)
And you're still young. You're not even 30 yet.

**Alexandr Wang** (53:55)
Yeah.

**David Senra** (53:55)
So this is like a third of your life.

**Alexandr Wang** (53:57)
There was something that Paul Graham said for a long time, which is like, you know, if you think of your company as your life's work, like you will operate differently. I did really genuinely think of Scale as my life's work for the whole time that I was working on it. That was a tough emotional process. And then I think what ultimately got me was like a combination of, wow, this is like a win-win, win-win, like kind of all, it's a good deal for all parties. And also just this like, I saw the potential of what could happen at Meta. And you know, this is a point at which like, I think Meta on AI certainly looked like damaged goods in many ways and like was maybe not the most appealing place to work on AI.
But I think that kind of like triggered my entrepreneur side where I was like-

**David Senra** (54:51)
You can essentially rebuild it. It's like a refounding of the lab.

**Alexandr Wang** (54:54)
Yeah. Yeah, like I think this is one of the things that ended up being kind of fascinating, which is like, because it was, you know, it was clear that there was so much work to do, it really like cleared the way for me to be able to kind of build a lot of stuff up from scratch, set up the right principles, build the right culture, like it created the conditions for us to build something amazing.

**David Senra** (55:19)
And is that how you and Mark discuss this? Like, hey, we have to hit a reset here. Like, obviously, like we're not, if we keep on this path, like we're essentially gonna throw out what we have and redo it with a completely different level of talent. Are these the conversations that are occurring between you and him? It didn't seem like he wanted like a minor adjustment.
You understand what I'm saying? He's just like, oh, this is not working at all. It's not gonna work, then let's, you know, go down to the foundation and rebuild, correct?

**Alexandr Wang** (55:46)
It was an evolving conversation where I think there were like, like one of the things that I believe really strongly. I think Elon is like, has demonstrated this in various times in his career, where you just have like a small, incredibly cracked, highly technical team that's like very flat. And like, if you do that, you can accomplish a lot very, very quickly.
So that was something that I had a lot of conviction in. And like, I believed in AI, like that is the right approach, especially if you had to do what we had to do, which is like move very, very quickly. And I think early on, that was one of the things I talked to Mark a lot about. And I think he was excited about as well. That ended up becoming one of the tent poles of our overall strategies, like small, very flat, highly technical team, very high talent density. How quickly can you move if you have those ingredients?

**David Senra** (56:36)
From an outside perspective, it seems like Mark empties the clip, just the way I think about this, right? Have you ever read this book called The Mind of Napoleon?

**Alexandr Wang** (56:44)
No.

**David Senra** (56:44)
Okay, so The Mind of Napoleon, published in 1957
I found it because I saw this interview, I think Tyler Cowen interviewed Sam Altman, and I think it was in 2019, and he asked him, what's the most important book that you read this year? And he said The Mind of Napoleon. So it's very hard to find. I buy the book. It's 300 pages of just Napoleon and his own words, organized by topic. And in that, he talks about over and over again that hesitation is fatal. But he says, before you engage in a course of action, there's a lot of deliberation. He'll like study from every angle, make sure he's making the right decision. I feel there's like an echo with the way Mark operates.
Does a lot of deliberation, make sure he's on the right path. But once he makes that decision, he just goes all in. He won't like, he just empties the clip. And that's the way I felt about like what was occurring right at this point where he comes and gets you. And then you guys start rebuilding this entire organization.

**Alexandr Wang** (57:28)
I think he really has internalized that failure doesn't matter. It matters like when you win, how big you win.
And I think this overall concept, I think, enables him to operate, I think truly without fear in a lot of circumstances, because I think he is just very comfortable taking lots of risks.

**David Senra** (57:46)
He's got that great line where it's like in a world of changing all the time, the biggest risk is not taking any.

**Alexandr Wang** (57:51)
Yeah, exactly. I think he's internalized this quite deeply. Like there's certainly like versions of the world where Meta looks a lot more like Google in some sense. Like it's just like, you know, more slow moving and more bureaucratic and just like looks very different as a company. But I think he, because he's internalized in these lessons so deeply, keeps the thing dynamic and moving and live.

**David Senra** (58:13)
Talk me through the difference between how like, how you were as like, you're the founder, you're running Scale. Now, you're refounding this lab working with Mark, like the different ways that you approach your work in those two environments.

**Alexandr Wang** (58:29)
At Scale, one of the things like I really internalized, I don't even remember where this advice came from, but it was kind of one of these ideas that like, if you want to be a good founder, you have to be able to do every job. Had a very strong point of view about how like every little thing at the company should happen and should work. And that resulted in a company that was like very much so a product of my effort and like my point of view. And it like expressed itself in all sorts of ways throughout the company, but also made me the bottleneck in very big ways. There's like pros and cons of that for a company. I think definitely, I think that's like, you know, if you were to start a company and it's your first time starting a company, you should like definitely take that approach because it's like much more likely to be successful than if you don't take that approach.

**David Senra** (59:12)
Will Scale be your first company?

**Alexandr Wang** (59:13)
Scale is my first company.
Yeah. But at Meta, like it was a very different assignment because we had to accomplish so much in so little time. Like I didn't have the luxury of being able to, quote unquote, do every job within the lab. I certainly am not an AI researcher. I'm also not a like product designer. I'm not, you know, I'm not all these things that are like totally pivotal to the organization being successful. So at Meta, very much so, I adopted this like philosophy around just how do we create an environment where we're gonna hire incredible people. Like it was like job number one, hire brilliant and incredible people, like we're at the top of their field across every discipline.

**David Senra** (1:00:04)
Why do you think you're able to do that at Meta? It's just because you have more resources? Like why can't you do that?

**Alexandr Wang** (1:00:09)
I think one of the things that was very charismatic and attractive about the founding moment of MSL was there was an opportunity to build a lab from scratch with a really, really small team. And we had a strong point of view of where we're going, personal super intelligence, that I think resonated with people. Like I think everyone who works on AI wants it to help people, wants it to ultimately mean something to their mom or to their grandma or to their grandpa, wants it to be something that's meaningful to every single person in the world. Because of the fact that we're doing this with the resources of Meta, there was an opportunity to, we weren't going to be bottlenecked by compute, we weren't going to be bottlenecked by infrastructure, we weren't going to be bottlenecked by distribution, we weren't going to be bottlenecked by the things that startups often are bottlenecked, but it was an opportunity to really build something that you could put your stamp on and have a lot of influence over and really shape. I think that was quite exciting for a lot of people.

**David Senra** (1:01:11)
That's why he chooses to spend an insane amount of money, what looks like an insane amount of money, getting a handful of top talent because then he knows that those top talent will recruit in turn other top talent. But you need that as a starting point, correct?

**Alexandr Wang** (1:01:26)
Yeah, and I think one thing that is maybe someone underappreciated about that specific part is that, I mean, the stock prices of OpenAI and Anthropic ran up a lot. So it just happened to be the case that if you looked at how much these people were making, if they stayed at OpenAI or Anthropic, it also was a lot of money. So I think for a lot of the talent, it ended up being kind of net neutral in many ways, comp-wise. But obviously, I think it's kind of like the same thing. Oftentimes, a lot of us don't think about how much the early employees or the early researchers at these labs that have had immense stock value appreciation, what their comp looks like.
We started this fully on the belief of having and hiring most brilliant people, that's one. St. Clair North Star Personal Superintelligence, those two. How do we create the environment where people do their best work? At Meta and in MSL, I'm doing much more of like quote-unquote traditional management, so to speak, because these are the things I'm thinking a lot about, is how do I create the environment where all these brilliant people who are exceptional and very, very special can all operate and achieve the greatest expression of their talent? I'm thinking a lot more like almost like a coach in some ways versus at Scale, it was like very different. Like I was the auteur, I was like the person whose like point of view had to be expressed in everything that we did.

**David Senra** (1:02:59)
Say more about that you feel like a coach.

**Alexandr Wang** (1:03:02)
I think that like my job is to A, like help set the North Star and the directionality of where we want to go, which again, personal super intelligence, winning on consumer AI, like building AI that means something to every person, and then spotting in the team special talent, and then giving people the environment resources to be able to express that maximally. Like I think one thing that big companies often mess up is that there's like exceptional people at most big companies, but they just like are not empowered to do their best work, and that's why they often leave to go to smaller companies or start startups or whatever it might be.

**David Senra** (1:03:44)
You mentioned Jeff Bezos' shareholder letters earlier. That's something he would repeat as well. And all the books are about him, but also shareholder letters. If you have great people that can't build, they're going to leave.

**Alexandr Wang** (1:03:52)
Yeah, exactly.
And AI is such a special thing. I think this term research, now it feels like it almost doesn't mean anything, but by definition, humanity doesn't know the limits of what these models are capable of, and what are the things you can do with them. They really are these like unknown artifacts that we don't understand support. So like it really is science and research. We are exploring the limits of what you can do with this technology, and what are the things that can be built. And it is a process that requires lots of trial and error. It requires like brilliant people to have incredible insight. Like it's one of these things that you can't think about this process, like a very operationally intense process. People need space and time and resources to be able to do their best work.
And I think about this in many dimensions, right? I think Nat Friedman is absolutely brilliant. And as I mentioned, so much of Muse, if there were a single person whose single point of view came through on Muse, it is Nat. It's important for him to be in a position where he can fully express all of that. And then we have some brilliant researchers. They have very, very exciting ideas. How do we create an environment where they are able to explore those? And most of them won't work out. Some of them will work out incredibly well. The cases where that works out justify all the investment. So there's two kinds of problems, so to speak, in that nowadays is like diamond mining or building skyscrapers. And it depends on what the distribution of the payoff of the things that you're working on are. So there's some areas where the distribution of super power a lot. Most of the things you do will be kind of useless, but then some of the things you do can be like literally a million times more valuable than everything else. VC, I think, is a great like diamond mining kind of industry to give a sense. It's just all about like being able to identify the special ideas and like see those through.

**David Senra** (1:05:54)
And that's easy to do. Just look at, just go to your 19th birthday party.

**Alexandr Wang** (1:05:58)
Yeah, I mean, that's like unbelievable.

**David Senra** (1:06:01)
There are people listening that don't know what the hell I just referenced. Can you talk about real quick who was at your 19th birthday party and why that would have been a good bet if they just invested everybody around the table?

**Alexandr Wang** (1:06:10)
This is like a really crazy thing to think about. My 19th birthday party, I was a freshman at MIT. It was in January. I was doing a winter internship at a trading firm called HRT. There were like 10 of us, 12 of us, something like that. Almost all of them were students at either Harvard or MIT. Most of us already knew each other from various math and science or computer science competitions. Some of the other people were Jeffrey Yan, who went on to start Hyperliquid, very successful.
Scott Wu went on to start Cognition, very successful. Another person there was Jesse Zeng, went on to start Decagon, also quite successful.
Another person is Vicky Yee, who is, I think, a brilliant researcher, works at Anthropic. Everyone was incredibly talented. I actually talked to the founder of HRT recently, and HRT itself, by the way, now is crushing it unbelievably.

**David Senra** (1:07:09)
What does HRT do?

**Alexandr Wang** (1:07:11)
HRT, it's a proprietary trading firm, so they trade their own money. In Q2 of 2026, had 11 billion of revenue, and I think 8 billion of profit is the record number. This is, I think it's under a thousand people work at HRT. I mean, it's like unbelievable. But I recently met up with the founder of HRT, and they were talking about like, oh yeah, we're starting to do some private investments. I was like, just invest into the interns.
All the interns get seed checks.

**David Senra** (1:07:45)
That's great.

**Alexandr Wang** (1:07:46)
I grew up doing math and science and computer science competitions and Olympiads, and got to know all sorts of people from all around America doing this kind of stuff. It's like quite surreal to see the people that I did competitions with become so successful.

**David Senra** (1:08:04)
It's gonna be fascinating what all of you do the next few decades. Before I interrupt you, did you have more to say about diamond mining and skyscraper stuff?

**Alexandr Wang** (1:08:11)
Basically, it's like, does it have a power law payoff where some things just like pay for like, literally like a million times the investment, or is it something more like building skyscrapers, which I would describe data annotation or data businesses as more like this, which is like Amazon Prime Delivery is another example where the payoff is pretty linear and you have to just get develop a process where you're like really, really amazing at doing it. If you're building skyscrapers, then it's like a very operational business and it's all about like squeezing every ounce of efficiency out of that process. And you just look at it and you figure out like, I can make it like 2% more efficient this way and 1% more efficient that way and half a percent more efficient that way. And you just try to squeeze every ounce of optimization out of it.
And then there's diamond mining where you're kind of like, hey, everyone just like, you know, go forth, try all your crazy ideas. And like you're just nurturing the ideas that seem promising.

**David Senra** (1:09:09)
That's what you feel you're doing at Meta right now?

**Alexandr Wang** (1:09:10)
That's what I feel I'm doing at Meta.
And the building skyscraper stuff, generally speaking, is what I felt I was doing at Scale. And that's like this big paradigm difference.

**David Senra** (1:09:21)
Going back to the coaching and the way, the difference of how you're essentially managing now at Meta compared to what you did at Scale, why do you have so many direct reports? Do you have like what, 100 direct reports? How many direct reports?

**Alexandr Wang** (1:09:29)
Yeah, I think more than 200, yeah.

**David Senra** (1:09:31)
How and why?

**Alexandr Wang** (1:09:33)
Going back to it, like one of the founding thesis of MSL and what we want to do in rebuilding this lab was how do you have like really, really high talent density?
How do you make it like the best place for a lot of these brilliant people to do their best work? And how do you build an organization that's like technically focused where the time people are doing the best work? You have the opportunity to really do their life's work. And one of the design principles around this was making it very flat. Effectively, all the research that we hired into this group called TBD, they report directly to me. And it's more of a statement of the fact that like, this is like anti-bureaucracy, like TBD is like literally anti-bureaucracy. The point is we're hiring brilliant people and you all have like demonstrated clearly that you can do brilliant, brilliant work. You have like done it before in your careers. So I don't need to be micromanaging you to do brilliant work. You're going to be able to do that on your own.
We need technical leadership. So some of you are going to be responsible for like setting clear technical directions for your groups. And we have this kind of like pod structure where we have various pods and there's various technical leads of the pods who tie break on the technical decisions. So there's like a technical leadership structure in place. But from a quote unquote people management perspective or from a bureaucracy perspective, we're just anti-bureaucracy. And then the other part of this is like, we do make a lot of group decisions. Like we want to debate because it is like a very talent-dense group of like brilliant people. We want to have those conversations where we're all discussing what do we think the right path is.
Everyone in the lab has done brilliant things. Like we want to hear all these opinions. We want to arrive at things that we all believe are the best path forward. So it's certainly like an unconventional way to run the team. And like, I would be lying if I said I was like the best manager to more than 200 people. But this part of the point is that like, they don't need managers. They need a great environment. They are all brilliant. They're all extremely capable. They just need the room to cook. Yeah.

**David Senra** (1:11:44)
And so maybe not a coach. You're kind of like the steward of a great environment so they can do great work.

**Alexandr Wang** (1:11:48)
Yeah, exactly.

**David Senra** (1:11:50)
Alex, this is awesome, man. Thanks for taking the time.

**Alexandr Wang** (1:11:52)
Yeah, thank you.

**David Senra** (1:11:54)
I hope you enjoyed this episode. Please remember to subscribe wherever you're listening and leave a review and make sure you listen to my other podcast founders for almost a decade. I've obsessively read over 400 biographies of history's greatest entrepreneurs, searching for ideas that you can use in your work. Most of the guests you hear on this show first found me through founders.
