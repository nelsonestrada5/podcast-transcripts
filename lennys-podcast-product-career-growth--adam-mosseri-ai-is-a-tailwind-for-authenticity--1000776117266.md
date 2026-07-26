---
podcast: Lenny's Podcast: Product | Career | Growth
episode: Adam Mosseri: AI is a tailwind for authenticity
transcript_id: 1000776117266
fetched_at: 2026-07-26T17:19:00-04:00
credits_charged: 1
---

**Adam Mosseri** (0:00)
No, I think taste matters a ton. In a world where it's easier to build things, it's more important to make sure that your time is spent figuring out what you should be building in the first place. The people who I think are gonna make the most of it are the ones who are clear-eyed about what AI is good at and what it's not good at, and also have an instinct or a nose for what it will be good at and not good at.

**Lenny Rachitsky** (0:23)
What's something that the Instagram algorithm knows about human behavior that people may not realize?

**Adam Mosseri** (0:30)
I think people assume that there's a much more detailed semantic understanding of everybody's interests and preferences in the algorithm than there is.

**Lenny Rachitsky** (0:38)
Is the rise of AI content a headwind or a tailwind for Instagram versus other platforms?

**Adam Mosseri** (0:44)
I think it's gonna be a tailwind, but I think it's gonna be a challenge. In a world where there's an abundance of synthetic content, I actually think people are gonna seek out creativity and authenticity and people. I don't think we should filter out AI content. I think we should let you know if content is AI content or not. That's hard, by the way.

**Lenny Rachitsky** (1:04)
Where do you think human brains will continue to be most valuable as AI continues to eat more and more of that product development life cycle?

**Adam Mosseri** (1:12)
That's a great question.

**Lenny Rachitsky** (1:13)
So...
Today, my guest is Adam Mosseri, head of Instagram. Over three billion people use Instagram monthly. That's one in every three people alive. It boggles the mind. Prior to Instagram, Adam designed and led the early Facebook newsfeed. He also ran the team that built the Facebook ranking algorithm. And eight years ago, he took over Instagram from its founders, Kevin Systrom and Mike Krieger. He's a designer turned product manager, turned leader of Instagram. Adam is also famous for being the face of all of the controversy and changes that come with evolving Instagram as a product, which we talk about. Before we get into it, don't forget to check out lennysproductpass.com for a free year of the most interesting and well-crafted AI products in the world, available exclusively to Lenny's newsletter subscribers. With that, I bring you Adam Mosseri.
Adam, thank you so much for being here. Welcome to the podcast.

**Adam Mosseri** (2:13)
Thank you for having me. Excited to be here.

**Lenny Rachitsky** (2:15)
You've been doing product for a long time. You get to see how a lot of teams operate across Meta within Instagram.
What is the canonical product team look like in 2026? What's most different today in how teams operate slash should operate versus say a couple of years ago?

**Adam Mosseri** (2:33)
It's changed a lot this year.
For the longest time at a big company like ours, the canonical team was something like two or three Android engineers, two or three iOS engineers, two or three server engineers, maybe a generalist, a PM, a designer, a data scientist, a researcher if you're lucky, and maybe that's about it. So on the order of a baker's dozen.
That is a function of, you want to have for anybody who's writing code, someone who can review their code and who's familiar with that code base, and having these different functions that are more specialized. I think it's very different at a startup. But this year, it's changing. We've adopted what we call pods, which are just mini teams, where it's, call it four to six engineers who are a bit more generalists.
One we call product staff, which is sort of a devolution of the PM, so a PM who can do some of what a designer does and some of what a data scientist does and some of what a research does, leveraging the latest tools that we have for them. And then whatever specialist they need. If they're doing something that requires a pricing strategy, you need a senior data scientist. If you're doing something that is really novel from an experience standpoint, you need a very senior product designer. So we try to build a team based on the needs of the work a bit, but then end up with a much smaller core, which is more on the order of six or seven usually. And that is a very big shift that's just happening to us this year. But they, just by virtue of having less people to coordinate, they can often move faster and make better decisions, a little bit less designed by committee. So we talk a lot about, you know, AI adjusting and improving productivity, and that's part of it. But I think another part of it is just the small teams, I think, often are just more effective.

**Lenny Rachitsky** (4:38)
This episode is brought to you by our season's presenting sponsor Work OS.
What do OpenAI, Anthropic, Cursor, Vercell, Replet, Sierra, Clay and hundreds of other winning companies all have in common? They are all powered by Work OS.
If you're building a product for the enterprise, you've felt the pain of integrating single sign-on, skim, RBAC, audit logs and other features required by large companies. Work OS turns those deal blockers into drop-in APIs with a modern developer platform built specifically for B2B SaaS. Literally every startup that I'm an investor in that starts to expand up market ends up working with Work OS. And that's because they are the best. Whether you are a seed stage startup trying to land your first enterprise customer or a unicorn expanding globally, Work OS is the fastest path to becoming enterprise ready and unblocking growth. It's essentially Stripe for enterprise features. Visit workos.com to get started or just hit up their Slack where they have actual engineers waiting to answer your questions. Work OS allows you to build faster with delightful APIs, comprehensive docs and a smooth developer experience. Go to workos.com to make your app enterprise ready today.
I love this. So on this team of six to seven, what's the makeup again? And which role are you finding you have less of if you're going from the kind of the, if you're going 50% size?

**Adam Mosseri** (5:59)
You just have less specialists, right? So you might not have any. There might be four engineers and a product staff, and there's no data scientist, there's no designer, there's no researcher, there's no content designer. The product staff is the generalist that sort of supports all of those things. I mean, what's clearly happening is all of the functions are starting to bleed into each other and the, and the whole industry is wrestling with what that means.
You know, a lot of what a data scientist does at a big company, for instance, is relatively mechanical. And so, you know, there's stuff that they do that is really more like, you know, art and science, and the stuff that's really more like just pulling data, data management. You know, so some of the tools that we're building internally to understand, for instance, a traditional data science question would be a waterfall. So if you wanted to look at it, people creating reels, you would look at all the steps and then how people fall off on each step and try to figure out whether there might be opportunities to improve things. That kind of basic waterfall analysis is like much easier now to use some of our internal tools to just pool automatically as opposed to having to have a data scientist do a bunch of bespoke work for that. So a product staff might be able to do that now and they couldn't do that a year ago.
So you just end up with this general, these people have more generalist shapes and then when you need it, when you really need it, you have a more senior ideally or just more creative specialist. So a phenomenal product designer or just a genius data scientist or researcher.

**Lenny Rachitsky** (7:32)
This is so interesting. It's exactly what I just heard. I had Fiona Fung, the head of engineering for Claude Code and Cowork on the podcast. She's Boris Cherny's manager and she described the people she hires now are, one, builders with great taste that can take an idea from end to end, and people with deep expertise in a very specific domain.

**Adam Mosseri** (7:53)
The tasting matters a lot. I really agree with that. Boris used to work at Instagram.

**Lenny Rachitsky** (7:58)
Oh, that's right.

