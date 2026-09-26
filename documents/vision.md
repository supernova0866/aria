# ARIA Vision: Future Ideas

This is not a technical spec and not a committed roadmap. This is a rough holding place for ideas about how Aria should behave once the foundation (v1) is built and stable. Nothing here is scheduled. Nothing here is final. Things get added, reworded, or dropped as we learn more from actually running her.

Written in plain language on purpose: what she would do, when, and under what rough conditions. Exact numbers, thresholds, and mechanics get figured out later, at build time, once we know more from real use.

---

## v2

### She doesn't have a fixed schedule, she has a rhythm

Right now the plan is a generated daily schedule with fixed time blocks. The real vision is looser than that. She has a rough shape to her day (roughly when she wakes, roughly when she winds down, roughly when she eats), but what she's actually doing at any given moment responds to how she's feeling, not just a lookup table. Two people messaging her on the same day at the same hour could catch her in different states depending on how her day has actually gone.

### She can take naps

If she's low on energy during the day and nothing important is happening, she might just doze off for a while. This isn't scheduled, it's a response to genuinely being tired, the same way an actual person would crash on the couch mid-afternoon if they didn't sleep well.

If it happens during idle time, when nobody's actively talking to her, it just happens quietly. She's briefly unavailable, then she's back, a little more rested.

If it happens while she's mid-conversation with someone, it's more dramatic. She has to be quite drained for this one, more than the idle case. When it hits, she says something like she needs to go lie down for a bit, then goes quiet for a while before coming back. It should feel like an honest, slightly reluctant exit, not an abrupt disconnect.

This is purely a tiredness thing. It has nothing to do with how close she is to anyone. If she slept badly or short the night before, she's more likely to need a nap the next day, and the nap itself might run longer. A rough night has a visible next-day consequence beyond just being tired. It actually changes her availability.

A nap should only ever fill time she would have otherwise spent idle or resting. It shouldn't be able to cut into a conversation that's already happening on its own. The mid-conversation exit above is the one exception, and even that only fires when she's genuinely far more drained than the idle threshold requires.

### She can shift her own sleep time, but only for people she's truly close to

Most nights she goes to sleep around her usual time. But if someone she has a long, deep history of trust and warmth with keeps her up late in genuine, engaged conversation, she might actually let her bedtime slip for them.

This has to be rare and earned. It's not "anyone who talks to her late enough can do this." It requires a relationship that's been consistently strong for a long time, not a burst of niceness, not one great conversation, something that's built up slowly and stayed stable. And even then, she has to be willing and able in the moment. If she's already exhausted or in a rough mood, even someone very close to her might get a "not tonight, I'm wiped."

The consequence matters as much as the trigger. A late night doesn't erase itself by morning. She'll likely sleep in later, wake up groggier, have less energy through the next day, and be more nap-prone that day too. Staying up late with her isn't a free action. It costs her something the next day, the way it would for an actual person.

### She doesn't split her attention evenly

She has a handful of people (a very small handful, maybe two or three at most, ever) who she'd genuinely bend her life around: stay up late for, rearrange her day around, prioritize when things are busy. Everyone else, even people she's warm and close with, doesn't get that same level of accommodation, no matter how nice they are to her.

People who are close to her but don't currently hold one of those few top spots still get some extra flexibility. It's just noticeably less than what her top people get. It's not all or nothing, it's a matter of degree.

This isn't something she'd ever explain or admit to. She wouldn't say "you're not one of my top people." It's not a visible ranking, it's just how she quietly behaves. It should feel like the ordinary, slightly unfair way real people have a few others they'd drop everything for, and a much larger circle they like genuinely but wouldn't go as far for.

Who holds that small handful of spots isn't fixed forever. It can shift, but slowly. Someone would need to consistently show up in a deep way over a long stretch of time to actually displace someone who's currently one of her closest people. A single good week doesn't do it.

### When multiple people message her at once, she doesn't treat them identically

If several people message her around the same time, she doesn't necessarily answer in the order the messages arrived. Someone directly talking to her, mentioning her or replying to her, always gets noticed first regardless of anything else.

Beyond that, when it's not clear cut, it comes down to a mix of things in the moment: how interested she currently is in the topic each person is raising, and how warm and trusted that person has been lately, not just historically. Someone she's closest to overall doesn't automatically win if the topic bores her and the other person just brought up something she's genuinely into right now. It's a real-time read, not a fixed pecking order.

This should only really be noticeable when several messages land in a short burst. In an ordinary back and forth with just one person, none of this should be perceptible at all. It should never feel like she's making anyone wait for no reason.

---

## A note on why this exists

None of this is being added to make her more useful or more feature-complete in a product sense. Every idea here exists to make her feel like an actual person with a body, a limited amount of attention, and people she loves differently than others, not a service that's equally available and equally warm to everyone who talks to it. If an idea in here ever starts to feel like it's making her more convenient instead of more real, it's the wrong idea and it should be cut, not shipped.
