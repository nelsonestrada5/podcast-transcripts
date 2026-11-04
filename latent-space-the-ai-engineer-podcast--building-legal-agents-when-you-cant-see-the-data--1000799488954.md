---
podcast: Latent Space: The AI Engineer Podcast
episode: Building Legal Agents When You Cant See the Data - Jacob Lauritzen, CTO of Legora
host: Jacob Lauritzen (CTO of Legora)
transcript_id: 1000799488954
published_at: 2026-11-02
source_url: https://open.spotify.com/episode/3iXjVy6f9OGxyjKm47g0nd
---
**Jacob Lauritzen** (0:00)
People were asking us about mythos and everything, even though I think realistically a lot of legal work does not require mythos-level intelligence.

**SPEAKER_2** (0:06)
Paralegals, gone. Junior lawyers, gone, I don't need them.

**Jacob Lauritzen** (0:10)
That's actually not what we're seeing. We had one problem where it wouldn't cite properly, so next model release solved, it went from 70% to 99%. It's like we did nothing and great. But if you're doing a $400 million M&A transaction, you're going to want Legora. We're just going to be 20 engineers for the rest of the company's history, and we're going to beat everyone who's much bigger.
We're 100 engineers now and it feels like we're way too small. But it's something that I'm toying with is like how much of our product can just be the agent. We're sold the other stuff.

**SPEAKER_2** (0:39)
Okay, we're here in the studio with special guests. Jacob Lauritzen, CTO of Legora. Did I get it right, Lauritzen?

**Jacob Lauritzen** (0:45)
That's fine. Yeah, that's okay. I'm not too sure how it's Danish. Yeah, exactly.

**SPEAKER_2** (0:49)
Does it have a special history?

**Jacob Lauritzen** (0:50)
It just knows, Sen is like son, son of.

**SPEAKER_3** (0:52)
Son of Lauritzen.

**Jacob Lauritzen** (0:53)
So you have son and yeah. So son of Lauritzen, that's my name.

**SPEAKER_3** (0:56)
Nice.

**SPEAKER_2** (0:57)
We've crossed paths here and there. You spoke at AIU a few times, and obviously Legora is one of the fastest growing legal tech in history.
And you said something at the start in a pre-show that I thought was really interesting. You said that your origin is very European, even though obviously you're expanding in New York and SF. What feels different about your culture?

**Jacob Lauritzen** (1:17)
I think we are just at the core, probably very humble about what we're doing, because we've always been the underdog from the very beginning. No one believed a small startup in a basement in Stockholm was going to outcompete this huge behemoth that was way ahead of us in the US. So I think we've always been underdogs since we've always been very humble. We've always had to fight for our existence.
I think something we've had to learn is we've also become more and more, as we've entered the US and been in the US a lot more, is to be a little bit more bold and tell the world how great we are, because it doesn't come naturally to, I think, some of us.

**SPEAKER_3** (1:54)
I kind of want to start by going over your guys' product, because I feel like with a lot of these legal products, they're kind of under wraps. You're not supposed to show it. But yeah, if you could just talk about what does the product look like, and maybe how did you guys get there? What have been the product iterations that got you to where you are today? I think that would be really interesting.

**Jacob Lauritzen** (2:13)
Absolutely. The way everything started was ChatGVT with Swedish laws. It's a search tool in it. That was literally the entire everything. So that's where we started. We started with legal research, which is like a huge market basically in the world where lawyers spend a lot of time figuring out what are previous cases that look like this, what's the legal precedent, what have previous people done in these situations. That's extremely important.
And so that has always been part of our product. Basically, we started from an agent, you could ask questions and it would query laws. That was a very simple beginning. And then from that, it's expanded. And so it's expanded in like, what can the agent do? It will now draft a lot of stuff really well. It will edit Word files. It will move your files away, organize everything, run really complex analyses.
And we've added just a bunch of more features to it. So one of our features is called Tabular Review, which is now a name that's being used in industry. And we're very happy to see Claude for legal using our terminology for what they're building.

**SPEAKER_2** (3:13)
We've got to talk about that.

**Jacob Lauritzen** (3:14)
Which is actually a way to just bulk extract and bulk review many, many, many agreements, which you do in due diligence and when you raise money or whatever.
So that's part of it.
We help lawyers just do their work much more efficiently, much better. And then outside of just doing the work, we're also now helping orchestrate the work a lot more than we were just even a year ago. So we have a thing called Lists, which is sort of like linear for us. And we have Intake, which is a way to collaborate with clients. And we have Portal, which is also sort of a way to collaborate, you know, lawyer to lawyer, client to lawyer, lawyer to agent, agent to agent maybe.
We're spending a lot of time there because there's just frankly, the way that you work with a lawyer 10 years ago, or maybe even today is really painful. And there's loads of room to do that in a much better way, to be honest. And so those are like, I think, the two things. It's doing the work and it's also like, orchestrating the work.

**SPEAKER_3** (4:12)
When did you guys start doing or building the agent?

**Jacob Lauritzen** (4:15)
So, I mean, we basically had this switch from the assistant to the agent, we call it, right? I guess that the agent, I don't know, I want to say a year ago, probably.

**SPEAKER_2** (4:25)
Yeah. So this is a rough timeline for people who are understanding YC 2023 Yes. And you were YC founder as well. YC24.
YC24.

**Jacob Lauritzen** (4:33)
Yeah, I was in YC23.

**SPEAKER_2** (4:35)
Yeah.

**Jacob Lauritzen** (4:35)
Legora was 24

**SPEAKER_2** (4:36)
Okay. And then, so there is, this is like a little bit pre-agents really taking off.

**Jacob Lauritzen** (4:41)
Exactly.

**SPEAKER_2** (4:42)
And then like using models obviously change everything.

**Jacob Lauritzen** (4:44)
Yes.

**SPEAKER_2** (4:44)
I mean, in one sense today, we had a preview of the products. It does look, well, preview, we had a private thing. Well, we will put up a video on YouTube. It's mostly like ChatGPT for lawyers.
Very fair to say that. But then the sidebar has a lot of nice custom tools like the tabular view, like the intake, which I really liked, and a bunch of other things.

**Jacob Lauritzen** (5:07)
Exactly.
That's exactly what it is. It's coworker ChatGPT, just like really, really good for legal work.

**SPEAKER_2** (5:13)
And the workflow for either in-house corporate lawyers, people looking for according regulations, all these things. And we can talk about more of the products there.

**SPEAKER_3** (5:23)
Yeah. What models are you guys using underneath? Can you talk about that?

**Jacob Lauritzen** (5:27)
I mean, we're using a bunch of different ones depending on task, right?

**SPEAKER_3** (5:31)
And that's not available to the lawyer to see? You guys pick yourselves.

**Jacob Lauritzen** (5:36)
Yeah. Well, we've been back and forth on this.

**SPEAKER_3** (5:38)
Yeah.

**Jacob Lauritzen** (5:39)
Just like everyone else, I think. In the agent, there's a model selector for the primary model, but there are certain tools that we use different models in, and there's like tabular view and like we try. I think we found it most effective to subdivide the problem and route on like as we subdivide the task. But we do right now have a picker in the agent.
I'm not sure if that's going to stay there always, to be honest. So, yeah.

**SPEAKER_2** (6:03)
Yeah, I mean, so I bring a little bit of context to this because I'm an advisor for Cognition.

**Jacob Lauritzen** (6:07)
Yeah.

**SPEAKER_2** (6:08)
And when I joined, part of my thesis for what an agent lab is, an agent lab is ideally a domain-specific GPT wrapper, right? Like we are the domain experts. We will pay attention to you. We will serve your needs way, way more than the Frontier Labs, and we will give you the best of the Frontier Labs, according to our judgment. So our job is to decide for you because your job is not to...

**Jacob Lauritzen** (6:31)
Exactly. We will always keep you on the Pareto Frontier and make sure that it's great all the time and you don't have to dive into all the details. Because one of the things that I've exactly to this point, if you go to a lawyer and you ask them, oh, you're going to draft this contract based on this precedent, do you think that's a sonnet high or an opus mid task? They won't know.

**SPEAKER_2** (6:50)
Just give me this part of this model.

**Jacob Lauritzen** (6:51)
Just make sure it works.

**SPEAKER_2** (6:52)
My hourly rate is $1,000 an hour. Exactly. Just make it work.
So yes, I originally came in with that. I was like, oh yeah, this is what Devin does differently. And now we have five things in the model picker, including Fable and Opus and Astra. And people want to experiment with the fancy new model. Is that the same?

**Jacob Lauritzen** (7:12)
I think so. I think it's definitely way less illegal than it is in coding, engineering, but there are definitely people that just want Fable 1 right away and people were asking us about mythos and everything.
Even though I think realistically a lot of legal work does not require mythos level intelligence.

**SPEAKER_2** (7:29)
Yeah. So exactly. I think basically you're like, okay, we'll give it the option. You ask for this.

**SPEAKER_3** (7:35)
Exactly.

**SPEAKER_2** (7:35)
But you're going to run down your credits like 10x faster than them.

**Jacob Lauritzen** (7:39)
Yeah. I would have loved. We fought introducing it for a very long time and then in the end, we just kind of caved in and we're like, okay, if you want this level of control, then we'll give it to you.

**SPEAKER_3** (7:48)
So you think the models are already as good as lawyers need? There's no need for them to get better?

**Jacob Lauritzen** (7:54)
I think it's a power distribution. So there's probably 60 percent of the work. We can do really well right now, and from now on, it's like a cost and latency thing. But then there's the rest of the thing where, especially for very complex analysis, we still need more intelligence. And then I think there's also just the work expands.
That's the work that we have right now, but also the work with Forward Deployed, thus probably expands with intelligence, I imagine.