**Adam Mosseri** (7:59)
Yeah, he was a senior. I see it Instagram for a while. I love seeing him. He's all over threads now. It's like he's sort of like the face of Claude Code.

**Lenny Rachitsky** (8:05)
He's killing it. He's a celebrity now.

**Adam Mosseri** (8:08)
He really is. He's his own little, yeah, for sure. In a world that is like on fire right now. No, I think taste matters a ton. So in a world where it's easier to build things, it's more important to make sure that your time is spent figuring out what you should be building in the first place.
Actually, so a lot of designers right now are very anxious about their roles. You know, I've got these other generalists doing design, you've got engineers doing design, product staff doing design. But I'm actually pretty long on design or designers because they tend to have taste. And I think that is something that is much more difficult to imagine being automated away. And so there's other challenges with design sometimes, but I'm pretty long right now on designers.

**Lenny Rachitsky** (8:59)
I've always felt that too, as it is so easy to build and all the work that AI produces is so like, you can tell this was Claude design. I know what you did here. This is Codex.

**Adam Mosseri** (9:10)
Well, they all have their vibe, right? Your vibe code, your apps, we call it vibe code, and you're like, oh, that's a Codex app or that's a Claude app.

**Lenny Rachitsky** (9:17)
Right. And that's replete, that's lovable. You can predict these things.
I've always thought that too, that design should be thriving. For some reason, it hasn't yet. If you look at jobs for designers, they're kind of flatlining. I feel like the missing piece is like the PME piece of deeply understanding the business and what will grow it, and what success will, you know, like all that stuff, the business side of it versus the taste side of it.

**Adam Mosseri** (9:40)
Yeah. I think you're going to see, like, you know, we have a senior designer at Instagram called Nate, who just transferred into product stuff. So I think some of what you'll see is, you know, it will be harder to talk about design roles and who's a good designer because they're not going to just stay in traditional design roles. You know, if you're an amazing designer, you might, you probably have strong opinions outside of just the interaction in visual design. You probably have strong opinions on product strategy, even on the business, on the go-to-market. And so I actually think some of our strongest product staff are going to be converts from design and from data science who are just looking to expand their reach. And they were influential across functional boundaries before, but this world where those functional boundaries are just wildly blurred, just allow them just to jump in. And so sure, they'll be technically a generalist on paper, but they're clearly have a uniquely strong ability in one type of craft. But they've got the ability and strong opinions to make informed decisions across other parts or other crafts. And so I don't know that all the strongest designers I have will all be in design.
They probably will be the majority, but I can imagine a bunch of really strong ones moving roles. But I mean, I should also check my own bias here though, I started as a designer at Facebook way back when, and I switched roles.

**Lenny Rachitsky** (11:05)
Designers are great.
I'm a big fan. So this is really interesting. There's always been this GM model where different types of functions can become GMs. It's like this product staff role feels like a similar situation where different functions can become product staff.

**Adam Mosseri** (11:17)
Yeah. And that was true of PM before, which is so much more true now.
And I mean, in some ways, it's probably the age of the generalist, but I still think there's going to be a real important role for these really amazing specialists who are just, they're all about going. I wish I was like that. I always had this, like, I romanticized like a phenomenal machine learning engineer or AI researcher or shoemaker. Like, I think that's the coolest thing in the world, but it's never been my shape. I've always been, I've never been great at anything. I've always just had range. That's always been my strength.

**Lenny Rachitsky** (11:55)
Same.
Okay, so this idea of product staff, so the idea is on these new pods, so this is like a new thing you guys are doing. So there's these pod teams, product staff, engineers, and maybe one specialist that's going deep on, say, pricing algorithm or something like that. So what this tells me is there's these, like, adjacent roles that are maybe more in trouble over the years. Data science, for example, user research, for example. You talked about designers being anxious. Is there, is there anything there just like, you know, these, maybe folks in these groups should think about shifting to other roles?

**Adam Mosseri** (12:27)
I mean, there's anxiety everywhere. I mean, I've talked to a lot of people at a lot of other companies, and it just seems like this is a lot of concern right now about competition, about job displacement, about unintended or unforeseen consequences of all this technology and all this moving so quickly. So that's definitely happening.
I think that you will see the functional lines continue to blur, but I still think there will be room for functions. They'll just be shaped differently. They'll be more, they won't all be senior ICs necessarily, but they'll all be either senior or on their way to being senior. You can't just have a bunch of super senior data scientists and no new ones, because then who's going to be the new super senior data scientists in the future. So you need to basically hire and mentor and grow talent. Maybe the team is smaller overall, and then those who aren't on their way to being super senior, move into more of a generalist role. I think that's like a reasonable soft landing. But I do think you're going to want to make sure you're investing not only in today's senior talent for each specific function, but in tomorrow's. Otherwise, I think you're going to regret it in a couple of years, my take. That said, who knows what the world looks like in a couple of years.
So my big thing is generally like don't be overly confident in whatever your predictions are because there's just too much flux right now.

**Lenny Rachitsky** (13:51)
The Benedict Evans was on the podcast recently said the same thing. We don't know anything about what's going on.

**Adam Mosseri** (13:56)
Yeah.
I like him a lot. I'll make sure I'll listen to the podcast.

**Lenny Rachitsky** (14:00)
Yeah.
So you talked about taste. This makes me think about, so you're interviewing a lot of people, hiring a lot of people. What are some traits that are like trending up in things that you look for more and more now in this world? What are some traits that are trending down and maybe less important to you?

**Adam Mosseri** (14:17)
I mean, there are some things that are the same, right? So for the longest time, almost no matter what the function, I always look for three things. Do you have grit? You've got some drives and fire in your belly. Are you a quick learner?
And are you reasonably, ideally very self-aware so that you can actually take feedback and know what you're good at and what you're not good at? Because if you are those things, if you got fire in your belly, you learn quickly and you're self-aware, you can get good at anything eventually.
But if any of those things are missing, it's usually an issue. So that's the baseline. Right now for hiring, but just for I think people who are going to be more successful over these next five or 10 years as things change so significantly. I think two things that I'm continuing to encourage myself to do are to stay curious, and to put yourself out there. I just think you got to try things. This is like to that point before that no one really knows what's going on. You just have to be willing to try things. I don't know, do you speak another language?

**Lenny Rachitsky** (15:25)
Russian, yeah.

**Adam Mosseri** (15:26)
Yeah, so when you learn another language, I think one of the most important things, one of the best predictors, this is my guess, I don't have any research on this, about are you gonna get good at speaking, is are you willing to sound like an idiot? Are you willing just to say it and be corrected and not be offended and then just get better and better? You have to put yourself out there. And with all of these new tools and models and technologies, I think you just have to be willing to try stuff. So if you're curious and you try stuff, I think that you'll learn, you'll adapt. But if you're not curious or you're not willing to make mistakes or try things, I think you're in a ton of trouble. Or you think it's going to be a really difficult time. So those, I think, are premiums, not just for hiring at a company like Meta or a team like Instagram, but I just think across the industry and multiple industries over the next 10 to 20 years. Is there something that maybe we're looking for less of? For some of these functions, I think that there's some that are still going to be very large teams. You need people who are really good at managing large organizations. Large organizational leadership is its own craft and skill. It's actually different than management.
But I do think there'll be less of those roles. I think we'll have more smaller teams and there'll be less people who manage thousands of people.
That's not that that job will go away, but that will be less of what I'm looking for in hires, because I'm going to have less roles like that.

