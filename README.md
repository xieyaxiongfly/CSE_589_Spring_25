---
layout: home
title: CSE589 Modern Networking Concepts
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Modern Networking Concepts
---

# Modern Networking Concepts
{: .fs-9 } 

Spring 2025, University at Buffalo 
{: .fs-6 .fw-300 }

**Instructor:** 


{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Course Updates 
All updates, Progamming Assignments, Homeworks, and Wireshark Labs are updat
ed on Piazza.
We will also be using Piazza for class discussion. 
The system is highly catered to getting you help fast and efficiently from classmates, 
the TA, and myself. Rather than emailing questions to the teaching staff, 
I encourage you to post your questions on Piazza.

Please join at the following link: [https://piazza.com/buffalo/spring2025/cse4589/info](https://piazza.com/buffalo/spring2025/cse4589/info)

Access Code: You should find it under the Announcements tab in UBLearns Brightspace.

## Course Description

The course introduces basic elements of modern computer and telecommunication networks. The focus is on the four upper layers of the popular five-layer TCP/IP model. 
In each layer, the state-of-the-art hardware and software technologies are introduced. These include, for example, DNS, HTTP, SMTP, and P2P systems at the application layer, TCP/UDP protocols at the transport layer, routing and forwarding, intra-domain and inter-domain routing algorithms at the network layer, random access protocols at the MAC layer, and local area networks (Ethernet and WiFi). Advanced topics such as multipath TCP and software defined networking are also briefly discussed.

The objective of the course is to enable students to
- gain fundamental knowledge of computer and telecommunications networks
- understand various tradeoffs and choices in current networking technologies
- learn basic network programming
- prepare for studying advanced topics (e.g. CSE 620, CSE 630, CSE 646), and a career in the field of computer networking.

At the end of this course, each student should be able to:
- Have a good overall picture of computer networking in general and the Internet in particular.
- Have a rough idea of how various networking components (hardware/software) work and where they belong in the 5-layer protocol stack.
- Know how to do network programming in C/C++ under Unix.
- Know how to do basic performance analysis of popular networking protocols.
- Know how to use popular networking tools such as WireShark and iperf.
- Start reading more advanced/research-oriented networking materials.


## Lecture Time & Location

Tuesday and Thursday, 5:00PM-6:20PM,    Knox 104, North Campus

## Important Dates
Final Exam: 7:15PM-10:15PM, May 9th 2024

## Prerequisites

Students need to have some basic knowledge of operating systems,
calculus and probability theory, data structures, and algorithms.
In addition, they must be **proficient in C or C++ programming**.



## Required Textbook
James F. F. Kurose and Keith W. Ross, "Computer Networking: A Top-Down Approach F
eaturing the Internet", 7th edition, Addison Wesley, 2017.

## Reference Textbooks
- *Computer Networks: A Systems Approach*, Larry Peterson and Bruce S. Davie.
- *UNIX Network Programming : Networking APIs : Sockets and XTI : Volume 1, Second Edition*, W. Richard Stevens, Prentice Hall, Oct 1997, ISBN: 013490012X. **Recommended!**
- *Advanced Programming in the UNIX Evironment*, W. Richard Stevens, Addison-Wesley, 1992, ISBN 0-201-56317-7.
- *Computer Networks*, Andrew Tanenbaum, Prentice Hall PTR; 4 edition (August 9, 2002), 912pp.
- *Internetworking with TCP/IP, Volume 1: Principles, Protocols, and Architectures, Fourth Edition 4TH*, Douglas E. Comer, Prentice Hall, Feb 2000, ISBN: 0130183806
- *The TCP/IP Illustrated, Volume 1: The Protocols*, W. Richard Stevens and Gary R. Wright, Addison Wesley Longman, Dec 1993, ISBN: 0201633469
- *The TCP/IP Illustrated, Volume 2: The Implementation*, W. Richard Stevens and Gary R. Wright, Addison Wesley Longman, Jan 1995, ISBN: 020163354X
- *Queueing Systems: Theory, Vol. 1*, Leonard Kleinrock, Wiley, John & Sons, January 1975
- *Queueing Systems Volume 2: Computer Applications*, Leonard Kleinrock (Editor), Wiley, John & Sons, April 1976

## Course Policies

- **Late policy**: All assignments are due on the day and time posted.
  - You can submit an assignment up to 7 days late with a fixed daily penalty of 
	10% out of total points. Latest submission (7 days late) will receive at most 30%
 	of max points even if it's all correct; 0 points if more than 7 days late.

  - **The workload is heavy, so start the assignments, especially the project assignments, early!** 
	Excuses that you did not have enough time for an assignment will not be considered. 
	Extraordinary circumstances will be considered at the discretion of the instructor (not the TAs!), 
	contact the instructor via E-mail if you think these apply to you.

  - Teams: **Teams are allowed for the two programming project assignments only** and will be grouped 
	at the beginning of the semester and are NOT subject to change during the whole semester. 
	If you do not satisfy with your team in the middle of the semester, 
	send an email to the instructor and explain your situation. 
	We may regroup your team and/or ask for an in-team peer review base on the situation

  - Exams: If you miss an exam because of sickness or similar reasons, 
	visit a physician and obtain a note detailing the period during which you were medically incapable of taking the exam. 
	Notify the instructor immediately via e-mail or telephone (voice mail) if you are going to miss an exam, 
	before the exam takes place unless medically impossible. 
	See the instructor as soon as you return to class. 
	If you miss an exam without a valid excuse, you will receive a zero grade for that exam.
	No make-up exam will be available without a valid excuse.

  - No extra work in the next semester will be given to improve your grade.

- **Regrading policy**:
  - Homeworks/WireShark Labs: Homework/Lab grades will be posted on UBLearns. 
	You can look up graded homework/labs from the UBLearns. 
	Questions about homework/report grades should be sent on piazza via private post within **one week** after the grade is posted on UBLearns. 
	If you are not satisfied with the TA's response, 
	you should contact the instructor no later than 3 days after TA's response..

  - Programming assignments (PA): 
	Grades for the programming assignments will be posted on UBLearns. 
	If you have questions about your grade, you should contact the TAs on 
	piazza via private post or during their office hours within **one week** after the grade is posted on UBLearns. 
	If you are not satisfied with the TA's response, you should contact the instructor no later than 3 days after TA's response.

  - Exams: Exams will **NOT** be returned. 
	Exam grades will be posted on UBLearns, and you will be able to see your exam during the instructor's office hours. 
	If you have questions about your grade, you should contact the instructor by email or 
	during office hours **within the time period specified** after the grade is posted on UBLearns.

  - No regrade requests will be considered after the deadlines mentioned above.


## Grading Policies
The overall score will be calculated based on the scores from the Homework,
Lab, Exam and Programming Assignments as follows:



- Midterm Exam: 20%
- Final Exam: 20%
- 4 Homework & 4 Wireshark Labs: 20%
  - The best 3 scoring Homeworks are considered: 4% each Homework
  - All wireshark labs: 2% for each lab
- 2 Programming Assignments 40%

Homework/ Wireshark Labs should be done individually.
Programming Assignments can be done individually or in the same team of up to 2 s
tudents. Recommend to work in teams

## Academic Integrity

- **No tolerance on cheating!**
  - All academic integrity violation cases will be reported to the department, school, and university, and recorded.
  - Fail the course on any homework assignment/lab, project, or exam even for fir
st offense.
  - Team members are equally responsible.
  - Consult the Department and University Statements on [Academic Integrity](https://www.buffalo.edu/academic-integrity/policies.html).

- Group study/discussion is encouraged, but the submission must be your own work.

- Homeworks: Homework reports must be written up **individually**. Use of reference materials in the library or online is allowed, providedthat the homework explicitly cites the references used. 
**Note that copying the solutions from online sources or the previous semester is still considered cheating even if you cite the sources.**

- Wireshark labs: Labs need to be done individually. Discussions of ideas are welcome, but exchanges of reports are not allowed.

- Programming assignments: Programming assignments can be done individually or in teams of up to 2 students. One submission per team, one grade per team. 
Engaging in discussions concerning concepts is permitted; however, sharing of source code is strictly prohibited. 
In instances where external resources have been consulted, such as online materials, the provided demonstration code, 
or Beej's Socket Programming Guide, students must clearly annotate the relevant sections of their work with commentary, 
demarcating the beginning and termination of the referenced material. 
**Importantly, under NO circumstances may students rely on the work of their peers, 
including but not limited to GitHub repositories or code submissions from previous academic terms.** 
We reserve the right to make the ultimate 
determination regarding breaches of academic integrity policies.

- Students who do share their work with others are as responsible for academic dishonesty as the student receiving the material. 
Students are not to show work to other students, in class or outside the class. 
Students are responsible for the security of their work and should ensure that 
printed copies are not left in accessible places, and that file/directory permissions are set to be unreadable to others.

- Excuses such as "I was not sure" or "I did not know" will not be accepted. If you are not sure, ask the TAs and /or the instructor.
- Any student may withdraw their submission (homework, lab, projects) any time, 
no questions asked, BEFORE any AI violation is discovered.

## AI Tools
**No use of AI Tools for any submissions**
- AI Tools like ChatGPT, Google Geimin, etc. are not allowed.
- They can be used to understand the concepts and for clarifications.
- Use of AI Tools for the submissions in any class work (Homeworks/Wireshark Labs/Programming Assignments) will not be acceptable.

## Medical Emergencies
Accommodation for medical emergencies will be made on a case-by-case basis. Requests for extensions based on medical emergencies must be accompanied by documentation of the emergency from [http://www.buffalo.edu/studentlife/who-we-are/departments/health.html](student health services).

## Accessibility Resources
If you have a diagnosed disability (physical, learning, or psychological) 
that will make it difficult for you to carry out the course work as outlined,
or that requires accommodations such as recruiting note-takers, readers, or extended time on exams or assignments,
please advise the instructor during the first two weeks of the course so that we may review possible arrangements for reasonable accommodations.
In addition, if you have not yet done so, contact: https://www.buffalo.edu/studentlife/who-we-are/departments/accessibility.html.


