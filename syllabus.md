---
title: Syllabus
layout: single
toc: true
toc_label: "Syllabus Contents"
---

This page reconstructs the syllabus for Spring 2025 Artificial Intelligence
from the surviving course repository. It should be treated as historically
grounded, but not guaranteed identical to the exact public site text that
existed during the semester.

## What This Course Is About

For our purposes, artificial intelligence was treated as competence exhibited
by computer systems: methods by which machines can represent information,
perceive aspects of their environment, and take actions toward goals. That is
intentionally broader than the present habit of treating AI as synonymous only
with large language models. Contemporary AI services and LLMs belonged in the
course, but as one family of tools among many.

The surviving opening lectures make the course motivation fairly clear. The
point was not only to teach students how to call a fashionable API. It was to
place current AI systems in a longer technical history of automated reasoning,
formal logic, search, planning, learning, language, and decision-making, and
to study how these techniques can be assembled into complete software systems.

Examples of AI systems in this broader framing included:

- search engines
- recommendation systems
- chatbots
- speech recognition and text-to-speech systems
- deduction and consequence engines
- decision and optimization systems

The early history material also appears to have emphasized the "AI effect":
once a capability becomes routine, people stop calling it intelligence and
start calling it "just computation." One purpose of the course was to resist
that short memory by treating current systems as part of a longer and richer
technical lineage.

## Course Objectives

The course-organization lecture broke the course goals into four audiences:
theoretical, practical, research, and programming.

### Theoretical

Success in the course meant being able to explain and use several classical AI
techniques and algorithms, and to implement straightforward versions of them.

### Practical

Success in the course meant understanding how AI tools fit into larger
software pipelines, and being able to evaluate the advantages and
disadvantages of different system-design choices.

### Research

Success in the course meant being able to study, internalize, and discuss
classic AI papers, and to explain them coherently to others.

### Programming

Success in the course meant being able to integrate different AI techniques,
platforms, and tools into a coherent, working software artifact.

## Expectations

The recovered course-organization notes are explicit about the expected
background:

- Students should be able to read and internalize research literature and
  other complex technical material on their own.
- Students should be able to design and build medium-sized software systems.
- Students should be able to program against APIs and external platforms.
- Students should be sufficiently fluent in at least one implementation
  language to work through documentation, libraries, debugging, and deployment
  issues across the software lifecycle.

This was therefore not a "prompting tricks" course. It assumed enough
technical maturity to move back and forth between theory, research papers,
programming languages, cloud services, and actual implementation work.

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

- *The Reasoned Schemer*, 2nd edition
- selected classic AI papers
- Prolog and logic programming videos and notes
- selected decision-procedure / logic-programming materials

## Grading

The surviving gradebook and grade-calculation notes give the following
breakdown:

- Final Project: 30%
- Homeworks: 30%
- Paper Presentation: 25%
- Peer Evaluations: 10%
- Online Trainings: 5%

Recovered evaluated coursework:

- Azure training assignments
- one paper presentation
- three peer evaluations
- two miniKanren assignments
- one Prolog assignment
- one final project

The contemporaneous grading note also states that the final project was meant
to loom larger than the other work because it was the longest-running and most
comprehensive assignment of the semester.

## Communication

- Primary contact: [{{ site.author.emailaddr }}](mailto:{{ site.author.emailaddr }})
- Exact office-hours details for this course have not yet been recovered.

## Policies and Caveats

The exact public wording of late-work, attendance, and make-up policies has not
yet been recovered. If those details matter for the rebuilt site, the next
best sources are email, calendar records, or earlier syllabus drafts.

## Reconstruction Notes

The structured reconstruction data that backs this page lives in
`_data/syllabus.yml`. The main evidence comes from:

- `lectures/course-organization-topics-and-structure.org`
- `syllabus/4111-syllabus.org`
- `syllabus/final-grades-assessment-basis.org`
- `grades/final-grades.org`


When in doubt, ask your instructor. Violations of academic integrity
will lead to a score of zero on the offending assignment and likely an
immediately failing grade for the course.

### ChatGPT, Copilot, and GAI tools

This being new, I felt compelled to add a subsection. ChatGPT and
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