**Lenny Rachitsky** (16:48)
Something I'm hearing from a few folks is AI is almost kind of resetting people's impact and success in terms of some people that were maybe low performers pre-AI can now do like things they were bad at, or AI now allows them to do. And now they're thriving, building all these things, helping other people. Do you see that at all? Just like AI is just like lifting other people up, maybe lowering some people down.

**Adam Mosseri** (17:12)
Yeah, I mean, the job is just different. I mean, take engineering. Engineering used to be maybe not majority, but a large percentage, 40%, 50%, 60% writing code.
It's not now, especially if you talk to anybody in these labs, they're spending most of their time planning and reviewing code. That is a very different job. You might hate that, and you might have loved just writing code, or you might love that, and you might not have been that fast at writing code.
Who succeeds is a function of whose strengths are aligned with the tools, needs, and the businesses' needs, and so this is definitely happening. Another thing is you've had people who had good ideas about how to contribute it to other functions but didn't have the mechanical or technical skills to do so, and AI reduces the boundary to do that, and then all of a sudden they can.
For me, it's kind of funny because when I got hired at Facebook, all the designers had to be able to program.
I went through a technical loop. We gave up on that because it was too hard to hire people. But I now get to program again for the first time in maybe 10 years. I am not a good engineer. I'm a mediocre engineer on a good day. But now I can write code responsibly, which is just an amazing thing. You're seeing this across all sorts of levels and seniority and functions. Designers who are programming, engineers who are pulling data and doing strong analyses, data scientists who are putting together proposals for designs. The tools aren't all great, by the way. I think too often we have this really polarized binary outlook on the state of AI. Like are you AI-pilled or are you anti-AI? It's like people aren't binary. I said that to the team yesterday. And the state of the tools isn't binary either. They're amazing at some things and remarkably bad at others. And the people who I think are going to make the most of it are the ones who are clear-eyed about what AI is good at and what it's not good at, and also have an instinct or a nose for what it will be good at and not good at. Not next month or in a couple of months from now.

**Lenny Rachitsky** (19:38)
You mentioned that AI writes all our code now. Someone tweeted this idea that stuck with me for months now. Just like, remember we used to be able to just write code for free?

**Adam Mosseri** (19:52)
I think I'll be able to write code for free, just with a smaller model, but yes.

**Lenny Rachitsky** (19:57)
I guess that's true. There's a model that are close to free, but it's like, yeah, that's crazy. Now, it's just like, tell me.

**Adam Mosseri** (20:03)
Just think about the cost. Think about what you pay for a model now, and what the level of intelligence you're getting from that model is. Then at that same price point a year ago, what were you getting? At some point, the incremental value won't matter.
We're getting there, I think, with small projects and programming. I think the models will matter even beyond, this week you've got Fable and obviously Mythos from Anthropic. But I spent a lot of time with that this week.
For the first time, I'm like, I'm just talking to a much more technical, much smarter engineer than I am. The next version, a year out of that model, do I need to pay for frontier tokens for whatever Anthropic model 6 is? Or is Fable just fine for all of my side projects? Probably just fine. Probably pretty cheap by then too.

**Lenny Rachitsky** (21:04)
Yeah. When Kevin Weil was on the podcast, when he was CPO at OpenAI, he famously said, this is the worst the model will ever be.

**Adam Mosseri** (21:12)
Yeah.

**Lenny Rachitsky** (21:13)
Yeah. It's still hard to comprehend that. Wow. That's only going to get better.
So on this point of tokens, spend, ROI and things like that, Meta was famous for this leaderboard of token spend.

**Adam Mosseri** (21:25)
It's a terrible idea. No leaderboards for tokens.

**Lenny Rachitsky** (21:28)
Okay. Talk about that and just how do you think about just like budgets for engineers and product teams at this point? Just like spend as much as you want? Is it like there's a cap we have? Is there any sort of thing you've kind of figured out that works well?

**Adam Mosseri** (21:38)
Right now, we've managed to get the costs rained in a little bit by shutting down the silly things that we were doing. And so it's not that hard to build a token incinerator and that doesn't create a lot of value. And as soon as you actually look at the dollars in and value out, you might just be like, oh, that's just a bad idea. And so right now, we don't have token limits for our engineers. Actually, I think for anybody, really.
I think that will eventually have to happen, particularly if costs go up before they go down. I think they'll eventually go down for the reasons that we just talked about. But I think of it like as any other resource, right? Like I have to decide how to deploy capacity to my different teams, because I have a limited number of GPUs and CPUs and storage and RAM, etc. I have to decide how to deploy OPEX for labeling budgets across my teams. I have to decide how to deploy payroll for headcount across my teams. I think that you can imagine at least in a year or two coming that the burn rate of a strong engineer might be the same as their salary or their cost of employment. And if in that world, like you're going to probably need to put in some caps, the caps should probably be like a proportional to your sort of, you know, the company's sort of trust in your ability to use them in an ROI positive way. But I can imagine caps being healthy. Right now we're not there. I think costs will go up because we'll just be using more tokens, not because the prices will necessarily go up. But then I think prices will come down because all of these frontier models are going to be in a bit of a pricing war.
So we'll see. I think it'll be a bit of a roller coaster.

**Lenny Rachitsky** (23:23)
So coming back to this idea that, as you said, we've evolved from, we used to write all our code to now we're approaching, all code will be written by AI. And it feels like now the transition is, it's not just written by AI, but it's like one-shotted by AI. Like coding now is steering AI. And it's like how often you have to correct it is coding now. And then there's, so it's like the software development life cycle slowly being eaten by AI.
It'll start helping us come up with ideas, I imagine more and more. The question I like to ask people is, where do you think human brains will continue to be most valuable as AI continues to eat more and more of that product development life cycle?

**Adam Mosseri** (24:05)
Taste, like we talked about, judgment, particularly around strategy.
You might get feedback from an AI on the strategy, but you're not asking an AI to come up with a strategy anytime soon. If you are, then it's within the context of bounds you set. So here's my goal, here's my vision, here are my constraints, here's my job, here's my budget. I think that it looks more like management. You are trying to define what success looks like, decide how prescriptive you want to be about the path to success, and then giving feedback along the way, and that is its own craft.
It'll be interesting to see how, Matt, if some of the same dynamics come up. I believe that if you are too prescriptive as a leader with a team, you end up stifling good ideas. But if you're too open-ended, sometimes teams just waste time going in the wrong direction. And so that level of autonomy you give a team, like maybe that applies to agents in the future, particularly when we're talking not just about building something, but deciding what you build in the first place. But I think of vision as an articulation of the world or the state of the product you want to get to. And I think of strategy as an opinionated path to achieve that vision. Strategy can't be like, be the best or be amazing. It has to be controversial, that you have to be, a reasonable person should be able to disagree with it, because otherwise you're probably just trying to compete on raw execution. And I think both vision and strategy, I think, are going to be where our brains are, spending a lot of our, more and more of our cycles, and I think less on execution.

