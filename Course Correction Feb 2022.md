# Background

I've been creating Minecraft mods for... around five years?  My goal has always been to create content that hasn't been done in Minecraft before - content that _I_ want to see. For me, this is about creative expression - I _need_ to make things and to make them in a way that pleases me.

To that end, there is a specific mod I want to make.

The mod I want to make will require capabilities that don't exist in Minecraft and aren't readily available in modding frameworks or libraries.  At the start, I didn't know how to create these capabilities and the challenge of creating them was another source of motivation for me.

I initially tried to do everything at once and it was too much, so I began to create mods that were essentially studies - working mods that would force me to solve an important problem for the overall project but not overwhelming.

Eventually I decided to release some of these mods because, _why not?_  I had learned much by studying other mods and it seemed appropriate to give back in this way.  And while I am the primary audience, it does give me satisfaction to see others use and enjoy my work.

Sometime after that, I decided to make most of the capabilities I was developing available in the form of libraries because, again, _why not?_  It's objectively true that doing so has improved my code. Designing for others tends to squeeze out unhealthy practices.  And public libraries, if they are used at all, tend to attract feedback that informs more progress.

I've never done much to promote my mods because, to me at least, they are mostly experiments or works in progress - available for people to use but not really important or even "done". My mind has always been set on the end goal of the content mod I want to make.

As a result (and probably also because my tastes skew outside the norm) my audience has never been particularly large, and that has been fine with me.  I've not wanted the distraction of a "popular" mod.

But it turns out there's an answer to the question, _"why not?"_

# The Problem

It's clear now that a modest audience is not the same as _no_ audience.  I genuinely appreciate the interest shown by the community, and it is perfectly normal and reasonable for players and content makers to request improvements.

But what that means in practice is most of my time is spent writing code I either don't need, or which is more complicated than I need it to be.

Why is that?

Well, the mod I want to make is inherently incompatible with most other mods because of foundational gameplay features.  It's essentially a full conversion.  It doesn't need or want to depend on any third-party mods or modding platforms.

I _do_ envision third-party content within the context of the mod, and so APIs and JSON loaders remain valuable, so long as they support my workflow and improve the overall design.

But, if I am being selfish, there's no reason for me to add features I don't need, especially features that couple my code to other mods or archaic and suboptimal conventions (looking at you, Optifine).

And after considering my abysmally slow progress, I've concluded I either need to be more selfish, or I need to change my goals.

# Choices

The simplest choice would be to continue as-is, and accept that it may take many more years before I get to make the content I want to make, or that it may never happen. But I'm not getting any younger, and I want to do other things after this.  I'd burn out long before the end.

A second choice would be to fully embrace the goal of enabling other content mods and become primarily a library author. This has some appeal - I enjoy designing APIs and collaborating with other developers. And it never fails to improve my practice - there's always something more to learn.

But if my primary motivation is creative expression - and it is - then being a library author is ultimately unsatisfying.  My recent focus on libraries has already, to some extent, become a drain on my enthusiasm.

A third option would be to set aside Minecraft altogether and make a game of my own.  I probably _will_ do this at some point. I get no joy from dealing with the churn and constraints inherent in modding Mojang's game, especially when Mojang's stance towards PC mod authors - and I'm being charitable here - amounts to benign neglect.

Alas, I dusted off my design notes and spent some time writing story and dialog, and I still think this story is best told in the context of Minecraft. I reserve the right to change my mind, but it's either a Minecraft mod or I need to tell a different story.  And I still like the story I have.

So that leads me to the best choice for me: to be selfish and refocus my efforts on content.  I've pondered these choices for several weeks, and I expect this decision will stick.

# Hard Science

My decision may make more sense if I explain a tiny bit more about this mod I want to make...

It will be named _Hard Science_. The name is a reference to "hard" science fiction, where the world of the story obeys real-world physical laws, or at least speculates responsibly. The name is also a reference to difficulty - something vanilla Minecraft lacks. (Unless you equate grind with difficulty, which I do not)

You can expect it to deserve the appellation in both ways.

In the first five minutes you might think, "This is a Crash Landing remake," or "Someone ported Factorio back to Minecraft (again?)."  Yes, there's a kind of tech tree and there are objectives that drive the narrative forward, but you'll soon discover that story and character are the backbone of the experience.

It is essentially it's own game, set in Minecraft. It makes breaking changes to core Minecraft mechanics for _story_ purposes. These changes are extensive and can't be configured away without ruining the game. This, and the story-centric nature of the experience are what make it fundamentally incompatible with practically all other extant mods.