**SPEAKER_3** (8:21)
Early on, when you guys first started, I guess, transitioning to the agents or building the agents, what models were you guys using? I guess, it would have been like Opus 46 or something?

**Jacob Lauritzen** (8:31)
That would have been, yeah, Sonnet 46, Opus 46 is probably right.

**SPEAKER_3** (8:37)
What were the agents not good at at that point, that they're much better at now, even though it's only like nine months later?

**Jacob Lauritzen** (8:44)
Sub-agent delegation was one of them that we've gotten working really well now for like fan out type retrieval queries, works extremely well for us now.
That was difficult before. We basically track, so we have a team that's just doing evals, and so we track all of the model's performance in different practice areas which is subgroups of legal and different tasks across all of those. So we basically have a big sheet map and we're like, and then we can see them move and it's like, usually they improve most stuff, but there's actually a lot of model releases where they improve some and regress in others.

**SPEAKER_3** (9:15)
Okay.

**Jacob Lauritzen** (9:16)
And that actually happens a lot more than you'd think.

**SPEAKER_3** (9:18)
Like what are some of those tasks, like are you familiar with how you guys are running a lot of the evals? What are those different sub-segments I guess that you look at?

**Jacob Lauritzen** (9:25)
So like there's different just like framing stuff. So we have different basically like worlds or like RL environments essentially, which is like here's a- cause Lauritzen work in projects always more or less. So it's like here's 10,000 file data room. You're doing a due diligence. In the end, a great report looks like this. Like it contains all these red flags and like it doesn't contain whatever weird stuff and like we want it to be concise, etc. That's kind of how we've built it. So there's different tasks, which is like part of it is drafting a report. Like does the draft look good? Does it contain all the right stuff? Is the wording sound, the analysis sound? There's also the part of finding the red flags, like the analysis before that. So we can kind of like subdivide it a little bit.
And that's how we run the evals.

**SPEAKER_3** (10:07)
Interesting. What does your eval team look like? Like do you hire lawyers to like do that?

**Jacob Lauritzen** (10:12)
So yes, it's a mix. We have engineers and then we have lawyers and it's one team. So there's like three engineers and like three lawyers right now. And then we have a pool of what we call legal engineers, which is people that have worked in big law for like three or four years.
Typically, maybe they have a CS degree and like they're very tech forward. And then they come to us and because they want to like help change the industry.

**SPEAKER_2** (10:34)
Are they IT in big law?

**Jacob Lauritzen** (10:36)
No, they're lawyers in big law. They're lawyers in big law.

**SPEAKER_2** (10:39)
With CS degrees.

**Jacob Lauritzen** (10:40)
Yes.

**SPEAKER_2** (10:40)
Oh my god.

**SPEAKER_3** (10:41)
It's a Venn diagram.

**Jacob Lauritzen** (10:42)
Yeah, exactly. That's like our hottest person to hire for.
But they're also such a force multiplier because we can pull on them for the eval stuff and for the product development. It's just that you have a pool of 100 experts that use the product every day and go and talk to clients every day. And also they live this and have lived this. And we just pull on them to do evals and help us shape the product and it's such an advantage.

**SPEAKER_3** (11:03)
And curious, when did you guys start that team?

**Jacob Lauritzen** (11:05)
Evals grew out of the assistant agent team at some point. I think there was a point up until recently where it was like, honestly, it's just not really worth it. Because all models just got better.
So it was like, do we want to spend a lot of our time doing really complex evals? Or do we just want to build? Because there was so much to be gained from building a better harness and just sort of leaning in to everything's going to improve, and everything kind of just improved.

**SPEAKER_2** (11:30)
Yeah, like every two, three months, you get a different model.

**Jacob Lauritzen** (11:33)
Just pass it through, right? Exactly. I mean, we had one problem where it wouldn't cite properly, and so it would be difficult to follow. And it was like, next model release solved. It went from 70% to 99%. It's like we did nothing, and like, great.

**SPEAKER_2** (11:44)
Yeah, maybe the real work is keeping all the data private, making it taggable, sortable, adding new features like the tabular view. Is that the, you know... You mean over and above chat dbt? Yes, but obviously now you're also doing evals. I assume your use of open models is also increasing. We can talk about that.
So yeah, I don't know what I'm saying here apart from like, you know, what is the job? The job is maybe not... In the early days, it was not so much to do evals because it was mostly exposed model capability to lawyers.

**Jacob Lauritzen** (12:18)
Yeah, the huge part of it is just figuring out what does the legal profession look like in five years, ten years with all of this stuff. Like coding is maybe a year or two ahead, so that we can kind of look to that a little bit. But like, what are the primitives? How do people work? How do you collaborate if it's not a 200 thread email with like v5 word files back and forth? Like, what does that look like? And that's like, not even necessarily purely AI.
That's just like, build a much better product experience. Yeah. And make sure you do it with like, audit logs and data retention and all of those sort of really important things and regulate it in industry. And then there's the AI part, which is like make the work faster and better and proactive agents that react to stuff when it comes in, so you don't have to kick off everything. So I think a lot of the work is just figuring out what do we think it's going to look like in five years. If model capabilities keep increasing, if price keeps coming down, what could we do? Couldn't you log in and it's like command center where it's just like you need to react to these five things that the agents have been doing lately and review and check and improve the system? Maybe that's where we're going, or it is where we're going.

**SPEAKER_3** (13:20)
Yeah. Yeah. Yeah. I was going to ask, could you go into that in a little more depth? Like yeah, what is the law profession going to look like in a few years?

**Jacob Lauritzen** (13:32)
I should preface this by saying I don't know. I mean, who knows really, but I think we can look to coding a lot. I think all lawyers are going to be way more productive than they were before. They're going to be able to do a lot more stuff at a higher quality for lower cost. I think the profession itself, the work itself is going to improve a lot. It's going to be a lot more. I think lawyers are going to spend more of their time doing the stuff that they became lawyers to do.
You know, figuring out what's the right risk profile, what's manageable risk, what's like all of their strategic judgment and working with clients, they're going to do that a lot more and much less of the trolling through big documents to find the smoking gun or do all this menial super annoying work that a lot of lawyers have been doing.

**SPEAKER_3** (14:18)
What do you think is going to happen in the partnership model? Do you think that stays or what happens?

**Jacob Lauritzen** (14:22)
I actually gave this a lot of thought just like last week. Because the partnership model, I don't want to get into too much of the details, but the partnership model kind of exists because the only type of capital that these companies have is human capital. So it's not like us or a software engineering firm or a manufacturer or whatever. You have physical assets or some sort of intangible assets that you accrue over time and they pay dividends to the shareholders. But if you work in an industry like professional services, and it's the same for consultancies and whatever else, all of your value is in your people and you can't really own human capital.
Slavery is abolished, you can't own people, but you can rent them, you can pay the money. So partnerships essentially is a structure where you make the human capital of the owners of the company so that they stay. Yeah. Will that change?
It doesn't have to, but I think what we really want to do with the Lawyers, we actually want law firms to be able to build some intangible capital, some durable capital and you can build a system that learns of how you work. A lot of firms right now think about like, well, there's the ex-law firm way of doing things and we can codify that, I think, and we can build a system and whether that's a self-improving knowledge graph or whatever it is, and precedent files and documents where there's a way of working that produces a really good output and that can be their IP. So it's a way to codify the human expertise and judgment into a system.
That I think is, now I'm just rambling completely, but that's something that we want to help empower. Does that change the partnership model then? Because the incentives are different. In the partnership model, you just got to bring more clients, and you don't want to take away time from bringing in clients to codify your information basically. Because you get rewarded from Eat What You Kill or Make This Lark's Deb, whatever. That needs to change a little. We need to figure out an incentive structure where partners are incentivized to codify things, to build an asset for the company. But right now, there aren't, because the sumas, they leave the partnership, they don't get any dividends from the assets that they built.

**SPEAKER_3** (16:32)
Yeah.

**Jacob Lauritzen** (16:32)
So it's like a, yeah. I think the whole business model is, we'll see.

**SPEAKER_3** (16:38)
Yeah, it's all in question right now.

**SPEAKER_2** (16:41)
My actual other take, on the partnership level, that's like the top end of the industry. Actually, my take is more on the bottom end, right?

**Jacob Lauritzen** (16:49)
What happened there?

**SPEAKER_2** (16:50)
Paralegals gone, right? Junior lawyers gone, I don't need them.

**Jacob Lauritzen** (16:55)
That's actually not what we're seeing. So yeah, I think it's, I don't know, would you say that we're seeing that in engineering?

**SPEAKER_2** (17:01)
Yeah. Junior engineers are kind of cooked. You kind of have to come out of, drop out of university fully baked or else you're not going to make it.
I feel like I'm being a bit dramatic for a comedic purpose. But like, yeah, I know a lot of lawyers, they started as paralegal, they go to law school, all these things, right? And now they don't, they're not needed. They're seriously just not needed.

**Jacob Lauritzen** (17:26)
Yeah. Yeah.

**SPEAKER_2** (17:28)
Yeah.

**Jacob Lauritzen** (17:28)
It's interesting what happens to the partnership, like the pyramid. I think generally a lot of lawyers, you still need the next generation. And at least for engineering, the way I think about it is you have a good engineer today, they're worth a lot more even than they were two years ago because they can produce so much more stuff. Like if they're good, and I think it's the same thing in legal, where they can actually do a lot of really good work if they're good. So I think it's more that like really good lawyers or junior lawyers are worth a lot more.