**Lenny Rachitsky** (25:56)
Something I have always thought is, AI should be incredibly good at strategy, because you would think, here's the market, here's all the information on the market, our competitors, our metrics, our numbers, our growth, all these things, help me figure out how to win. You think AI, knowing all that, would be really good at this?

**Adam Mosseri** (26:14)
I think it could be. I have found it's not, unless you steer it pretty aggressively. And I don't mean towards an answer, I mean based on the constraints. It turns out when you're trying to come up with a strategy, there's a lot of things to consider, right? You need to consider the state of the technology, the personnel on the team and what's motivating them and what you can get. You know, sometimes coming up with an idea that is on the bubble, you know it's gonna actually attract some of the best talent. And so that kind of like that kind of the push then goes to the idea.
Obviously, the competitive landscape, the regulatory landscape for companies as large as ours and the compliance landscape, the identity and reason to exist for the brand, you know, you have to consider all of these things. I think if you ask an AI just for a strategy lazily, you're not gonna get something great. You're gonna get something pretty predictable that pop up at the competition would expect you to do. I think if you want a really more effective one, you need to think long and hard about what are all of the different inputs that need to be considered. Make sure you steer the AI in a way that it's considering those as well. And it needs to be a conversation in the back and forth. But I think if you're willing to put in the work and the time, it can definitely be helpful and definitely be clarifying, particularly if you tell it to be critical.
Different models have very different vibes though on how willing they are to be pushed back. So I recommend picking one that likes pushing back.

**Lenny Rachitsky** (27:44)
Yeah, Mythos has gotten really good at being like, I can't do this, let's move on. Like, there's all these limitations.

**Adam Mosseri** (27:49)
Claude has always been a little bit of a jerk in a way that I actually appreciate. I appreciate it, I really do. Cause I don't want one that's just like, oh, you're so right, I'm so sorry I said that. It's like, hold on, I want the real sort of intelligence.

**Lenny Rachitsky** (28:05)
I don't want the pleaser.
This point you made about people being excited about the strategy is such an interesting one. There's this idea that I read, I think Cory Doctorow wrote this. There's this kind of concept of a centaur and a reverse centaur. So centaur is a human body, this is going somewhere, I promise. Human body, horse, sorry, human upper part, horse lower part.

**Adam Mosseri** (28:28)
Horse body, yeah, yeah, yeah.

**Lenny Rachitsky** (28:29)
Horse body, where the human is in charge. And that's kind of, we prefer that, we want to be in charge. Reverse end chart, which is what we want to avoid with AI, is where the AI is controlling us, and we're just doing its bidding.

**Adam Mosseri** (28:40)
It's a horse head on a human body.

**Lenny Rachitsky** (28:42)
Yeah, exactly.

**Adam Mosseri** (28:43)
It's terrifying.

**Lenny Rachitsky** (28:44)
Like in a sense, like Uber drivers and DoorDash people, kind of this is their life, which is not great. And this is the danger, I think, for a lot of people is like, if it's giving us the strategy and telling us, here's what we're built, like no one's going to want to do that. So that's a really interesting counterpoint to, we don't want AI to be telling us the strategy almost.

**Adam Mosseri** (29:02)
Yeah, no, I think there's a lot of things to be careful about right now. And I would certainly not just assume that because you might be able to outsource some workflow to AI that you should. There are certain ones where I think it's really just a win-win. There are certain ones where I think is the risk outweighs the benefits.

**Lenny Rachitsky** (29:24)
This episode is brought to you by Mercury, radically different banking loved by over 300,000 entrepreneurs. And now with Command. I've been a customer of Mercury's for over six years. I have never once thought about leaving. Mercury is basically what happens when banking is built by product people, not by bankers. They make it so easy. Dare I say fun? To send invoices, move money around, set up virtual cards for folks on my team. Does your bank have an API, a Terminal Native CLI or an AI ready MCP server? I don't think so. And just recently, they launched Command, a conversational interface built directly into Mercury, which acts as your financial operator. I've been using Command to transfer money around, to figure out what categories I've been spending the most money in, analyze my cash flows. And just today, I used it to find out how much I've made from a specific sponsor over the past year. I just asked, how much have I made from X over the past year? Ten seconds later, I have an answer. It is so freaking cool. Visit mercury.com to learn more and apply online in minutes. Mercury is a fintech company, not an FDIC-insured bank. Banking service is provided through Choice Financial Group and column NA, Members FDIC.
Okay. Going back to product leadership, things you've learned along your journey.
We were chatting ahead of this about just things you've learned. And one thing that you said about some of the product, the best product leaders you've worked with, is that they're less visionary and more curators.
I'd love to hear more along these lines.
Yeah.

**Adam Mosseri** (30:55)
I mean, you do sometimes find amazing product leaders who are just like idea machines, just prolific idea machines. But I do think a lot of the best have taste, have something about them that really makes really strong talent want to work with them, but end up sort of being curators. Curators of people, curators of ideas, curators of technologies, curators of strategies. Because I don't really care if I'm hiring a strong lead for an area. If the strategy comes from them or comes from somebody else, I just care that there is an amazing strategy and everyone is bought into it and that we're executing against that strategy well. And so I think that some of the best product leaders, yes, have ideas. It's hard to be a great curator if you don't have some of your own ideas.
But embrace the reality that they can't come up with everything themselves. And so they need to create an environment in which great ideas bubble up and are chosen or decided upon. And so I think it's not just about curating ideas, but it's sometimes about curating teams and people.

**Lenny Rachitsky** (32:13)
I love that. I so agree. I feel like everyone's always joining a team and they just want to do a vision strategy, just like not actually hands-on work. And that way, I was coming in, here, let me do the strategy.

**Adam Mosseri** (32:23)
Yeah, exactly.

**Lenny Rachitsky** (32:26)
And I love this point that there's so much power and value and people underestimate just the need for just like a really good curator of the team's ideas.

**Adam Mosseri** (32:35)
Yeah.
Sometimes it's not just who's good or what idea is good. It's also what is going to work given the broader context. For instance, on team building, a huge thing that I'm always considering is not just like, is this person a really strong candidate for this role? It is how does this person fit into their leadership team? So if I first have an area like trust and safety, I have an engineering lead, I have a product staff lead, I have a data science lead, I have a design lead, I have a research lead. I need to make sure that those five complement each other. I need to make, and that's about what skills each one has, what weaknesses each one might have. I also need to make sure that they, this is more art than science.
Have a good vibe, right? You need trust and rapport. A leadership team with strong trust and rapport can work through most anything. A leadership team without trust or rapport, like anything can become an issue. And so that chemistry bit is, like I said, much more art than science, but that also matters. And so I think some of the best leaders and product leaders specifically also either do that instinctively or consciously, but they have a nose for building teams that are going to have good energy and good collaboration.

**Lenny Rachitsky** (33:59)
Warm and fuzzy stuff.

