---
layout: page
title: UPROAR - The Opinionated Privacy Engineering Course
permalink: /uproar/
---

## What is Privacy Engineering?
Privacy engineering is where software, the law, and ethics meet, with the aim of ensuring that everyone has their rights respected and their data processed fairly.

When data protection law requires state-of-the-art technical protections, engineers *must* be involved to implement these, yet there's often a huge communication gap between legal and engineering teams. They're both experts in their domains, but have very different perspectives on the product and find it hard to find common ground. With their combined engineering and privacy domain knowledge, privacy engineers help bridge this gap, 'translating' law and policy directly into code, or into technical requirements for other engineers to implement. But you don't need to be a (prospective) privacy engineer to benefit from this course. By learning a little domain knowledge and engaging on ethical questions, *everyone* can help bridge the gap to ensure the products we build respect users' rights and make the world a better place, not a worse one.

Which rights are we talking about protecting here? Well, data protection law establishes rights for each individual (the 'data subject'). The EU [GDPR](https://gdpr.eu/), for example, includes a right to have your personal data deleted, also known as the 'right to be forgotten'. At first, this sounds straightforward: of course you should have the right to delete your account from a product you no longer use. But enabling this in practice might require database and code changes in many different systems (some maintained by third parties), coordination between teams across the company, and legal advice to determine what data should and should not be removed. That’s when you call in the privacy engineers.

It's important to remember, however, that individual rights extend far beyond data subject rights. The right to privacy (Article 12) is just one of the 30 Articles in the [United Nations Universal Declaration of Human Rights](https://www.un.org/en/about-us/universal-declaration-of-human-rights). Violating someone's privacy may violate their other rights too, and while these rights are mostly complementary, sometimes they can be in conflict with one another, leading to hard ethical choices. How might privacy abuses violate the right to freedom of thought? And to what extent should we restrict freedom of speech to protect privacy? We'll explore these ethical questions and others like them in this course.

## What is UPROAR?
UPROAR stands for **UnaPologetically opinionated Resources On Automation and human Rights**. (Yes, I never let reality get in the way of my acronyms.) This is a course on privacy engineering for technology professionals. It was born out of my frustration at two major issues with existing free online resources on privacy.

Firstly, they tend to be very abstract, referring to high-level concepts such as "Privacy by Design" and "Privacy by Default" without **concrete technical examples** of how to actually implement this in software. I'm an engineer: give me requirements, system diagrams, and software tooling! Yod Samuel Martín and Gabriel Pedroza illustrated this perfectly in their [presentation](https://edps.europa.eu/sites/edp/files/publication/12-06-19_samuel-martin_gabriel-pedroza_pdp4e-privacy-engineering-toolkit_en_0.pdf) on the [PDP4E project](https://www.pdp4e-project.eu/) [^1]:

![What engineers get for privacy vs. what they want](/images/uproar/engineers-want.jpg "A presentation slide contrasting the high-level concepts engineers are given as privacy requirements with the detailed system design diagrams they want")

Secondly, they tend to be **culturally normative**, assuming that we all already have a shared understanding of what privacy means. Given that even the US and Europe - with a huge base of shared culture to work with - can't agree on what privacy means [^2], this seems like a pretty bold(ly inaccurate) assumption. This normativity sometimes also extends to assuming that privacy only matters in engineering for compliance purposes. As long as what we're doing is legal, it's okay, right? Not at all! As the title suggests, this course is strongly opinionated: it unapologetically takes an **ethics- and human rights-based approach** to privacy engineering. Privacy is far more than just data protection legislation, and I hope I can convince you of that.

This course is completely free. But I do expect you to do something for me in exchange: going forward, make some noise about privacy in your work. Cause some UPROAR. Don't just roll your eyes the next time someone proposes *"let's store data forever in our data lakehouse"* or *"the only metric that matters is user enagement"*; **fight back**!

## Prerequisites
If the phrases "make a PR" and the "software development lifecycle" are meaningful to you, then you're ready for this course. You don't need any privacy domain knowledge; we'll cover that as we go along.

This course is particularly aimed at software engineers and product managers. If you work in hardware engineering, I haven't forgotten about you, but many of the case studies will be less relevant for you. I apologize: I'm writing about what I know here, and my only exposure to hardware is attacking it rather than designing it. Still, I expect at least the first half of the course will be relevant, and I hope the rest will be transferable, giving you ideas on how you could incorporate privacy into the hardware development lifecycle. If you have hardware privacy experience you'd like to share, additional content is welcomed! Please see `Contributing` below.

## Course Modules
The course is under construction - stay tuned as modules are added.

* [Introduction - What is Privacy?](/uproar/introduction)
* [What Does Privacy Mean To Your Users?](/uproar/privacy-differences)
* Ethical Dilemmas in Privacy
* Defining Personal Data
* Data Protection Law Around The World
* Privacy in the Software Development Lifecycle (SDLC)
  1. Introduction
  2. Product Design Case Studies
  3. UI Dark Patterns
  4. [Privacy Threat Modeling](/uproar/threat-modeling)
  5. Dangerous Animals of Product Management, Privacy Edition
  6. Privacy as Code
  7. Privacy Enhancing Technologies (PETs)
  8. Privacy in ML and AI
  9. When Should I Talk To Legal?
* [Future Privacy Challenges](/uproar/future)

## Out of Scope
This course is intended to teach you how to protect your users' privacy in the digital products you build. It does not attempt to cover how to protect your own personal privacy. However, your personal privacy is hugely important, both for your own future and for our collective privacy as a society. If you haven't dived into this topic already, you'll likely find the first sections of this course (prior to `Privacy in the Software Development Lifecycle (SDLC)`) helpful to understand why we should be concerned about privacy at all. Beyond this, a great starting point for tools and best practices to defend your personal privacy is the Electronic Frontier Foundation's [Surveillance Self-Defense guide](https://ssd.eff.org/).

## Contributing
If you'd like to contribute content to this course, that's fantastic! Please feel free to get in touch with me to discuss your ideas or open a PR directly in the [GitHub repository](https://github.com/cattius/cattius.github.io). (This page is in the root folder as `uproar.md`; the individual course modules are in the `uproar` folder.)

In particular, I'm looking for help with the following:
* Translating the course content into other languages (high priority: French, Spanish, Arabic)
* Adding more region-specific content and case studies. How is privacy interpreted in your country or culture? Are there major privacy concerns being debated near you that aren't discussed here?
* Adding content on hardware privacy, as mentioned above
* Expanding beyond text-based content (audio, video, interactive exercises)

## Acknowledgments
This course began as part of my [Early Career Fellowship](https://www.internetsociety.org/fellowships/early-career/fellows/2023/) at the [Internet Society](https://www.internetsociety.org/). I'd like to thank my project mentor, the fellowship staff, the 2023 fellows, the Internet Society community, and all of the experts who gave up their time to teach us and debate technology policy with us during the fellowship. This course would not be the same without the whirlwind of ideas you exposed me to and the extensive feedback you provided. I'd also like to thank the [ECCRI European Cybersecurity Fellowship](https://eccri.eu/2023-2024-eccri-fellows/) staff, 2023-24 fellows, and workshop experts for the rewarding discussions on cybersecurity policy, and my team at [Dynatrace](https://www.dynatrace.com/) for their flexibility while I juggled my job with the two fellowships (and of course their enthusiasm for all things privacy!).

## License
<img src="../images/uproar/by-nc-sa-eu.png" alt="The CC-BY-NC-SA EU logo" height="35">

This course is licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). You are welcome to remix and adapt this work non-commercially provided that you credit me as the original author and license your work identically. Entirely optional, but much encouraged: please let me know about your use cases for and remixes of this course! I'd love to hear about them and, with your permission, feature them here. 

Please note that only the text and images I have produced for this course are covered by this license. It does not cover third-party content I link to, or quotes and images used from external sources; where relevant, I provide attribution and license information in a dedicated section on each page. My interpretation of 'non-commercially' includes adopting this course internally as a training course for your employees, and I would encourage you to do so. You can see Creative Commons' [guidance](https://creativecommons.org/faq/#does-my-use-violate-the-noncommercial-clause-of-the-licenses) for details, but essentially: as long as you're not trying to sell this content for a profit, I don't mind. And yes, including this content in your corporate machine learning dataset, including for generative large language models (LLMs), counts as commercial use and is prohibited by the license. Hands off.

## Footnotes and Attribution
[^1]: Slide screenshot used with permission. See slide 15 of the [original presentation](https://edps.europa.eu/sites/edp/files/publication/12-06-19_samuel-martin_gabriel-pedroza_pdp4e-privacy-engineering-toolkit_en_0.pdf) for full image attribution; the combined images were cited under right of quotation or provided by PDP4E project partners. *PDP4E: Methods and Tools for GDPR Compliance through Privacy and Data Protection Engineering* was an EU-funded project from 2018-2021 which developed a range of resources and software tools to help software and system engineers systematically apply privacy principles in their work. You can check it out on the [project website](https://www.pdp4e-project.eu/).
[^2]: See for example *Of Privacy and Power: The Transatlantic Struggle over Freedom and Security* by Henry Farrell and Abraham L. Newman, Princeton University Press (2019).