**SPEAKER_2** (17:55)
Yeah, it's always been the case, right?

**Jacob Lauritzen** (17:57)
Yeah, it's even more so. Yeah, it's polarizing even more so.

**SPEAKER_3** (18:00)
I'm actually curious about that. So the whole law business is basically charging per hour. So if each project now can be done a lot faster, is it going to be way cheaper?

**Jacob Lauritzen** (18:14)
This was actually a fun story.
I was reading Max's YC application and helping him get into YC, get Leia as it was called back then in YC. And this was my one thing.

**SPEAKER_2** (18:24)
And curious, Leia is a Danish thing for something?

**Jacob Lauritzen** (18:26)
No, a Swedish. No, also, it means nothing. There's this really funny story, and I think it was a Spanish newspaper that wrote about us in the early days, Leia. And then they explained that the abbreviation was Legally Efficient Yoda Assistant.
Why Yoda? Yeah, I don't know.

**SPEAKER_2** (18:46)
See, hallucinations are not just from LLAs.

**Jacob Lauritzen** (18:48)
No, I think journalists hallucinate. But no, it doesn't mean anything.

**SPEAKER_2** (18:53)
So he wrote the application?

**Jacob Lauritzen** (18:55)
Yeah, and my feedback to him was, people have tried this a million times. Legal tech has never been a thing, because there's no incentive for Louris to why would they be more efficient? They earn less money, it doesn't make any sense. But I think the reason that Louris do want to adopt this is that they understand the gravity of the situation. They know that the business model and everything is under pressure, and they need to change, because the competitive pressure is so high.
The billing model itself, I think, is also going to change. We've already seen that, particularly in the US, that a bunch of stuff is actually being priced on a project fee and not on an hour's fee, particularly lower end stuff on the spectrum, whatever it is, small reviews and whatever. Some of it, honestly, is being done for free, and some of it is just being priced on a flat rate.

**SPEAKER_3** (19:39)
So where is the money being made, then? In the strategic work. Yeah, I feel like a lot of what you guys talk about is M&A specifically, like that's where all the money is made.

**Jacob Lauritzen** (19:47)
That's just a very easy example.
Litigation is also. The big work still is there, and it's very valuable. And so those spend, lawyers will spend more of their time there. Client relationships also super important.

**SPEAKER_2** (19:59)
Like a CRM?

**Jacob Lauritzen** (20:00)
No, just like spending more time with the client. Like a lot of law firms will, or historically have basically done stuff for free just to have their relationship with the client. And so now they can do that, but they don't have to lose a lot of money on doing it.

**SPEAKER_2** (20:12)
I thought I just had to pay the lawyer money just to be my friend.

**Jacob Lauritzen** (20:16)
Isn't that the retainer thing? Yeah, that's...

**SPEAKER_2** (20:19)
You told me I can do it for free?

**Jacob Lauritzen** (20:20)
Yeah, you just have to find the right lawyers.

**SPEAKER_2** (20:25)
Okay, cool.

**Jacob Lauritzen** (20:26)
Or Latent Space has to grow much bigger, I don't know.

**SPEAKER_2** (20:27)
Yeah, we're trying.
Okay, so you're saying obviously the strategic work and all these high-value add is still there, but our legal fees are not going down. But you also said paralegals are not affected, or they're just shifting. And this is something that we also did worry about with Cognition.
People worry about the phrasing of like, we will replace your junior engineer, because nobody likes that kind of statement. But in actual fact, yes, some part of it does happen. Other junior engineers embrace it and they become more productive, exactly like you just said. So I guess, is there a new term for this role or this job that is having traction with your customers?

**Jacob Lauritzen** (21:10)
You mean the super AI-pill junior legal? Nothing, I've found yet. Maybe we should coin one.

**SPEAKER_3** (21:15)
Isn't it legal engineer?

**Jacob Lauritzen** (21:17)
That's our, and also now an industry thing.

**SPEAKER_3** (21:20)
Yeah.

**SPEAKER_2** (21:21)
CSJDs.

**Jacob Lauritzen** (21:22)
Exactly. Yeah. And maybe that's those other people that are best positioned to do this kind of stuff.

**SPEAKER_2** (21:28)
I think that the derogatory term meat proxy, where you just sit in front of the machine and type in something that someone else tells you to type, and then you repeat what the machine tells you to say. But I do think a very good meat proxy is just like, well, you know agents very well, and you know Legora very well, and you know how to like, this is my toolkit, and you know, every industry has a toolkit, and I can use my tools to do the thing that you need me to do.

**Jacob Lauritzen** (21:52)
But I guess then you're not really a proxy, right? You're actually just doing meaningful work.

**SPEAKER_2** (21:57)
Yeah, it's just like I no longer like, you know, I'll talk about tabular review because that's the thing that happens a lot. I have hundreds, thousands, millions, thousands.

**Jacob Lauritzen** (22:06)
We do up to a million cells, I think.

**SPEAKER_2** (22:08)
In a single, that's impressive.
We should talk about the table and the windowing. Yeah, I'm working on a big case, I have a million documents, I type it in. Usually, I'll throw a pair of paralegals, lock them in a room. And they'll sit there until 4 a.m. That doesn't need to happen, right? Because now they can extract it and you can go and re-prompt everything. So yeah, I think now I don't need a paralegal for that, but a good super AI-pilled paralegal would do something else.

**Jacob Lauritzen** (22:36)
Yes, exactly.

**SPEAKER_3** (22:37)
Whatever it is.

**Jacob Lauritzen** (22:37)
They can do more stuff, or spend more time on the things that they didn't have time for before. Or actually sleep, who knows?

**SPEAKER_3** (22:44)
I have a question. So you guys bought a company, Cura.

**Jacob Lauritzen** (22:48)
Is that how you say it?

**SPEAKER_3** (22:49)
You guys used your own product to do the M&A?

**Jacob Lauritzen** (22:51)
Yes, we do that all the time. So how did that work? Can you talk a little bit about that? Yeah, that works great. We're doing that a lot. Our legal team is, I mean, Integ has been built with our legal team. Because right now we have a Slack workflow where everyone's closed their stuff in, and they're like, this is annoying, right? And it's efficient, so it's like, great, we should do Legora for that.

**SPEAKER_3** (23:08)
Yeah. Can you talk a little bit about that? Like, you know, what that process looks like?

**Jacob Lauritzen** (23:11)
Yeah, absolutely. So it's, we do a lot of the due diligence ourselves because we can do it with Tabular View and other tools. We do still have Council coming in to like assess certain risks or like, you know, there's payroll. And so Zucura was simple because I was all in Sweden, but, you know, we've done one in Canada and one in Australia. And so there's like payroll in Australia. Okay, do we want someone to look at this like a bit more strategically? So there we will still use Louris for the strategic part where they can actually be sparring partners and help us a lot on like how to figure out how to structure this the right way. But a lot of the more menial stuff, we could actually just do ourselves. So like a lot of the early things we would find, and we have had cases where we found something that's been like a red flag and then we've pulled the brakes.

**SPEAKER_3** (23:55)
Can you talk a little bit about any of these?

**Jacob Lauritzen** (23:56)
No, I don't think so.

**SPEAKER_3** (23:58)
All right. Early on, you said your early customers were Swedish, like Swedish law firms. Have you seen a difference between working with like Swedish law versus like American law firms, that sort of thing?
And you guys are mostly working with like big, big law firms, right?

**Jacob Lauritzen** (24:14)
Well, we're also smaller law firms also. We definitely started really, really big law firms, but 50 lawyers also and get a lot of value.

**SPEAKER_3** (24:23)
Yeah. So have you seen differences between working with like the Swedish ones versus American ones, maybe like even, I don't know, Asian ones? Yeah.

**Jacob Lauritzen** (24:30)
I think the European ones have been a bit slower to move. The American ones are very forward and move really quickly. I think it's also very high on their agenda of the American companies, more so than the European ones, I think. It's like a strategic, super important thing we need to just do a lot here. The American companies generally both corporates and law firms also have a much higher appetite to custom build stuff. That's like a thing that they all want to do.
Like, hey, we want to build this huge thing with you guys and structure it in whatever way, where Europeans are much more like, we'll just take the off the shelf and figure it out.

**SPEAKER_3** (25:04)
What's an example of something they would want to build themselves?

**Jacob Lauritzen** (25:06)
Integration since they're all like, some of these customers built their own CRM and their own document management system and their own all sorts of stuff, and they want to build that, and then they want to build triggers that you do a review in Salesforce and goes to this one person for whatever reason and they do something, and then it goes into Legora and then it goes back in, and that's the simple end, and there are some that are extremely ambitious, where it's like a whole new product that they want to build with us, and we can't really do that. But that's definitely a thing where American companies really want to build their own more than European ones do.

**SPEAKER_3** (25:39)
And the European ones are like, hey, they give you product suggestions or?

**Jacob Lauritzen** (25:43)
Yeah, for sure. I mean, we have great collaboration with all of them. So they'll say, hey, this sucks, this is great, we want more of this, and we'll just build a product that does that.

**SPEAKER_3** (25:52)
Okay, so they don't see an existential threat here in their business. Whereas the American ones do?

**Jacob Lauritzen** (25:58)
I don't know if that's the reason that they want to custom build versus not custom build. I think they both know that this is extremely important and key to their firm's success and their corporate success. So it's both extremely important. I think it's just a different way to achieve it.

**SPEAKER_3** (26:12)
Okay. Another question I think maybe you want to bring this up is product metrics. How do you know that we're actually doing something good here?

