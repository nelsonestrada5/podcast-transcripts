---
podcast: All-In with Chamath, Jason, Sacks & Friedberg
episode: The Fight Over Open Source AI, Anthropic's $1.5B Payout, NYC Socialists Evictions = Violence?
transcript_id: 1000778249497
fetched_at: 2026-07-26T17:27:00-04:00
credits_charged: 1
---

**Jason Calacanis** (0:00)
All right, everybody, welcome back. Episode 282 of the World's Greatest Podcast. It's your podcasters' favorite podcast. It's your mom's favorite podcast. It's the All-In Podcast with me again, David Sacks from Palihapitiya, David Friedberg. It was a big week. It was a big week. The continuing number one story in the world is Kimi K3. It sparked a debate about banning Chinese open source models here in the United States. Then it's gone all the way to the White House last Friday. We talked about it here. China's Moonshot AI released Kimi K3, open source model, obviously, performance on par. On par, not six months behind, not 12 months behind, but now on par with models like Opus 4.8 and GPT 5.6, which in and of itself is extraordinary, but about 50% cheaper.
This has created a bit of a panic, similar to the deep seek moment that we had here back in early 2025 The White House, David Sacks, has gotten involved. Michael Kratzios, friend of the show, said, quote, we have information that Moonshot AI distilled Anthropic's fable for the development of its K3 model. Here's how the Trump administration has reacted so far. Monday, Axios reported the White House was considering banning Chinese open-source models. A couple of weeks ago, David, I think it was three weeks ago. I gave that to you as a hypothetical, and here we are. On Wednesday, Wired reported that Howard Letnick, from our Commerce Department, friend of the show, does not want to ban Chinese models. So apparently, palace intrigue, there might be different opinions inside Trump's White House. And instead, they want to incentivize more US frontier labs to develop better open-source models. Polymarket says, 45% chance US government bans an open-source model in 2026
That was a brand new market story. It just was at 22% a couple days ago. Sacks, you called it.
Two months ago, our first victory FAP of the episode.

**David Sacks** (2:04)
I think where it's all leading to is an effort to ban open-source models. There's a lot of breadcrumbs leading here. If you look at a lot of the rhetoric around how models need to have guardrails and that with open-source models, the guardrails can be removed and therefore, they're dangerous. You see this rhetoric already in Anthropix blog posts. Any threat that they describe, they go out of their way to take that shot at open-source models. I think, again, they're trying to create ideas or put predicate facts in the public record to justify an action later on. I think it's just a matter of time before they feel like they're at a position where maybe they can push for that type of ban directly.

**Jason Calacanis** (2:44)
All right. There it is, Sacks.
What's going on at the White House? What is the administration's position here? Why are we getting multiple? Is the White House testing and probing to figure out what their position is here? Or is it just this is a super dynamic situation? What's going on?

**David Sacks** (3:04)
Well, look, I mean, I have it on good authority that there is no decision by the White House to ban open-source models, and I think they want that known. I think there's an ongoing conversation happening around what to do about Chinese distillation, and we should talk about that. But no decision has been made, and the president listens to a course of voices. He wants to get advice from as many people as possible, and I'm confident that if everybody weighs in, that the president will make the right decision, as he always has with these tech issues. I think his instincts have been absolutely impeccable on this, and he's always supported a, let's say, lighter regulation, more open approach, and that's why I think the US is winning the AI race. So I think that's kind of where things stand.

**Chamath Palihapitiya** (3:51)
Where do you stand?

**Jason Calacanis** (3:52)
Where do you stand, Sacks? That's what everybody wants to know.

**David Sacks** (3:55)
Yeah, I think it's important for me to make my opinion known in the spirit of, again, contributing my voice so the president hears all perspectives and then can make the best decision. Look, I think it would be a tragic mistake if the government were to take action against the open-source ecosystem. That would do nothing but hurt America's position in this AI race. It would backfire badly.
And I think that the key point here is that regardless of what you think about distillation, you cannot punish American developers for it. So, you know, you can't say that American companies and American developers can't use Chinese contributions to the public domain. That's just cutting off our nose to spite our face. I mean, obviously, American companies have to be able to use everything that's in the public domain because the rest of the world will be using those things. And let me just say, I've said for a while that Anthropic is guilty of regulatory capture of attempts to seek government protection. This is a company that is the fastest growing tech company at scale in history. They started the year at 10 billion of ARR. They're now over 70 billion of ARR. This is not a company that needs government protection. This is not a company that is under threat from competitors or whether they're Chinese or otherwise. And yet they have been very successful at trying to panic everybody into thinking that they need some sort of government protection. And the tell on this, the way that you know that this whole distillation thing is fake is because if stopping distillation was their primary objective, Anthropic would push to ban Chinese access to American models, not American access to Chinese models.

**Jason Calacanis** (5:39)
Yes, they could. And that is achievable. They could block it.

**David Sacks** (5:42)
So there are the ones in the best position to block it. If distillation, if industrial scale distillation is a national security threat, there are the ones who need to stop it because that is the place where distillation occurs. You have to stop it at the source. Once you allow Chinese companies to distill, the horse is out of the barn.

**Jason Calacanis** (6:01)
Yeah.

**David Sacks** (6:01)
And the reality is that I think that what's happening here is that in their lust for growth, Anthropic has done a very poor job at stopping distillation. I mean, they're saying that distillation is occurring at industrial scale. Okay, if it's industrial scale, it must be pretty obvious to see.

**Jason Calacanis** (6:21)
Yeah, the way it's happening is waves of accounts being created by students rolled up and sold on the dark web, you know, in those kind of channels. So you got people in Manila, in the Philippines, I understand, and India, signing up for all those accounts and then sending them to the dark web and selling them using IP addresses from America. Yeah, so that's how it occurs.

**David Sacks** (6:41)
But the more industrial scale it is, the more obvious it is to see. And Chamath has been saying for a while, why don't you KYC your customers? Well, they know that if they KYC their customers, it'll slow their growth. So instead, what they're saying is, hey, ban our competitors. Well, that's ridiculous. I mean, they're in the best position to stop the distillation. I think that they're negligent about doing that. Or I mean, if they really think it's that big a threat, they should use a few points of their 90% gross margins to do that. What you don't do is then say that American developers cannot use everything that's in the public domain.
So it seems to me that this debate is all backwards, that the question should be on Anthropic to explain why it's doing such a bad job, not on the whole American open source ecosystem to be punished for Anthropic's failure.

**Jason Calacanis** (7:34)
All right, Friedberg, I have a really good question for you, but before we do that, Chamath, can you give me maybe a little bit of what you're hearing on your sales calls for 80, 90? You're talking to enterprises, they're hearing all these reports, whether it's you, Dario, this pod, other places talking about, hey, open source is ready, this is the moment, get control, AI sovereignty, et cetera.
They must be calling you up and saying, hey, okay, we're ready. How do we get these things on-prem? How do we do it? So what's happening on those calls you're doing with the enterprise? And then can you maybe give people an idea of what distillation is and why it's so important here?

**Chamath Palihapitiya** (8:13)
Let's start with the second thing. Distillation is when you fire up a model and you ask it a question, and you observe it, and you take its output, and you use that in training of your own model. Now multiply that behavior by tens of millions, and what you exfiltrate is essentially trillions of questions and answers.
And Sacks is right. If you really care about distillation, you implement KYC. You force people to make an account, not just with a username and a password, but with some form of identification, maybe with a bounded credit card. There's all kinds of steps that you can take that would frankly slow things down in terms of revenue traction, but would solve the distillation problem on its face.
So that isn't really a thing. It's a bit of a red herring. The other thing on distillation is everybody has at some point distilled. The question is, who is distilling from whom? And it looks like that funny meme where there's like nine Spider-Men all pointing at each other. That's what this is. Because Anthropic has distilled from all of these publishers. They just pay a $1.5 billion fine. Apparently, OpenAI distilled from the New York Times. There's still an ongoing lawsuit. The Chinese labs have distilled from Anthropic.

**Jason Calacanis** (9:46)
It's wholesale stealing everywhere. Yeah.

**Chamath Palihapitiya** (9:48)
Well, I don't want to call it stealing because it's not clear who actually owns the copyright in the first place. But here should be the important observation.
These models are getting commoditized much faster than anybody thought.
And how do we know this? Because there is no meaningful sustained advantage once a model publishes their performance criteria. What you see is literally within weeks, other models, some open, some closed, some open weight, who are able to match and in some cases exceed the performance. So I think what's happening here is a handful of American companies have realized, whoa, this value that we are seeing today may not be sustainable in a five and 10 year period. And when you go and present a business model to Wall Street, you need to have that certainty, otherwise it impacts your valuation. And so I think a lot of what's happening right now, Jason, is a valuation preservation game by the closed frontier labs. Because if you actually understood how commoditized these things are becoming and the velocity at which it's happening, you see that the real business model is not in the foundational model anymore. It's at the application layer above and it's in the infrastructure below, whether that's the cloud or whether that's chips. And so I think in the absence of regulatory intervention, and in the absence of the United States government stepping in to put their thumb on the scale, what will happen is that as people learn about how value is changing, they're going to put more value in the application layer and more value in the infrastructure layer. That is bad for closed frontier labs, especially when they're mispriced 25 to 50x, the open alternative. And so this is an attempt to stop a competitor that is of the same quality, but just much cheaper. Now there's another important thing here, which is if the United States government intervenes, it will tank the stock market. Okay. Period. Not debatable. Now you can debate which companies get tanked. And we can probably play that scenario out. But for example, if they said no more open source, American companies cannot use open source. Okay. Let's just take at it from a stock perspective. Let's take an average normal company, Coca-Cola.
Hey, Coca-Cola, you're trying to use AI to improve your business. You know what? You can only use these two options, and those things cost 50 to 100 times more than your other best alternative that you may use otherwise.
That will eventually show up in your costs because AI is supposed to be this incredible thing that just kind of solves every problem and does everything for you. And so this incredibly important input into your cost model is now orders of magnitude, multiples greater than your competitors that are outside the United States, simply because you're in the United States. So what would the capital markets do? They're going to say, wow, you have a crazy cost structure. This doesn't make sense. You're forced to absorb costs that aren't rational nor market driven. So then Coca-Cola has to get re-rated. But then you look at the people who are selling those tokens, and this is where Anthropic and OpenAI need to understand. If the government comes in and actually tells you that there's no open source, their valuation will crater. Why? Because all of that revenue is artificially being propped up. It's not being driven by market demand where you're being forced to compete. It's because of regulatory capture where you now get an artificial constraint, but it only works in one market.
Anyways, all roads lead to market chaos if anybody gets involved, so we should just not get involved.

