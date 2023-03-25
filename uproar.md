---
layout: page
title: UPROAR - The Privacy Engineering Course
permalink: /uproar/
---

## What is UPROAR?
UPROAR stands for **UnaPologetically opinionated Resources On Automation and human Rights**. (Yes, I never let reality get in the way of my acronyms.) This is a course on privacy engineering for technology professionals. It was born out of my frustration at two major issues with existing free online resources on privacy.

Firstly, they tend to be very abstract, referring to high-level concepts such as "Privacy by Design" and "Privacy by Default" without **concrete technical examples** of how to actually implement this in software. I'm an engineer: give me requirements, system diagrams, and software tooling! Yod Samuel Martín and Gabriel Pedroza illustrated this perfectly in their [presentation](https://edps.europa.eu/sites/edp/files/publication/12-06-19_samuel-martin_gabriel-pedroza_pdp4e-privacy-engineering-toolkit_en_0.pdf) on the PDP4E project:

![What engineers get for privacy vs. what they want](/images/uproar/engineers-want.jpg "A presentation slide contrasting the high-level concepts engineers are given as privacy requirements with the detailed system design diagrams they want")

Secondly, they tend to be **culturally normative**, assuming that we all already have a shared understanding of what privacy means. Given that even the US and Europe - with a huge base of shared culture to work with - can't agree on what privacy means, this seems like a pretty bold(ly inaccurate) assumption. This normativity sometimes also extends to assuming that privacy only matters in engineering for compliance purposes. As long as what we're doing is legal, it's okay, right? Not at all! As the title suggests, this course is strongly opinionated: it unapologetically takes an **ethics and human rights-based approach** to privacy engineering. Privacy is far more than just data protection legislation, and I hope I can convince you of that.

This course is completely free. But I do expect you to do something for me in exchange: going forward, make some noise about privacy in your work. Cause some UPROAR. Don't just roll your eyes the next time someone proposes "let's store data forever in our data lakehouse" or "the only meaningful metric for us is user enagement"; fight back!

## Prerequisites
If the phrases "make a PR" and the "software development lifecycle" are meaningful to you, then you're ready for this course. You don't need any privacy domain knowledge; we'll cover that as we go along.

This course is particularly aimed at software engineers and product managers. If you work in hardware engineering, I haven't forgotten about you, but many of the case studies will be less relevant for you. I apologize: I'm writing about what I know here, and my only exposure to hardware is attacking it rather than designing it. Still, I expect at least the first half of the course will be relevant, and I hope the rest will be transferable, giving you ideas on how you could incorporate privacy into the hardware development lifecycle. If you have hardware privacy experience you'd like to share, additional content is welcomed! Please see `Contributing` below.

## Course Modules

The course is under construction - stay tuned as modules are added.

1. What Even Is Privacy, Anyway: Are We Talking About The Same Thing?
2. Privacy Around The World
3. The Human Rights-Based Approach to Privacy
4. Defining Personal Data
5. Privacy in the Software Development Lifecycle
6. Data Governance
7. [Privacy Threat Modeling](/uproar/threat-modeling)
8. Product and UI Design: Privacy Dark Patterns
9. Dangerous Animals of Product Management: Privacy Edition
10. Privacy as Code
11. Privacy Enhancing Technologies (PETs)
12. Privacy in ML and AI
13. When Should I Talk To Legal?
14. Future Privacy Challenges

## Contributing

If you'd like to contribute content to this course, that's fantastic! Please feel free to get in touch with me to discuss your ideas or open a PR directly in the [GitHub repository](https://github.com/cattius/cattius.github.io). (This page is in the root folder as `uproar.md`; the individual course modules are in the `uproar` folder.)

In particular, I'm looking for help with the following:

* Translating the course content into other languages (high priority: French, Spanish, Arabic)
* Adding more region-specific content and case studies. How is privacy interpreted in your country or culture? Are there major privacy concerns being debated near you that aren't discussed here?
* Adding content on hardware privacy, as mentioned above
* Expanding beyond text-based content (audio, video, interactive exercises)

## Acknowledgments

This course began as part of my [Early Career Fellowship](https://www.internetsociety.org/fellowships/early-career/fellows/2023/) at the [Internet Society](https://www.internetsociety.org/). I'd like to thank my project mentor, the fellowship staff, the 2023 fellows, the Internet Society community, and all of the experts who gave up their time to teach us and debate technology policy with us during the fellowship. This course would not be the same without the whirlwind of ideas you exposed me to and the extensive feedback you provided. I'd also like to thank the [ECCRI European Cybersecurity Fellowship](https://eccri.eu/2023-2024-eccri-fellows/) staff, 2023-24 fellows, and workshop experts for the rewarding discussions on cybersecurity policy, and my team at [Dynatrace](https://www.dynatrace.com/) for their flexibility while I juggled my job with the two fellowships and of course their enthusiasm for all things privacy.

## License

This course is licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). You are welcome to remix and adapt this work non-commercially provided that you credit me as the original author and license your work identically. Entirely optional, but much encouraged: please let me know about your use cases for and remixes of this course! I'd love to hear about them and, with your permission, feature them here.

My interpretation of 'non-commercially' includes adopting this course internally as a training course for your employees, and I would encourage you to do so. You can see Creative Commons' guidance on this for details, but essentially: as long as you're not trying to sell this content for a profit, I don't mind. And yes, including this content in your corporate machine learning dataset, including for generative large language models (LLMs), counts as commercial use and is prohibited by the license. Hands off.