**Adam Mosseri** (34:01)
Yeah. Well, the flip side is also true, right? Like I've had many times in my career where I've had two people who I think are amazing and I even adore them and love them. And they just can't get along.
You're like, this isn't a competency issue. This is just a personality issue. And you just have to sometimes call it and split them.

**Lenny Rachitsky** (34:23)
I want to transition to talk about Instagram, the product, the platform, things you guys have learned there. Let me start with this question. What's something that the Instagram algorithm knows about human behavior that people may not realize?

**Adam Mosseri** (34:38)
One of the most common misconceptions is actually in the opposite direction. I think people assume that there's a much more detailed semantic understanding of everybody's interests and preferences in the algorithm than there is. Most of what's really driven the progress in the world of recommenders over the last five, ten years have been, you know, these large embedding models and these other techniques that basically produce artifacts that cannot be read by people. They're not legible. They're like giant vectors. It's like, sure, I can show you the vector, but it's just going to be a bunch of numbers in like a seven dimensional space. It's like, and so when, when we talk about, does the algorithm know something, usually we think in these more semantic terms, it knows I like surfing and it's like, it doesn't, it just has this big ass number that happens to correlate with surfing. Um, that said, I think that is starting to change, right? I think that what, one of the things that LLMs are enabling is they can describe in, you know, words, you know, English for, or whatever language you prefer, what some of those previously illegible artifacts, um, are at least proximate to, if not mean directly, right? So this is like the thing I've been really, I posted about this this week, this thing called your algorithm. Basically, the idea is we take a look at all of the stuff that you've interacted with, and then, you know, we all of that is in an embedding space. You can think of embedding space as a map. You can map a bunch of videos into the same map. And so videos that are close are similar. And now we can just have an LLM just be like, describe that part of the map. And it can be like, oh, that is like deep pour over coffee snobbery.
And that's kind of amazing.

**Lenny Rachitsky** (36:29)
That is so cool. Like you can ask the LLM to look at these numbers and extrapolate here is like the topic that you're interested in.

**Adam Mosseri** (36:36)
Yeah. Or look at the videos. And so the way you're both, so you can also embed concepts into that same space. And so embeddings are really the underlying technology underneath LLMs, right? That's how all the whole thing works. And so, you know, so what we do now is we let you, you know, quote unquote, see your algorithm. You can see what topics we think you're interested in.
And you can adjust it. You can add and remove things. But the idea here, giving people some agency back in a world where, you know, these social media apps are getting taken over by recommendations.
But we can't do a lot of other things yet, which we will be able to do. You know, there's things that aren't topical that you might ask for. I want more fun content. I want to see my friends more. I don't want to see my high school's kids, friends' kids' photos. You know, I don't know. We can come up with what... I don't want to see seven photos in a row, but I'm happy to see six photos in a row. Whatever you have hearts can, you know, whatever your mind can come up with. So we have a lot of work to do. And so I'm excited about that. But I think a misconception historically is until recently, we don't really know as much about you as you think. We're just like, oh, like you liked these photos. This these people also like those same photos and they like these other photos. So you might like those other photos. Like that's kind of how I'm oversimplified. That's like, yeah, kind of how it worked. Now only now are we actually getting as sophisticated as I think people have assumed we've been for many years.

**Lenny Rachitsky** (38:06)
That is really interesting.
One that comes to mind is to kind of this transition everyone eventually goes through to this like algorithmic, broad, global feed, everyone. It always feels like people think, I just want to see chronologically everyone I know and follow. And that's going to be my favorite feed. And it continues to be proven wrong. No, you actually engage a lot more, a lot more when it's this algorithmic feed of things we think you will love.

**Adam Mosseri** (38:31)
Yeah, it's tough because I mean, I get, I mean, I posted this week, this thing about agency and I just got destroyed in the comments, which is just part of the job.
I get it, right? But there are a couple of issues with the chronological feed. So one is, and some of this is the tension between an individual's interests and what works when you scale it up, right? So if you do a pure chronological feed, the incentive for everybody is to just post as much as possible.
Because it will always be at the top of everyone who follows this feed as soon as you post. So what ends up happening is that the feed gets overwhelmed with professional content, with usually large company content and publishers, because the New York Times can pump out 50 things a day. Your best friend won't.
You might get one thing a week from them. And so your feed just gets taken over. So part of it is the incentives that emerge. Because when you design these systems, it's almost like designing a city. You need to think about, okay, here's how the mechanics work. What are the incentives that arise? How are people going to act within those incentives? And then what happens? And the other thing is sometimes the most interesting thing was just not the most recent thing. Recency is an important input into relevance, but it's not the only one. My sister got engaged last night and, you know, she's in Germany. She didn't. If she did, she's married. She got married last year. That's why it was tough for mine. But if she got engaged, you know, I missed it because she lives in Europe and, you know, we're different time differences. Like, do I really want to see a picture of, like, my brother's po-bo sandwich, you know, po-boy sandwich, or do I want to, like, see my sister's things first? So I, it's tough. It's tough. I'd love to figure out a way to find the right balance. I want to give people agency over the experience. But I think it needs to be in a way that creates a system that makes sense, not just for us as a business, which matters. I'm not pretending that's not an issue, but also for the overall community. Because we've done chronological by default and where you can make it default, and you see not only does usage go down, overall sentiment goes down. The individual who made that choice might be happy at the moment, but when you just get pummeled with stuff you're less interested in over the course of months, we ask, we run surveys at massive scales. We just see people start to become less and less satisfied with Instagram.

**Lenny Rachitsky** (40:57)
Kind of along these lines, everybody asks you about this these days, AI and content and how that all impacts everything that's going on. I want to ask you something I haven't seen someone ask you.
Is the rise of AI content a headwind or a tailwind for Instagram versus other platforms? Do you think this helps or hurts you guys?

**Adam Mosseri** (41:17)
I think it's going to be a tailwind, but I think it's going to be a challenge.
Not just because it's more content. Obviously, we're an attention business, driven business, we're an advertising business, more content means potentially more attention. That's not for free, though. I don't think we're very good at ranking AI content yet, this great AI content, this crap AI content. You should just see the stuff you're interested in and not any of the stuff you're not interested in. But I do think that in a world where, or for years now, and I've said this many times, power is shifting from institutions to individuals across industries. The easiest example of sports were players are more relevant than teams now, and that was not the case when I was a kid.
In that world, I think it behooves us to invest in individuals, and to invest in specifically for Instagram and creators, and I mean creators broadly. I don't just mean influencers who are promoting branded content and making native-only videos. I mean, anybody who's using platforms like Instagram to help do what they do. You could be a journalist, you could be an artist, you could be selling scarves, you so, but you're out there as yourself creating and sharing content that helps you achieve whatever it is you're trying to do. We've been leaning in that direction for many years now. That's been one of our two or three most important audiences for as long as I've been on Instagram. In a world where there's an abundance of synthetic content, I actually think people are going to seek out creativity and authenticity and people more, not less. I think that will help us. That doesn't mean that we won't have AI content on our platform. There's going to be bad and good AI content, and we're going to try and handle that the way we normally handle content. So unsafe goes away. Interesting versus not interesting is based on ranking and personalization. But I think people are going to really seek out other points of view. Because Instagram was never just about the content, it was always about, to a certain degree, the person behind the content, the point of view, the reason they're sharing it, their perspective. And I think that's going to become more important, not less. And I think given that we are not the best at a lot of things, but we are the largest creator platform. And if you look at how we define creators and how many creators use us versus other platforms, I think it will be a tailwind for us, because I think people are going to seek out people.

