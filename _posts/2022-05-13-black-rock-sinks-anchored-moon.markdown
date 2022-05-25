---
layout: post
title:  "A black rock sinks an anchored Moon"
date:   2022-05-13 10:00:00 -0400
categories: postmortem
author: cinjon
blurb: "We run a postmortem on Luna and UST, before looking beyond to Frax, FXS, and the possibility of algorithmic stablecoins."
feedback: false
hidden: false
---

# When a black rock sinks an anchored Moon

We invested in the Luna presale, closing in October 2018. Since then, and up until the cataclysmic events in early May 2022, we followed the story closely. 

There are a terrific amount of strong write-ups on the internet detailing what Luna is, how it worked, and what happened when Luna/UST hit the death spiral. Some of these are forward-looking views written by capable Cassandras; others are post-facto views written by insightful investigators. A brief list:

1. A twitter [thread](https://twitter.com/FreddieRaynolds/status/1463960623402913797) from FreddieRaynolds predicting seven months beforehand almost the exact play that (likely) broke UST.
2. A [writeup](https://hjalmarpeters.medium.com/why-i-am-betting-against-terrausd-2bc0f5668997) from Hjalmar detailing his play against UST and examining different depegging scenarios. Additionally, the [longbet](https://longbets.org/891/) challenge from Hjalmar to the world.
3. A twitter [thread](https://twitter.com/4484/status/1524006086147252227?s=21&t=o2JysAjiE0Q0iE-w9TQQcA) detailing what happened in the attack that broke UST.
4. A real-time twitter [thread](https://twitter.com/jonwu_/status/1523793482850050048?s=20&t=qBJb7CcDYVTovCMRTDXZxg) of what was happening as UST was depegging.
5. A pseudo-insider [view](https://twitter.com/0xHamz/status/1525117483295854593?s=20&t=E3YQ8Sdimy9twytCB-_Jnw) of the war chats occurring while UST was depegging and Luna was losing its value. It also describes the moment when Luna was doomed as being when it lost control of its capital flows. This resonates with other global capital movements and is a good lesson to consider.
6. A couple weeks later [amalgamation](https://newsletter.stakingrewards.com/p/terra-staking-rewards-special-comment?s=r) of what happened, plus opinionated (but informed) views on how to view Luna and the space going forward.
7. A well-written and straightforward [inquiry](https://newsletter.stakingrewards.com/p/terra-staking-rewards-special-comment?s=r) into each of the key points affecting Luna. 

Rather than add yet another report, we just add a few choice thoughts on what’s happened, what we learned, and how we view a key player in this space:

1. Would Luna have died without the reported attack from institutional investors?
   <ol type="a">
   <li>It didn’t have to, but likely yes.</li>
   <li>Our theory was that whales would leave after the first rate change in Anchor, and that that would cause a run to the exit.</li>
   <li>That theory would have held up regardless of the push by institutions trying to make massive $$ gains. The big issue was that Anchor caused a massive asset / liabilities risk that was too hard to unwind safely.</li>
   <li>Could it have been unwound safely? Yes.</li>
   </ol>
2. How did the BTC purchases work? Does that actually have reflexivity in it?
   <ol type="a">
   <li>This was really a way to take inflated currency and buy a real world asset. Among other companies, Gamestop, AMC, and Tesla all have done this successfully the past few years with hardly anyone batting an eye except to repeat, endearingly, “Oh yeah, Reflexivity amirite.”</li>
   <li>It’s specifically taking made up money (UST / Luna) and turning it into actual solid digital currency, i.e. bitcoin. they could have done this with USDC too but that’s against their ethos, as well as being against their hope that BTC rises to help their balance sheet mismatch.</li>
   <li>However, this was actually a bigger mistake than realized. Bitcoin is different from USDC because in a time of massive sell pressure, USDC will keep the peg (it can’t not ...) and Bitcoin will drop like a log. This happened.</li>
   </ol>
3. Did the 4pool have an affect on the space?
   <ol type="a">
    <li>No, not really. It got flooded with UST but that just meant that those pairs don’t get traded anymore. The others in the 4pool - frax, ust, usdc - can still be traded amongst themselves easily.</li>
    </ol>
4. Did we see this coming?
   <ol type="a">
    <li>Yes. We foresaw a death spiral as possible early on and starting taking action the last week of March, liquidating almost all of our position before Luna/UST collapsed. The only part of our position that remained were those that we had locked up to support protocols build on Luna, e.g. Astroport.</li>
    <li>More generally, we understood that the most important aspect for growing the value of Luna was increasing the demand for UST. Anchor was an albatross around its neck whose load needed to be lightened, but in the early days this was ok! The problem was that they kept it going well past when they could handle the liabilities involved with such little assets on the balance sheet.</li>
    </ol>
5. The recursive nature of Anchor was a blessing and a curse.
   <ol type="a">
    <li>By letting people borrow at much less than the deposit rate, it meant that users would borrow UST at ~14%, then deposit it to get ~19.5%. They would then take that 19.5% and use it to borrow more to repeat.</li>
    <li>This fueled demand for UST and consequently increased the Luna price, which pleased many people who saw their investment having “paid off”.</li>
    <li>However, this was an artificial recursive mechanism that was bound to unwind, either through growth or through a bubble pop. The growth never came so a sudden pop was the only solution.</li>
    <li>A sudden bubble pop from a recursive borrowing spree is commonly seen as a Ponzi.</li>
    </ol>
6. History will see Luna/UST as a ponzi, but it never needed to be nor was that their intention. They let this run wild but without Anchor running for so long, the Luna/UST ecosystem could have kept growing into what was becoming a collateralized algorithmic stablecoin. In other words, I don’t agree with this [analysis](https://twitter.com/gametheorizing/status/1526376821260009472), and would welcome conversation on it. 
7. The big winner in this could be FRAX. A thesis for FRAX is the following:
    <ol type="a">
    <li>Stablecoins are necessary for the space. They’re a huge opportunity.</li>
    <li>There's three main ones historically - USDC, USDT, and DAI. Those three all have problems that others try to solve. The ones who have done the best job of addressing them are FRAX and (rip) UST.</li>
    <li>Focusing on FRAX, they're asking a question of "why can't we let the market decide the collateral ratio?" That question worked very well as a first question and enabled massive success with their first wedge being dao treasuries.</li>
    <li>Their next play is happening right now with V2 and the AMOs, which you can think of as wedges into the rest of crypto that (should) simultaneously reduce the volatility and increase the liquidity of FRAX.</li>
    <li>In other words, if the AMOs work in the way that they could, where their usage trends way upward and others start building them too, then you'll see a multi-chain FRAX world (already happening) with their tentacles stemming into many different important market operations, all with a responsive collateral ratio implying that they can quickly mint according to market liquidity needs.</li>
    </ol>
8. Why is FRAX impervious to the problem that UST had?
    <ol type="a">
    <li>It’s not. FRAX is also a two-sided stablecoin with FXS being its Luna.</li>
    <li>However, it also has a floating collateral ratio which means that from birth it’s been more robust to a problem in the protocol that would break its knees.</li>
    <li>It additionally has a history of learning what *not* to do from watching other algorithmic stablecoins fail and appears to be executing very well on slowly growing a coin that a) doesn’t contain landmines, b) works capably with the entire space, and c) reduces its systemic risk in any one region through the AMOs.</li>
    <li>Of course, time will tell. All businesses must survive many winters before they are wise. We will continue watching FRAX and trying to help it avoid catastrophe.</li>
    </ol>
9. Are *any* algorithmic stablecoins impervious to the problems that UST faced? 
   <ol type="a">
   <li>Yes … if they are fully or over-collateralized. DAI is proving to be robust to these issues.</li>
   <li>Empirically, we haven’t had any under-collateralized stablecoins achieve Lindy-level trust.</li>
   <li><b>Super interesting question</b>: is there any impossibility theorem lurking in the midst of this conversation?</li>
   </ol>