**David Sacks** (13:38)
What it sounds like is you're saying that American enterprises will pay a token tax if the government gives Anthropic and OpenAI a government-enforced duopoly, and enterprises are no longer free to use open source like the rest of the world.

**Jason Calacanis** (13:53)
D'osvidana, yes.

**David Sacks** (13:55)
We will put ourselves on an island of overly expensive AI.

**Jason Calacanis** (14:01)
You can have Coca-Cola or Pepsi or Coca-Cola or Pepsi. You have two beverage choices.

**Chamath Palihapitiya** (14:07)
You have two beverage choices, but they cost 50 times more than coke outside of America. This is the point. We already have coke everywhere, so you can buy 50-cent coke or $50 coke. Why would you buy a $50 coke when you can buy 50-cent coke?

**Jason Calacanis** (14:21)
All right, let me get Friedberg in here.

**David Sacks** (14:24)
Okay, I was going to say just one thing on this. This goes back to my point of these proposals to ban open source that are coming from Anthropic. They don't solve the distillation problem. If distillation is a problem, you have to stop it at the source.
In other words, if you want to ban open source in America, the rest of the world will still be using Chinese open models. We want to solve that problem.

**Jason Calacanis** (14:45)
Yes, and that means they'll get the data and they'll get the reinforcement learning, and then we lose the AI race guaranteed. So, Friedberg, let's take it from a Gramm-Allison and level up the discussion here.
It would be quite provocative to ban the Chinese models. How does Xi Jinping respond to that? How does the CCP respond to that? This is a crazy chessboard. It would seem like a pretty escalatory and we'd be going up the ladder. Yeah, Friedberg?

**David Friedberg** (15:12)
Yeah, look, I don't think it's as relevant that the open source model is published by China. I get that there may be security risks, that those can be estimated and addressed. I think on the three things that are worth highlighting on this issue, I'm very much aligned with Sacks and Chamath. I think the three things are really around distillation. I don't think distillation is just about AI.
Distillation is a process whereby you look at the end product that someone else has produced in thinking about and learning about how to engineer your product. It is a common technique that is used across every product category in every industry.
One car maker will look at how the other car maker's car operates and they will use that to help them design a better car. You know, at Google, in the early days, we would submit millions of search queries to Yahoo and Microsoft search engines to see what the result sets were, and we would compare our results against their results as a way of improving our search engine rankings and our algorithm. It was a very common technique. It doesn't mean we were stealing their algorithm. We didn't go into their servers and steal their software. We looked at the output of their software and used that to improve our software.

**Jason Calacanis** (16:22)
It was called benchmarking, right? It was benchmarking.

**David Friedberg** (16:25)
There's been a million terms. Exactly right. And so I don't think that this matters as much. I think the question around copyright infringement or IP infringement...

**Chamath Palihapitiya** (16:33)
That's our second story.

**David Friedberg** (16:34)
Sacks is right. There's a terms of service question here, but that's on the service providers to fix. The terms of service blocking people from doing this if they so chose. But the copyright argument, the IP argument is really bad. Did they steal the software? They didn't steal the software and they just looked at the output. That's not IP infringement, that's not copyright infringement in the classical sense.
I do think from a distillation IP argument perspective, it's the output, not the process that matters. The question is, are they taking copies of copyrighted software and using it or are they looking at the output? I think output, not process of engineering is what you really need to assess here.

**David Sacks** (17:11)
Can I start something, Friedberg, and you can comment on it. I think a lot of people in the, let's say, policy-making community don't understand this distinction, but I think everybody in tech does, and I think it's a big part of why there's a disconnect on this, is there's a huge difference between model weights and outputs.
Right? So the weights are the, it's the file of numbers, it's the numerical parameters in the model. That's the software code. That's the code. That's the code. And if Chinese companies were to steal weights, proprietary weights from Anthropic or OpenAI, that would be theft. That's right. But that's not what we're talking about here because no one's accused that. What we're talking about here is taking model outputs and then trying to learn from them.

**David Friedberg** (17:55)
Using other people's software to learn.

**David Sacks** (17:56)
Yes, and it's exactly the situation you said with like the Google searches or whatever. And here's the thing that's so hypocritical is that OpenAI and Anthropic have both argued that they are free to train on all the world's output regardless of whether the creator wants them to or not.

**David Friedberg** (18:12)
That's right.

**David Sacks** (18:13)
That is their current position. That's like Chamath mentioned in the New York Times lawsuit. The New York Times is suing OpenAI right now for going onto the New York Times website in violation of the New York Times terms of service, scraping all the information and training on it. And OpenAI's argument is, look, we're not sealing anything. We're taking the output of the New York Times and we are deriving our own model weights. And that is exactly what these Chinese models are doing is they are taking the output of American models and then they're deriving their own weights. They're learning from it.

**Jason Calacanis** (18:46)
Yeah. And so the accusation, though, just so we're clear here, is that there is ethical issues around the industrial scale, covert, breaking of terms of service. That's what the White House has been talking about as well.

**David Sacks** (18:59)
Yeah, 100%.

**Jason Calacanis** (19:00)
So just so people understand, there is a bit of recognition of that in this.

**David Sacks** (19:03)
Yeah, yeah, look, let me be clear that I'm not defending China in this.
In fact, look at my bona fides. I was the first administration official to even talk about distillation. I did it in January of 2025 when Deepsea came out. I went on Laura Ingraham, and I think I was probably the first person in the government to even explain this concept publicly to people. And moreover, I was a co-author of the Winning of the AI Race report, in which the whole premise of it was that we want to win. We want to beat China. So, I'm definitely not someone in this camp that doesn't want the US to win. I want the US to win. The question is how?
And if we shoot ourselves in the foot by banning open source, which is to say, not letting all of our American companies take advantage of open source, when the rest of the world is able to, then that is a huge problem. Now, I'm fine with Anthropic and OpenAI enforcing their terms of service. They need to do a better job, stop the distillation from occurring in the first place. If there are things that the government can do to help them, okay, but I'm not sure what those things are. What needs to happen is those companies need to do a better job enforcing their terms of service. Yes, that's right.

**Jason Calacanis** (20:10)
Now, Friedberg, I think you said you had three points you made. I think you made one. I want to get the other two out of you.

**David Friedberg** (20:15)
Yeah. So the other one was just on the free speech argument, which is, look, what is an open source model? And I think the audience needs to understand this if you're not from the software industry, that open source is a downloadable package of software. You can think about it as downloading a text, a book. You just got all the code. Once you get the code, you've got it on your computer. You don't have to be connected to the Internet. You can just run it and use it.
And I think part of the challenge that's going to be faced here, if there is any attempt at restricting open source, it's going to open a can of worms on how do you actually enforce restrictions on open source, because you're basically telling people once they've downloaded and gotten a copy of this free publicly available software, they're not allowed to use it.
And that becomes a real challenge. I don't think we have a lot of great precedent for that. It's going to be very ugly to try and stop open source. I do think there's a question on like copyright action. But if there is, there's a legal due process to go through to make that case and stop that open source from being available. And then my third point is just open source is better for the world.
To Chamath's point, this is 100 times cheaper. That is better for the industry, for enterprise. The beneficiaries are going to be the economy, the consumer.
Fundamentally, if you look back on the Internet, in the early days, Netscape made a proprietary browser and a proprietary server software, the Netscape software. And they went public and they were the first to do this. And it was super valuable and profitable. That company ended up getting crushed because of open source. The Mozilla Foundation was formed to create an open-source web browser called Firefox. And then Google ended up hiring everyone and made it Chrome, but it was still open-source. The Apache Foundation set up the first HTTP server as an open-source product, rather than having to pay Netscape or Microsoft or Oracle for their server software. Anyone with a computer could download the Apache software and make a web server and be on the Internet and create a website. And what ended up happening is the value accrued to the Internet. It didn't accrue to the small number of software providers that controlled the gate and the portal of the Internet. Basically, everything got open-source and Google took off and eBay took off and Etsy and Amazon and all the millions of small websites and all the millions of small businesses and everyone that benefited from an openly accessible, open-sourced Internet. If the Internet was closed and there was proprietary software gates and portals throughout the Internet that everyone had to pay to get through, the Internet would not have taken off and the economy wouldn't have grown.

**David Sacks** (22:42)
We had that Friedberg.

**Jason Calacanis** (22:43)
It was called AOL and CopyServe.

**David Friedberg** (22:45)
Like, literally, we had that. And now, when we look at this analogy, the analogy here is if open-source AI takes off, then all the worries that Bernie Sanders and Elizabeth Warren and all the socialists are harping and larking about are not going to be the case anymore because you're not going to see all the value of AI accrue to two or three or four companies and their small group of billionaire shareholders. What will happen is AI proliferates and a million AI-integrated enterprises all over the world will benefit. Everyone will benefit, the economy will grow, jobs will be created, and AI becomes a power for good for creating an open economy. So I know that some people that are listening to this in the government and that are on the other side are going to say, but Chinese open-source versus American open-source, let it all proliferate. And frankly, if the Chinese are violating copyrights, if they are violating stealing software, go after them for that, put in place trade sanctions, do all the sh** you can do to stop that from happening. But fundamentally, open-source AI will transform the global economy and it will ensure that the economic value of AI will diffuse to everyone and not be held captive by a small number of control.

**Jason Calacanis** (23:52)
This is why the 1% that controls open-source, if they have it, that the oligarchs are going to get, the clock's wrong and we don't need to have a wealth tax. Chamathi, we're going to add to this.

**Chamath Palihapitiya** (24:03)
We have to acknowledge that it's incredible how fast the value capture at this segment of the market has basically evaporated. I've never seen it in my 25 years in Silicon Valley where a sector of the economy can absorb hundreds and hundreds of billions of dollars.
And then you think that there's going to be economic pricing power many decades into the future. And it effectively evaporates in months. Months.

**David Friedberg** (24:34)
It took off in months. Remember?

**David Sacks** (24:35)
Remember how big Anthropic was?

**Chamath Palihapitiya** (24:36)
It took off in months and it's evaporated in months.

**David Sacks** (24:38)
No, I got it. This is an area where I disagree with you guys.

**Jason Calacanis** (24:40)
Evaporate is a strong term. It does look like it could slow down or it could plateau.

**Chamath Palihapitiya** (24:48)
Go ahead, Sacks. Make your argument and I'll give you my argument.

**Jason Calacanis** (24:50)
Yeah, but let me pull up the Anthropic revenue chart before you go there, Sacks, because this will help mitigate it here and educate the audience. As you can see here, we got a little bit of a stall in Anthropics revenue in the last couple of months.
This is third party tracking, so it's not perfect data, but we do see that this is a clear headwind. Then, do you have the second chart I had? I talked on the pod just last week or the week before when we're having the discussion about open source and I think it was Brad Gerstner from Altimeter was talking about, hey, tokens are still growing. Well, there are routers that track open router. The better an open source model does and the easier it is to implement on your own servers and take it in house, et cetera, those are dark tokens. They're not recorded. You're not going to see them show up on a revenue chart anywhere because they're free, essentially. You just need to have servers and energy to do them. And here you see that now well over 50%, and a lot of these are coming from Chinese.

