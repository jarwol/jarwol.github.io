---
title: "The Role of Alignment in High-Performing Teams: Part 1"
date: 2025-03-02
description: "Exploring strategies for achieving organizational alignment, focusing on vertical and long-term alignment."
tags: ["alignment", "org"]
categories: ["Culture", "Leadership"]
draft: false
---
Most of us have been part of “average” teams, but if you’re fortunate enough to have been part
of a high-performing team, the difference is striking. The high-performing team ships continuously,
delivering value to users seemingly exponentially faster, and does it with a higher quality bar.

I’ve often reflected on the high-performing teams that I’ve been a part of, what made them successful,
and why those conditions are so hard to sustain. My conclusion? There's no silver bullet. Many variables
contribute to team performance—company size, industry, location, and team composition, just to name a few.

That being said, there do exist conditions which, when absent, make it nearly impossible for a team to
achieve high performance. Of those, I’ve found one to be particularly crucial: alignment.

## Let’s align on alignment

Before I launch into some concrete strategies for building alignment in an organization, it’s necessary
to be crystal clear about what it is and why it’s important. Fittingly, difference in interpretation of terminology
is a common cause of friction and misalignment that can hurt team performance. So I’m going to define alignment as:

> Every member of a team or organization sharing a common understanding of goals, priorities, and strategic direction.

Alignment is so critical because performance is a vector–it includes directionality. At the risk of using a cliché analogy,
consider a rowing team. Even if the team consists of the strongest individual rowers in the race, the boat won’t move efficiently
if everyone isn’t rowing in sync toward the finish line, and they’ll lose the race.

How about a less contrived example? Imagine a streaming company that has a goal of decreasing subscriber churn rate. Imagine a streaming company that wants to reduce subscriber churn. The Analytics team identifies a key insight--Subscribers who take more than a minute to find content are much more likely to churn.
Meanwhile, the Content Engineering team meets with the Infrastructure team and learns that the company's storage and bandwidth costs represent a significant and growing portion of overall technology spend. They determine that leveraging a new video format with better compression will result in major savings with only a negligible decrease in stream quality. At first glance, this seems like a good initiative--it materially improves the company's bottom line, but it's an example of organizational misalignment. Reducing operating expenses is not the main focus of company strategy, so it’s unlikely to lead to an outcome that leadership is happy with. It doesn’t matter if the Content Engineering team is firing on all cylinders and shipping code faster than any other team in the company. They’re moving in the wrong direction.

### Horizontal and vertical alignment
That hypothetical organization exhibited good **horizontal alignment**, but poor **vertical alignment**.
Picture your company’s org chart. Horizontal alignment is alignment between members of the same team and between different
teams and functions at roughly the same level of the organization. Vertical alignment refers to top-down alignment from
the CEO (and the Board) down to the rest of the C-suite, then their direct reports, and so on down to the individual contributors.
{{< figure src="images/vert-horiz-alignment.svg" alt="Vertical vs. horizontal alignment" width="600px" >}}

Expanding on the streaming company example above, good vertical alignment would be all of the relevant teams understanding
the goal of reducing subscriber churn, and good horizontal alignment would be the Content Engineering team, Product Management,
and Design collaborating to implement better personalized content tiles on the home screen that will reduce the average time
to find and play content. Both types of alignment are important and come with their own unique challenges, but I’m going to
focus primarily on vertical alignment strategies.

Achieving vertical alignment is like a game of telephone, where a little bit of context is lost as strategy and direction are communicated to the next level down, until the people actually tasked with executing on that strategy end up misaligned with what leadership expects. The more layers an organization has, the more alignment gets lost in translation.

{{< figure src="images/alignment-loss.svg" alt="Loss of alignment" width="250px" class="float-right" >}}

Thinking of it mathematically, imagine there is a percentage of the strategy, the coefficient of misalignment, that is miscommunicated or misinterpreted as you move each level lower in the org chart. Let’s conservatively assume it’s 5%. In a 10-person startup with only two levels of hierarchy, we end up with 95% alignment in the worst case. Not bad! But vertical alignment becomes more difficult to achieve as an organization grows and adds more levels to the hierarchy. In a large enterprise with eight levels of hierarchy, for example, the alignment at the bottom level is $0.95^6 = 74%$. The teams doing the work are now more than a quarter misaligned with the company vision. 

## Tools for long-term alignment

For any of you in a leadership role, there’s a fairly intuitive reason for this cascading loss of context.
As leaders, we’re often in meetings or conversations with our peers where strategy, goals, and other topics that contribute
directly to alignment are discussed. Through sheer force of exposure in these settings, leaders build alignment with each other,
and it becomes easy to forget that the folks reporting to you don’t have all that context. It takes deliberate planning to ensure your vision and priorities are clear to the people who are charged with executing it.
There’s no shortage of tools and strategies you can implement, but I recommend at least one for long-term alignment (2+ years)
and one for mid-term alignment (one quarter to one year). The rest of this post will focus on tools for long-term alignment,
and I’ll follow up with another one covering the rest of the alignment process.

### Conveying purpose

The goal of driving long-term alignment is to develop a shared understanding of the prevailing reason(s) your organization
exists and how it operates. Vision, mission, purpose, and charter are all tools you might’ve come across that are aimed at addressing that need. I like using a vision and mission statement for large organizations with a broad remit and charters for individual teams or
small orgs that are more narrowly scoped. This isn’t an exact science, though. You should use whatever feels right to you and your team.