**Jacob Lauritzen** (26:22)
Yeah.

**SPEAKER_3** (26:22)
How do you think about that? I'm assuming that's also related to evals.

**Jacob Lauritzen** (26:25)
So we have the regular product metrics that we care a lot about. Are people spending a lot of time in our product?
Do they seem to get a lot of value out of it? Do they renew it? Do they come back a lot? We have really good numbers for an enterprise software of our Dow over Mao and our hours spent per month in the product are extremely high. And then we do some sort of, we do online evals also where it's like, try to figure out, generally, like did we solve the problem here? Just with a super cheap LLMS address, try to just have an online metric and then we can use that also when we do roll-ups of new things, we can just compare feature flag-wise. Okay, did it improve or did it catastrophically decline? Because one thing actually that might be interesting, that's difficult for our business is, we can't look at any traces basically. We can't look at any data because it's all super confidential. And that's extremely frustrating to work with because you basically don't know what people are doing.
So it's like, here's an agent and it can do so many amazing things and I have no idea what people are actually doing with it.

**SPEAKER_3** (27:20)
I would have assumed you guys signed some sort of agreement with the law firm and they're like, oh yeah, sure.

**Jacob Lauritzen** (27:24)
I wish, yeah, I wish. No, but the thing is a lot of the data that they have is not even theirs, it's their clients and it's super confidential, so we can't look at it. And so basically we have an e-valuS team that's trying to approximate what we think everyone is doing and build that into e-valuSets.
So that's just a super annoying kink of the business.

**SPEAKER_2** (27:41)
Can you do paraphrase? So for example, ChachiBT has a slash feedback thing that directly fully sets a full trajectory. But obviously that is not possible for you guys. But you can use LLM to paraphrase from this real thing, make a synthetic thing that is close enough, but change all the names, change all the details.
Yeah.

**Jacob Lauritzen** (28:04)
We can't read those. I mean, there's always a range, right?
If you paraphrase all the way down to three values and you pick one of them, then obviously that's fine. If you just remove the names, then that's maybe not fine. It's like we are generally pick the most safe way. So we restrict ourselves as most possible because we, there should be no risk at all.
But there are things where it's like, okay, we know that the failure modes are probably these 10 or 20, so we can classify it into one of those and that's a helpful signal. We can classify it into the types of tasks and the practice areas also, and then we have an idea. It's something that we're always trying to figure out how to do in a smart way.

**SPEAKER_3** (28:42)
Also, on the privacy front, I guess, I'm assuming even two years ago, it must have been insanely difficult to get the law firms to be okay with this, but how do they think about their data being sent over to Anthropiq? Yeah, it must be a huge thing.

**Jacob Lauritzen** (28:56)
All of our infrastructure is on Azure primarily for this reason, because when we started, law firms were like, AWS? No, no way.

**SPEAKER_2** (29:05)
Law firms don't trust AWS?

**Jacob Lauritzen** (29:07)
Yeah, it's different now. No, but they were like Amazon, Google. We can't trust them within our data. So basically, we had to host everything on Microsoft, because they already have 365

**SPEAKER_3** (29:16)
So they're okay with Microsoft?

**Jacob Lauritzen** (29:17)
Exactly, because they've already done whatever, security review, et cetera, for all of their documents and all of their word and whatever. So Microsoft is an approved vendor in their mind. And so we had to host everything on Azure. And that's changed over the past few years. So now people understand, okay, we need to get on Cloud, we need to do all this kind of stuff. There's also a lot more people talking about on-prem back then. That's also disappeared completely. People understand that you should just do it in the Cloud, and it's safe, and it's probably safer than what you're doing.
So that's changed a lot, but it was really painful.

**SPEAKER_2** (29:44)
And by the way, it's only been three years, so it's actually...

**Jacob Lauritzen** (29:47)
Yeah, it's a huge shift. It's great.

**SPEAKER_2** (29:50)
I mean, good for you guys, but yeah, I don't expect the... The legal firm, the legal industry has somehow ignored this for the last ten years.

**Jacob Lauritzen** (29:56)
Yeah. I think we needed the AI kicking the butt for everyone to understand that, and we need to change our ways a little bit.

**SPEAKER_2** (30:03)
Okay.

**SPEAKER_3** (30:04)
So also then on like open-source models now are getting really good. So yeah, how are you thinking about that with the...

**Jacob Lauritzen** (30:10)
Yeah. We're just thinking about, to your point, just bring our clients along on like the Pareto frontier. And like the map of all the models and what they're good at, and their latency, and their cost, and their governance, and their regional availability. How do we just optimize across all of that? So some open-waist models are great for some tasks, and then we'll use them there.
Some will post-train, and some will just use the frontier models.

**SPEAKER_2** (30:36)
Yeah. You called it model arbitrage. You have different favors, you did some research on this, where you were firmly anthropic at the start of the year.
GROK is improving a lot. Yeah. You want to give an example of a model that wasn't ranked highly overall, but you want to shout it out as surprisingly good? Yeah.

**Jacob Lauritzen** (30:55)
I think not overall good. Gemini, one of the early Geminis, yeah, extremely good for certain types of transcription and speaker attribution. So we used that for transcription.

**SPEAKER_2** (31:07)
Oh, so you have a granola.

**Jacob Lauritzen** (31:10)
We actually probably will build a meeting thing, but this is just a talk to speech, speech to text, text to speech, just like in any other app that has this. And we do actually also transcribe files. If you upload hearings or whatever, we'll then transcribe them for the mental text and so we can do all of our analysis on it.

**SPEAKER_2** (31:28)
No 11 labs.

**Jacob Lauritzen** (31:29)
No 11 labs for DPA reasons. Same thing is like the data processing agreement, I should say. So our data processing agreement has very few vendors on it, because we just need to keep it super tight on where any data goes.

**SPEAKER_2** (31:43)
I think that is one of the benefits of a Gemini and OpenAI where you come to us, we have most of the things that you need, and that is actually very valuable. Even if it doesn't have to be state of the art, if it's mostly good enough for all tasks, then who cares?

**Jacob Lauritzen** (32:01)
I should actually shout out also Microsoft's transcription model.

**SPEAKER_2** (32:05)
My transcribed?

**Jacob Lauritzen** (32:06)
Yeah.
It's great. It's better than the old Gemini.

**SPEAKER_2** (32:10)
Yeah, they did some good results. I don't even know. Usually, all of them are top two, top three, top four in terms of the arena scores, and that's good enough.

**SPEAKER_3** (32:20)
Yeah, exactly.

**Jacob Lauritzen** (32:21)
You have all the governance and it's super scalable, and it's like, that's probably good enough.

**SPEAKER_3** (32:24)
Yeah, I was going to say, at this point, are pretty much the speech-to-text models good enough to where you're like, one word here, there, if it's off, that's fine.

**Jacob Lauritzen** (32:32)
No. No. For sure. I've done this a lot. Particularly in legal, there's some, we had this thing where I forget if it's in Australia where there's a certain name for a person in court and they would consistently transcribe it as condom.
So there's certain things that you don't want there.

**SPEAKER_2** (32:52)
Yeah, but so usually you run an LLM layer on top of it, and then you extract some keywords, and then you run the transcription model again with the keywords. Like this is kind of my workflow so far.
But yeah, if you've just done this on any large scale, you will pick up tons and tons of transcription errors on any domain that is not like average day-to-day conversation.

**Jacob Lauritzen** (33:12)
Yeah. Absolutely. If there's any sort of jargon in there, it's going to be tough.

**SPEAKER_2** (33:17)
Yeah. I think Whisper and 11 Labs still transcribe cloud code as cloud code.

**Jacob Lauritzen** (33:25)
And it's very, very common.

**SPEAKER_2** (33:29)
So that's how you know there's a lot more to improve.

**Jacob Lauritzen** (33:31)
Yeah, absolutely.

**SPEAKER_2** (33:33)
I do want to cover a little bit on the agent product side. So we've covered a few of the top-level stuff. We've already name-dropped Tabular Review. We've name-dropped Intake. And you've got some other stuff that we haven't even touched on yet. But I just want to cover the big two, let's call it that.
Is that fair to say the big two?

**Jacob Lauritzen** (33:52)
Agent and Tabular Review.
And projects. Yeah, and our Word add-in is also something. Because a lot of people work inside of Word. And so our Word add-in is a huge, an outlook add-in also.

**SPEAKER_2** (34:03)
Yeah, so I just want to cover the big ones that everyone must know.
So Tabular Review is basically like fan out of like a lot across each document. You can ask the same question across all documents. You select it on the table and then work back and forth. A million is impressive. What's any other like engineering considerations or performance things? Like what's hard about this?

**SPEAKER_3** (34:24)
Before we do that, can you just like walk through like, what is the user experience for a lawyer? And then like actually using Tabular Review.

**Jacob Lauritzen** (34:31)
Yeah, yeah.

**SPEAKER_3** (34:32)
So like what are they doing like with Tabular Review? And then we can go into that.

**Jacob Lauritzen** (34:35)
Sure.

**SPEAKER_3** (34:36)
Yeah.

**Jacob Lauritzen** (34:36)
So they, it's typically, I mean, a good example is just a due diligence, right? Where it's like, we need to review all employment contracts, all the supply contracts, all of whatever. And so employment contracts, you put 10,000 employment contracts in there. And then you...

**SPEAKER_3** (34:49)
Like each cell is one employment contract?

