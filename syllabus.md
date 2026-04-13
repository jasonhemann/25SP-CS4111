---
title: Syllabus
layout: single
toc: true
toc_label: "Syllabus Contents"
---

This syllabus contains policies and expectations for Spring 2025 Artificial
Intelligence. Please read it carefully. Policies and expectations in this
course may be modified at any time by announcement in class, by email, or by
changes to this page.

## What This Course Is About

For our purposes, artificial intelligence is competence exhibited by computer
systems: methods by which machines can represent information, perceive aspects
of their environment, and take actions toward goals. That is intentionally
broader than the present habit of treating AI as synonymous only with large
language models. Contemporary AI services and LLMs belong in the course, but
as one family of tools among many.

The point of this course is not merely to teach you how to call a fashionable
API. We place current AI systems in a longer technical history of automated
reasoning, formal logic, search, planning, learning, language, and
decision-making, and we study how these techniques can be assembled into
complete software systems.

Examples of AI systems in this broader framing include:

- search engines
- recommendation systems
- chatbots
- speech recognition and text-to-speech systems
- deduction and consequence engines
- decision and optimization systems

This course also takes seriously the "AI effect": once a capability becomes
routine, people stop calling it intelligence and start calling it "just
computation." One purpose of the course is to resist that short memory by
treating current systems as part of a longer and richer technical lineage.

## Course Objectives

This course has four overlapping goals: theoretical, practical, research, and
programming.

### Theoretical

You should be able to explain and use several classical AI techniques and
algorithms, and to implement straightforward versions of them.

### Practical

You should understand how AI tools fit into larger software pipelines, and be
able to evaluate the advantages and disadvantages of different
system-design choices.

### Research

You should be able to study, internalize, and discuss classic AI papers, and
to explain them coherently to others.

### Programming

You should be able to integrate different AI techniques, platforms, and tools
into a coherent, working software artifact.

## Expectations

This course assumes the following background:

- Students should be able to read and internalize research literature and
  other complex technical material on their own.
- Students should be able to design and build medium-sized software systems.
- Students should be able to program against APIs and external platforms.
- Students should be sufficiently fluent in at least one implementation
  language to work through documentation, libraries, debugging, and deployment
  issues across the software lifecycle.

This is not a "prompting tricks" course. It assumes enough technical maturity
to move back and forth between theory, research papers, programming
languages, cloud services, and actual implementation work.

## Main Topics

- History, scope, and changing definitions of AI
- Classic AI papers and student-led paper discussions
- Azure platform work and API-oriented AI development
- miniKanren, relational programming, and logic-as-programming
- Languages, grammars, evaluation, and interpreters
- Program synthesis and staging
- Neural networks, learning, and backpropagation
- Prolog, DCGs, and declarative debugging
- Minimax and alpha-beta pruning
- ASP and ASP Chef

## Readings and Materials

Primary materials for the course include:

- *The Reasoned Schemer*, 2nd edition
- selected classic AI papers
- Prolog and logic programming videos and notes
- selected decision-procedure / logic-programming materials

Additional readings and links will be posted with the schedule and
assignments.

## Evaluated Coursework

- one student paper presentation
- Azure pre-learning modules
- two miniKanren assignments
- three student presentation evaluations
- one Prolog assignment
- one final project

## Grading

The course grade is based on the following breakdown:

- Final Project: 30%
- Homeworks: 30%
- Paper Presentation: 25%
- Peer Evaluations: 10%
- Online Trainings: 5%

The final project is the longest-running and most comprehensive assignment of
the semester, and it is weighted accordingly.

## Contact

- Personal, private (FERPA, etc) messages: [{{ site.data.authors[site.author].emailaddr }}](mailto:{{ site.data.authors[site.author].emailaddr }}).
  You should expect a response within 48 hours.

A great regular way to reach out for help is via our
[office hours]({{ site.baseurl }}/people/).

## Academic Integrity

When in doubt, ask your instructor. Violations of academic integrity
will lead to a score of zero on the offending assignment and likely an
immediately failing grade for the course.

### ChatGPT, Copilot, and GAI tools

This being new, I feel compelled to add a subsection. ChatGPT and
other code generation tools utilize advanced machine learning models
to assist users in generating code, answering queries, and providing
solutions to various problems. I will have exercises where we practice
using them in class.

These tools can be beneficial for understanding and learning, it's
crucial to use them responsibly. My problems are small because you are
learning, Tools like ChatGPT can provide quick answers, but do not
scale equally well to professional software developer sized problems.
Your submissions should be your original work. If I can tell that you
used ChatGPT or similar tools to assist in your assignments---by
inspection, or from my interactions with you---that is the same as any
other cheating.

If you want to use these tools to help you learn, do so on problems
that are significantly different enough from those I assign to you.

## DSS

It is the policy and practice of Seton Hall University to promote
inclusive learning environments. If you have a documented disability
you may be eligible for reasonable accommodations in compliance with
University policy, the Americans with Disabilities Act, Section 504 of
the Rehabilitation Act, and/or the New Jersey Law against
Discrimination. Please note, students are not permitted to negotiate
accommodations directly with professors. To request accommodations or
assistance, please self-identify with the Office for Disability
Support Services (DSS), Duffy Hall, Room 67 at the beginning of the
semester. For more information or to register for services, contact
DSS at (973) 313-6003 or by [e-mail](mailto:DSS@shu.edu), or visit
their [webpage](https://www.shu.edu/disability-support-services/index.cfm).

## Acknowledgments

Thanks over the years for inspiration and content from at least the
following: Dan Friedman, Shriram Krishnamurthi, Lindsey Kuper,
Marco Morazán, and Kris Micinski.

![In the syllabus]({{ site.baseurl }}/assets/images/syllabus.gif "Might just be worth checking.")