**Lenny Rachitsky** (43:42)
And this connects to your earlier point that companies, like senior times, can pump out a bunch of AI content versus a creator. And so you're saying you kind of want to protect against that too, allow individuals to continue to perform well in spite of just all this AI content.

**Adam Mosseri** (43:58)
If you just love AI content, great. Like you should be able to have a feed that's just like AI town. And if you don't, then you shouldn't have it in your feed. To me, it's like, I don't think we should. I understand why people are. I'm not oblivious to the overall paradigm shift and sort of revolution that we're sitting in. But I don't think we should judge content based on the tool that made it. I think we should judge it based on the content, the point of view, the person behind the content.
I don't think we should filter out AI content. I think we should let you know if content is AI content or not. I think we should let you know more about the person who posted anything so that you can make informed decisions about whether or not to believe or trust them based on knowing who they are or where they are, or how many times they've changed their profile, or if their profile is three days old or three years old.
But I don't think we should be making value judgments based on what tool you used.

**Lenny Rachitsky** (44:59)
Is there an AI content creator you love? They are just like this so good. I love watching these AI videos.

**Adam Mosseri** (45:06)
Yeah. What is she called? Plastic dream sequence? Is that what it is?
Check it out. Check it out.
Plastic dream sequence. I have it on my phone. I'll double-check. It's these sort of dolls, Barbies, but they're like singing songs and these little tiny silhouettes and snippets, and it's just amazing. It's a little weird, but also kind of amazing. It's very clearly AI. It's not pretending not to be, but it has a very clear creative and aesthetic point of view. Every time I come by one, I'm like, yep, we're doing this now. I'm going to watch this for 30 seconds.

**Lenny Rachitsky** (45:47)
I have it pulled up here and I want to watch it, but I'm not going to. That's awesome.

**Adam Mosseri** (45:53)
If only that AI, that's another one. He's in France. I think he's in Paris. He uses multiple different tools and models, but he kind of tries to create these dreamscapes and animate them. So he uses one model to create the image, another one to create the video, music, etc. He's very clearly got his own aesthetic.
You can think of him as a painter, but this is his tool.

**Lenny Rachitsky** (46:18)
Is there a vision of AI versus human in the feed? Do you think it'll...
You said you maybe want to mark it. How do you think about people? Are they going to be AI account, non-AI account? How do you think about it, or is that still a work in progress?

**Adam Mosseri** (46:31)
Maybe we'll end up in the same place, but there's a difference between marking content and marking accounts, and they're both useful and interesting. So if content was created with AI, I think you should be able to know that. That's hard, by the way, because we can detect that right now, but as these models get better, we might lose the ability to detect that. So we should also be very careful to be honest with you about how confident we are in our own sort of assessment. But I think you should be able to just ask, like, hey, is this AI? And we should be able to tell you, we think it probably is, or we're not sure, or it's definitely not, or it definitely is.
I actually think we might be more practical to label camera-captured content, like basically non-AI content as opposed to labeling AI content long-term for a couple of reasons.
But then at the account level, I think it also matters. There is definitely a new spam vector, which is these fake accounts, which by the way, an AI creator, that's fine. There's nothing wrong with that necessarily. But there are these spam vectors which are trying to abuse that, and they're selling bogus supplements, and it's like an AI monk and it doesn't present inside, obviously, it's an AI and it's just trying to take advantage of a certain aesthetic or a certain stereotype. That we need to figure out how to crack down on that. So I do think we should be making sure that you know. Basically, you just need to know and then you can make your own informed decision. Is the account a real person or not? Is the content a real piece of content or not?

**Lenny Rachitsky** (48:01)
When you think about other platforms in the space, social content platforms, are there any features or just ways of approaching stuff that they do well, that you're kind of jealous of or really impressed by?

**Adam Mosseri** (48:15)
Yeah, there's a bunch. Everybody, so many people do so much. Because I mean, for me, one of the things that we are finally catching up with, but I've been always very impressed with is TikTok and their recommenders' ability to break small talent.
In the world of ranking recommenders, you can talk about exploitation-based ranking. That sounds terrible, but it just means like using the data you have. Then you can talk about exploration-based ranking, going and trying to figure out what someone might be interested in, that they might even not know they're interested in yet.
It is much easier to move engagement by showing people stuff that you know they'll probably like, because lots of people like it. It's much harder to go and figure out how to essentially test content so that we can see like, hey, maybe you, sure, you like Bieber, but you might also like Afropunk. And so we're just going to show you some Afropunk and see what happens. If you do the latter, this exploration-based ranking, you can, I think it's really good for niche creators and small creators because you give them a chance to find an audience that either wasn't going to see them before or didn't even know that they were interested before. So we've invested a lot over the last couple of years in ranking, not just increasing engagement, but increasing originality, increasing the number of pieces of content that break out, increasing recency to stay culturally relevant. And so a lot of that has been inspired by TikTok and ByteDance. I think we're catching up. There's actually a couple of those areas where we, I think, by the best we can tell, we're ahead of them. There's a couple where we're still behind. But we have line of sight to, I think, being the best in class at recommendations for the first time during my tenure. So that's, I think, and they get a lot of credit for inspiring a lot of that work.

**Lenny Rachitsky** (50:05)
Nice job.

**Adam Mosseri** (50:07)
Well, we'll see. Not there yet. They call me disappointed dad. My team is always like, can you ease up on the disappointed dad vibe? So I'm trying to be a little bit more generous about giving people their flowers.

**Lenny Rachitsky** (50:22)
Like you say that, but that's an interesting common thread across really successful leaders is just never being satisfied. Yeah.

**Adam Mosseri** (50:29)
It's a blessing and a curse.

**Lenny Rachitsky** (50:31)
Here's all the problem. It is.
On this creator piece, I think that's also, people complain about this global algorithm, not showing them all their friends. But I feel like this is a benefit of what happens when you do this. Now that you can break new creators into a wide audience if you have this global algorithmic feed, which is really great for a lot of people.

**Adam Mosseri** (50:55)
I'm out there talking about a lot of these contentious issues and I get beat up a lot in the comments, which is fine. My main thing here is just to try to communicate that there's almost always trade-offs. You can't just have all of the things, unfortunately.
You want to never see something you're not interested in, then you're also just going to see the most basic, general, lowest common denominator stuff all the time. You want to discover new and interesting things, you're occasionally going to see stuff that was just a miss.
But this isn't just true about ranking. All these major debates have trade-offs. Privacy and safety, those two things are intention. Do you want a company scanning your messages or not? There's some really significant trade-offs on both sides of that debate. And so, generally speaking, when I argue and engage in the debate with people who feel really strongly about things, I'm not usually trying to convince them, they usually, their mind is usually made up. I'm just trying to enumerate all of the different puts and takes for the rest of the people watching the conversation.