**Chamath Palihapitiya** (25:53)
By the way, Sacks, I want to be clear before you give the counter. I'm not saying that these companies won't make money. That's not what I'm saying.
But what I am saying is that markets are very savvy in looking through current earnings and asking a very specific question, which is what does this revenue look like 10 years from now? Does it go up? Does it go down? Is there more competition or is there less competition? Is it effectively monopolistic or is it more of a commodity? If it's a commodity, how many people can price this good? At what price is the market clearing price of that good in 10 years? All I'm saying is normally those variables get exposed, those cards get turned over relatively slowly.
You have five, 10-year cycles to transition from being an exclusive provider of a good to effectively a commodity provider of a good. And all I'm observing is it's so unique that only technology could create a market where that cycle could get compressed into a few years, because it is very hard if you're an allocator of money to sit there and look at this data and not wonder to yourself why it's not a commodity in five to seven to 10 years. And when they get to that conclusion, which every capital allocator will, because it will be pretty negligent to not, it's very hard to assign huge future premiums. And where the real money is going, by the way, and we saw it in Google's earnings, which I'm sure we'll talk about, it's going to the cloud, it's going to the infrastructure. So by the way, there's another cohort of people that don't want to see the end of open source, because they want to serve the cheapest models possible because they know that's where all the margin capture is.

**Jason Calacanis** (27:37)
What's your, where's this going, Sacks? Is it both open, we're gonna just see a proliferation? I mean, as far as I'm concerned, there is an unlimited appetite for on-demand intelligence, and there's going to be, I don't think there's an upper bound for how much intelligence you can tap, as long as it continues to get better, which then the thesis would be, yeah, it's a commodity, and the prices keep going down, but consumption keeps going up. What's your thoughts on?

**Chamath Palihapitiya** (28:01)
You have to assume that this is exactly the example that you guys used. It's a web browser.
And in a web browser, it's a mechanism to get to a place. And so the apps that are actually the places are where the value is captured. And I think if you assume for a second that intelligence becomes completely ubiquitous, it's widely available, the marginal cost of it is effectively zero, the energy to generate it is effectively zero, which I think is an accurate assumption, it's very hard to make the case of why this isn't like the browser.

**Jason Calacanis** (28:35)
And it becomes, just gets subsumed into the Amazon Web Services, cloud businesses, Elon's Web Service, etc. Sacks, where do you think this is going? And then we're going to go to our second story, which is the IP story. Third story is going to be the markets and Google, specifically in Tesla and SpaceX.

**David Sacks** (28:49)
Look, there's been a lot of violent agreement on this show so far. So let me just make the counter argument. I think that both open source and closed source will be big winners in this. I think the market is huge and they each serve their purpose. What happened is with the introduction of Kimi K3, there's a little bit of a panic in which everybody said, oh my God, all the Chinese models have caught up and they're giving them away for free, and they're going to destroy our leading American frontier labs.
Anthropic and OpenAI are running around saying, listen, we can't continue to invest billions of dollars if Chinese companies can just steal our weights. So that's the argument that they're making that government officials are responding to. The truth of the matter is that, when Kimi K3 first launched, I was concerned about it because I was like, oh, has China caught up? Are they now able to produce a much cheaper frontier model? Then the details started coming out. So Ben Thompson on his blog went through some of the cost numbers, and it turns out that Kimi K3 is not that much cheaper to run. There's not a significant cost advantage to it. So that's point number one.
Point number two is that China has not caught up. It's true that Kimi K3 scored really well on the arena battleground for front-end coding for web development, but that's just one test. That's just one dimension. There are areas where it scores really well, but there's lots of other areas where it doesn't score that well. So it is not a clear advance or a clear catch up to the leading American models. Moreover, you still have stuff in the labs by Anthropic and OpenAI that is way ahead of this. And the reports are that Sam is going to Washington over the next week to go talk about GPT 6.0, which is blowing the doors off. So I don't believe that China has really caught up. I think there's...

**Jason Calacanis** (30:38)
Sam's going to go see daddy? And what is he going to ask for?

**David Sacks** (30:40)
I think there's incredible unreleased models in the pipeline, and we need to let our horses run here and not slow them down with a bunch of unnecessary hoops. And if we do that, I think we're going to be just fine. I don't believe that China has caught up. I still think we are six months ahead. And then just the final point on this, if you look at revenue, which is the test of real usage in the real world, Anthropic and OpenAI are blowing the doors off. They are by far the fastest growing tech companies at scale that we've ever seen. Jason, you showed this chart that supposedly shows a hiccup in Anthropic. Listen, their internal forecast was to 10x this year from 10 to 100 We're in the middle of the year, they're already over 70 billion of ARR. They're easily going to get to 100 billion. We don't really know what this little blip is here. I think one thing it might be is that OpenAI, if you superimpose the OpenAI chart on this, they have re-accelerated over the past month.
I think that if you were to add OpenAI-

**Chamath Palihapitiya** (31:40)
Codex is excellent.

**David Sacks** (31:41)
Codex is excellent and I think they're taking a little bit of share. Sam is out there tweeting that we've got our mojo back.
They're taking their forecasts up. I think they were expecting to end the year at $60 billion of ARR. I think they're forecasting more like $75 billion of exit ARR. My guess is that if you were to superimpose OpenAI and Anthropic and looked at them together, and you were basically just to say that, let's call it the frontier model duopoly in the US, you do not see any slowdown, you do not see any blip. They're taking their forecasts up. The reality is that if distillation is going on, it's been a thing for, again, I pointed it out back in January of 2025 with DeepSeat. It's been a thing this entire time that they've been growing exponentially.
I just don't believe that these guys are actually suffering in any way. I don't think they need government protection. I think they're growing exponentially. Still, this is a little bit of a case of, what do you call it in basketball when a player flops? You're flopping, yeah. You try to draw a foul. A foul flop or whatever.

**Jason Calacanis** (32:42)
Yeah, it's a flop.

**David Sacks** (32:44)
Well, or you basically act super dramatic after a foul in order to draw the charge.

**Jason Calacanis** (32:49)
You're foul baiting when you're trying to get a foul and then you're flopping, which is just making like an exaggeration like LeBron does.

**David Sacks** (32:55)
Yes, it's a LeBron.
It's a flair flop where these guys are trying to draw the foul. They're trying to get the government to intervene. Now, why are they doing this? Because they're in the middle of road shows right now. Chamath, to your point, I do think they get the legitimate question about, why won't you be commoditized over time by open source? By far, the best response to that would be that if they can lure the government into giving them a government-protected duopoly, then that would be incredible.

**Chamath Palihapitiya** (33:24)
The best answer is what you gave. And Anthropic and OpenAI should own this because they're good at it, which is they're going to go up the stack to the application layer.

**David Sacks** (33:34)
Well, they already have.

**Chamath Palihapitiya** (33:35)
They've done it. I know, but they've done it in this way, which is a little ham-handed in some cases.
But they're excellent at it. These end-user apps are really good and they should just own that. And that should be their answer to Wall Street, which is, guys, we have the best model. We will eventually go up the stack. And if I were them, I'd actually practice the following answer. There may be a version of a model that I don't release and just keep for myself and I'll just use in my own applications. How about that?

**Jason Calacanis** (34:00)
Well, that would be super anti-competitive.

**Chamath Palihapitiya** (34:04)
No, it's not. They're allowed to build a model and not release it and use it for themselves.

**Jason Calacanis** (34:08)
Hold on. Let me answer that.
It would be anti-competitive in the eyes of their customers. It might not be in the governments, but if you are using them as a customer and you're lovable, which I talked to, and they're paying a ton of money for your 11 labs and you're paying them a ton of money and they say, hey, we got our latest and greatest. You can't use it because we're going to compete with your company. They would stop using it and they go to open source. I'll tell you why, Sacks, I think you're wrong on this issue. I think open source is having its moment. I work with startups. They are all moving off of these and they're using open source and using it at much cheaper rates because a lot of the jobs don't need the latest models. They can use the last generation's models and people are moving them local. They're hosting them themselves. This is, I think, a non-zero chance that this is going to derail Anthropic and OpenAI's IPOs and their midterm future.

**David Sacks** (34:59)
No, they're going to be fine. They're going to be fine. I don't believe you're following. No, no, no, hold on.

**Jason Calacanis** (35:03)
Let me finish, guys. I'm making my point. Shut the up for 30 seconds.
I believe that this is going to derail their IPOs. I'm taking it from the top. It's going to derail their IPOs. It's going to be headwinds against it because I think that they're going to have massive margin compression. I believe they're spending so much money that I think they're going to get caught in a trap. I think this could be a trap for them. They overspend. They don't have the same profitability and it doesn't pencil out. And startups are the future. The startups are what eventually the enterprise copies. I think you're wrong. Sacks, go ahead.

**David Sacks** (35:39)
Well, I'll come back, but let Chamath respond because he's raising his hand.

**Chamath Palihapitiya** (35:42)
You're wrong. You're totally wrong.

**David Sacks** (35:44)
I think you're wrong, Sacks.

**Jason Calacanis** (35:46)
I think they have caught up for 95% of the jobs. This is a crazy habit. I'm not saying that the IPOs are off, but I think that their market caps and the headwinds are coming. It's a non-zero chance that they're going to get slowed down.

**Chamath Palihapitiya** (35:58)
I think the answer is slightly different. It's not that 95% of the bleeding edge tasks can be done by everybody. It's that 95% of the tasks can be done by many different models. That's the actual answer, and that's okay.

**David Friedberg** (36:11)
That's exactly right, Chamath. I agree.

**Chamath Palihapitiya** (36:13)
It's also okay for Anthropic to say, you know what, I have this next generation class of model. I'm going to instantiate, I don't know, a life sciences program, a cybersecurity business. That's where they can capture, as Sacks was saying before, over time, trillions and trillions of enterprise value, because I do think they have excellent models and they have excellent engineers and they have momentum. But if you're going to build a business model that tries to ascribe this layer as having a lot of terminal value, I think that that is a mathematical mistake.
That's it, you can't do it.