**Jacob Lauritzen** (34:51)
Each row is one employment contract. And then for cells, you ask questions basically. So like the first question, the first, sorry, per column. So the first column might be, what's the termination period?
And then it's going to fill out for everyone. It's 30 days or whatever it is. And the next question is like, is there an IPE assignment clause or whatever? Next one is like, how much do we have to pay them if we fire them? Or whatever it is, like how much are they getting paid? And then it's going to fill out the entire thing. You can also just ask the agent to do this. Like if you just drop 10,000 files into the agent and say like, do a due diligence on this, it will spin up a tabular review and run all of them and wait for it to be done. And then analyze the results and it can then highlight like red flags. Okay, the CEO is getting paid an outrageous amount or there's like this weird bonus structure. Okay, then obviously we need to look at that. And then the agent from that can draft a memo to send to the client or it can just do the review and then have a lawyer or the user just be like, okay, let's look at this here, the red flags. There's also collaborative so that you can comment on it for other people to look at, et cetera.

**SPEAKER_3** (35:51)
And why do you choose that like spreadsheet format?

**Jacob Lauritzen** (35:54)
Yeah, it's just a lot better to, it's super easy to work in.
It's really easy to get an overview super quickly of what's going on and to review it. So all of the stuff that we produce also has citations back to source documents and so you can basically review it super easily. If you want to just make sure that everything's right, you can also highlight cells, these are reviewed or whatever. These are the ones that are flagged and you can comment and collaborate. That's much easier than any other form factor that we've tried.

**SPEAKER_2** (36:20)
Yeah. I will say that the spreadsheet form factor has a lot of pull in some areas, but somehow hasn't really spread.
I find it very weird. Like Clay is another one on the GTM side that is very known for the spreadsheets. You guys, I don't really know if anyone else does a large spreadsheet AI thing.

**Jacob Lauritzen** (36:41)
No.

**SPEAKER_2** (36:42)
There was like V7 that tried to launch, there's like Sheets, even in Finance domain, I don't really have a top name that does spreadsheets. I agree.

**Jacob Lauritzen** (36:53)
I think it's like a great, if you have fan out and you do the exact same thing and you're extracting stuff, it's such a great form factor to understand what's going on.

**SPEAKER_2** (37:01)
Do you find like you must export to Excel or like people are happy to live in your spreadsheet?

**Jacob Lauritzen** (37:05)
People are happy to live there.

**SPEAKER_2** (37:07)
Do you use AG Grid or your own AG Grid? That seems to be like the leading one. I mean, they've done this for like, I don't know, 15 years.

**Jacob Lauritzen** (37:13)
Yeah, they know how to.

**SPEAKER_3** (37:15)
Yeah.

**SPEAKER_2** (37:16)
I mean, I'm happy on that spreadsheet angle. I mean, I think the only other interesting thing for me engineering wise is the fan-outs.
Engineers maybe are well-equipped to understand the trade-offs of like, well, okay, before you use fan-isting out on a million documents, maybe test it on like two.

**Jacob Lauritzen** (37:33)
Yeah. Does that work before you go nuts?

**SPEAKER_2** (37:35)
Do they do that? Yeah, they will.

**Jacob Lauritzen** (37:36)
So our type of the view actually will run the first 10 rows.

**SPEAKER_2** (37:39)
Yeah, just check, right?

**Jacob Lauritzen** (37:40)
Yeah. Does this make sense? Did it show us what we thought it was going to show us? Yeah, that's really good. But also for people, when people built this, it's just really good for them to iterate quickly on the first 10 rows so they're getting the results that they want and then they can go ahead.

**SPEAKER_2** (37:53)
Yeah. I am happy to move on to the next thing, intake, which is your Slackbot.
Everyone has a Slackbot. What's different about yours?

**Jacob Lauritzen** (38:00)
So ours is just legal specific. And what happens with ours is it's not actually, it might also, we will probably also build one that's just an interface to the agent, but it's actually specifically to basically kick off an agent that then adds a task to our lists. So we have this lists thing, which is like linear first, that's the closest equivalent. And so it will add it to a specific intake lists. And then lawyers and agents can go into Legora and just be like, okay, these are the things that people are sending to us as our law firm or as our legal team in a big corporate. We can kick off agents for them, we can collaborate on them, and then we can just like mark them as done and then it gets sent back in Slack.
So it's more of a, it's not just like kicking off an agent, it's more of a like, I don't know, storefront thing where it's like, here's the ticket, I want this thing reviewed. Okay, now here it is, it's back, no one needs to change anything, and the legal team just sits in Legora and like manages the agents and everything there.

**SPEAKER_2** (38:52)
I think the data structure for this kind of thing is really interesting, because it's like basically the inbox, right, for all these kinds of queries that can potentially translate into a thing, into something else, into something else. And like, I don't know, is it hard to integrate all these with all the other features, or do you just not worry about it?

**Jacob Lauritzen** (39:12)
No, it's not. I think we have some primitives that work really well. So lists is a great primitive, because it's essentially, it's like extremely flexible. It's also like a Notion database.

**SPEAKER_2** (39:21)
Yeah, a Notion database.

**Jacob Lauritzen** (39:22)
It's like a Notion database. And so you can basically configure it for whatever you want. And we, of course, invest a lot into making this super scalable and work really well. And you can have triggers on them, automations on them, and it's like a great glue to glue everything together, because then you can kick off an agent run based on a list if something happens. And then that comes back and populates a field or whatever, adds new documents or whatever it is. And so it's just like you might coordinate a bunch of coding agents with linear or some sort of task management tool. We can do it similarly with lists. And so agents can create lists, and lists can create agents, and agents can read lists. And so it's like the agent swarm comes alive.

**SPEAKER_2** (39:54)
Yeah. Do people get excited or overwhelmed by that? I feel like this is basically end user programming.
You can let people set up crazy automations. Some people get super obsessed by it, and they become like, it'd be cool to have a legora influencer.

**Jacob Lauritzen** (40:09)
Yeah, like Clay has influencers.

**SPEAKER_2** (40:12)
Is that worth it? Too overcomplicated?

**Jacob Lauritzen** (40:14)
We need the flexibility, even if we don't actually expose it to the end user. Let's say this was just all internal, then it's a really fast way for us to utilize people like our legal engineers to basically build a lot of products extremely fast. So you can build custom fund management dashboards. You can basically build that on list with your own generative UI, and then you basically have a new product that some people are going to love, and we can have a marketplace of just a bunch of specialized products that we can scale super quickly because all of the legal engineers can just build new ones. If they're out with a client, oh, you want your own? Easy. We'll just fix one for you. So it's like a lovable inside Legora a little bit. And if we don't want to expose it, that's also how we build our own custom features. So we made another acquisition in the UK called Wexler, and they're doing fact intelligence, which is for litigation mostly, which is like you upload a million documents for a lawsuit or whatever. And then we extract facts from those with named entities and dates and whatever. And then when you have all the facts, you can basically hold them up against each other and see which ones are corroborated and which ones are political disagreement.
And that's extremely powerful, because then you can also transcribe a court hearing and be like, oh, he said this thing, but actually the e-mail over here says that he was not there.
And if you see it live, it's like so fucking cool. And that we can also build on this primitive. And so we can build a lot of really cool things on this one primitive, basically. That's how we think about it. Like we have to be, as we scale the company, we just have to solve so many things. And so I think a lot about how do we build a core primitive that we can scale to many different end products and create very customizable experiences.

**SPEAKER_2** (41:52)
Okay, so what core primitives do you have? Let's just restate for people.

**Jacob Lauritzen** (41:56)
Lists is a core one.

**SPEAKER_2** (41:58)
Yeah, super configurable one.

**Jacob Lauritzen** (41:59)
Yeah, projects, basically containers of files, file systems. The agent, of course, you can kick that off and run that in very different configurations.

**SPEAKER_3** (42:07)
Do you have a name for the agent, by the way?

**Jacob Lauritzen** (42:09)
No, we don't.
No, you mean like we called it like Leia or like we gave it a name? No.
Yeah, Leia would be cool.
People used to talk about Leia as like a named entity.
But yeah, we stopped that. We might be bringing it back. It might be confusing. So Lists, Agent, Tabular Review, which we're considering, is that actually an instantiation? You can take this as far down as you want, but those are probably the big ones.

**SPEAKER_3** (42:37)
Yeah, so I actually wanted to talk a little bit about FTEs, because this sounds kind of like that. And I think Max has talked about that a little bit. That like, okay, when you onboard a new big customer, you want to get them value like ASAP so that they stay on Legora. Yeah, how has that evolved? When did you guys start that Forward Deployed team?

**Jacob Lauritzen** (42:56)
So we hired our first Forward Deployed engineer. That was our first time in New York, also YC founder, nine months ago maybe. I'm not actually sure.

**SPEAKER_3** (43:04)
Are they considered legal engineers or no?

**Jacob Lauritzen** (43:07)
No.
True engineers. But it is something that I think about, is how do we exactly enable that at scale? And I think a really core thing is how can we empower our legal engineers, how can we empower our power users and our legal engineers to customize the product in a powerful way? And then, of course, we will still have Forward Deployed engineers help out, do all the custom integrations and the scoping and figuring out what's possible and feed all of that back into core product development. So that's kind of how I think about it. Almost the first line, second line defense, where it's like legal engineers should be able to customize a lot of stuff and build a great experience. And then where they can't, or we need to make core product changes or custom integrations or whatever, we have Forward Deployed engineers who also then cycle in a little bit behind.
Sometimes they'll just work on the product and sometimes they'll work with clients.

**SPEAKER_3** (43:52)
Can you walk through an example? Okay, so you just got this new client. What's step number one? Are you guys like, okay, hey, we have a Forward Deployed engineer for you guys.
They're going to go build some kind of product for you. How does that work?

