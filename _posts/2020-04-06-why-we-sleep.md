---
layout: post
title: "Why We Sleep?"
date: 2020-04-06
authors: [Jonas Van Der Donckt]
tags: [opinion, book review, science]
---
<p align="center">
  <img src="/images/why_sleep/belly.jpg" width="100%"/>
</p>

This post is a (scientific) summary of Matthew Walker's "[Why We Sleep?](https://www.goodreads.com/book/show/34466963-why-we-sleep?ac=1&from_search=true&qid=Rza4SwiuDq&rank=1)", accompanied by some fun facts and tips to improve your sleep quality.

><div style="text-align: left;">"There does not seem to be one major organ within the body, or process within the brain, that isn’t optimally enhanced by sleep (and detrimentally impaired when we don’t get enough)."</div>
><cite>— Matthew Walker</cite>

## My commitment to sleep
<!--more-->

During the first semester of this academic year (2019-2020), I added a [machine learning](https://studiegids.ugent.be/2020/EN/studiefiches/E061330.pdf) course to my curriculum. Within this class, students had to apply machine learning in a "large project". Being a PhD student gave me the freedom to choose my own project, which was to create a sleep stage scoring machine learning model using polysomnography (sleep clinic) data. This sparked my interest in sleep and made me read Matthew Walker's book.

<p align="center">
  <img src="/images/why_sleep/hypnogram_prediction.png" width="100%"/>
  <figcaption><small><p align="justify"><b>Fig. 1:    Physicians summarize sleep-clinic data by displaying the sleep stages over time, also known as hypnograms. The figure above compares the physician's sleep stage assignments (<i>Hypnodensity ground truth</i>) with my machine learning model's prediction (<i>Hypnodensity prediction</i>).
  Official sleep stage scoring guides acknowledge 4 sleep stages (and wakefulness). The sleep stages can be divided into two groups; (1) non-REM sleep (N1, N2, N3), and (2) REM sleep. REM is an abbreviation for Rapid Eye Movement. N1 is transient light sleep, normally followed by a transition into the N2 medium sleep stage, to finally tumble into deep N3 sleep.
  This is the ideal case, but as visible on the graph above, there are a lot of mini-awakenings and this order isn't always maintained. The REM-sleep is the phase where the person is dreaming and mostly occurs at the end of the sleep (this explains why we are sometimes able to recall our dreams), where the deeper N3 sleep resides itself in the beginning of the night.
  </b></p></small></figcaption>
</p>

The book indicates the importance of sleep and outlines the effects of sleep deprivation.
Matthew Walker reached his goal as the book made me reflect on my own sleep hygiene; I want to improve my sleep quality, and as the succeeding quote exquisitely states:

><div>One practice known to convert a healthy new habit into a permanent way of life is <b>exposure to your own data.</b></div>
><cite>— Matthew Walker</cite>

I (re)started using [Sleep as Android](https://sleep.urbandroid.org/). This is an app that allows sleep tracking and gives you statistics such as sleep regularity, sleep quality, snore detection and many more. It even gives you tips/challenges to obtain better sleep hygiene and you can set 'smart alarms', which will go off once you reside in a lighter sleep phase, giving you a more pleasant awakening.

<p align="center">
  <img src="/images/why_sleep/sleep_graphs.jpg" width="65%"/>
  <figcaption><small><p align="justify"><b>Fig. 2: My own sleep graphs from Sleep as Android. As the COVID-19 lockdown is ongoing, my sleep hygiene has improved significantly. Right now, I don't have to set an alarm anymore to wake up at 7 a.m.! I leave it as an exercise for the reader to infer the dates on which I didn't sleep in my own bed :wink:.
  </b></p></small></figcaption>
</p>

This little app forces me to reflect on my sleep behavior on a daily basis. It doesn't allow to suss my conscience as the data speaks for itself!

## Our internal clock

Our sleep-wake cycle is controlled by two processes; (1) the circadian rhythm, i.e., our 24-hour biological clock, and (2) the levels of adenosine in our brain. The circadian rhythm ensures the release of **melatonin** in the (circadian) evening and thus acting as a time cue for the anticipating sleep. During wakefulness, **adenosine** levels gradually start to increase, inhibiting arousal and causing sleepiness. Adenosine levels can only be decreased when asleep.
<!-- The succeeding figure illustrates the concept of sleep pressure. -->

<p align="center">
  <img src="/images/why_sleep/urge.png" width="100%"/>
  <figcaption><small><p align="justify"><b>Fig. 3: Sleep pressure can be seen as the "gap" between the wake drive and sleep drive process. On the left graph, we focus on a point with low sleep pressure, as we are in the (circadian) noon, we observe low levels of melatonin, and the adenosine levels are gradually building up. The right graph indicates a moment with high sleep pressure, i.e., the (circadian) evening. Also note the adenosine depletion during sleep, thus lowering sleep pressure. Both these graphs are borrowed from "Why we sleep?"</b></p></small></figcaption>
</p>

However, after the agricultural revolution, humans started to mingle with their natural sleep-wake cycle. We can now mute the sleep signal of adenosine by using a chemical that makes you feel more alert and awake: **caffeine**. Caffeine levels peak approximately thirty minutes after consumption and has a half-life of five to seven hours. Next to this, we started spending more and more time looking at screens in our (circadian) evening. This inhibits the release melatonin, which makes sleep onset more difficult. Which on its turn results in a longer sleep onset duration and more worrisome sleepers.

## Sleep deprivation

Within this section, I will answer the following research question:

>*"How much sleep can a human lose each night, and over how many nights, before critical processes of the brain fail? Is that individual even aware of how impaired they are when sleep-deprived? How many nights of recovery sleep does it take to restore the stable performance of a human after sleep loss?"*.

A study has shown that ten days of 6-hour sleep was all it took to become as impaired in performance as going without sleep for twenty-hours straight [[1]](#Banks_consequences_sleep_deprvation). The most important finding from this study was that **you don't have any notion of how sleep deprived you actually are**. Additionally, three full nights of recovery sleep (i.e., more nights than a weekend) are insufficient to restore performance back to normal levels after a week of short sleeping.

**Regardless of the amount of recovery opportunity, the brain NEVER comes close to getting back all the sleep it has lost**. This is true for total sleep time, just as it is for NREM sleep and for REM sleep. **Humans (and all other species) can never get “sleep back”**. This takeaway from the book hit me really hard as I deprived myself significantly from sleep between my sixteenth and twenty-first year (getting 4-5 hours of sleep for several consecutive nights, sometimes resulting at 20 hours of sleep after 4 nights). I can now even note the consequences of this bad habit; I'm more forgetful, my spatial awareness declined, and was not such a 'thoughtful guy' during that period. Reading the consequence section of sleep deprivation, could give one some sleepless nights, so I will spare you from that.

><div align='justify'>Wakefulness is low-level brain damage, while sleep is neurological sanitation.</div>
><cite>— Matthew Walker</cite>

### But are you actually sleep deprived?

* After waking up in the morning, could you fall back asleep at 10 or 11 a.m.?
* If you didn’t set an alarm clock, would you sleep past that time?
* Do you need caffeine to function optimally before noon? (or did your brain deplete enough adenosine during sleep)

If the answer to either of these questions is yes, you are most-likely sleep deprived (and using caffeine as self-medication). So please, take your sleep seriously and try to apply as many tips from the last section!


## (Fun) facts
To finalize the theoretical part, I want to present you some facts. Some of these show the importance of sleep, but most importantly, they are all good conversation starters.

* **Post-pranial alertness dip**: All humans, irrespective of culture or geographical location, have a genetically hardwired dip in alertness that occurs in the mid afternoon hours.
* **Sleep is universal**: There is not a single organism which lives 24+ hours that does not enter a rest state to repair what has been damaged while active.
* **The power of naps**: Daytime naps as short as twenty minutes can offer a memory consolidation advantage.
* **Morning lark/Night owl**: For some people, their peak of wakefulness arrives early in the day, and their sleepiness arrives early at night. These are *morning types* and make up about 40 percent of the population. They prefer to wake at or around dawn, are happy to do so, and function optimally at this time of day. Next to this, there are *evening types*, whom account for approximately 30 percent of the population. They naturally prefer going to bed late and subsequently wake up late the following morning, or even in the afternoon. The remaining 30 percent of people lie somewhere in between morning and evening types, slightly leaning towards evenings, like myself.
* **Be rational**: If you deprive yourself of sleep, you'll mostly lose REM (dream) sleep, which is important for emotional intelligence and stability. Heavily sleep deprived people (such as world leaders) are thus less capable of making rational decisions and empathizing with others.
* **For the bodybuilders**: When given just five and a half hours of sleep opportunity, more than 70 percent of weight loss comes from lean muscle, not fat. When offered eight and a half hours’ bed-time, over 50 percent of weight loss comes from fat while preserving muscle.
* **Beauty sleep**: Studies have shown that only one night of 5-hour sleep results in looking more fatigued, less healthy, and significantly less attractive, compared to your looks after a full night of 8 hours of sleep opportunity [[2]](#Beauty_sleep).
* **Late night snack**: The less you sleep, the more you are likely to eat. Inadequate sleep decreases the “I’m full” signal, whilst amplifying the “I’m still hungry” feeling.

### Not so fun facts

* **Sleep loss and the reproductive system (men)**: Men who report sleeping too little have a 29 percent lower sperm count than those obtaining restorative full nights of sleep. Additionally, under-slept men also have significantly smaller testicles than well-rested counterparts.
* **Sleep loss and the reproductive system (women)**: Routinely sleeping less than 6 hours a night results in a 20 percent drop in the follicular-releasing hormone in women.

And last, but not least:

* **Sleep loss and the immune system**: A study showed that a single night of sleeping just 4 hours wept away 70 percent of the natural (cancer) killer cells circulating in the immune system, relative to a full eight-hour night of sleep [[3]](#Sleep_immune).


## Tips for a better night sleep

Now it's time to provide you with some practical guidelines towards a better sleep hygiene. Most of the succeeding tips are distilled from [[4]](#12_tips):

* **Stick to a sleep schedule**: Go to bed and wake up at the same time each day. Yes, this also includes the weekends. As creatures of habit, people have a hard time adjusting to changes in sleep patterns. Sleeping later on weekends won’t fully make up for a lack of sleep during the week and will make it harder to wake up early on Monday morning. Set an alarm for bedtime. Often we set an alarm for when it’s time to wake up but fail to do so for when it’s time to go to sleep. *If there is only one piece of advice you remember and take from these tips, this should be it*.
* **Don't exercise too late**: Exercise is great, but not too late in the day. Try to exercise at least thirty minutes on most days but not later than 2 to 3 hours before bedtime.
* **Avoid caffeine and nicotine**: Coffee, colas, certain teas, and chocolate contain the stimulant caffeine, and its effects can take as long as 8 hours to fully wear off. Therefore, a cup of coffee in the late afternoon can make it hard for you to fall asleep at night. Nicotine is also a stimulant, causing smokers to sleep only very lightly. Additionally, smokers tend to wake up too early in the morning because of nicotine withdrawal.
* **Avoid alcoholic drinks before bed**: Having a nightcap before sleep may help you relax, but heavy use reduces both your REM and deep sleep, keeping you in the lighter sleep stages.
* **Avoid large meals and beverages late at night**: A light snack is okay, but a large meal can cause indigestion, which interferes with sleep. Drinking too many fluids at night can cause frequent awakenings to urinate.
* **Don’t take naps after 3 p.m**: Naps can help make up for lost sleep, but late afternoon naps can make it harder to fall asleep at night.
* **Relax before bed**: Don’t over schedule your day so that no time is left for unwinding. A relaxing activity, such as reading or listening to music, should be part of your bedtime ritual.
* **Take a hot bath in the evening**: The drop in body temperature after getting out of the bath may help you feel sleepy, and the bath can help you relax and slow down so you’re more ready to bed.
* **Create a dark, cool, and gadget-free bedroom**: Get rid of anything in your bedroom that might distract you from sleep, such as noises, bright lights, an uncomfortable bed, or warm temperatures. You sleep better if the temperature in the room is kept on the cool side. A TV, cell phone, or computer in the bedroom can be a distraction and deprive you of needed sleep. Having a comfortable mattress and pillow can help promote a good night’s sleep. Turn the clock’s face out of view so you don’t worry about the time while trying to fall asleep.
* **Have the right sunlight exposure**: Daylight is key to regulating daily sleep patterns. Try to get outside in natural sunlight for at least thirty minutes each day. If possible, wake up with the sun or use very bright lights in the morning. Sleep experts recommend that, if you have problems falling asleep, you should get an hour of exposure to morning sunlight and turn down the lights before bedtime.

I sincerely hope that this makes you take sleep more seriously. Your loved ones will thank you for doing so.

---

## References
<a name='Banks_consequences_sleep_deprvation'>
[[1]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1978335/) Banks, Siobhan. "Behavioral and physiological consequences of sleep restriction." Journal of clinical sleep medicine 3.05 (2007): 519-528.

<a name='Beauty_sleep'>
[[2]](https://www.bmj.com/content/341/bmj.c6614.short) Axelsson, John, et al. "Beauty sleep: experimental study on the perceived health and attractiveness of sleep deprived people." Bmj 341 (2010): c6614.

<a name='Sleep immune'>
[[3]](https://www.sciencedirect.com/science/article/pii/S088915910200003X) Irwin, Michael. "Effects of sleep and sleep loss on immunity and cytokines." Brain, behavior, and immunity 16.5 (2002): 503-512.

<a name='12_tips'>
[[4]](https://www.nlm.nih.gov/medlineplus/magazine/issues/summer12/articles/summer12pg20.html) Reprinted from NIH Medline Plus (Internet). Bethesda, MD: National Library of Medicine (US); summer 2012. Tips for Getting a Good Night’s Sleep