**Jason Calacanis** (36:46)
Open source can be a headwind to these companies specifically because all of their best customers, and I talk to them, whether it's Loveable or 11 Labs or the startups that were spending hundreds of thousands of dollars with them every quarter just last six months ago, they have all moved en masse, GLM 5.2, making their own models.
The cat's out of the bag. They are going to start losing a lot of customers to open source, and Google and AWS and Elon Web Services are going to host them. And how do I know this? Every time I do a job, I'm using perplexity computer, not a paid partnership or anything. It just happens to be the best harness that I found. And I start with Grok, Nemotron, GLM 5.2, and I also put it into Claude, and the results are as good or better. In other words, I can't even tell the difference between these.

**David Sacks** (37:37)
Let's superimpose the OpenAI numbers on top of the Anthropic numbers, because I think it supports the point I'm trying to make here.

**Jason Calacanis** (37:42)
Yeah, and these are estimates, by the way. This is not like literally from the companies. Just want to make sure people know.

**David Sacks** (37:47)
According to this company that, I mean, look, who knows how they drive this? We don't know that they're totally true.
They're basically showing that OpenAI's run rate, which is ARR, it rose from 33 billion in May to 41.3 billion in July. So they're seeing acceleration. Like I said, I mean, Sam is out there saying they got their mojo back. They're going to have their best 12 months forward looking ever.
And look, Anthropic is still growing really fast. We've talked about this on a previous show. It's not physically possible to grow 10X year over year forever. You'll run out of compute, you'll run out of energy, you'll run out of everything. People. Yeah, there's just no way. To do things. But Anthropic, I mean, look, if anybody had said, if anybody had said Anthropic would be at over $70 billion in the midpoint of the year, back in January they're at $10 billion. Nobody would have said it. You would have said, this is the fastest growing tech company of all time. The idea that they're at risk of getting their entire franchise destroyed, it's not in the data yet, is what I'm trying to say. Moreover, Chamath, to your point, it's not only about the model, it's also about the harness, it's about the connectors, it's about the enterprise agreements. There's a lot of things here that you need in order to grow a business like this.
This idea that they need to race to get government protection because of a competitive risk that might happen in the future, I think is just unseemly and gross. This is literally the most successful tech company of all time, and they're racing to the government to basically say, you need to protect us against our competitors. Not just our Chinese competitors, our American competitors.

**Chamath Palihapitiya** (39:27)
Our potential future competitors.

**Jason Calacanis** (39:28)
Yeah, they should hire Lina Khan. Okay.

**David Sacks** (39:30)
Frankly, it's gross. And let me give a couple of examples because I know people don't have a lot of sympathy for Chinese companies. That's fine. I'm not defending Chinese companies. I'm defending American developers who need to be able to use everything in the public domain. And let me give you an example.
Mura Moradi, her new model.

**Jason Calacanis** (39:45)
Thinking machines.

**David Sacks** (39:46)
Thinking machines. They currently have the best American open source model. You know how it was trained? It was bootstrapped. It was distilled off a Chinese model, KimiK2.5. Now, if you say that Chinese model is based on IP theft, what is Thinky?
It's a derivative work off a model that Anthropic is trying to taint as being IP. By the way, there's been no evidence of this. There's no evidentiary process. They are simply trying to paint with a very broad brush here and say that now that model is tainted. Let me give you another example. So Cursor rolled out its new product Composer 2
They were able to post-train that model using KimiK2.5 on their own proprietary coding data. Okay, so think about this. They started with a Chinese open-source model and then they used their own data and they came up with a new derivative product. This is the way that open-source works. You take things that are in the public domain, you fork them, you make them your own. And by the way, once it's in the public domain, it's not a Chinese model anymore. It is open weights that are freely available to anyone. It's a file, okay? And you take that, you fork it, you run it on your own hardware in an American data center. No packets are going back to China.
No data is going back to China. Nothing is going back to China. An American company has taken open-source contributions in the public domain, made it their own, and then developed their own model. And if you say that American companies can't do that, or that somehow it's tainted with IP theft, you are basically going to put a dagger through the heart of the entire American open-source ecosystem. And that is exactly what Anthropic wants because they do not want to have the competition.

**Jason Calacanis** (41:31)
Friedberg, maybe you can close this out here, and then I'll put my final-

**David Friedberg** (41:36)
I'll just zoom out for a second, and I'll say-
Think about the strategy as well for China. If you think about the global economy of the last 50 years, the US has accrued so much value by being at the core of the knowledge economy and effectively a services economy. And in that sense, through the development of intellectual property of IP, of knowledge, and then the conversion of one bit to another bit, we've been able to drive trillions of dollars in GDP.
Meanwhile, we outsourced manufacturing and created a sleeping giant in China, where they have this incredible manufacturing capacity. And at the end of the day, if you think about the course of like human technology evolution and human prosperity, it's largely driven by our capacity to convert molecules from one form to another, and use the least amount of energy possible to do that. All of technology ultimately leads to that simple equation, molecule conversion, making that beautiful couch behind you at the lowest cost possible, making materials, making semiconductors, making all this stuff. Everything in our world is driven by molecule conversion. So at the end of the day, if the knowledge economy and the services economy gets compressed, much like AI and open-source AI in particular effectively flattens that value, because all of that value is now open source, it's free, and it's simply a function of turning on a switch and running it. The value of the US and the Western economy has been largely degraded. And what's left is the value of the molecule economy, the ability to convert molecules and use energy to do that. When you look at the juxtaposition of China versus the United States today, we have one terawatt of electricity production capacity in the US, and they're on their way to having eight.
We have about 10 billion square feet of manufacturing capacity. They have 200 billion square feet of manufacturing capacity. So they have 20x the manufacturing capacity, 8x the electricity production, plus all of their other sources of energy. And I think that's the long game for China over a decade, two, three decade process, is by compressing the knowledge economy and the services economy, commoditizing it completely, they are left holding all the value in the global economy because they can make stuff and they can make it cheaper than anyone because they have the most electricity production. That's a very simple rubric for kind of how I look at the long game that they're trying to play here.

**Jason Calacanis** (44:09)
You believe they're trying to commoditize this very important space, just like they did for cables and cars, etc.

**David Friedberg** (44:16)
Global knowledge and global services, the creation and movement of bits gets commoditized and what's leftover is the creation of electricity and the creation of molecules, both of which they have this very difficult to surmount advantage that's going to make them the core dependency for the world. That's what I think is kind of the long game here.

**Jason Calacanis** (44:36)
And just so you know, this data comes from reports in places like the information or other sources or leak numbers, and they try to just make charts based on it.

**David Sacks** (44:48)
Yeah. And by the way, I have my own sources too. I've talked to investors in these companies and I'm just telling you that both Anthropic and OpenAI are taking their estimates up right now.
Their forecasts up. So I mean, look, I think in the future, it may be the case that open source takes share. Fine, it's because the market's so big. And there is always a market for open because open is more controllable, it's more customizable. You can own it. You get the data sovereignty. You get the sovereignty, but it's also more work.
So there are different use cases. There's different parts of the market.

**Jason Calacanis** (45:21)
That's actually very interesting. The more work part, there, Sacks, is super interesting. Like three to six months ago, it was so much work to stand these up.
And now there's so many intermediaries building the harnesses that default to it, that that is getting worked out. But that has always been the issue with open source for sure, is the amount of work it takes to implement. If you do want to implement this inside of your organization, please make a call to 8090 and try the Software Factory. Use the promo code jcal to get a free consultation at 8090

**David Sacks** (45:51)
All right.

**Jason Calacanis** (45:53)
Can they get a free consultation?

**David Sacks** (45:55)
Everyone is talking their books.
Everyone is talking their books, actually, including, I'd say, the Anthropic and OpenAI investors. It's amazing how many of these investors...

**Jason Calacanis** (46:05)
Brad was on this show two weeks ago. Were you on the episode? Brad was like, let me tell you why this is going to...

**David Friedberg** (46:11)
He's holding on.

**Chamath Palihapitiya** (46:12)
He's holding on to those white knuckle...

**Jason Calacanis** (46:17)
He's like, oh.

**David Sacks** (46:18)
I actually give Brad a lot of credit because I do think that he's objective about public policy or as objective as you can be, given that he does own all these companies. But look, let me just tell you that, you know, I see a lot of folks who are suddenly China hawks and saying, we need to stop China. We'd stop.

**Chamath Palihapitiya** (46:34)
Oh, yeah, no, they're China hawks, everybody wants to sell their chips there.

**David Sacks** (46:37)
How about disclosing first whether you're on the cap table of Anthropic?

**Chamath Palihapitiya** (46:41)
Absolutely.

**David Friedberg** (46:42)
Are you guys on any of these cap tables?

**David Sacks** (46:45)
No, I'm not.

**Chamath Palihapitiya** (46:46)
Not directly.

**Jason Calacanis** (46:46)
No, not directly.

**David Sacks** (46:48)
Indirectly, yes.

**Jason Calacanis** (46:49)
Indirectly, maybe a little access. You know what it's like, Chamath? It's like when you got that great flush or straight and you're like, please don't pair the board. Brad's like, don't pair the board. Please don't pair the board.
All right. Here we go.

**David Friedberg** (47:02)
I love open source. I love this open source AI stuff.

**Jason Calacanis** (47:05)
I love it.

**David Friedberg** (47:06)
I think it's so awesome. The value, it's just like there's so much to be done with it. It's just exciting and awesome. Chamath's point is exactly right.
Most of the models can do 95 percent of the tasks. If that's the case, then it's not like everyone needs to scramble to get the best open source model. You just need open source to do 95 percent of what you want to do with AI.
Then the other 5 percent, you get specialized or high value or you pay a premium. By the way, if you're a big enterprise and you need to have wrappers and support and all these other tools for your employees, buy Anthropic or OpenAI or Grox tools or Gemini.

**Jason Calacanis** (47:40)
Just make plenty of options. Make sure you have a good partner. Use the promo code JCal. You get a Zoom call with Chamath. Okay.

**David Friedberg** (47:47)
You get a Zoom call with Chamath.

**Jason Calacanis** (47:49)
You get to have a Zoom call with Chamath and take a selfie with him on Zoom.

**David Sacks** (47:52)
I'm sorry.

**David Friedberg** (47:53)
If anyone is going to sign a $10 million contract with 80, 90, you get to have three of the four of us for a five-minute Zoom call.

**Jason Calacanis** (47:59)
Absolutely.

**David Friedberg** (48:00)
You get to come up.

**David Sacks** (48:01)
We're all going to show up for the Zoom call.

**Jason Calacanis** (48:03)
You get to guest host on the pod.

**David Friedberg** (48:05)
Anyone ready to make a pre-purchase on a million dollars of potato seed, you also get to have the pre-vote on that five-minute Zoom call.

**SPEAKER_5** (48:10)
Use the promo code SACKSYPU.

**David Sacks** (48:13)
Yes.

