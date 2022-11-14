---
title: "On Valuing Defensive Midfielders"
author: "znstrider"
date: "November 14, 2022"
format:
    html:
        code-fold: true
jupyter: python3
toc: true
---

In his article [What is midfield for?](https://www.getgoalsideanalytics.com/what-is-midfield-for/) Mark Thompson [(TweetsbyMarkT)](https://twitter.com/TweetsByMarkT) elaborates on the difficulties of measuring the impact of actions in midfield that Statsbomb's Thom Lawrence coined the 'trough of meh'. On average actions away from both goals seem to not have much measurable impact on the probabilities to score or to concede. 

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">✨ New ✨<br>One of the quirks of football analytics is that as you move away from goal actions have a _miniscule_ probability of leading to goals<br><br>This is unsurprising with so few goals per match, but raises the question: what do you measure there?<a href="https://t.co/EZ51oYOMAF">https://t.co/EZ51oYOMAF</a></p>&mdash; mark thompson (@TweetsByMarkT) <a href="https://twitter.com/TweetsByMarkT/status/1592083908300271616?ref_src=twsrc%5Etfw">November 14, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

In his recently published book "Net Gains" [Ryan O'Hanlon](@rwohan) came to the conclusion that teams probably should not spend as much on midfielders as on other positions, because they seem to have less impact. While this might be sound practice if you believe the conclusion of event-data possession value models that midfielders' impact is measurably smaller than that of players in other positions, I thought this might be a little too rash.

I agree that the value of defensive midfielders is very hard to quantify. But most models lack the context to adequately capture the true value of a situation, especially in midfield. I will elaborate on why I'm not convinced that defensive midfielder are less important than other positions. The central nature of their position on the pitch would have one believe the opposite to be true!

The way I see it is that in comparison to basketball, a team (that is good enough at the passing and positional aspects) has the ability to patiently set up its structure such that it minimizes the risk of turnovers and counterattacks, and to lure and manipulate their opponents defensive setup, all the while probing with passes, movements and runs into depth until a **good** forward option opens up. That's how I would interpret @TiotalFootball's 'building capacity'.

In this way of thinking, a central midfielder who stabilizes possession, by making himself available as a passing option, binding opponents to open up passing lanes to teammates, and by being in a good position to regain the ball in case of a turnover, is an indispensable role. But the value of that role does not mainly lie in ball progression, incisive passing and chance creation. A holding midfielder provides structure and makes sure the ball stays with the team, as long as needed. 

#### It's hard to quantify the value of facilitators

Why don't those players shine in possession value models? They are facilitators. They don't necessarily offer the ball progression and incisive passing themselves, which are the actions that are seen as valuable by most possession value models. Compare Sergio Busquets to Joshua Kimmich. Would one say that Kimmich is clearly the better player due to his creative passing? I don't think so. But he will he valued more highly by those models, because he attempts and completes many more speculative passes.  

At Barcelona other players usually take the role of offensive creation. Why would Busquets initiate the attack when there was Lionel Messi who did it much better? Don't get me wrong. Busquets COULD probably play more vertically, and do well at it. But that's not his main strength. That's not what his team needs. That's not his role. So what I am saying is: Whatever value a player generates cannot fully be evaluated independently of the context of the team level. 

The reason facilitation of valuable actions is hard to measure is the lack of game context in event-data based models.
When I position myself well to receive the ball in the center behind the first defensive line and immediately lay it off to a fullback who can drive into space, should that be attributed solely to the fullback? Should that be attributed to him at all if there is acres of space that *anyone* would drive into?  
Tracking data based models will incorporate this context and *implicitly value* the high probability of a progressive action *in this situation*. Thus most of the value would not be assigned to the fullback - he just does what he *is expected to do*. A big part of the value would be divided up between the players creating the situation.

The same would be true if offensive players find themselves in more space with better forward passing options - context unseen by event-data models.

Another interesting viewpoint to look at is this: What happens when a good team that tries to implement a possession heavy approach lacks a great holding midfielder? An example might be Borussia Dortmund. They have three of the best centerbacks in the Bundesliga, a great box to box player in Jude Bellingham, but lacking a dependable, disciplined six in the spirit of Sergio Busquets or maybe even Julian Weigl. Their positional structure and consistency is not matching BVB's expectations.

Maybe the value of a good defensive midfielder can only be seen when he is missing?