A vision statement should be inspirational and reflect the aspirational future state of an organization. It should rarely need to change except in the case of a significant company pivot. A mission statement focuses on more specifics about what the strategy is right now in service of the vision. Consider Amazon:
> **Vision**: To be Earth’s most customer-centric company, where customers can find and discover anything they might want to buy online.

> **Mission**: We strive to offer our customers the lowest possible prices, the best available selection, and the utmost convenience.

The vision and mission statements are both broad and inspirational, but the mission mentions prices, selection, and convenience as levers to make Amazon Earth’s most customer-centric company. 

Here’s another example from the Platform Engineering org that I currently lead:
> **Vision**: To enable effortless innovation of the products that drive our business.

> **Mission**: To empower our technologists to create, deliver, and operate high quality software quickly, reliably, securely, and cost-effectively.

While the mission statement specifically references enablement of better software development, the vision statement is broader and reflects our north star of making it easier and faster for our company to innovate and deliver value to our customers by any means possible. Visions and missions are great for being able to quickly reflect on any initiative or decision and ask “is this in service of our overall vision?”

Each individual team in my organization also has a team charter that succinctly describes why the team exists and in some cases how they accomplish their goals. Here are a couple examples:
- **Developer Experience** - “Optimize developer productivity and satisfaction through tooling and resources focused on the local development experience.”
- **Platform Observability** - “Enable deep operational visibility, data-driven insights, and incident response capabilities for platform systems.”
Charters clarify how each team contributes to the organizational vision and mission and help with horizontal alignment and responsibility lines between teams. They also serve as great elevator pitches for explaining what the team does to other people.

### Building culture

The final technique that I’ve found helpful for long-term organizational alignment is adopting **organizational principles**
(aka core values aka leadership principles). Org principles are a way to broadcast the values that the organization prioritizes,
serving as a framework for shaping culture, making decisions, and guiding behavior. I’ll again look at Amazon as arguably the
best example of a company who truly buys into this concept. Amazon’s [leadership principles](https://www.amazon.jobs/content/en/our-workplace/leadership-principles) permeate all parts of the company culture. They’re covered in interview sessions, they’re part of year-end performance reviews, and employees actually reference them frequently in everyday discussions:
> Following up directly with the user who reported that bug was a great show of **customer obsession**, Maria!

> In service of **bias for action**, I’m going to move forward with option A.

This sort of investment and operationalization is the difference between org principles which contribute to a consistent, positive culture and just a bunch of buzzwords on a wiki page that nobody pays attention to. 

I’ve admittedly borrowed from my time at Amazon in some of the specific ways that I try to integrate org principles into my own teams’ cultures. Here are some practical suggestions for successfully leveraging org principles in your team:
1. **Involve the whole team**. Whether you’re starting a new organization or introducing org principles for the first time, include as much of the team in the process as possible. That doesn’t necessarily mean starting from scratch and brainstorming with your entire organization, though. I recommend drafting a set of potential principles with your immediate leadership team and then pulling in the larger team to ask questions, provide input, or even vote on which to include if your draft list is a superset of what you want to end up with. It’s important that people have a chance to weigh in and feel heard in order to get the right kind of buy-in at the start.
2. **Publish them prominently**. Display your org principles on the front page of your team’s internal wiki, on the canvas of your org Slack channel, or wherever else your team will see them frequently. Ensure everyone in the org knows where to find them.
3. **Integrate them into your hiring processes**. Explicitly assign org principles for each interview session to cover and build up a question bank that interviewers can draw from to get a useful signal from candidates on each of them. Have recruiters or hiring managers share the org principles with candidates in advance of the interview to emphasize their importance to the team.
4. **Include them early on in your onboarding process**. Within the first week of joining the team, present new hires with the org principles, their significance, and how they impact the team culture.
Make them part of career growth. Publish expectations for org principles for each role/level on the career ladder and have managers give feedback throughout the year and during any formal performance review processes you have. Make them an important part of promotion criteria.
5. **Embrace them in your day-to-day**. Follow the Amazon examples from above and publicly praise team members when they demonstrate org principles. Ensure your leaders are doing the same, and it will quickly spread to the rest of the organization.

One final thing to know about org principles is that they work well in relative priority order. It clarifies the true focus of your org culture and helps guide action when two or more principles are opposed. For example, my top org principle is ***customer focus*** and number three is ***be data-driven***. Most of the time these principles are aligned, since we’re often collecting more data to better understand user pain points and where to invest our effort to improve their experience. Consider a scenario, however, in which we’re working on a new release of our infrastructure-as-code library that eliminates boilerplate code and greatly simplifies the process of creating and deploying services on our platform. The feature has confirmed interest from a number of our users, and it will be dev-complete by the end of the week. We also want to instrument the library to emit telemetry events to understand who is using the library, what resources are being created, and when errors occur. The telemetry functionality is expected to take another two weeks to implement. Using the org principles as a guide, we would note that ***customer focus*** is higher priority than ***be data-driven***, and decide to release the new library without telemetry in order to get it in our users’ hands sooner. Then we would follow up with a new version that includes telemetry when it’s ready. We’d be forgoing some useful data for a couple weeks, but it’s a good compromise when we’re pretty sure it’ll make our users happy faster.

That’s it for long-term alignment! The next post is going to focus on achieving mid-term alignment using OKRs and, finally,
how to translate this all into a strategic roadmap that executes on the priorities conveyed through this top-to-bottom alignment.
