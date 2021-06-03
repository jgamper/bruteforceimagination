---
layout: post
title: "Notes from Google Startup Accelerator"
date: 2020-08-02T08:18:30-04:00
description: Some key thoughts written down
comments: true
---

At Cervest, we were [accepted](https://blog.google/outreach-initiatives/entrepreneurs/11-startups-addressing-global-problems)
to Google Startup Accelerator along with 11 other startups, from more than 1,200 applications in total. By then, 
we already had some experience with accelerators,
e.g. [Creative Destruction Lab (CDL)](https://www.creativedestructionlab.com/locations/oxford/). 

<div class="img">
    <img class="col three" src="{{ site.baseurl }}/assets/img/accelerator/oxford_cdl.jpg">
</div>
<div class="col three caption">
    From Brown et al. <a href="https://arxiv.org/abs/2005.14165">Language Models are Few-Shot Learners</a> (2020). 
</div>

CDL seemed to be oriented
towards very early stage companies, and seemed to be a bit more prescriptive in its tone and focused largely on founding
principles and practices, business strategy, etc. Despite mixed utility from Oxford-CDL it was however cool to have an 
opportunity to sit across the table with [Patrick Pichette](https://en.wikipedia.org/wiki/Patrick_Pichette) (Ex CFO
of Google from 2008 until 2015), or Dhiraj Mukherjee (Shazam co-founder). 

Google Startup Accelerator programme on the other hand is far broader. Every startup is assigned mentors,
who work closely with the company - making the right introductions to relevant people within Google's network. Advice,
mentorship and introductions ranged anywhere from technical to business or customer oriented topics.
For example, early in the programme, we had a few meetings with Google Cloud team to speak about MLOps & CI/CD for machine learning
pipelines. 

Later in the programme we had two presentations from googlers, summarised below. Both
were around building teams. First, focused on establishing the right atmosphere within the existing team, while the latter
focused on hiring. 

### Understanding and Building Effective Team

This session was fully based on Google's own internal research publicly available on the following 
[link](https://rework.withgoogle.com/print/guides/5721312655835136/)
([featured](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html?smid=pl-share) in New York Times).
Link to my presentation 
<a href="{{ site.baseurl }}/assets/img/accelerator/understanding_building_effective_teams_notes.pdf" target="_blank">notes</a>.

In summary:
 
> Effective teams are psychologically safe, dependable and structured, and allow individuals to find meaning and 
> drive impact.
> 
> Effective team leaders are aware of their preferences and biases, and nurture an inclusive environment and a growth 
> mindset for their teams.
 
#### What do _Teams_ entail?

First major difference between the presentation and the published research, is that the presentation
did not define what a team is! That of course, did not stop the presentation from being useful, however it did
catch my eye as according to their definition (taken from [Kozlowski et al. (2001)](https://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?referer=&httpsredir=1&article=1396&context=articles))
_working groups  are characterized by the least amount of interdependence. They are based on organizational 
or managerial hierarchy. Work groups may meet periodically to hear and share information_. While _teams
are highly interdependent - they plan work, solve problems, make decisions, and review progress in service of a 
specific project_. These definitions appear to be in contrast with commonly referred use of teams - a group of employees that
share the similar qualifications. 

<div class="img">
    <img class="col three" src="{{ site.baseurl }}/assets/img/accelerator/teams_are_different.jpg">
</div>
<div class="col three caption">
    From Kozlowski et al. <a href="https://digitalcommons.ilr.cornell.edu/cgi/viewcontent.cgi?referer=&httpsredir=1&article=1396&context=articles">Work Groups and Teams in Organizations </a> (2001). 
</div>

#### Measuring team _effectiveness_?

Second difference, is the discussion of the way that the study on team effectiveness defined the metric! As with any
objective optimisation, that being design of anexperiment, machine learning system, or management an appropriate metric or 
objective needs to be specified. 

<div class="img">
    <img class="col three" src="{{ site.baseurl }}/assets/img/accelerator/dj_hand_importance_of_metric.jpg">
</div>
<div class="col three caption">
    From DJ Hand <a href="https://arxiv.org/abs/math/0606441">Classifier technology and illiusion of progress </a> (2006). 
</div>

Too often, both in machine learning model development, as well as in management, the optimisation objective does not reflect
the complex reality of the environment within which the model or the management practices are deployed. In the case of team building
it is important to consider different actors interacting, each having their priorities. These priorities are not just quantitative,
like number of code lines written or customer satisfaction, but also qualitative. Executives, team leaders, and team members - each
will be focused on different aspects of assesing the team effectiveness. 

> Executives were most concerned with results (e.g., sales numbers or product launches), but team members said that team
> culture was the most important measure of team effectiveness. Fittinly, the team lead's concept of effectiveness spanned 
> both the big picture and the invidiuals concerns saying that ownership, vision, and goals were the most important measures.

Essentially, quantitative metrics such as sales performance, or number of tickets, resolved issues, releases or milestones provides
concrete measures, but lack situational considerations. 

#### Findings - what matters for effective team?

Their research showed what really mattered was less about who is on the team, and more about how the team worked together.

In order of importance:

* Psychological safety: Trusting one another to take interpersonal risks, seek divergent opinions and resolve interpersonal
conflict when it arises. **Allows to disagree efficiently in teams.**

* Dependability:

* Structure and clarity: An individual's understanding of job expectations, and the processes. 

* Meaning: Sense of purpose in either the work itself or the output of the team. Meaning is personal and can vary from financial
security, team success, or self expression. 

* Impact: The subjective jugdement that your work is making a difference, is important for teams.

On the other hand, variables that were not significant **at Google** (does not mean they will not be important elsewhere). 

* Colocation of teammates

* Concensus-driven decision making

* Individual performance of team members

* Workload size

* Seniority

* Team size

* Tenure

#### Implications - psychological safety

The presentation focused on the implications of the research - one should
focus on the human values, when working in or managing a team. Investing into team dynamics is as important as hiring 
top talent. A few slides followed that were oriented to help manager build a good dynamic within a team:

<div class="img">
    <img class="col three" src="{{ site.baseurl }}/assets/img/accelerator/effective_team_questions.jpg">
</div>
<div class="col three caption">
    From presentation <a href="{{ site.baseurl }}/assets/img/accelerator/understanding_building_effective_teams_notes.pdf" target="_blank">notes</a>. 
</div>

A team leader should model the desired atmosphere within the team. Cultivate a mindset of openness and empathy, switch off
the autopilot and be present. Very important, for a leader is to investigate other perspectives, for greater understanding and 
collaboration to emerge. Each member of a team, has their own bias, including the team leader, and the latter should most certainly
recognise that. Broadly these biases could be divided into:

* People - focus on Who (inclusion, group dynamics, participation levels).

* Process - focus on How (decision making, timelines, structure, methods).

* Results - focus on What (problem to solve, task to accomplish, the product to build)

It's about recognising where do people come from. An interesting example was given how one would think about work from home
during COVID-19 pandemic:

<div class="img">
    <img class="col three" src="{{ site.baseurl }}/assets/img/accelerator/three_personalities.jpg">
</div>
<div class="col three caption">
    From presentation <a href="{{ site.baseurl }}/assets/img/accelerator/understanding_building_effective_teams_notes.pdf" target="_blank">notes</a>. 
</div>

**There is a lot more in the presentation** <a href="{{ site.baseurl }}/assets/img/understanding_building_effective_teams_notes.pdf" target="_blank">**notes!**</a>
Like suggesting team members having their well being OKRs, and actively showing that one respects people's
well being. Having things like calendar blocking time, or friday no meetings day.. 

Finally, it is impossible to feel psychologically safe without being engaged. Jeremy Neuner shared his use of Launchy. At the 
end of weekly meeting someone would have to give a stuffed rocket to someone who did something that week. That allows to engage
, connect, and build recognition of the weekly wins of others, big or small. 

#### Implications - structure & Clarity

Interesting point brought up on employees creating their user guide. Outlining their work and communication styles, 
annoyances, strengths, personality types - at Cervest we have already been using new joiner forms for some time, although
the idea of adding communication preferences sounded great. In general, there were five points covered:

1. Online "User guides"
2. Recurring 1-1s
3. Weekly Team Meeting
4. OKRs
5. Roles & Responsibilities

For 2 & 3 refer to <a href="{{ site.baseurl }}/assets/img/understanding_building_effective_teams_notes.pdf" target="_blank">notes</a>.
Points 4 & 5 are tightly coupled. OKRs, or any other business measurement methods, express goals and intents. They are 
measurable milestones to advance objectives. Must describe outcomes, not activities, and preferably describe the end user 
impact of these activities: "publish average and tail latency measurement from 6 Colossus cells by March 7th" rather than
"assess Colossus latency". Measurable milestones must include evidence of completion; this evidence must be available, credible
and easily discoverable. 

Roles & responsibilities, must be assigned per OKR per person. There should be the Responsible person, who will do the work,
can be multiple. The Accountable person, has to be one, who makes final decisions and has ultimate ownership. And there can
be a consulted person (can be many) who needs to be consulted before a decision or action is taken. 

### Finding, Hiring and Building Your Team

The second presentation was delivered by Martin an EMEA staffing lead for Google Ireland. As
in the first presentation, it provided an interesting perspective to hear how other startups who participated
in the session have been managing their recruitment. The talk was broadly divided into: 1. Finding & hiring; 
and 2. Onboarding. 

#### Finding the right candidate

It all starts with the job description, its almost like a mirror of the cv, and is also an assessment
of the company by a potential candidate. Generally, there are four components of a strong job description:

1. Area - the mission and the purpose of your company.
2. Role - a few sentences that directly address the candidate ("You will be...") and share daily functions.
3. Responsibilities - specific job deliverables.
4. Qualifications - education, experience and skills required, has to be specific. But it is useful to divide
into minimum qualifications (basic certifiable, typically non-negotiable qualifications) and preferred qualifications.
Preferred qualifications entail non-mandatory skills and experience of an ideal candidate, typically more qualitative. But,
it is mimimum qualifications that are used for initial screening. 

It is important to be inclusive, and choose the words carefully (gender neutral, there are tools)! Be factual about what 
it takes to succeed, consistent and open minded, and set expectations. Its important to use language that everyone 
understands! 

#### Interviewing

First, have a few standardized questions you ask each candidate and manage time properly during the interview. Develop
a rubric based on the qualifications of the role and the behaviour you're looking in the interview. Write feedback
asap! Be specific in the feedback and stay focused on the key attributes and qualifications for the role!

A fascinating study from google showed that four interviews was enough to predict new hire's performance with 86%!
Additional interviews provide marginal improvement to the accuracy. 

Address biases by reflecting on the entire interview, and decide on standards in advance. Do your best in avoiding to
comparing candidates, and instead compare to the established standards. Question what you and others mean by "fit".