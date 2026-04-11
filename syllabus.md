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

## Overview

The course treated artificial intelligence broadly rather than as only modern
LLM usage. The recovered materials show a mix of historical AI papers, logic
and relational programming, grammars, interpreters, program synthesis,
staging, neural learning, Prolog, game-tree search, and ASP, with an emphasis
on integrating these ideas into real software systems.

## Course Objectives

By the end of the course, students should have been able to:

1. Explain and use several classical AI techniques and algorithms.
2. Read and discuss classic AI research papers.
3. Evaluate tradeoffs in AI system design.
4. Build software that integrates multiple AI-related techniques into a
   coherent system.
5. Work with real APIs and deployment platforms, especially Azure-hosted
   services.

## Expectations

- Students were expected to read technical material independently.
- Students were expected to present and discuss research papers in class.
- Students were expected to build working software artifacts, not only produce
  reports.
- The course assumed enough programming maturity to read documentation, work
  against APIs, and debug medium-sized systems.

## Main Topics

- History and scope of AI
- Classic AI papers
- Azure and AI service platforms
- miniKanren and relational programming
- Languages, grammars, and evaluation
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

Recovered grading weights:

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