**Jacob Lauritzen** (44:05)
So it's very different client to client, right? But if it's a big client and they're super engaged and they have all these streams of things that they would want to do, or they already have, typically they have already tried to build something and it's failed. And they're like, this is a problem that we'd like to solve. Then we'll basically staff them with legal engineers and a Forward Deployed engineer potentially, depending on what their thing is. And then we'll just be like, hey, these guys will come, they'll make you successful. They will sit with all your lawyers and teach them how to use it. And figure out all the workflows that you have right now and build them into Legora. And some of that will just be a legal engineer, and some of that will require a Forward Deployed engineer.

**SPEAKER_3** (44:39)
What is that separation, I guess, if you could talk about that a little bit?

**Jacob Lauritzen** (44:43)
Legal engineers configure the product as a power user would.
They don't write code.
And a Forward Deployed engineer writes code into production, basically. I guess that's the-

**SPEAKER_3** (44:53)
What kind of background did the Forward Deployed engineers normally have?

**SPEAKER_2** (44:56)
He said YG Founders.

**Jacob Lauritzen** (44:57)
Yeah. Founders, regular engineers.

**SPEAKER_2** (45:01)
D was the guy.

**Jacob Lauritzen** (45:01)
Yeah, exactly. D was our first.

**SPEAKER_2** (45:03)
Two YC companies and worked on Search and Meta.

**Jacob Lauritzen** (45:05)
Yeah. She's awesome.

**SPEAKER_3** (45:06)
Yeah.

**Jacob Lauritzen** (45:08)
Okay.

**SPEAKER_2** (45:08)
That's a high bar.

**SPEAKER_3** (45:09)
She's great.

**SPEAKER_2** (45:09)
Yeah.

**Jacob Lauritzen** (45:11)
First boost on the ground in the US.

**SPEAKER_3** (45:14)
What are some examples of, I don't know, workflows or things that these people are building for the clients? Do you guys have like, oh, these are like, you know, there's a couple of use cases that like all the law firms are like, you know, this is the first thing that our FDs are going to do when they go in.

**Jacob Lauritzen** (45:28)
It's very different.
Some core workflows everyone have and we can just build in Legora and that could be anything from like, this is how we handle these types of NDAs or whatever. And then it's just like you activate it and it's more like skill building really for at least. And most of the FDs that's more like, there's something that we can't do yet. Like we need some more flexibility in some of the primitives or whatever it might be, or we just have this really complex system that we need to integrate into. And then they'll go out there and they'll build the integration against our APIs and maybe expand our APIs or whatever to make that work.

**SPEAKER_3** (45:59)
And how does the like legal structure work there? Because you said you guys yourselves can't even work on deals.

**Jacob Lauritzen** (46:06)
Yes. Yeah.

**SPEAKER_3** (46:07)
So like how do they work on client projects?

**Jacob Lauritzen** (46:09)
You mean the law firms, how do they work on client projects?

**SPEAKER_3** (46:12)
How do your FDs work on client projects?

**Jacob Lauritzen** (46:14)
So they don't touch the data still. So they'll just build the system.
But they will also be on-boarded like an employee sometimes. So like they might get a laptop and everything. Like to the law firm?

**SPEAKER_2** (46:24)
Yeah. If they need to.

**SPEAKER_3** (46:25)
Interesting.

**Jacob Lauritzen** (46:26)
That doesn't happen very often because like usually they just build an integration and like kind of works. But they can if they need to.

**SPEAKER_3** (46:31)
And you only on-board FDs into a customer, I'm assuming, if they're a certain size. Yeah.

**Jacob Lauritzen** (46:36)
It needs to make sense. Because our FDs can also work on core product, right? So it's like a constant prioritization thing.

**SPEAKER_2** (46:43)
Is there a rule, like, I guess, does every, like, you know, so Palantir famously had like, you know, four days you spend on-site, one day you come back and contribute back to the products, anything like that?

**Jacob Lauritzen** (46:53)
No. I mean, to be fully honest with you guys, it's still, it's still, you know, still early days in a lot of this.

**SPEAKER_3** (47:00)
And where do you see it headed? Maybe over the next year?

**Jacob Lauritzen** (47:03)
I do think that it's going to be more, maybe not exactly like Palantir, but like, I think we will have a larger, in constant circulation group of FDs that will maybe sit with a client for like two months or whatever to build out this one thing, and then they go to the next one, et cetera, et cetera. Yeah, but I do imagine us rolling in with legal engineers and forward deployed engineers to like work on specific projects.

**SPEAKER_2** (47:24)
Yeah, the API business is actually interesting, like you said, because, you know, that's another rule that you can have, where you are CTO, maintainer of the Legora platform, right? We will offer everything that we have in the Legora web app as an API, and then you guys can use whatever.
Is that a promise they make or...?

**Jacob Lauritzen** (47:43)
That's not something we are promising now. We do have APIs that you can build against, but not the entire surface of the product.

**SPEAKER_2** (47:49)
That's the curious thing, like, is that the strategy?
And obviously, you know, some people will love it, because I don't have to learn a new tool, I can just use the existing tool I have, right? And then I just, like, install Legora, for example, with the Word document stuff. Other than that, you know, I do think like, then you have to maintain it.

**Jacob Lauritzen** (48:07)
Exactly. That's been my thing. That's why we've tried not to do it.
We haven't had APIs. I mean, we started our APIs like six months ago or something. We fought it for a very long time, mostly because, yeah, I just don't want to, we move so quickly in the product that I don't want to be like slowed down by having to maintain old API versions for like a data model that we've changed. I mean, now we're bigger and things are different, so now it's a cost that we can take on. But like when we're 20 engineers, it's just like, we move so quickly that we can't do this.

**SPEAKER_2** (48:35)
I have toyed with this, right? Like it's just generally good for all companies to have a platform team and a product team, because the product team, you have one, but then you can easily spin up a second one as long as the platform is not super tied to the product.

**Jacob Lauritzen** (48:47)
Yeah.

**SPEAKER_2** (48:47)
Yeah. You know, like a very simple one is Web App, Mobile App, or like Web App, Mobile App, MCP, and then like, you know, whatever, like other integrations.
Then your FDEs just are one more client to the overall platform anyway.

**Jacob Lauritzen** (49:01)
Yeah. And I think even the agent, you can think about it this way. There's like a harnessed team that runs the agent, and then you can even build a product around it with like scales and automations and whatever else.

**SPEAKER_2** (49:11)
Yeah. This is like very famously the Amazon Web Services mandate. Like Bezos was like, guys, no more backdoor access. You only offer other teams your APIs, the same APIs you offer customers. If you don't have it, you build it.

**Jacob Lauritzen** (49:24)
Yeah.

**SPEAKER_2** (49:25)
And then the customers will also get it.

**Jacob Lauritzen** (49:26)
Yeah. I think that's also changing a little bit.
A lot of APIs now, like one thing that we're toying with is like, can the agent be the API? I know it sounds weird, but like for some of this stuff, what they actually want to do is they want to trigger certain things to happen. For some part of this, you could just be, I'm not saying that we're doing this, but it's like a thing that I'm toying with in my head is, could that just be like, okay, you trigger the agent and ask it to do this thing? Like obviously, it's way less efficient than if you just had like an API that you always hit and it's like, you know. But it's something that I'm toying with is like how much of our product can just be the agent versus all the other stuff.

**SPEAKER_2** (49:58)
Well, you know, unbounded execution and costs and latency. Is that the only hold back?

**Jacob Lauritzen** (50:04)
Yeah, and I think deterministic, like maybe 100 out of or in 2 out of 100 times, it's going to do something whack that we didn't want it to do.

**SPEAKER_2** (50:12)
We're going to go into like harness and model fine-tuning in a bit. But I think there's a product question about restraint, about what you don't do, because you could do all that. And obviously, there's a prioritization issue.
Are you more on the point of, let's say no to most things, and then only do a short number of stuff, or no, actually, we want to do more things, and we just need to hire like 100 people?

**Jacob Lauritzen** (50:36)
I was very strongly the first thing for a very long time. Let's just say no to everything, like keep the endg team. I think I've said this before, but one of our presentations that I did, after I've been at Legora for half a year, I pulled up this slide of the 300 Spartans for the movie, and I was like, we're just going to be 20 engineers for the rest of the company's history, and we're going to beat everyone who's much bigger. We're 100 engineers now, and it feels like we're way too small. I wanted to do that, but I think in the real world, we're in fierce competition, people want so much stuff.
I could be a Puritan and just be like, no, we have to stay 20 people, and we can only build whatever, but then we just lose, and people would go elsewhere. So we have to build more, and so I think my job is to figure out, how do I build a system where we can build a lot, but actually only where we can, the customer feels like we've built so much stuff, but we've actually only built a few things. That's how I think about my job right now.

**SPEAKER_2** (51:27)
Yeah, I mean, primitives is right, you know?

**Jacob Lauritzen** (51:29)
Yeah, exactly. I think that's really powerful.

**SPEAKER_3** (51:32)
Do testing your products, just seeing if there's any pull here, and then you're like, no, let's just focus on our main thing.

**Jacob Lauritzen** (51:39)
We haven't made, I mean, we've made certain strategic bets, but we've not tried anything that we don't have a lot of confidence in already, mostly because we just have a mountain of demand. It's like we want all of these things, and so it hasn't really made sense for us to try to be like, hey, maybe this thing could work, because there's so many people screaming for the other things, and so we mostly build those. And then sometimes we'll disagree with clients and we'll be like, actually, I think this thing over here will make a lot of sense strategically and then we'll try to build that anyway.