**Jason Calacanis** (48:13)
If you'd like to guest host, the first person to put a $25 million check into Launch Fund 5, gets to guest moderate an episode with your boy Jay Cal. All right. Promo City this week. All right. Anthropic. Copyrights. Here we go. Anthropic has settled their AI copyright lawsuit for $1.5 billion.
Billy, on Monday, largest copyright settlement Friedberg in the history of the United States of America.
First major AI training lawsuit to settle. There are many more in the pipeline. Anthropic downloaded 7 million books from pirated websites to train Claude. And that alone, it may or may not be a crime. This has been adjudicated a little bit in the courts. They had ruled previously that AI on copyrighted books is legal under fair use, but there's going to be some future cases. So this is a settlement. They didn't go to the bat. Lawyers get an $101 million, authors get $3,000 a book. 500,000 books were covered in it. Thus far, 91% of the covered authors have claimed their share. Tons of other ones are on the way.
And here's your second Victory Fast. Of the episode. Content providers as a group. Need to get together and fight for their rights in unison. New York Times, Medicare.

**David Sacks** (49:33)
Fight for their right to party.

**David Friedberg** (49:34)
No, fight for the right to get paid and to survive.

**Jason Calacanis** (49:37)
I'll tell you what to do, chat to ABT and say, as a group... Either give us these terms or don't index us. They are interfering with their ability to leverage their own content. It is profoundly unfair. And those magazines and newspapers need to... What's up?
What's that? It's possible. YouTube is a great example. That's what's going to happen here. There'll be a settlement where they are going to be able to claim their content.

**David Friedberg** (50:01)
I will bet any amount against your premonition here, J Cal.

**Chamath Palihapitiya** (50:06)
This is like the opposite of Northrop's office.

**Jason Calacanis** (50:08)
I am going to go with, for my biggest winner, now 2024 training data owners like the New York Times, Reddit, X, Twitter, YouTube, et cetera. I think what we learned in 2023 was that the language models are starting to hit parity very quickly and that the real value is going to be in, and it may even become commodities and open source may win the day. Then I think the winner is folks who have the training data.

**Chamath Palihapitiya** (50:34)
You know the best thing about this is watching Jason's reaction to Jason. I just love it.

**Jason Calacanis** (50:39)
Did you do a picture of me? Just be like, oh, go, J Cal.
Friedberg, did we make a bet here? Did we make a bet?

**Chamath Palihapitiya** (50:45)
I don't know.

**Jason Calacanis** (50:46)
He's gone.

**David Sacks** (50:47)
Well, actually, this settlement, I don't think quite proves exactly what you want it to prove, J Cal.

**SPEAKER_5** (50:55)
Good.

**David Sacks** (50:57)
Can I make a nuance here?

**Jason Calacanis** (50:59)
Of course.

**David Sacks** (51:00)
Okay, look, obviously, I'm not a huge fan of Anthropics. I think they're potentially destroying the whole ecosystem for their own purposes of regulatory capture. But let's just be very clear about what- Let's just be very clear about-

**Jason Calacanis** (51:12)
Come on the show any time, Darya.

**David Sacks** (51:13)
Yeah. Let's just be very clear about what this judgment was and was not. So what Anthropic did is they pirated all these books from LibGen, and they trained on them. And the reason why they got in trouble is because they basically took stolen books. They didn't even pay for one copy of them. But if they had paid for just one copy of each book, they could not have been nailed for piracy.
They would have been potentially under fair use, which I understand JCal is still being litigated in the courts, but that would have been their defense. So the reason why they got nailed with this $1.5 billion judgment is they wouldn't even buy one copy. It is still Anthropic's position, and it's OpenAI's position, that they should be able to train on all these books under fair use if they buy one copy. And that issue has not been resolved yet. Now, you should be able to see the total hypocrisy of their point of view relative to the previous issue, which is they believe they should be able to train on every creator's output in the world, you know, as long as I guess they bought one copy of it, against the will of those creators, whether those creators like it or not. They believe it is fair use to train their models and derive their own weights based on fair use. However, they say that the one type of content that you should never be able to train on is their output. That is currently their position is completely hypocritical. And actually, if you go back to Anthropics blog post in February, where they defined this concept of industrial scale distillation attacks for the first time, they coined that expression. And this is, you know, I worry that people in the government policy makers don't understand that this is all part of a Anthropic op. No one used the terms distillation and attack together until Anthropic wrote that blog post. Distillation was simply an industry standard practice. But then Anthropic coined this idea of industrial scale distillation attacks. In any event, if you go to that blog post, search for the words IP theft. It's not in there. Anthropic did not claim, even though they were trying to coin this new concept and brand this idea of industrial scale distillation attacks, they did not have the chutzpah to claim that it was IP theft.
The cojones, the hypocrisy, the chutzpah to claim that it was IP theft. Why?
Because they maintain that it is their right to train their models on all the world's output, even if the creators don't want them to.

**Jason Calacanis** (53:46)
IP for we, but not for the.

**David Sacks** (53:48)
Exactly. So, so Jake, I don't even want to get into whether you're right or not on the fair use question. Maybe you are right. I don't know. Okay. But my point is about the hypocrisy. And they themselves never claimed that this was IP theft by the Chinese companies. What they tried to claim was that it was a national security threat, because what would happen is these Chinese companies would distill off them, create their own models, and those models would not have guardrails. So they were making a different kind of argument.
That argument, though, never found purchase with policy makers, because I think that they could see that, yeah, look, guardrails are important, but it never really found purchase until Anthropic started claiming, oh, this is IP theft. But they have not been willing to make that argument publicly, because they know that it would poison all of their fur use lawsuits that are happening. And Chamath, like you mentioned, the New York Times is currently suing OpenAI for basically an industrial-scale distillation attack. I mean, OpenAI went on the New York Times website, used scrapers, slurped up all of their information at a scale that no human could achieve, and then they used that as training data and reverse-engineered the model weights effectively.
So my point is that even Anthropic and OpenAI won't publicly admit that what China is doing is IP theft, because they are doing it themselves. It's totally hypocritical, and I don't think policy makers should be making arguments that these companies themselves won't make, because they know that they will lose all these court cases.

**Jason Calacanis** (55:22)
Friedberg, any thoughts here on, and obviously this is still being litigated, as we've discussed, as 150 major cases. New York Times is one of the music industry.

**David Friedberg** (55:32)
Let me ask you a question, JK. Let's say you wrote a book.

**David Sacks** (55:34)
You have a question for me?

**David Friedberg** (55:35)
Let's say your book, your book, I don't know, let's call it Genuflecting the Novel, the Great American Novel.

**David Sacks** (55:39)
It could be Angel in 11 different languages.

**David Friedberg** (55:43)
So you write this book, Thank you, HarperCollins. and you opt to not submit it to AI, because there's a restrict, you keep it closed. No one can read your book.

**Jason Calacanis** (55:52)
Like we did for Google search, you can't be on Google search.

**David Friedberg** (55:54)
No one can read your book, you're not letting anyone read your book. You want to pay for your book if you want to read it. Ten bucks. Someone pays $30 for Genuflect the Great American Novel, and they read it, and then they write a review. They publish their review on the Internet. Now, on the Internet, the review where it talks about your book and describes your book gets web crawled by an AI engine, and the AI engine learns from that, learns about your book, and now there's some commentary made about your book when someone asks a question about your book in the AI engine. Do you feel like your copyright was violated in that sense?
The AI never ingested your book, it ingested metadata about your book, it ingested reviews about your book, it ingested third-party analysis about your book, all of which was on the open internet, and it didn't just copy that stuff, but it used it to learn about your book.

**Jason Calacanis** (56:41)
So you're saying these 1,500 reviews for Angel, How to Invest in Technology, Starters, Timeless Advice from an Angel Investor, Turned 100,000 into 100 million, these reviews would then be the basis of the AI. So I guess I would have to be okay, but this like, you know, this eloquently brash blueprint for Angel Investing, that verified review.
Yes, I would be fine with that five star review being in there.

**David Sacks** (57:04)
These one and two star reviews, I don't want to.

**David Friedberg** (57:06)
But you now have no knowledge, you now have no knowledge of the process.

**David Sacks** (57:08)
Did you plan that five star review, Jake Howell? Did Jake Howell plan that?

**David Friedberg** (57:10)
Jake Howell, how many of those 1,498 reviews did you not write, three?

**Jason Calacanis** (57:15)
Yeah, actually, I'll tell you the secret, when you guys actually get asked to write a book or any of you have the capability of completing a book.

**David Friedberg** (57:21)
Yeah, cause I'm 97 years old, living in the 19th century.

**David Sacks** (57:24)
What AI agent did you use? What bot did you suppose that?

**Chamath Palihapitiya** (57:29)
Now we know where he pointed that stupid open source AI slop cannon that he's building.

**Jason Calacanis** (57:36)
I verified the purchase too. Friedberg, you make a great point. Oh, there it is, Jennifer, great American novel, practical wisdom for mastering ambition, building resilience and winning at life, work, innovation.

**David Sacks** (57:50)
That's a master virtue signaling.

**David Friedberg** (57:52)
Yeah, that's a master virtue signaling.

**Jason Calacanis** (57:55)
Incredible.

**David Sacks** (57:56)
That's beautiful. That is beautiful.

**David Friedberg** (57:57)
But J Cal, this is my point. Knowledge can't be contained, it's diffuse.
The form of copyright is very clear, the case law and copyright is very clear. I cannot lift text out of your book, reprint it and claim it as my own. That is a violation of copyright. But my reading of your book, my reading of the reviews of your book, the diffusion of the knowledge that arises from your book, that is ultimately going to lead to some abstract transformation of knowledge into a new output that someone might read. I think it is very unlikely that we will find ourselves in a place where the idea that knowledge transferred digitally, processed digitally and turned into other content is going to end up violating copyright.

