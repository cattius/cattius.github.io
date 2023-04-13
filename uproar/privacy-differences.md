---
layout: page
title: What Does Privacy Mean To Your Users?
permalink: /uproar/privacy-differences
---

We each see the world through a set of cultural goggles - what Lipartito describes as "a system of values, ideas, and beliefs which constitute a mental apparatus for grasping reality". In other words, our mental operating system: the **software of the mind**. Each person's goggles are uniquely their own, and we're often blind to the fact that we and everyone around us are wearing them. 

I've never seen my goggles, but if you put me on the spot and demanded I describe them, then I'd *guess* that mine are about 1/3 British 🇬🇧 culture, 1/3 Austrian 🇦🇹🇦 and EU 🇪🇺 cultural values, and 1/3 other influences in my life (the US 🇺🇸, the Catholic church ⛪, the software industry 👩‍💻, hacking/infosec 🥷, and a fair few more I'm not even aware of). Of course, we could dig even deeper into what my goggles are made of: which cultural part of British society am I really talking about? "British culture" looks very different on the factory floor than it does at Eton, and looks different again in Glasgow versus in Cornwall.

**What do you think your cultural goggles are made of?**

These goggles determine how we perceive others, how we behave in our daily lives, and how we filter and evaluate information in general. In this module, we're going to try to lift up our goggles for a second and imagine how yur users around the world might see the world through their goggles. Of course, we won't be able to cover everything: cultural comparison and analysis is the domain of entire research fields. Fortunately, you don't need to be a cultural expert to design privacy-preserving software: the key thing is to **be aware of your own goggles**. Build as diverse a team as you can, try your best to imagine how your users' needs might differ from your own when you're designing and threat modeling, and acknowledge when you've reached the limits of your imagination and need to do further research or consult an expert.

 * hofstede, hall
 * compare UK and austria as example - even amongst cultures we think of as super similar and lump together as 'europe', there are differences
 * collectivist societies - individual right to 'be let alone' may not make sense if you share a house with all your relatives
 * saving face, family honor. buddhist perspective.
 * high context societies - designing communication apps. gulf social media examples

## Hofstede's Cultural Dimensions Theory
One tool we can use to understand our users' cultural context is Hofstede's cultural dimensions theory, which is a framework for cross-cultural communication. It was initially created by Geert Hofstede as part of his study of employee values worldwide at IBM from 1967-1973. Now of course, no single framework could ever capture the nuances of all possible cultural differences, and there are many alternative ways to make a comparison that would prioritize other values. But it's still a helpful starting point, and you might be surprised by how substantially countries differ.

TODO.

https://www.nspw.org/papers/2017/nspw2017-wang.pdf - inclusive privacy, mentions under-represented populations around the world

## Case Study: Social Media in the Arab Gulf
* https://arxiv.org/ftp/arxiv/papers/1604/1604.03626.pdf Privacy and Social Media in the context of the arab gulf
* https://norahak.com/2015/11/26/fatwas-and-social-media/. if a woman constantly has a man watching over her shoulder, how can you protect her privacy? what could you hide from the screen? similar idea to protecting privacy of partially-sighted people
* https://dl.acm.org/doi/10.1145/2702613.2702629 - saudi youth, privacy, intimacy and freedom of expression

## Children's Privacy
TODO.
* https://iapp.org/news/a/a-view-from-dc-privacy-gets-inclusive/ - california's age-appropriate design code, UK has one too
* privacy policies and notifications must be accessible for children
* related laws like COPPA
* don't overprotect or censor - autonomy and self-determination

## Employee Privacy
* Microsoft productivity score
* https://crackedlabs.org/daten-arbeitsplatz

## Privacy and Accessibility
TODO.
* Privacy challenges for partially-sighted individuals - some research into this - Apple has a mode to help a little with this that darkens the screen with a wave

## Privacy for High-Risk Individuals
* Political activists, journalists, whistleblowers - https://www.youtube.com/watch?v=dEjZiAGM7YY could be relevant, ISOC content + reading lists Article 19
* Victims of stalking or domestic violence. Eva Galperin's work, Coalition against Stalkerware.
* Politicians, active military, public figures  -> example of Parler traffic starting to be routed through Russia overnight after AWS takedown

## Privacy at War
> "When being visible from the sky is legally considered being in public, a fence is no longer protection from prying eyes."
* https://www.publicbooks.org/can-drones-have-ethics/
* Use of biometrics in Ukraine; privacy in Ukraine; privacy for refugees and border policing.

## Intersectional Privacy and Value Sensitive Design
* THESE ARE SOCIOTECHNICAL SYSTEMS! good overview of applying design thinking to privacy: http://library.usc.edu.ph/ACM/CHI2019/1proc/paper262.pdf
* https://link.springer.com/chapter/10.1007/978-3-030-82786-1_13 - links everything together. includes Gulf states privacy research, accessible privacy, disability
* https://hbr.org/2019/01/the-era-of-move-fast-and-break-things-is-over - Minimum Virtuous Product instead of MVP
* http://techpolicylab.uw.edu/wp-content/uploads/2017/10/TPL_Diverse_Voices_How-To_Guide_2017.pdf
* https://www.envisioningcards.com/?page_id=2#4
* http://securitycards.cs.washington.edu/cards.html
* https://faculty.washington.edu/pkahn/articles/vsd-theory-methods-tr.pdf - explains 3 parts of VSD
* https://techpolicylab.uw.edu/wp-content/uploads/2020/08/TPL-Instructional-Case-Studies-08-05-2020a.pdf
* https://uxdesign.cc/human-values-matter-why-value-sensitive-design-should-be-part-of-every-ux-designers-toolkit-e53ffe7ec436
* https://inclusiveprivacy.org/news.html
* canada AIDA, AI act - fundamental rights impact assessments

## Resources
* ["They Don't See Their Work As Surveillance": Jennifer Pan on Chinese Welfare and Society](https://www.publicbooks.org/they-dont-see-their-work-as-surveillance-jennifer-pan-on-chinese-welfare-and-society/)

## Bibliography
[^1]: *Culture and the practice of business history* by Kenneth Lipartito, Business and Economic History (1995), JSTOR. [PDF](https://citeseerx.ist.psu.edu/pdf/5ddc8c70a09315985e39852d0209701b8915281b).
[^2]: *Global Mindset as the Integration of Emerging Socio-Cultural Values Through Mindsponge Processes: A Transition Economy Perspective* by Quan Hoang Vuong, Global Mindsets: Exploration and Perspectives (1996), Routledge. [PDF](https://philarchive.org/archive/VUOGMA).
[^3]: *Privacy Rights and Protection: Foreign Values in Modern Thai Context* by Krisana Kitiyadisai, Ethics and Information Technology 7 (2005), Springer. [PDF](https://csts.arts.chula.ac.th/cest/feeds/Krisana/7156321v361p0324.pdf).
[^4]: *Privacy Protection: A Tale Of Two Cultures* by Subhajit Basu, Masaryk University Journal of Law and Technology 6 (2012). [PDF](https://core.ac.uk/download/pdf/230601209.pdf).