**SPEAKER_3** (52:07)
Like strategically for you?

**Jacob Lauritzen** (52:08)
Yeah, exactly. So what are those things? So one of those things was the agent actually. So no one was actually asking for, I want it to be, I want the assistant that I'm using to have more agency and do things without me asking it. Like no one, no one ever, but we're just like this is definitely why the industry is going. This is going to empower you to do so much cool stuff.
Collaboration was another one where we think the industry is going in a place where you can collaborate inside of where you're working, which is the Legora and not in emails and text messages. So yeah, there are a few of those.

**SPEAKER_3** (52:38)
And then once you say, okay, yeah, we want you guys to use agents, I'm assuming internally at the law firm, it's going to take a lot for them to actually learn how to do that. And so that's where you kind of like say, hey, FD is going there and teach them what they can do.

**Jacob Lauritzen** (52:52)
Yeah, legal engineers mostly. Oh, legal engineers. But they're like, some people call them forward deployed legal engineers if you want, but that's essentially what they are.
Then they go in and help them structure their workflows around the capabilities of the agent.

**SPEAKER_3** (53:05)
You guys said previously, I think Max said this, but that early on specifically you guys weren't fine tuning your own models. Is that still the case?

**Jacob Lauritzen** (53:14)
Yeah, so we haven't fine-tuned any models up until now. I think now in the past few months, open-weights models have become extremely capable, and so we will do it for certain tasks, where we think there's a huge delta between what a frontier model can do at the cost and latency, versus what we think a post-trained model can do. Legal research is a great example.
It's a fan-out retrieval problem, and you can make a really effective model to those queries super quickly and super cheaply at low latency.

**SPEAKER_3** (53:43)
So, specifically, you're post-training them to be better at searching?

**Jacob Lauritzen** (53:47)
Very specific bounded tasks. Yeah, exactly. We're not trying to train our own fable to be the main agent. I don't think that's like a...
We won't win that versus Anthropic, most likely.

**SPEAKER_2** (54:00)
There's still a lot of search and retrieval research or RAG research to do that is maybe less glamorous. It's not actually even model training sometimes. It's just architecture and pipelines. You did a case study with TurboPuffer, but there's also...
Do you do late interaction of...

**Jacob Lauritzen** (54:19)
Yes, absolutely.

**SPEAKER_2** (54:20)
You do that.

**Jacob Lauritzen** (54:21)
We actually don't do that, but you're completely right that this is... There's one guy on the team, Sun, who just really cares about search, and he basically comes to me all the time. He's like, we should do these things. There's these new embedding models, and we can do this late interaction. He actually talked to TurboPuffer teams to get them to build multi-vector so that we could do these types of things.
But no, there's loads of low-hanging fruit generally, even before models. And even in the harness, honestly, if you just want to create a better output for our clients, there's so much stuff that we can do that has immediate impact before training models.

**SPEAKER_3** (54:51)
What makes a good harness for the law industry, I guess? You guys are making, I'm assuming, your own custom harness.

**SPEAKER_2** (54:57)
Yeah, of course.

**Jacob Lauritzen** (54:58)
The way that we edit files is important. The way that we do an analysis is important. The way you do legal research is all baked into it. So if you might have a problem that comes up or sees something, then it knows how to go and do the legal research to figure out what the answer is, what the precedent is.
That's all very important. And then, of course, there's all the governance stuff around it as well.

**SPEAKER_3** (55:17)
Yeah, it seems like the search is probably, like would you say, the most important tool that you guys are really customizing? Because if you can't pull in the right information.

**Jacob Lauritzen** (55:25)
Yeah, and then you're screwed.
I think it's search and analysis. Yeah, it's search, it's analysis, and it's drafting, probably. Because drafting word, drafting huge contracts is actually also not super trivial.

**SPEAKER_3** (55:39)
Like what about it is not trivial?

**Jacob Lauritzen** (55:40)
Because you have to, let's say you're drafting a huge contract from scratch, then you have to find precedents of like, how do we do this previously? Do we need this type of clause or not?

**SPEAKER_3** (55:49)
A specific law firm, how did they do it previously?

**Jacob Lauritzen** (55:51)
Yeah, so I am the law firm, and I'm about to draft a huge whatever. NDA is very simple, but there are contracts that are way more complex. And then you need to find the right precedent first. Because like, lawyers just don't sit and start typing stuff.
They figure out what clauses have we used in similar deals. And similar can mean a lot of different things. As I'm sure you know in search, it could be like, same industry, same type of company, same whatever. And so you need to identify the right precedent. You might have like multiple documents that you then try to figure out which part should I take from what document. And that's actually non-trivial. So it's essentially also a search problem.

**SPEAKER_2** (56:25)
Which model is best at drafting?

**Jacob Lauritzen** (56:28)
I'll say, I told you this yesterday, definitely Fable and Opus are extremely chatty.
I'm sure you guys have known this. They're very verbose.

**SPEAKER_2** (56:36)
So that's not good?

**Jacob Lauritzen** (56:37)
That's generally not good.

**SPEAKER_3** (56:38)
I noticed Astra is pretty good at writing.

**Jacob Lauritzen** (56:40)
Astra is pretty good at writing, much less more concise.

**SPEAKER_2** (56:44)
Are you running like a hundred different problems to be sure?

**Jacob Lauritzen** (56:49)
We can do certain things, but I think the chatty-ness verbosity is actually a little bit difficult for us to do. So this is, I think, let's see. But probably the next model from Anthropo is going to be much better at this. Astra is actually very concise.

**SPEAKER_2** (57:00)
Yeah, and I assume they all have a Slack channel with you, and you're telling them this, right?

**Jacob Lauritzen** (57:04)
Yeah, exactly. This is not news to them.

**SPEAKER_2** (57:05)
No, no, no.

**Jacob Lauritzen** (57:06)
They know this.

**SPEAKER_2** (57:07)
Then the other thing that I really care about is hallucination. Do they make stuff up?

**Jacob Lauritzen** (57:11)
So we have a citation system where we basically check what they're writing, has a link, so the user has a link they can click, and it highlights with a bounding box like in the PDF or whatever where this information was taken from. And we can sort of make sure that what it says always is citable somewhere, even multiple layers down. So like if the agent writes something based on a tabular view, it can cite the cell in the tabular view or the row in the tabular view. So you can actually click multiple layers down and sort of validate it all the way up.

**SPEAKER_3** (57:41)
Are you finding that lawyers are verifying that these citations are correct or not?

**Jacob Lauritzen** (57:47)
Initially, some of them work, but now it's the same thing.

**SPEAKER_2** (57:51)
People should collucinate links to Supreme Court. They don't care.

**Jacob Lauritzen** (57:54)
That happens.
I think it's like coding. You have engineers that just don't give a shit and just send agents, and you have people that sit and read every comma.

**SPEAKER_3** (58:03)
There's just so much that, how can one even do that?

**Jacob Lauritzen** (58:06)
Yeah, but I think they probably just like we know in code review what to look for, what is the system or whatever. I think they also know, okay, this is the thing. These are the red, this is the thing that's important. Let me just double-check these things, then these sound reasonable, so it's probably fine.

**SPEAKER_3** (58:18)
Okay. Interesting.

**Jacob Lauritzen** (58:20)
Just like if you receive something from a junior lawyer, it's the same thing you do, right? Just like, I should double-check this and this probably is fine.

**SPEAKER_2** (58:25)
Any other elements of, let's call it legal reasoning, what's the legal frontier that models are not good enough yet, that you want from the next generation of models?

**Jacob Lauritzen** (58:35)
Nothing I can think of specifically right now. I think long document reasoning is still difficult.

**SPEAKER_2** (58:41)
Long, like, million token contracts is okay?

**Jacob Lauritzen** (58:43)
Yeah, exactly. You have a huge contract. And like, you're making edits across it. It's a difficult thing to do for a model today.
And like, remember that you changed all these things up here and like, the definitions changed and the ordering changed and whatever else.

**SPEAKER_2** (58:56)
So the simplest would be one shot. You feed everything in and then one shot output. You don't do that. You break it up into chunks and then you orchestrate edits.

**Jacob Lauritzen** (59:03)
Yeah, exactly. And this is like one of those things that are funny, like, that are fun to be part of in this industry, right? So our word ad was like, we've done MapReduce and we've changed them. There was one big one and there was like one big one in multiple sizes. Like, we keep changing the scaffolding that we build around as models change.

**SPEAKER_2** (59:20)
Yes.
I would say I recently I do a lot of like news reporting, obviously, because of what I do. And I've recently shifted from MapReduce to throw everything into context. And it's better. Yeah, exactly.

**Jacob Lauritzen** (59:33)
But it's also it's different. I mean, we had this problem with search where it's like, you're searching for certain things in a huge contract and you can MapReduce it. But then it might, if you're summarizing any sort of thing, then it might lose some important nuance in between the chunks. Essentially, if you just summarize the individual parts up. And so, this has been a problem where it's like, we can do two types of search. We can also do the other one where it's like, you need to have reasoning in the different steps there in between. So, I'm trying to think of a really good example here. Yeah, there's some documents where they talk about something at length over like, let's say, two pages or whatever. And then each individual chunk is not necessarily relevant to the search term or what they're trying to figure out. But together, it's extremely relevant. And so, yeah, these are some of the problems where it's-

**SPEAKER_3** (1:00:15)
And it must be hard, like you said earlier, to actually make the models better at that, because you can't even look at the contracts, right?

**Jacob Lauritzen** (1:00:23)
The real contracts.