**Jason Calacanis** (58:40)
I understand your position. There are workarounds. Obviously, we've always had cliff notes. If a book became good enough, somebody could write the cliff notes of it. You can't stop that. There's a four-part test for this. We've talked about this for three years here on the pod. What I'd say is, American companies should take 10 percent of their revenue if they're building these models and do splashy-cashy and do settlements, and that's exactly what's happening. If you're a copyright owner, you should study what the music industry does. They are rabid dogs, and they will fight tooth and nail and keep you in the courts until you submit and make a settlement and agree that you're licensing it, and then that gives them that case law and that settlement to go to the next person and the next person and the next person, and that's why they've been able to successfully defend it. And then if you're competing with me, that becomes the issue. So if you said, hey, what's this book about and what do people think about it? What are the best parts of it? And that comes from the reviews, okay, fine, fair enough. The problem is, and I'll share with you, there's been some other lawsuits here that are making the way to their courts.
What's going to be the problem is the application level layer that you talked about, Chamath, as they go into the application layer and they use this, there's a big court case here. Obviously, you know about some of these, but there are now other cases. There are music cases. There's a New York Times case. The one that's kind of interesting is Thompson-Reuters versus Ross. This is a final judgment on AI training copyright.
There's a company called Westlaw. They're like LexisNexis, and people have been trying to claim that they can train on the outputs of something like Westlaw, and when you're in the same business as me, that has a special place in copyright law because you're infringing on my ability to use my copyright, and your argument, I think, Friedberg holds up, that it wouldn't stop somebody from buying the book, but the second you are actually competing with me directly, that's when these things have problems, and that's why I think the music industry is going to win, and some other places are going to win. But listen, this is brand new territory. These lawsuits are brand new territory, and IP law does not actually have the nuance yet. So we're going to as a society have to make a decision here on what is fair. I suggest, just like the self-regulatory group that we talked about last week, all the AI companies should get together, take 10 percent of your revenue, put it in a pool, and keep paying the people and getting permission from them so you can get updates on the content, so you can get the next book, so you get the next New York Times story, the next Reuters story.

**David Sacks** (1:01:11)
10 percent is not going to satisfy the rabid dogs. Let me tell you, they're going to go for 100 percent. Now, Jake, here's a question I want to ask you. Yes, please. Given that the fair use doctrine is not a decided matter yet, given that Anthropic and OpenAI are embroiled in huge lawsuits against very well-financed content creators and those communities and the outcome is indeterminate and there's billions of dollars at stake, maybe even their entire product at stake, do you think that they have potentially made a fatal mistake by arguing that distilling content against the wishes of its creator is IP theft?
Do you see what I'm saying?

**Jason Calacanis** (1:01:52)
Yes.

**David Sacks** (1:01:52)
Like, is this potentially a fatal mistake? See, here's what they could have done.

**Jason Calacanis** (1:01:55)
Well, you would bring that to the Supreme Court and you say, hey, listen, you already said it.

**David Sacks** (1:01:58)
But here's what they could have done. What Anthropic could have done is they could have said, listen, we have these Chinese companies are creating fake accounts and they're using proxies to basically use our product in violation of our terms of service. Now, using those model outputs is not IP theft because it's fair use. However, it's a deceptive business practice for these guys to lie about who they are when they set up accounts at scale. And so they're engaged in a deceptive business practice. And we're going to do everything we can to stop that. But we'd like the government's help in stopping that too. However, we're not saying anything about IP theft.
Would that be the more nuanced approach?

**Jason Calacanis** (1:02:34)
Of course.

**David Sacks** (1:02:35)
Because I think that they're on the verge of being hoisted on their own petard here.

**Jason Calacanis** (1:02:38)
Yeah. I mean, I think kids call it a cell phone, right? Like you basically, it's just a classic cell phone. And in most of these cases, settlements happen. So again, if you just look at the music industry, the newspapers, the magazines and some of those folks and book authors, they tend to be very meek.
There's a new trend happening now, Friedberg. A lot of content providers are saying to Google, take us out of the index because Google has one bot, and that bot does the Google crawl and that bot also does the AI crawl. And what the industry is saying is, hey, split that up. I want to be in Google, but I don't want to be indexed in AI. So people are now saying, hey, we'll take you out of the index, which Rupert Murdoch got right. If all the newspapers said collectively, do not index us, Google, we're no indexed, that would have made Google come to the table and give them a royalty and give them some money for being indexed.

**David Friedberg** (1:03:28)
They did that, dude. There was a deal that happened, but it didn't go the way you're describing.

**Jason Calacanis** (1:03:33)
Well, because they didn't have a united front. Now I think the New York Times learned that.

**David Friedberg** (1:03:36)
They wanted Google's user base, so they ended up doing a deal where they had this paywall exclusion rule, where it was like you could show a certain number of free articles. There was a whole negotiated settlement.

**Jason Calacanis** (1:03:45)
I'm talking even long before that, when the first index happened. But here's, I think we are on the cusp of some type of a settlement getting done here.
And I think that would be good for America to take a leadership position in that. Because you do want to keep getting that. But all of these content companies, they should be meeting with each other, the music industry, the New York Times, all of them to stop their content from getting used without their permission and from competing with them.

**David Sacks** (1:04:13)
That's my- You only get a settlement when both sides can agree. And it seems to me that if you're one of these content creator lobbies, and you see that an Anthropic has just told the government that training on a creator's output without their consent is IP theft, Yeah, they're on your side.
they have now basically confessed to their entire product being stolen. And it seems to me that why wouldn't the content creators now assert that they're entitled to own 100% of Anthropic's revenue? It seems to me that this could be a bridge too far, that they're so good at regulatory capture, they're so good at making these arguments and getting the government involved to create new regulations to protect them. But I wonder if this was just a little bit too cute, and again, if they had just positioned it slightly differently, if they said, look, these Chinese companies are creating fake accounts, that's a deceptive business practice, we're not saying this is IP theft, right? But instead, they said IP theft, and now the whole startup community is activated. You saw that, you know, Gary Tan and 200 startups wrote that letter, why? Because they know that if this IP theft thing sticks, that all derivative works of Chinese models are tainted now, too. So that means the whole startup ecosystem is now at risk.

**Jason Calacanis** (1:05:33)
Yeah.

**David Sacks** (1:05:33)
So I just wonder if these guys have just gone, it's just all a bridge too far.

**Jason Calacanis** (1:05:37)
I mean, if you go to Washington, and you lay down with the dogs, don't be surprised if you wake up with the fleas.
They decided to engage in this, so they may have poked the tiger. I think it's pretty accurate. By the way, the publishing schedule for 2027 was released. We have some new books coming. You heard mine, Genuflecting, coming to you now. Ferrari on My Wrist, How to Win at Life and Afford a $250,000 Watch from David Sacks.

**David Sacks** (1:06:07)
Oh my God.

**Jason Calacanis** (1:06:07)
This is pre-Ozempic, Sacks. We're gonna need to get that done. Here it is, The Fight to Save America, Destroying Socialism, Shrinking the Debt and Winning AI by David Friedberg.

**David Sacks** (1:06:16)
I like that book.

**Jason Calacanis** (1:06:16)
Yeah, it's a pretty good one, I think.

**David Sacks** (1:06:18)
That's a good book, I love that.

**Jason Calacanis** (1:06:18)
By the way, this is our new All-In. Here it is, Chamath Palihapitiya, A Sexual Italian Summer.

**SPEAKER_5** (1:06:25)
It's a romance novel.

**Jason Calacanis** (1:06:27)
This is the only person who decided to do fiction.

**Chamath Palihapitiya** (1:06:29)
This is fiction.

**Jason Calacanis** (1:06:31)
It's fiction, it's fiction, Chamath.

**David Sacks** (1:06:33)
I got Chamath's non-fiction novel also.

**Jason Calacanis** (1:06:35)
Oh, you have his non-fiction as well. Here it is, here it is, Enterprise Sales. Chamath Dystopia, How My Software Startup F***ed My Italian Summer.

**Chamath Palihapitiya** (1:06:45)
It's great, it's great.

**Jason Calacanis** (1:06:47)
Oh my God.

**David Sacks** (1:06:48)
Wow, that's coming from the All-In.

**David Friedberg** (1:06:50)
The IT guy in Milan.

**Jason Calacanis** (1:06:51)
Absolutely.
This is coming from All-In Books. It's our new publishing label coming in 2027 We'll also have the Brad Gerstner, Bill Gurley, Elon Musk and other titles coming, so we'll have those on future episodes. More titles coming. Breaking topic here. Google and Tesla shared their results today, had a lot of talk about capital expenditures. Google blew the doors off of their-

**Chamath Palihapitiya** (1:07:18)
Blew the doors off. I mean-

**Jason Calacanis** (1:07:19)
It was insane. Outrageous, and they were down like 7% to 10%.
Google Cloud, growing 82% year over year-

**Chamath Palihapitiya** (1:07:27)
Because of their cash flow numbers.

**Jason Calacanis** (1:07:30)
Yeah, because of the cash flow numbers. And now is on $100 billion run rate. That's but one business. Tesla's CapEx surged 142% year over year, and they expect $25 billion in CapEx.
Google's CapEx forecast from $195 to $205 billion this year. So next year will be even higher. Tesla down 14%, Google down 7% hour of taping, who knows, but both reported negative free cash flow. In other words, the amount of cash in the bank went down instead of up. And for Google, that was the first time ever.
IPO update, SpaceX down 30% from its day one closing price, now trading $1.5 trillion. A lot of pressure on the stock. We'll talk about that as well.
Obviously, they went public at $2 trillion, got a big pop, the Elon pop. And there could be more downward pressure or it could have found a bottom. You never know with these things. This is unprecedented territory. We've never had an IPO this big, but some lockups, here's the chart. Bunch of lockups are happening at different stage intervals. So, let's, Chamath, talk a little bit. Here's your SpaceX. I guess CapEx, Chamath, is being built out, obviously, for AI. And there is the case of OpenAI spending on CapEx in order to provide their service. But then there's also Google, which is making these CapEx investments to resell it as part of Google Cloud, an incredible product. And then on the other side, they're using it for their own, obviously, infrastructure. And their business is just growing like crazy, whether it's YouTube or Google Cloud, or even search is still growing. So I looked at this and I said, well, this seems like a really good use of capital. Instead of just giving dividends, like building out this infrastructure, to me sounds like an investment in the future. It seems like a buy signal to me, but the market is obviously disappointed. Why is the market disappointed? Is it a buy signal for you? Is it make you more excited about management and what Sundar and Sergey are doing over there? Or does it make you concerned?

**Chamath Palihapitiya** (1:09:31)
Yeah.
I'm more bullish. Do you know what Google's 25 year average return on invested capital has been since going public?

**David Friedberg** (1:09:42)
Take a guess. 21%.

**Chamath Palihapitiya** (1:09:47)
No.

**David Friedberg** (1:09:49)
23%.

**Chamath Palihapitiya** (1:09:50)
No.

**David Friedberg** (1:09:52)
29%.

**Jason Calacanis** (1:09:53)
Where's the f***ing price is right?

**David Sacks** (1:09:55)
35%.

**Chamath Palihapitiya** (1:09:56)
32%.

**Jason Calacanis** (1:09:58)
Jesus.

**Chamath Palihapitiya** (1:09:58)
Okay. This is when you are a machine and a group of people and a business model that compounds money at 32% over 20 year average, you give these guys the benefit of the doubt. These are not people that are flying fast and loose. They are methodically investing in their edge. And this is, I go back to the first conversation.
They are going to get massively rewarded. You know, there was a lot of Twitter chatter or ex-chatter about Gemini usage and was it real or was it not real? And is their revenue growth really coming from AI-enabled workflows? It's all malarkey. Google has an incredible search experience. They've seemed to be navigating this transition to use AI. It's been done very well. They have an incredible cloud business and they have an incredible silicon business.
The best thing that can happen to them is 500 different models proliferate and they support all of them because they will make so much money at the silicon layer, they'll make so much money as the cloud provider and they'll find a bunch of apps including YouTube and other things to make money from because you use the AI to target ads better or to help make better content, etc.

