---
layout: default
title: Home
seo:
  type: Course
  name: { { site.title } }
nav_order: 1
---

# {{ site.tagline }}

<!--{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}-->

<!-- Course Description here -->

Simulation methods, model building, random number generator, statistical analysis of results, validation and verification techniques. Digital simulation of continuous system. Simulation and analytical methods for analysis of computer system and practical problems in business and practice. Introduction to the simulation packages.

## Teaching team

{% assign instructors = site.staffers | sort: 'index' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Logistics

**Where**: UB70502 (Theory) and UB60804 (Lab).

**When**: Class is Thursdays and Saturdays at 3:30 - 5 PM, and Lab Class is Tuesdays 2-5 PM.

**Links**:

- [Email](https://www.gmail.com): This is the primary way where you and the teaching team should communicate.
- [Discord](https://discord.gg/EXXDGVsvjD):
  We will post all important announcements here alongwith mail, and you should ask
  all course-related questions here.
  For personal matters that you don't wish to talk in Discord, you can
  email the teaching staff at [meem.arafat@bracu.ac.bd](mailto:meem.arafat@bracu.ac.bd), keeping [joyanta.csebracu@gmail.com](mailto:joyanta.csebracu@gmail.com) in CC.

<!-- ## Class

Each class is divided into two parts:

1. **Lecture** (45 minutes): an instructor gives a standard lecture on a topic
   (see the [calendar](/calendar) for the list of topics). Lectures are be
   based on [these lecture notes](/lectures).

1. **Discussion** (45 minutes): there is a student panel discussion on the
   required readings posted on the [calendar](/calendar). -->

## Recommended Books

- [A Primer on Scientific Programming with Python - Hans Petter Langtangen](https://github.com/cse474-bracu/fall2022/blob/main/resources/1._H.P.L._-_A_Primer_on_Scientific_Programming_with_Python.pdf)
- [Modeling and Simulation in Python - Allen B. Downey](https://github.com/cse474-bracu/fall2022/blob/main/resources/2._Allen_B._Downey_-_Modeling_and_simulation_in_Python.pdf)
- [Introduction to Computation and Programming Using Python - John V. Guttag](https://github.com/cse474-bracu/fall2022/blob/main/resources/3._John_V._Guttag_-_Introduction_to_Computation_and_Programming_Using_Python__With_Application_to_Understanding_Data_2016_The_MIT_Press.pdf)

## Coursework

Your grade is based on few activities:

1. Attendance (5%)
2. Lab (20%)
3. Midterm Review + Viva (20%)
4. Assignment (20%)
5. Final Project (30%)
6. Final Project Update (5%)

### 1. Attendance

Self-Explanatory.

### 2. Lab

The course includes a compulsory 3 hour laboratory work each week.

### 3. Midterm Review + Viva

[**Paper reviews**](paper-reviews). For the midterm assessment, you will be assigned 1 paper. You
should read the papers carefully and write a review of the paper.
Your review should be a few paragraphs (in the style of a conference review,
say for ACL or NeurIPS).

### 4. Assignments

There will be different types of assignments. Such as, Paper Reviews, Literature Review, Situational Questions, etc.

[**Paper reviews**](paper-reviews).

### 5. Final Project

[**Final Project**](projects) There will be one final project, which allow you to get hands-on experience with Simulation and Modeling.

Projects will be done **individually**.
Each project should be written up clearly and succinctly; you may lose points if
your writing is unclear or unnecessarily complicated. Projects must be typeset
using LaTeX, and
submitted as a PDF. We strongly encourage you to use LaTeX: there are
user-friendly web interfaces like [Overleaf](https://www.overleaf.com/).

You need to use any of these LaTeX formats for creating your Project Final Report.

- [IEEE (Bibtex Version) "[Recommended]" (Copy The Project to Your Overleaf)](https://www.overleaf.com/read/vshtnzwrbnzj)
- or [IEEE (Bibitem Version) "[For those who are new in LaTeX]"](https://www.ieee.org/content/dam/ieee-org/ieee/web/org/conferences/Conference-LaTeX-template_7-9-18.zip)

### 6. Final Project Update

Once the final project gets selected, there will be weekly meetings with the TA, where updates of your project will be taken. As well as, the TA will help you to structure your project and report further.
You need to attend the meetings mandatorily.

### Submitting coursework

**Submissions**: All coursework are submitted via
Google Forms by the deadline which will be send to your email.
Do not submit your coursework via email. If anything goes wrong, please contact the Teaching Assistant.

<!-- **Late days**: A homework is ⌈d⌉ days late if it is turned in d days past the
due date (note that this means if you are 1 second late, ⌈d⌉=1 and it is 1 day
late). **You have 3 late days in total that can be distributed among the
homeworks without penalty.** After that, the maximum possible grade is
decreased by 25% each day (so the best you can do with d=1 is 75%; paper
reviews will be graded as fails if they are late and you have no late days). As
an example, if you are out of late days and submit one day late, a 90 will be
capped at a 75, but a 72 will not be changed. **Note that we will only allow a
max of d=2 late days per homework.** -->