Why set it in Minecraft?  Well, it's a convenient plot device for this particular story.  More appealing to me is the opportunity to poke fun at the game so many of us know and love.  I won't say it's a deconstruction of Minecraft, but I also won't say it's _not_ that.

# So Now What?

Now I work on the mod I want to make!

In the near term, that's mostly writing and designing.  Taking a break has helped me realize the major technical problems are solved, or I've learned enough that I know how to solve them.

That's not to say the remaining coding will be easy or short - it's daunting.

And that is why it makes sense to flesh out the story and mechanics first, and then pare it down.  It can't all get done, and I'd rather cut out the less-than-great and wildly impractical bits before the remaining code is written.

I don't know how long this will take.  It could take a long time! And most of what I'm creating, even when I start writing code again, won't be publicly visible until the mod is in a playable state.  (I don't want to spoil it.)

This means you may not see much from me by way of updates.  Maybe I'll find some bits that work as teasers.  Maybe not.

# Wait... What About the Mods You Already Have?

This is the difficult part: I have no specific plans to develop or support my existing mods (library or content) going forward.  Some libraries _will_ see updates and improvements (because I need those) but... **_I won't address any issues or enhancement requests related to other mods or modding platforms, unless I happen to have the same requirement for my own content._**

In other words, I'm going to act like a selfish jerk who doesn't care about the people who have supported my mods up until now.

I don't like this.  It feels wrong and leaves me sad. It took weeks of agonizing, internal debate for me to finally accept that this is necessary.

But it _is_ necessary.  I know myself. If I don't set a hard boundary here and now, then there will always be "just one more thing" to do that is not the content I set out to make. My project will never progress, and I'll continue to exhaust my attention on a portfolio of half-finished mods and libraries until I burn out.  And if that's the outcome, I may as well give up now.

That out of the way, maybe it isn't as bad as it sounds...

All of my existing content mods (and some that have been teased but never published) will make an appearance in Hard Science. For example, do you like Exotic Blocks or Facility?  Those are merely previews of what's to come.  Been waiting patiently for Pyroclasm to work again? It's part of the story. But you'll have to wait until Hard Science ships - there will be no more updates from me.  I regret any disappointment or frustration this causes.

For my libraries, I will make updates, but with a twist - I'll have my own forks specifically to support the needs of Hard Science.  These forks will strip out any features or dependencies that get in my way, and will probably not be very compatible with other mods.  There won't be any non-maven distributions until Hard Science ships, and I will target a single mod loader (which will almost certainly be Quilt, as soon as it is ready).

For example, I still need Canvas, and I need it to have more features than it does today, but I _don't_ need it to be compatible with ancient resource pack standards I'll never use. Or as another example, I don't need it to work with Forge or Fabric's rendering hooks.

Why create a fork for my own libraries?  Because I want to leave space for others to carry them forward, now or in the future. I still think FREX and platform-agnostic APIs are a Good Idea. Sadly, I don't have the capacity to carry them forward in a way that supports the broader modding community.

In practice this means I'd be turning over day-to-day control of those mods to some other person or group of people who would chart a course forward.  We'd have a common baseline, so there will be an opportunity to share code in either direction, but not an obligation.

That said, I will probably retain some level of administrative control, at least for a while, until I'm confident I haven't unwittingly empowered yet another authoritarian asshole as a project leader - we have enough of those already.  But ultimately even the CurseForge/Modrinth pages (along with whatever minuscule revenue they bring) would have new owners.

With the vram.io domain and maven repo already created, some of the infrastructure is in place, and I'm happy to continue hosting these projects, for now, if that remains useful to their new owners.

So, do you want to carry the torch for Tress Do Not Float or Exotic Blocks? Do you want to take FREX or Canvas to the next level? If so, my DM's are open - let's talk.  I'd be gratified to see them continue without me.

# Conclusion

While this is a new beginning for Hard Science, it's also marks the end of my active involvement in my other mods. I'll still be around, but it will be different - something will be lost, and I will miss it.

I would not feel this way if not for the community of people who have used and contributed to those mods, along with the many people who assisted and encouraged me along the way.

And so, while this occasion may be sad, it is a gentle and reaffirming kind of sadness - a remembrance of something good that must fade away to make room for new opportunities.  

For all of that, I thank you.

Until next time,

Grondag<br>
February 27, 2022