**Jason Calacanis** (1:11:11)
Fragmentation is good for them.

**Chamath Palihapitiya** (1:11:13)
Oh, it's great for them. It's a compounding machine. I think the reaction, by the way, is because Jason, I saw a tweet from Ryan Peterson. I don't know if it's true, but he said, Google will be spending 20% of this year's military budget in CapEx. So maybe what people are reacting to is just the scale of the investment they haven't seen. They're free cash flow negative for the first time since going public. So that obviously takes people by surprise.
But they're in a huge investment period, and I think it'll pay off dividends, even if they, as Friedberg's first guess was, half the number. So even if they did half the number, they'd still be over to even less than 500 Still young, yeah.

**Jason Calacanis** (1:11:50)
I mean, Friedberg, if you look at Apple, I think they bought back half their stock, they've given hundreds of billions of dollars back in profits, and gosh, it seems to me, giving all this money back in the form of buying back your shares or giving tons of dividends, I think it's great that tech companies are now saying, wait, we have something to invest in. The next big thing is on-demand intelligence, and there is no upper bound for intelligence. Or I don't think anybody, I certainly don't see, any time in the next 10 years, people saying, I got enough intelligence, I've solved all the problems in the world, I think they're gonna keep wanting it. So what do you think about this incredible change in basically $100 billion, $200 billion, depending on the company, just going into CapEx?
This seems like a savvy move, right? All of us think this is a good thing.

**David Friedberg** (1:12:40)
I mean, if you want to bet against Google's deployment of capital into infrastructure, because you'd rather have them give you cash for your shares today, you shouldn't own the stock.
Someone else will buy it. I think Google wins in a lot of different ways. There's just so much to Google. There's the consumer business, which is a lot of stuff. There's also YouTube. There's also GCP. There's also this portfolio of other bets, which, by the way, includes 10% of SpaceX and a good chunk of Anthropic that they own and so on.

**Jason Calacanis** (1:13:12)
Waymo worth $120 million.

**David Friedberg** (1:13:14)
I think they just took $100 billion right up on Anthropic in the quarter. So they had $100 billion market to market on Anthropic just in one quarter, and they own a piece of all these businesses. So there's a lot to like about Google.
But just on GCP, I think that there's probably no better suited enterprise layer than GCP to take advantage of capturing value with AI for that enterprise setting. Why is that? I think you're just so much better because you have so much of your enterprise data, all your email, your drive, a lot of information that you would want to have AI have knowledge of and have AI have access to, to improve workplace productivity. And then they're model agnostic. I mean, you can run any model you want and you can run any workflow you want, and you don't have to be tied in. A lot of other cloud service providers, cloud SaaS, they're kind of model dependent to run in a certain way.
With Google, you can better tune your system how you want to tune it. And what's the worst, worst, worst-case scenario? The worst, worst, worst-case scenario is they have the lowest cost infrastructure in the world to run other people's models as a service like Elon did with Grok, with the Colossus.

**Jason Calacanis** (1:14:23)
Elon Web Services seems to be doing pretty great.

**David Friedberg** (1:14:25)
And look at the return Elon's making on the Colossus install. So I think if Google, in the worst-case scenario, none of their application layer stuff works, none of their network effects work, and they don't have any good models, they're still going to have the world's best infrastructure they can print cash on for if you believe in AI. So if you want to bet on AI, I think the best public market stock to own is Google. And by the way, you also get YouTube, you also get the consumer, you also get everything else. The multiple is kind of ridiculous right now.

**Jason Calacanis** (1:14:53)
We talked about this on a previous issue. I think, Chamath, and you and I were talking about like what Apple should do next. And I think we both came to the conclusion, it's like, why not have Apple Web Services? They have such great relationships with developers. They have the App Store.

**Chamath Palihapitiya** (1:15:08)
It's not so easy because you have to build a cloud service provider. You have to build some critical infrastructure. It's taken Amazon, call it 17 years to perfect it.
It's taken Google, call it 12 or 13 years to mostly catch up. But the minute that you sign up to be a web provider, Jason, and a cloud service provider, what you're really signing up for is five nines of reliability and uptime. And that is just extremely expensive. Getting to the first two nines, you know, 99% uptime. If you're hosting something for a pharma company or a defense company, you can probably do it for relatively cheaply. Getting to the third nine, 99.9, probably costs you in the billions. Getting to the fourth nine costs the tens of billions. But getting to that fifth nine costs hundreds of billions. And that takes a real investment and real technical skill. And there's only three games in town.

**Jason Calacanis** (1:16:03)
Yeah, I think Tim Cook's not the guy to do it, but this new CEO might be, since he's an engineer. But they've returned in the last decade.

**Chamath Palihapitiya** (1:16:11)
They could buy a new scaler.

**Jason Calacanis** (1:16:11)
Approximately 900 billion, 755 in buybacks and 140 billion Sacks in dividends. Just let that sink in. 900 billion. If they had invested that in Anthropic and SpaceX and other things, they just could have found some good uses for that money. But Sacks, any thoughts here on what's happening?

**Chamath Palihapitiya** (1:16:28)
Sorry, but who's to say that the investors that got that money didn't find a good use for it?

**Jason Calacanis** (1:16:33)
Oh, yeah, so on society level. But I just think Apple could have been more ambitious if they just spent half that money instead of on buybacks and dividends, on creating new products and actually releasing their car, maybe buying some interesting companies. I think they would be a better company.

**Chamath Palihapitiya** (1:16:46)
I think it was very much a do-no-harm capital allocation strategy, which worked for the stock. It's going to be really interesting to see if John Ternes flips the script.

**Jason Calacanis** (1:16:55)
I think he does. I think he's gonna be like engineer guy and yeah. All right, enough on the markets. The markets are gonna do what markets do. We will talk about Iran and other stuff like that when there's more news for venture capitalists to comment on. Right now, it's just on on. I know everybody keeps asking.
I don't think there's much for us to say on it. I do think there's a lot for us to say in Socialism Corner, our new reoccurring theme here, Friedberg. Every week, there's more news coming out of Socialism Corner.

**David Friedberg** (1:17:23)
Why don't you show my videos on Socialism going back six years?

**Jason Calacanis** (1:17:26)
Let's add to the Friedberg Socialism rants earlier this month. New York City dictator slash mayor Zohran Mamdani.

**Chamath Palihapitiya** (1:17:36)
Don't misuse that term, please. Come on.

**David Friedberg** (1:17:38)
Jason, that is standard.

**Jason Calacanis** (1:17:39)
Posted a rental ripoff hearing at New York City's Tenement Museum after the hearing. He introduced a rental ripoff report. He passed Bars Landlords from charging applications for credit checks.
It's going to let landlords require a credit check or the 40X rent income standard, but not both. Legally recognized as Tenant Unions and more. He's obviously frozen the rent for a year at the hearing. An activist wore a COVID mask and referred to evictions as the violence of evictions. Here's your 22nd clip.

**SPEAKER_5** (1:18:10)
The Mamdani administration is emboldening us so that we no longer tolerate the violence of evictions as a matter of business as usual.

**Jason Calacanis** (1:18:22)
What were we just watching? Is that the Sacks? Do you remember the guy from Fat Albert who had the hat like that?

**David Friedberg** (1:18:28)
Can we pull that guy up?

**Jason Calacanis** (1:18:31)
Remember the guy from Fat Albert who had the hat? What's his name?

**David Friedberg** (1:18:35)
Oh my God.

**David Sacks** (1:18:36)
Is COVID still happening? I thought COVID was over. No, she just got a booster.

**Chamath Palihapitiya** (1:18:41)
That was like a super duper mask.

**David Friedberg** (1:18:42)
That was a super duper mask.

**Chamath Palihapitiya** (1:18:44)
That just wasn't like a little cloth one. That was one of those big ones.

**Jason Calacanis** (1:18:48)
I mean, combined with the hat, it was, that was pretty, there it is. I remember that guy from, what is going on?

**David Sacks** (1:18:57)
Wait, we're going to give Friedberg a chance to do a rant? Yes. I mean, I could do a rant on this.

**Jason Calacanis** (1:19:01)
No, no, let's give Friedberg his, this is Friedberg, rare meat, Friedberg.

**David Friedberg** (1:19:07)
In 1787, John Quincy Adams published a work called A Defense of the Constitutions of Governments of the United States of America. In that work, he had a comment, the moment the idea is admitted into society, that property is not as sacred as the laws of God, and that there is not a force of law and public justice to protect it, anarchy and tyranny commence. Then in 1791, he made the statement publicly, property must be secured or liberty cannot exist.

**Chamath Palihapitiya** (1:19:41)
In an essay series, can you unpack it and explain why he said that? Do you think?

**David Friedberg** (1:19:45)
Fundamental to the foundation of the United States of America was this idea of private property rights. Because if you think about where everyone that came to America was coming from, there were these tyrannical governments, monarchies or whatever, where some overlord or some cabal could decide at any point to take the things that you have. You had no private property rights as an individual. They could come in, they're like, that farm is my farm. You're actually a serf. I'm the lord. That thing is my thing. You have a right to use it because I vest you that right to use it. I am the all-powerful. I am the tyrannical overseer of these lands. It was that stasis that drove so many to come to the United States and say, we want a place where individuals, one person can say, I own something and no one can take it from me.
Private property rights are the foundations of liberty in America.
This idea that you can then claim acts of violence, that you can then claim circumstances of extraordinary, extravagant wealth and say to that individual, I now have a right, the government now has a right to take your private property, ultimately leads to this tyrannical form. It starts out as being an anarchic because, and remember, anarchy is a temporary state. It's always in between one state and another.
All anarchies end up in tyranny. Groups of people fight each other, they're all stealing from each other. Everyone just goes and takes and gets what they want. And eventually people coalesce, they form groups. And those groups become the more powerful groups and the powerful groups end up winning. And they become the tyranny over the mass. And that is why all anarchies eventually evolve into tyranny. So anarchy and tyranny are one in the same.
And fundamentally what's going on with these socialist principles is that we are taking your private property and you no longer have rights on your private property. Whether you are a landlord or whether you are a wealthy person that we've deemed to have too much wealth, we now will have the rights to come in and take your property and control it and take it from you. And it always starts with this framing of moralistic intent. We are good, you are bad for the following reasons. You have committed violence against the people that live in your building. You have taken too much wealth and none of us have wealth. We have a right to go and take your wealth from you. It has always started from this point of view that you are bad. So the first framing is that the private property owner is evil.
And that the private property owner has committed an act of injustice against those who don't have the private property. And that is the justification for taking away their private property rights. And it is the beginning of this transition towards a tyrannical system, which will ultimately be what I call this kind of great American politburo, or whatever socialist framework gets set up by the cabal of the socialists and what they're trying to put together. So all of these little acts, while seeming ridiculous and insane and inappropriate, in aggregate, are the same thing. They're a transition away from private property rights, which is the foundation of the United States of America. That's why I think we should all be so shocked. And to John Quincy Adams' point, we need to vehemently defend those rights. As soon as those rights start to slip away, even in the tiniest way, it is a cascading effect, and everything will become tyrannical, and it will be very ugly in the United States of America.