**Lenny Rachitsky** (52:05)
Speaking of getting torn apart in the comments, you're so in the middle and think of all of these really hairy situations, changing the feed, you're like in the Cambridge Analytica lawsuit, all this. You're in the center of so much controversy. Is that something?
Oh man. Is that just like you, I will lead into this, this is the thing I need to do? Or is it like Zuck being like, Adam you gotta be the front face of all the stuff, get in there. Where does that come from?

**Adam Mosseri** (52:38)
It started on News Feed, so I used to run News Feed at Facebook, and my take was that the debate was going to happen with or without us, so we might as well participate. So I started being really active on Twitter specifically, because that's where journalists really lived at the time, and I thought it would show some humility to show up on their turf, so to speak. My Twitter ended up being the darkest place in my life, because I just followed all of our biggest critics. That's not a dig on Twitter, that was just what I did.
And that's where it started, and it kind of slowly built from there. For better or for worse, we've become a really important part of daily life for a lot of people. We touch a lot of people. We have a lot of responsibility, and there's a lot of change, and with change means there's gonna be anxiety and stress and scrutiny. We've made great decisions. We've made mistakes. We've been criticized for things that I think, we've been criticized unfairly. We've been criticized fairly. And so we just need to accept that this debate is going to happen broadly. So I just think it's better for us to talk about it. And just be clear about what we're doing, why we're doing it, what the trade-offs are. If people disagree, that's okay. We're not necessarily winning over friends when we talk about what we do. But I think over the long run, people are fundamentally more afraid of things that they don't understand, and about things where people are more secretive and less accessible. And so I've been tried, I've tried to show up in a accessible and authentic way.
And I've made mistakes and I have enjoyed it at times and hated it at other times. That's kind of how it started. There was also kind of a fun debate in Mark's sort of senior leadership team a long time ago, where we were just talking about how we're a social media company, we had like a very sort of conventional approach to communication and like press releases. And so why don't we just use our platform? So I was not in that debate, but I stuck myself into that debate, try to mediate it. And I think, but that was also a reason why I ended up getting sucked in, because Mark was like, all right, well, let's see. Like, why don't you try and see how it goes.

**Lenny Rachitsky** (54:48)
What's something that helps you deal with the hate that flows at you every time you say something that people disagree with?

**Adam Mosseri** (54:55)
You try to put it in perspective, right? So it started with, I did a redesign of News Feed in 2009 We launched it March of 2009 for Facebook. I was a designer. I was like an IC designer, front entry level designer. And the first comment that came in was something pretty derogatory. It was like homophobic and anti-Semitic. It was just like, literally, we're all sitting there, we launched this thing, and we're just looking at the stream of comments. And it's like the first one, and it was specifically about, they don't know me, but it was like, what expletive, expletive sensor, sensor designed this shit? I was like, oh, it was me.
And I was devastated. I was a 25-year-old kid. And I don't know, I thought about it. And I came to this idea that if you spent 30, 40, 50 minutes a day at your desk, and you organize your photos there, and you wrote letters to your friends there, and you read there, and then I just came and I rearranged your desk and I didn't tell you, I didn't warn you, I didn't even explain why. Like you would be pissed and that would be reasonable. And that was what was happening just with millions of people. So I try to put things in perspective. And then I try to step away from it, get time with my kids, get time outside.
There are months where it's really not hard at all and there are months where it's really, really grinds on me.

**Lenny Rachitsky** (56:31)
On those lines, there's a famous kind of reversal when you redesign the feed into this kind of video scrolly experience. There's this whole protest, the world protested.

**Adam Mosseri** (56:41)
Yeah, that was pretty rough.

**Lenny Rachitsky** (56:44)
What was kind of like, okay, wow, we're actually not right and we should go back. What was kind of, what helped you decide, okay, let's change course?

**Adam Mosseri** (56:50)
So actually that one got, three or four things got conflated. We had to redesign a feed that went to the video viewer. That was a test to 4% of users on iOS. It was a not, it was not going to roll out. It was just like an early test to get some sense and feedback on the idea. We were also leaning into Reels a lot. We were also leaning into recommendations. So posts from accounts you don't follow a lot. And there were also creators who were upset about the fact that their reach was going down and they were blaming ranking changes on that. Those four things got all conflated. We had some pretty big name creators publicly slap us. Then the press covered that creator backlash, which then got more creators doing it. So we ended up with this little bit of multiplier effect or echo between the creator community and the press back and forth. But we were never going to launch that. That was an early test. We knew it was going to need work. We actually have continued to grow video and invest in creative tools and invest in ranking and invest in recommendations and that's driven in most of our growth in the years since.
I think we were pushing. Well, I don't know.
I think my real takeaway wasn't that we should have not tested that design necessarily. I think we could have been done a bunch of things better to explain and maybe move a little slower. I think we were just pushing things a little bit too fast. When you are responsible for a platform like Instagram, you need to be reasonable and realistic about how much you can evolve it. Now, I would much rather have backlashes like that every couple of years, but continue to evolve and continue to stay relevant. Then the alternative, which would have been like we didn't have video, we didn't have DMs, we didn't have stories, we didn't have ranking, and we wouldn't be on having this podcast right now.
But the cost of leaning in is that you're going to occasionally make a mistake, and you're going to definitely pay for it.

**Lenny Rachitsky** (58:58)
It's interesting how running experiments now is very risky for companies at your scale. One person spots it and I go, shit.

**Adam Mosseri** (59:06)
You don't need to be proactive about communicating it, but you need to have a calm strategy. For any design change or any test that could be controversial, we talk about it beforehand and be like, okay, not if it leaks, when it leaks, what are we saying? Should we talk about proactively? Should we talk about reactively? Either way, what's the message? Because you can't launch something to 3 billion people and not test it first, but you can't test something at our scale and not expect people to cover it. So you have to be ready to talk about it before you even know you want to launch it.
It makes the development cycle more complicated than it used to be.

**Lenny Rachitsky** (59:54)
Yeah. The head of growth at Anthropic launched an experiment with pricing and it just went crazy on Twitter. He's like, it's all about the 1 percent of people were just trying stuff. They're like, no, the Anthropic fit.

**Adam Mosseri** (1:00:04)
Pricing particularly, that one is a real, you got to be real careful with that one. We've all learned these lessons. We should all share notes more. That's what I think.

**Lenny Rachitsky** (1:00:12)
You're someone not to avoid the internet hating you for the day.

**Adam Mosseri** (1:00:15)
Yeah, I'm happy to talk to that growth and the Thropic.

**Lenny Rachitsky** (1:00:21)
He's all right.
Okay, I'm going to take us to two recurring corners on the podcast, Fail Corner and Hot Seat Corner. Fail Corner, what's something that you worked on that was just a huge failure that helped you become better?

**Adam Mosseri** (1:00:33)
Oh, a bunch.

**Lenny Rachitsky** (1:00:35)
So many.

