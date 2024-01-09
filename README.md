# Introduction to homotopy type theory (reading course)

Autumn term 2023, study period 2, 7.5 credits

* For master students, this is an instance of *Research-oriented course in Computer Science and Engineering* (Chalmers: [DAT235](https://www.student.chalmers.se/sp/course?course_id=36287), GU: [DIT577](https://kursplaner.gu.se/pdf/kurs/en/DIT577)).
* PhD students can take this course as a PhD course.

**Note**.
This course is run as a self-study reading course.
Therefore, you must have the motivation and capacity to digest material without teacher presence.

## Teaching team

* Teacher (course-responsible): [Christian Sattler](https://www.cse.chalmers.se/~sattler/)
* Teacher: [Matthias Hutzler](https://www.chalmers.se/personer/hutzler/)
* Examiner (DAT235/DIT577): [Ana Bove](https://www.cse.chalmers.se/~bove/)

## Purpose

Homotopy type theory is a young area at the intersection of computer science, mathematical logic, homotopy theory.
It is based on the discovery of rich higher structure in the identity type of Martin-Löf type theory.
This relates to homotopy theory, an area of mathematics.
Homotopy type theory can serve as a constructive logical foundation with powerful extensionality principles ("when are two elements of a given type equal?").
It is also an internal language for higher toposes, a kind of mathematical objects useful in certain areas of modern mathematics.

This reading course serves as an introduction to this area.
After completing this course, you will be able to:

* explain the basic concepts of homotopy type theory,
* reason in homotopy type theory on a formal and informal level,
* spot faults in logical deductions,
* characterize the identity types of concretely given types,
* classify types according to their truncation level,
* manipulate higher inductive types,
* translate between the different perspectives of univalent mathematics on mathematical objects (for example, abstract versus concrete groups),

## Prerequisites

For master students:
* The prerequesites of DAT235/DIT577 apply.
* You must have passed DAT350/DIT235 *Types for programs and proofs*.

  Alternatively, you must have documented knowledge in category theory.
  If you have not seen type theories before, it may take you extra effort at the beginning of the course to become familiar with these kinds of logical systems.
  Chapter I (particularly Sections 1–4) of the course book can bring you up to speed.

For PhD students:
* Contact the course-responsible teacher with your background.

## Design

We will read (see [Literature](#literature)):
* Egbert Rijke's *Introduction to Homotopy Type Theory* (the prerequisites cover some sections in Chapter I; we will use them to make sure everyone is one the same page),
* selected chapters of *Homotopy Type Theory: Univalent Foundations of Mathematics*.

For every week, the course-responsible teacher will select [sections for you to read and exercises to solve](schedule.md).
You should do this on your own (you are welcome to form study groups).
In particular, you should solve all the selected exercises to the best of your ability.

It is up to you how to solve the exercises:
* on paper,
* in a proof assistant based on type theory such as Agda or Coq (if you are familiar with it).

There are formal solutions to every the exercises, but you should look up solution only after you have solved the exercises by yourself.

Every week, we will have a two-hour meeting where:
* we will discuss the sections you have read,
* you will present solutions to some of the exercises.

You are expected to take an active role in the weekly meetings.
All students must present exercise solutions at least once (see [Examination](#examination)).
If you exceptionally cannot attend a meeting, you may send in your solutions electronically; we might make it possible for you to receive feedback.

Two hours are too short to discuss all of the material.
Therefore, we encourage you to organize independent meetings and discuss the material on your own.
Additionally:
* we have a Zulip instance (see [Communication](#communication)) for online questions and discussions,
* the teachers may offer consultation times.

## Examination

To pass this course, you need to:
* successfully present exercise solutions in our weekly meetings at least once,
* pass a final written hall exam.

Beyond the feedback you receive when you present your solution, your exercise solutions will not be graded.
However, you are welcome to grade each other informally, particularly for exercise solutions that were not presented due to lack of time.

The exam will be a four hours with no aids allowed.
The problems will be of similar format to the exercises you have solved.
They may have different difficulties for the purpose of grade differentiation.

The exam will take place on **Friday, January 12** at **14–18** in the EDIT building (room to be announced).
It will have problems of different difficulty levels to ensure everybody gets a chance to pass.

**Update (December 23).**
Here is a [practice exam](exam-practice.pdf?raw=true).
The actual exam will follow the same format, but may have different numbers and topics of problems.

### For PhD students

If you take this course as a PhD course, you need to do some additional work to pass.
* You must be active in our weekly discussions.
  This includes giving feedback to students who present exercise solutions.
  Additionally, you may be asked to give feedback for students who hand in electronic solutions.
* You need to achieve a grade of at least 4 in the exam.

## Schedule

The weekly meetings will take place on **Fridays** at **15:15–17:00** in **EF** (lecture hall on 6th floor of EDIT building).
This has determined by [this poll](https://choodle.portal.chalmers.se/YZVDfAyYLAyTXKVW).

In the first week, we will have an optional introduction meeting on **Monday, October 30** at **13:15–14:00** in **6217** (meeting room on 6th floor of EDIT building, near staircase D).
You can come if you:
* need help to get started,
* want to meet people and form study groups,
* want to discuss things with me in person.

Your weekly reading and digestion tasks are [collected here](schedule.md).
Throughout the course, we will monitor your workload based on your feedback and set tasks in line with the time you are expected to spend.

There is a special [pre-exam meeting](schedule.md#special-pre-exam-meeting) on **Wednesday, January 10** at **16:15–18:00** in **EF**.

The exam takes place on **Friday, January 12** at **14–18** in **EE**
You will need to bring identification.

## Literature

* Egbert Rijke's [*Introduction to Homotopy Type Theory*](https://arxiv.org/abs/2212.11082).

  This is the main book the course is based on.
  A printed version is due to appear, but the above version will remain freely available.

* [*Homotopy Type Theory: Univalent Foundations of Mathematics*](https://homotopytypetheory.org/book/) by the Univalent Foundations Program.

  This is a secondary resource.
  We may use it for some further topics such as higher inductive types.

## Communication

We use [Zulip](https://lot.zulipchat.com/#narrow/stream/407220-HoTT-reading-course) for announcements and online discussions.
To create an account, use [this link](https://lot.zulipchat.com/join/tipdqgohyzsxnmxziqumen3q/) and change one letter so that the URL contains the word *vip* (spam protection).
Our stream is called *HoTT reading course*.

The stream is organized into *topics* (Zulip lingo for threads).
Feel free to create new topics, for example for questions that you want to discuss.
This is useful if you are stuck on something in your weekly reading.
Conversely, you can help your fellow students by engaging with and possibly answering their questions.

One benefit of Zulip over Slack and Discord is that it is free software.
It also supports [LaTeX rendering](https://zulip.com/help/latex)!

## How to register

For master students: contact the examiner.
As stated in the course syllabus for DAT235/DIT577, it is up to the examiner to decide whether a student is accepted to the course or not.

For PhD students: obtain the approval of your supervisor and examiner.
Then contact the course-responsible teacher.