**SPEAKER_3** (1:00:24)
So do you guys ever ask them for like, hey, can you make example contracts that are similar to your real ones?

**Jacob Lauritzen** (1:00:29)
Yeah, so we have feedback and we can receive feedback from them. And if they're willing to engage, yeah, exactly. Or they're just like, hey, this is like super important to us and it's not working well. And then we're like, great, can you like anonymize the documents and like the problem and whatever? And if we can recreate it, then we can fix it.

**SPEAKER_3** (1:00:43)
Yeah.

**SPEAKER_2** (1:00:44)
I mean, so one version of this is you buy a law firm.

**Jacob Lauritzen** (1:00:47)
Yeah.

**SPEAKER_2** (1:00:48)
Which some people are considering.

**Jacob Lauritzen** (1:00:49)
Yes. But there's some stuff there on whether their data is actually their data or if it's the client's data.
So if the clients are all gone, then maybe it's fine. I actually don't know. Interesting. But it's a way to get a lot of data.

**SPEAKER_2** (1:01:05)
Yeah. People like Google is buying Spirit Airlines.

**Jacob Lauritzen** (1:01:08)
Exactly. Yeah. Same thing. Yeah, they bought the app for like $10 million, $7 million or whatever.

**SPEAKER_2** (1:01:14)
If you have a failed company, you still have your Slack, you can still have Slack. I think there's a YC company that buys your failed company.

**Jacob Lauritzen** (1:01:20)
Yes, there is.

**SPEAKER_2** (1:01:22)
Yeah. Because it's just like, I just want real people doing work.

**Jacob Lauritzen** (1:01:25)
Exactly.

**SPEAKER_2** (1:01:26)
And then pull stuff out.

**Jacob Lauritzen** (1:01:29)
Exactly. The problem with buying law firm data is, well, you get all the inputs, the real inputs, which is great.
The outputs are a little bit more difficult because you just get what their end result was and it's difficult to figure out if the way, you have to basically reverse engineer how they got there. So in our product, when we get real traces from real users, it's extremely high value. But if we just got this output and we don't know if it's good or bad or how it was created, it's a little bit difficult.

**SPEAKER_2** (1:01:53)
We're going to wrap up soon. The last thing I'll point people to is also, there's a lot of alpha left on embeddings. If you're a rag-heavy workload, you're just looking at MTB and you're taking top model, you're leaving a lot on the table. You should look at Voyage or some of the custom embeddings you've put into this.
So basically, don't take default embeddings. Even OpenAI embeddings, Japan AI embeddings, doesn't matter. Customize your embeddings. You will support that.

**Jacob Lauritzen** (1:02:18)
Yes, I think that's right.
The only thing is, you need to make sure that you're multi-language. So for us, we serve so many languages, so that's going to be more of a problem.

**SPEAKER_2** (1:02:26)
Europe is the king of this.
Mr. Ao, helpful there? No.

**SPEAKER_3** (1:02:34)
Until now, they just raised a ton of money, right? So maybe...

**SPEAKER_2** (1:02:37)
Yeah. They also raised a ton of money a year ago.

**Jacob Lauritzen** (1:02:41)
I think we need way more model companies out of Europe.

**SPEAKER_2** (1:02:44)
Yes.

**SPEAKER_3** (1:02:45)
I just wanted to ask you, what predictions do you have maybe over the next year for the wine industry?

**SPEAKER_2** (1:02:52)
We asked a little bit of that earlier. I'll modify it to your second question, which is, in two years, will lawyers do their work inside Legora? Will they use other tools like Cloud or your Tragedy and call Legora? Like the API.

**Jacob Lauritzen** (1:03:04)
Yeah. I think both. It really depends. I think if you're a big enterprise, you might have Cloud co-work and then you'll... I think it's similar to how I use linear through Cloud, but I still go to linear. I think enterprise will do that. I think law firms will just use Legora, because that's simpler and better.

**SPEAKER_3** (1:03:20)
Yeah. It kind of reminds me of open evidence for medicine.
You're basically that for a lot.

**Jacob Lauritzen** (1:03:25)
Yeah, exactly.

**SPEAKER_2** (1:03:26)
Encoding has gotten to a point where people... The labs will cut you off for competing with them, and this has happened twice.
Do you think that will happen to law?

**Jacob Lauritzen** (1:03:34)
No, I don't think so.

**SPEAKER_2** (1:03:35)
I think it's like, you know, they are releasing legal services.

**Jacob Lauritzen** (1:03:38)
Yeah, yeah, yeah, they are. I mean, we obviously talk to them a lot, but it's also like, hey, are you going to...

**SPEAKER_2** (1:03:44)
Your sales reps will say no, they don't make the call.

**Jacob Lauritzen** (1:03:47)
Exactly, that's not the... And they don't even know, like, often what's actually going on.
I don't think that's the case. They have so much stuff to capture in knowledge work, or in sort of enterprises knowledge work generally, that like legal has to be part of that, just like data analytics has to, and sales and marketing and finance. So like they have to do things that are good there, but they're never going to go as deep as we are. And I think if Claude takes small clients, small, you know, corporate clients, and they do some of their legal via Claude, that's great, that's fine. But if you're doing a $400 million M&A transaction, you're going to want Legora.

**SPEAKER_3** (1:04:22)
I had kind of an unrelated question, but I'm curious, are you guys going to law schools and kind of like getting them to like teach Legora in classes?

**Jacob Lauritzen** (1:04:32)
Like how does that work? Yeah, it's definitely a program that we are, I think we've started. I actually don't know exactly where we are, but we do want people in law school to learn to use Legora.

**SPEAKER_3** (1:04:42)
Are you seeing that like law schools are changing their curriculums a lot or not really?

**Jacob Lauritzen** (1:04:46)
I don't know. I wouldn't know actually.

**SPEAKER_3** (1:04:49)
Interesting.

**SPEAKER_2** (1:04:50)
I would actually do it a different way. You should do scholarships for law school for CS majors, for engineers. We will cover your-

**Jacob Lauritzen** (1:04:57)
After you've done CS, we'll put you in law school.

**SPEAKER_2** (1:05:00)
CS plus some software experience, we'll put you in law school. We'll cover it.

**SPEAKER_3** (1:05:04)
Or you do like the MA, like masters plus JD programs.

**SPEAKER_2** (1:05:09)
Yeah, we don't care what the masters.

**SPEAKER_3** (1:05:12)
Meaning like, because there's a lot of people who didn't do CS undergrad, so then they do like masters just to kind of like get that thought out.

**SPEAKER_2** (1:05:19)
Yeah.
I don't know. I don't see that as often. Yeah. People do JD, MBA. That's a thing. But JD, CS, I haven't seen it.

**SPEAKER_3** (1:05:27)
Happens. Yeah.

**SPEAKER_2** (1:05:29)
Yeah. Okay. Look, overall, super impressive progress. I mean, congrats on all your success. Like, are you still going to keep up the pace? Like, yeah, I think you're hiring in SF, New York.

**Jacob Lauritzen** (1:05:41)
We're hiring in, yeah, engineering. We're hiring in New York, Stockholm and London.

**SPEAKER_2** (1:05:46)
Yeah.

**Jacob Lauritzen** (1:05:47)
And all other roles we're hiring everywhere.

**SPEAKER_3** (1:05:50)
How many people do you have in New York right now?

**Jacob Lauritzen** (1:05:52)
A hundred. Okay.

**SPEAKER_3** (1:05:53)
And you guys are planning on how many in New York?

**Jacob Lauritzen** (1:05:56)
In New York?

**SPEAKER_3** (1:05:56)
Yeah.

**Jacob Lauritzen** (1:05:57)
For just like generally.

**SPEAKER_3** (1:05:58)
Let's just say, yeah, generally and generally.

**Jacob Lauritzen** (1:06:00)
A lot. As many as you can.

**SPEAKER_2** (1:06:02)
Yeah.

**Jacob Lauritzen** (1:06:03)
It's aggressive.

**SPEAKER_3** (1:06:05)
Yeah.

**SPEAKER_2** (1:06:05)
I mean, that's the home of corporate law, right? As far as America is concerned.

**Jacob Lauritzen** (1:06:10)
Yeah.

**SPEAKER_2** (1:06:11)
I mean, I'm looking forward to you buying a law firm. And it's super exciting. I think every industry, especially the top doctors, lawyers, coders, they all have to have two or three agent labs that just sort of dominate the space.

**Jacob Lauritzen** (1:06:28)
I agree.

**SPEAKER_2** (1:06:29)
So you guys have a great market. Yeah, I think so.

**Jacob Lauritzen** (1:06:31)
And I think it's only going to get much bigger as law changes and becomes more available to more people.

**SPEAKER_2** (1:06:37)
Yeah. Also, I think we're already super over, but the problems that you work on are very, like the frontier of knowledge work. Yes. Yeah. Okay.
Unless you're literally doing science, never you're supposed to do science. Other than that, most work is basically converges to legal. Yeah.

**Jacob Lauritzen** (1:07:01)
It's all legal in the end.

**SPEAKER_2** (1:07:02)
Yeah. Hiring, finance, everything. I just have to consult my lawyer.

**Jacob Lauritzen** (1:07:05)
So yeah, I know. Which is why I think it's a really exciting thing to work on because modern society runs in some way on legal. Yeah.

**SPEAKER_3** (1:07:13)
All right. That's it.

**SPEAKER_2** (1:07:13)
Thank you.

**SPEAKER_3** (1:07:14)
Thank you.

**Jacob Lauritzen** (1:07:14)
Thanks.