**Adam Mosseri** (1:00:36)
So I'll give you two maybe. So before Instagram, my first project as a PM was on a project called Facebook Home, which was a sort of fork of Android at the operating system level, and a piece of hardware with HTC. It was a spectacular failure. I learned way more in that year, year and a half, and I did it in any year, I think probably in my career. Because I was just a design manager before that. I declared myself a PM because the PM on the project quit, and I just threw myself head first in understanding carriers and OEMs and certification, as well as Android and operating systems, and just learned a ton.
And I'm happy I brought that project to an end because it had been going on for a long time. And sometimes the best thing you can do is execute an idea that doesn't have market fit well, just to decide whether or not the idea was a good idea in the first place. Another big mistake I made during my Instagram tenure was the first version of Reels was built on top of Stories. Stories had a ton of momentum. This was, I think, 2019
And we were trying to build Reels into Stories because we were trying to build on the thing that was growing the fastest. But it was not a strong foundation. Most, you know, the read-through rate on Stories is relatively low. There's way more Stories than most people have time to consume. So most of the Reels were never seen and then they disappeared. And if we had the version of Reels that we launched in like mid, just maybe we would think it's like the summer of 2020 and the summer of 2019 I think, I don't think TikTok is in, I think TikTok is still big and important, but I don't think it's as big as it is now. Because when they really took off was when the pandemic hit and a bunch of people had a lot of time at home and were looking for a little bit of joy and were totally fine with their phone having sound on. And so if you look at the numbers, the 2020 is when they exploded and we were out of position. And on one hand, I'm a designer, I'm trying to not add new things to the product, I'm trying to extend existing primitives, and that was the idea. On the other hand, I was wrong.
And it's a pretty big fork in the road if you just look at the overall business over the last eight years.

**Lenny Rachitsky** (1:02:55)
You create a lot of economic opportunity in the world, allowing TikTok to grow. Yeah, it's good.

**Adam Mosseri** (1:03:01)
I'm glad they exist.

**Lenny Rachitsky** (1:03:03)
Okay, final question.
I'm curious just about your screen time policy with your kids. I know you have three kids. There's a lot of concern these days about Instagram not being great for people, not for kids. A lot of tech executives don't let their kids use devices while they're building the product. As head of Instagram, how do you think about screen time with your kids?

**Adam Mosseri** (1:03:27)
The key thing for me is boundaries. It's also about education and having conversations with them. But my kids are too young to use social media. They're 10, 8, and 6 But they each have an iPad.
They have to earn their time. So they have different ways. They earn their time. It's usually about sitting down to do your homework three times for half an hour each, gets you a total of 90 minutes on the weekend, and then they can use that time on the weekend. But you have to set that boundary where it's like you can't just be, they ask for it and you give it to them. I think that matters a lot. And then I'm pretty opinionated about what they do on it. I approve what apps that they have. I think parents should be approving what apps to kids specifically are downloading on to their devices. We've been advocating for this at a policy level for a long time at Meta. I think those things help a lot. There are some exceptions.
One is planes. It's just like about surviving. I don't know if you were, for those of you who are parents.

**Lenny Rachitsky** (1:04:29)
I'm going to be, yeah.

**Adam Mosseri** (1:04:30)
Yeah, it's like you just like, that's just like, all right. You know, it's a 10-hour flight or 8-hour flight. It's like, yeah, you just need to get through it.
The other one that I'm starting to experiment with for my 10-year-old with is, so schools are interesting because I think I'm pretty supportive of a no phone in classrooms. That's happening more and more. I think that's just probably good for education. I do also know in the world of AI that there's concern about kids using AI and not learning critical thinking skills and I think that's a valid concern. But I also am worried about kids not learning how to leverage AI and then being at a disadvantage. That's a balance. I think you need both.
With my eldest, we started Bobcoding recently together. He just loves video games. So I was like, all right, let's make a video game. And so he's made this 19 level platformer game that looks like an 8-bit version of Super Mario from when I was a kid. But each level has its own theme, its own types of monsters, there's a store where you can buy different skins or weapons. And there's like, it's unbelievable what a 10-year-old who still types with three fingers can do with just a couple hours of sitting together. But that is more of like a, I want you to learn how to make things. I want you to be thinking, not just playing games. And I'm gonna sit with you and we're gonna do this together. So to me, these are the things that matter. Boundaries, scoping it down to the activities you think are healthy for your kid. Every kid is different.
But I do think you want your kids to be digitally literate, AI literate, because I think if they're not, they're gonna be at a disadvantage. But you also don't want it to be a free for all.

**Lenny Rachitsky** (1:06:22)
This is selfishly useful for me as a, as a, I have a three year old and I'm trying to figure all this stuff out. So this is useful.

**Adam Mosseri** (1:06:27)
Oh yeah, no.

**Lenny Rachitsky** (1:06:28)
For me to figure out a strategy.

**Adam Mosseri** (1:06:29)
It's amazing. It's a thing. And you're, you're, you're not that far off. You're really just not that far off. It's gonna happen in a couple of years.

**Lenny Rachitsky** (1:06:35)
Five coding next year. Let's do it.

**Adam Mosseri** (1:06:37)
I couldn't believe it. I tried to do it six months ago and it just totally didn't work. And then now with the newer models, it's been amazing.

**Lenny Rachitsky** (1:06:44)
What's their platform of choice? Are they Claude Coding person or something else?

**Adam Mosseri** (1:06:49)
My ten year old is using, is using Claude Code right now.

**Lenny Rachitsky** (1:06:51)
Amazing.

**Adam Mosseri** (1:06:53)
But we will see. We'll see how that goes.

**Lenny Rachitsky** (1:06:56)
Adam, I'm gonna let you go. Thank you so much for being here this year. You're just like such a gem of a person. It's just so obvious how clear, how authentic you are and just like how deeply you think about everything.
So I really appreciate you being here.

**Adam Mosseri** (1:07:10)
I appreciate you bringing me on. Been a fan for a long time. It's nice to finally get to have a conversation.

**Lenny Rachitsky** (1:07:16)
I really appreciate that.
Let me just ask you this final question to ask everyone. What's the way that listeners can be useful to you?

**Adam Mosseri** (1:07:23)
I just think you don't even have to tell this to other people, but just remember that this world and technology is complicated and there are almost always trade-offs and you can totally disagree with the decisions I or we make.
But just remember that we are people here trying to make these decisions, just trying to do the best we can. I actually do invite the criticism and the critique and the feedback, but know that none of these contentious debates are nearly as simple as most people pretend to make them out to be.

**Lenny Rachitsky** (1:07:59)
Wise words.
Adam, thank you so much for being here. Pleasure.

**Adam Mosseri** (1:08:03)
Thank you, Lenny.

**Lenny Rachitsky** (1:08:04)
Bye, everyone.
Thank you so much for listening. If you found this valuable, you can subscribe to the show on Apple Podcasts, Spotify, or your favorite podcast app. Also, please consider giving us a rating or leaving a review, as that really helps other listeners find the podcast. You can find all past episodes or learn more about the show at lennyspodcast.com. See you in the next episode.