**Jason Calacanis** (1:22:55)
Sacks, what are your thoughts here on Comrade Mondami?

**David Sacks** (1:23:00)
Yeah, I just want to add a layer to this idea. You know, these DSA socialists say that evictions are violence, and they basically want to stop them.
I think Friedberg's making the point that this deprives the landlord of their property, and that's true, but I think we also have to stop and consider what this means for the other residents in these buildings. I mean, first of all, if the landlords aren't making income because they got a bunch of delinquent tenants in the building, they can't now pay for upkeep and maintenance, and so these buildings become more dilapidated, and that affects the other tenants. But also, I have a friend who manages these apartment buildings, and he makes the point that it's often these squatters, these delinquent tenants who should be evicted but can't, who make the worst neighbors.
So when you think about the problems in an apartment complex where you've got people creating noise at night, maybe they're playing loud music, or you have people punching walls, or there's disgusting smells coming from apartments, or they're misusing common areas, or you have drunken and disorderly behavior. I mean, this is all the kind of stuff that happens in these rent-controlled apartment buildings. And you have to remember that there's long-standing residents, a lot of old people, who can't afford to find a new place. They depend on the rent control. And when you can't evict that unruly tenant, yes, it affects the landlord, but it affects the neighbors even more. Because now they're stuck in a downward spiral. And I think this is a problem with the progressive mindset across the board, is that these DSA types are always these, like, highly educated and often affluent types. And they can afford to have luxury beliefs about public spaces. Because they never use them, right? They don't use the bus or the subway or parks. And so when they get taken over by homeless drug addicts, they always defend the addicts, as opposed to the middle class and working class people.

**Jason Calacanis** (1:25:00)
An easy thing to do if you don't live in the tender one.

**David Sacks** (1:25:02)
Right, exactly. And it falls the hardest on the working class, because they actually need these amenities. They need the parks for their kids. Or they need to use the subway, right? And it's really a problem when you get people shooting up or doing drugs or, you know, defecating in a subway.

**Jason Calacanis** (1:25:17)
And you're walking your kids to school. Like the person in Marin County who has these luxury beliefs or on the Upper East Side, they just don't, they're abstracted from this. They don't need to deal with it.

**David Sacks** (1:25:27)
Right.

**Jason Calacanis** (1:25:27)
We talked about this on our-

**David Sacks** (1:25:28)
And it's no different with these rent-controlled apartments. I think that's the important point here is that if over a period of several years, you can't evict anyone, no matter how problematic they are, you effectively turn these apartment buildings into the equivalent of housing projects.
And that really affects decent people of modest income who have nowhere else to go, and their quality of life suffers. And look, the private equity wives in their gated communities will still feel good about themselves because they prevented these evictions, but it's the people in the building who are going to suffer the most.

**Jason Calacanis** (1:26:03)
And at least, and there, Chamath, these people are not just thinking from first principles. If you want to solve the housing problem, anybody with any basic understanding of economics would just say, well, increase the supply and the price will go down. And it actually doesn't matter which supply you add. It doesn't matter if it's luxury units or multifamily or single family. As long as there's more housing and there's transportation to get to it and to move people in and out, it'll be fine.
As I'm sitting here in Tokyo, like they figured this out a long time ago, just build up and put more units in. They figured it out in Texas, Florida, Nevada. The only people who can't seem to figure this out is like New York, LA, and San Francisco, just happens to be liberal elite enclaves. It's not hard on a conceptual basis, just allow people to build some more units and different types of units, and then the price will go down. Chamath, any thoughts here?

**Chamath Palihapitiya** (1:27:02)
The data from Austin says, once you relax the permitting constraint, you'll get more units built, and for every unit that comes online, it literally drives down the rent. If you want low rent, you need to have more units. If you want more units, you need to permit more aggressively. That's it. It's just a decision. The same political will that it would take Mamdani to pass this law, he could actually pass some permitting reform and it would do a lot more good. The thing on private property, the reason I asked Friedberg to explain it is, I really believe what he's saying is really important. It's funny to me this idea that at the limit, let's just say you're driving your car and all of a sudden, somebody jumps in it and they're like, well, now I'm here, you can't kick me out or you go outside, you leave your door open to go get a FedEx package or Amazon box and somebody runs in and sits on your couch. Now all of a sudden, you can't kick them out.
It sounds so ludicrously dumb.
If you force the owners of physical property to not be able to credit check and differentiate who they rent their apartments to, what's going to happen is rents will go up even more. I suspect that what they should do is they should pass this law and they should observe what the outcome is. Then you can do a pretty scientific AB comparison between New York City and Austin, and you'll know what works and what doesn't work.

**David Friedberg** (1:28:26)
Yeah.

**David Sacks** (1:28:28)
I mean, here's the problem is the socialists never learned. I mean, we already have tons of studies.

**David Friedberg** (1:28:33)
In Argentina, rents went down.

**David Sacks** (1:28:36)
Yeah, I mean, this is the problem with Chamath is that, look, if the socialists ever learned from their failed experiments, you wouldn't have Chicago.
We don't need New York to go down the tubes to know this isn't going to work because it's happened in so many other places already. But somehow it just never seems to stop.

**Chamath Palihapitiya** (1:28:54)
They never seem to learn, so they should run the experiment and learn. I mean, what's crazy is you'll be learning and it'll be a failure on the grandest stage possible. You're talking about the biggest, most complicated city.

**SPEAKER_5** (1:29:04)
My gosh. Yeah.

**Jason Calacanis** (1:29:05)
I mean, and Sacks, what happens if a landlord cannot raise the rent reasonably? Well, they have no incentive to invest in new units. They have no incentive to upgrade new units. And there's this trap in New York City specifically. They have made this regulations for apartments such that if you do a renovation, it has to get certain codes, and there are a ton of codes. Okay. So that means it's incredibly expensive.
So now they have, you have ghost apartments in New York.

**David Sacks** (1:29:37)
Now the housing stock becomes dilapidated. And look, they're doing something even worse now, I think, which is they are banning landlords from doing credit and background checks on potential tenants. And they say that you can't look at their income. So you can't vet whether they can actually pay the rent.

**David Friedberg** (1:29:53)
Who wants to be a landlord?

**Jason Calacanis** (1:29:54)
No more landlords.

**David Sacks** (1:29:55)
Right. So they're banning eviction. And then they're preventing you from doing the diligence to see if this is even a tenant who will pay the rent.

**Jason Calacanis** (1:30:02)
We've lost the script.

**David Sacks** (1:30:03)
So what are you supposed to do?

**Chamath Palihapitiya** (1:30:04)
The interesting question is, if you were forced to live under these rules as a landlord, what would you do? And the obvious answer is you'd start rent three or four times higher, and you force people to sign up to a multi-month prepayment, and you'd slowly ease those conditions until you find a market clearing price. That's the only way to do it. So rents will not go down.
Rents will go up. So run the experiment, and let's just observe what happens.

**David Sacks** (1:30:30)
That's a really good point, Chamath. Let's say that X percent of tenants are gonna become delinquent, right? And by the way, what's their incentive to pay when they know they can't be a victim?

**Chamath Palihapitiya** (1:30:39)
Zero, zero.

**David Sacks** (1:30:40)
So actually, a pretty significant percentage of people could just decide, I'm gonna make rent optional. And so now the landlord has to absorb those losses, and that means they have to pass on a higher rent to everybody else.

**Chamath Palihapitiya** (1:30:53)
You're gonna set the rent 3X higher, and you're gonna slowly meander it down. And like I said, you're gonna have to wire in the first full year of rent. Well, good luck.

**David Sacks** (1:31:02)
How is that more affordable?

**Jason Calacanis** (1:31:03)
It's even worse, Sacks. Not only do the landlords keep the dilapidated apartments, in some cases, it's better for them to just leave apartments, housing stock empty. So somebody leaves, they are forced to renovate it, and it costs more, you know, hundreds of thousands in renovations.
So they say, you know what? I'll just leave it empty for now. And so you have 50,000 ghost apartments, according to reports, in New York City.

**Chamath Palihapitiya** (1:31:34)
Well, that's an Airbnb problem. That's like a...

**Jason Calacanis** (1:31:37)
No, they banned Airbnb in New York. You cannot get an Airbnb.

**Chamath Palihapitiya** (1:31:40)
Oh, really?

**Jason Calacanis** (1:31:41)
Yes. So now...

**David Sacks** (1:31:42)
That's really interesting. Yeah, look, if you're a landlord, okay, I mean, I guess one thing you do is to sell and go to another jurisdiction. Another thing you could do is just wait this out. Because it's not profitable to run an apartment building. You can't raise your rents. You can't evict people. You can't diligence the tenants. So maybe you just leave the building empty and you wait this out.
I mean, that's assuming you don't have too much debt on it, right?

**Chamath Palihapitiya** (1:32:04)
More ghost apartments, yeah.

**David Sacks** (1:32:06)
And then you have ghost apartments.

**Jason Calacanis** (1:32:07)
Yeah. All right, listen, you've been thinking about coming to the All-In Summit. This is your year. Speakers are world class.
The events, the parties, the network, 80% of the people there, founders, investors, or high level operators this year, greater focus on networking.

**David Friedberg** (1:32:22)
The musical performances.

**Jason Calacanis** (1:32:22)
Oh, yes. I mean, in the past, we've had...

**David Friedberg** (1:32:25)
The food, the drink.

**Jason Calacanis** (1:32:27)
rhymes.

**David Friedberg** (1:32:28)
Diplo.

**Jason Calacanis** (1:32:28)
Diplo. We've had so many incredible people. Go to theallinsummit.com. All right, everybody, it's another amazing, all-time, legendary episode of the All-In Podcast.

**Chamath Palihapitiya** (1:32:41)
Love you, boys.

**David Sacks** (1:32:41)
Bye.

**Chamath Palihapitiya** (1:32:42)
Bye-bye.
