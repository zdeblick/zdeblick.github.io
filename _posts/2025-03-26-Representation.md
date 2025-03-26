---
layout: post
title: The representation problem
tags: Big+Picture Technical+Deep+Dives
---

I've spent a lot of time in this blog so far talking about very old democratic traditions, and in my last post I specifically called attention to the idea that democratic traditions evolved in a very different environment than today. In particular, the populations that participated in a single democratic system were very small compared to today's democratic states: the Athenian assembly (probably the largest of any like it until centuries later) typically consisted of tens of thousands of citizens residing in one city (Athens), while 642 *million* voters participated in India's last general election, spread out across an area almost 25 times larger than all of Greece. Try to imagine, for a second, an Athenian polis packed with 642 million citizens, all trying to participate in a single debate and enact a coherent policy. I actually struggle to imagine this, but I don't think it takes a lot of imagination to believe that this would not be an effective form of government. This is why, as states started to get bigger, they adapted existing democratic traditions like the assembly to serve larger and more spread out populations. In general, all have settled on some system of *representation*.

My computational neuroscientist alter-ego would tell you that representation is something the brain does all the time, when it uses some pattern of neural connectivity or activity to represent something in the real world. Why does the brain do this? Because it has to perform computations on visual, sound, and other input from the real world in order to choose appropriate (enhancing survival chances) behavior. So it transforms that input into some internal representation that is useful for performing computations (and giving computational neuroscientists something to study). 

Representative systems of government do essentially the same thing, for essentially the same reason. The basic input to a democracy is the will of the people, and the desired output is policy that maximizes some good property of those same people's lives (life, liberty, pursuit of happiness, stability, etc.). But for a large, diverse population, it is very difficult to incorporate the will of every person without somehow reducing the problem. So representative systems select a group of people small enough to actually debate and enact policy where each representative is selected to *represent* the will of some large group of voters. This essentially reduces the question of optimal democratic government to two mostly separate problems:

1. How to choose an appropriate set of representatives from a population?
2. What process should those representatives use to debate and enact laws?

The various democracies around the world have various answers to both of these questions, but all use this same basic idea. For the rest of today's post, we'll take a deeper dive into the first question, and in particular ask how good the USA's system is.

The USA has representatives at the federal, state, and local level. Except for the President, elected officials are selected state-by-state, and the states play a huge role for selecting the President too. (I've switched now to using "elected official" instead of "representative" because "Representative" refers to a specific type of elected official in America, but all elected officials represent some group of people.) Each state elects two Senators, each elected once every six years by voters across the entire state, and a number of Representatives proportional to the state's population (determining how exactly to apportion this number of Representatives to states is actually not a straightforward problem - I would highly reccommend checking out [this video](https://www.youtube.com/watch?v=GVhFBujPlVo) to get into it). Up until 1842, each state had a lot of freedom in choosing how to elect their Representatives and two different approaches were used by different states: single-member districts and block voting. 

In block voting, if a state had *N* Representative seats apportioned to it, its ballot would allow voters to vote for *N* candidates, and the *N* candidates who received the most votes would be elected. In states that used this system, each political party put exactly *N* candidates on the ballot, and voters tended to vote for all *N* candidates of their party of preference. The result was that the majority party tended to take all *N* seats. 

In single-member districts, the system we have today, states draw a district map, dividing the state into $N$ regions. Then in each region, a single-winner election takes place to elect the Representative from that district. 

From Chief Justice Robert's opinion in the 2019 case *Rucho v. Common Cause*: "The initial difficulty in settling on a ‘clear manageable and politically neutral’ test for fairness is that it is not even clear what fairness looks like in this context. There is a large measure of ‘unfairness’ in any winner-take-all system."

<iframe width="600" height="400" 
    src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTXkBFUNa5vrOnmA-BdhxNfDChfUIwgrRGCvc5azGLrP1WjM3up0ToZsxzdrFrGqY13ulzrfa5FddTJ/pubhtml?gid=80201397&single=true&range=F2:M438">
</iframe>
