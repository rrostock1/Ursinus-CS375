---
layout: syllabus
permalink: /
title: "CS375: Software Engineering"

info:
  course_number: CS375
  course_sections:
    - section: "A"
  course_title: "Software Engineering"
  credit_hours: "4 Semester Hours"
  course_homepage: "https://rrostock1.github.io/Ursinus-CS375/"
  course_prerequisites: "CS174"
  course_start_date: "2026/01/26"
  course_end_date: "2026/05/17"
  course_description: "Topics integral to the design, implementation and testing of a medium-scale software system combined with the practical experience of implementing such a project as a member of a programming team. Use of the Unified Modeling Language (UML) for software design. Prerequisite: A grade of C– or higher in CS-271. Offered in the spring semester. Three hours per week. Four semester hours. (Q.)"
  welcome_message: "Welcome to CS375!"
  questions: |
    Specifically, we will collectively consider questions like:
    <ul>
    <li>How can we organize large distributed software teams so that everyone can work together efficiently?</li>
    <li>How can tools help us to organize our code?</li>
    <li>How do we develop software systems that are easy to maintain and improve?</li>
    <li>How can we ensure that we are developing systems that both work correctly and satisfy user needs?</li>
    </ul>
  class_meets_days:
    isM: false
    isT: false
    isW: false
    isR: true
    isF: false
    isS: false
    isU: false
  class_meets_locations:
    - section:
        - day: "R"
          starttime: "07:00 PM"
          endtime: "09:40 PM"
          place: "PFA 107"
  midtermexam:
    - mdate: "TBD"
      mstarttime: "TBD"
      mendtime: "TBD"
      mroom: "TBD"
  finalexam:
    - fdate: "TBD"
      fstarttime: "TBD"
      fendtime: "TBD"
      froom: "TBD"
  flexible_submission_policy: 'In the absence of <a href="#accommodations">accommodations</a> arranged in advance with the instructor or college, all assignments are due at 11:59 PM Eastern Time on the date(s) stated on the schedule.  With prior permission and a reasonable first draft submission by the deliverable deadline, any student may request a three day extension on any deliverable, as often as needed.  Assignments will be accepted without prior permission following the original deadline, or, if requested, following the three-day extension deadline, with a points deduction of 10% per day if submitted before 11:59 PM Eastern Time on the day submitted.  If a student adds the course late, deliverables due prior to or on the day of that student''s registration will be due twice the number of days following the first day of the semester that they registered (for example, a student who registers on the third day of the semester shall receive six days to submit assignments from the first three days, and then the remainder of this policy takes effect for those and for all other deliverables).  Under no circumstances (including accommodations) can late work be accepted after the final class meeting, nor during final exams week, nor after the exam.'
  late_penalty_per_period: 10
  late_penalty_period: "day"
  banner: |
    <div style="width: 100%; display: table; border-collapse:separate; border-spacing:5px;">
    <div style="width: 100%; display: table-row;">
        <div style="display: table-cell; padding:5px; width:33%;">
            <a title="Aflafla1, CC0, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Iterative_development_model.svg"><img width="100%" alt="Iterative development model" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/39/Iterative_development_model.svg/512px-Iterative_development_model.svg.png"></a>
        </div>
        <div style="display: table-cell; padding:5px; width:33%;">
            <a title="Trashtoy, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:UML_class_diagram_example.svg"><img width="100%" alt="UML class diagram example" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/UML_class_diagram_example.svg/512px-UML_class_diagram_example.svg.png"></a>
        </div>
        <div style="display: table-cell; padding:5px; width:33%;">
            <a title="Ayalshi, CC BY-SA 3.0 &lt;https://creativecommons.org/licenses/by-sa/3.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Agile_testing_process_by_ayal_shimoni.png"><img width="100%" alt="Agile testing process by ayal shimoni" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Agile_testing_process_by_ayal_shimoni.png/512px-Agile_testing_process_by_ayal_shimoni.png"></a>
        </div>
    </div>
    </div>

instructors:
  - name: Ralph Rostock
    title: Adjunct Professor
    email: rrostock@ursinus.edu
    phone: ""
    office: "Pfahler Hall 217"
    officehours:
      - day: "R"
        starttime: "05:30 PM"
        endtime: "06:45 PM"
        location: "Pfahler 217"

textbooks:
  - title: "Design Patterns Explained"
    authors: "Alan Shalloway and James Trott"
    edition: "2nd Edition"
    isbn: "978-0321247148"
    link: false
    isrequired: false
    freelyavailable: false
  - title: "The Mythical Man Month"
    authors: "Frederick P. Brooks, Jr."
    edition: "20th Anniversary Edition"
    isbn: "978-0-201-83595-3"
    link: false
    isrequired: false
    freelyavailable: http://www.cesarkallas.net/arquivos/livros/informatica/Addison.Wesley.The.Mythical.Man-Month.Essays.on.Software.Engineering.20th.Anniversary.Edition.pdf
  - title: Software Enginering Lectures
    authors: Bauhaus-Uni Weimar
    edition: "CC NC-SA 4.0 Licensed"
    link: https://github.com/floe/software-engineering
    isrequired: false
    freelyavailable: https://www.youtube.com/playlist?list=PLjEglKdMOevU2STTGq79duxTXDFuO-k1H

objectives:
  - objective: "To gain perspective into software engineering best practices that enable teams to work together efficiently"
  - objective: "To develop software that is usable, scalable, and maintainable"

goals:
  - goal: "To use version control systems such as Git to manage software repositories"
  - goal: "To design user stories that capture the functional requirements of a software system"
  - goal: "To develop and implement a code test plan with good code and control flow coverage"
  - goal: "To develop and implement a user acceptance test plan"
  - goal: "To document a software system for both end-users and other developers"
  - goal: "To work efficiently on a software team according to software engineering best practices"
  - goal: "To design, develop, test, implement, document, and present a non-trivial software system"

grade_breakdown:
  - category: "Software Project Proposal"
    weight: "5%"
  - category: "Software Requirements Report"
    weight: "5%"
  - category: "Software Design"
    weight: "10%"
  - category: "Software Test Plan"
    weight: "10%"
  - category: "Software Documentation"
    weight: "20%"
  - category: "Final Presentation"
    weight: "15%"
  - category: "Peer Review"
    weight: "10%"
  - category: "Homework Assignments"
    weight: "20%"
  - category: "Class Participation and Quizzes"
    weight: "5%"

letter_grades:
  - letter: "A+"
    range: "96.9-100"
  - letter: "A"
    range: "93-96.89"
  - letter: "A-"
    range: "89.5-92.99"
  - letter: "B+"
    range: "87-89.49"
  - letter: "B"
    range: "83-86.99"
  - letter: "B-"
    range: "79.5-82.99"
  - letter: "C+"
    range: "77-79.49"
  - letter: "C"
    range: "73-76.99"
  - letter: "C-"
    range: "69.5-72.99"
  - letter: "D+"
    range: "67-69.49"
  - letter: "D"
    range: "63-66.99"
  - letter: "D-"
    range: "59.5-62.99"
  - letter: "F"
    range: "0-59.49"

schedule:
  - week: "0"
    date: "0"
    title: "Course Overview and Introduction to Software Engineering"
    link: "./files/cs375_week1.pdf"
    readings:
      - rtitle: "Course Overview"
        rlink: "../Ursinus-CS375-Overview"
    deliverables:
      - dtitle: "Homework Assignment: Warmup Handed Out"
        dlink: "./Assignments/Warmup"
        points: 10
        submission_types: "noupload"
      - dtitle: "Participation: Pre-Assessment Handed Out"
        dlink: "./Assignments/Participation/PreAssessment"
        points: 10
        submission_types: "written"
  - week: "1"
    date: "0"
    title: "Version Control with Git, Software Development Methodologies, Software Project Brainstorming & Team Formations"
    link: "./files/cs375_week2.pdf"
    readings:
      - rtitle: "Version Control with Git"
        rlink: "./files/software-engineering/02-git-oop.pdf"
      - rtitle: "MMM Chapter 16"
        rlink: false
    deliverables:
      - dtitle: "Homework Assignment: Warmup Due"
        dlink: "./Assignments/Warmup"
        points: 10
        submission_types: "noupload"
      - dtitle: "Participation: Pre-Assessment Due"
        dlink: "./Assignments/Participation/PreAssessment"
        points: 10
      - dtitle: "Software Project Proposal: Project Proposal Handed Out"
        dlink: "./Project/Proposal"
        points: 100
        submission_types: "written"
        rubricpath: "_pages/Project/project-proposal.md"
      - dtitle: "Homework Assignment: Git Handed Out"
        dlink: "./Assignments/git"
        points: 100
  - week: "2"
    date: "0"
    title: "Requirements Engineering & Team Workflows"
    link: "./files/cs375_week3.pdf"
    deliverables:
      - dtitle: "Software Requirements Report: Requirements Document Handed Out"
        dlink: "./Project/Requirements"
        points: 100
        submission_types: "written"
        rubricpath: "_pages/Project/project-requirements.md"
      - dtitle: "Homework Assignment: Weekly Standup Reflection Handed Out"
        dlink: "./Assignments/StandupReflection"
        points: 10
        submission_types: "written"
        rubricpath: "_pages/Assignments/assignment-standupreflection.md"
      - dtitle: "Software Project Proposal: Project Proposal Due"
        dlink: "./Project/Proposal"
        points: 100
        submission_types: "written"
        rubricpath: "_pages/Project/project-proposal.md"
  - week: "3"
    date: "0"
    title: "Requirements Validation & Backlogs"
    link: "./files/cs375_week4.pdf"
    deliverables:
      - dtitle: "Written Assignement: The Overdose Handed Out"
        dlink: "./Assignments/Overdose"
        points: 100
        submission_types: "written"
      - dtitle: "Homework Assignment: Weekly Standup Reflection Due"
        dlink: "./Assignments/StandupReflection"
        points: 10
        submission_types: "written"
        rubricpath: "_pages/Assignments/assignment-Standupreflection.md"
  - week: "4"
    date: "0"
    title: "Software Architecture"
    link: "./files/cs375_week5.pdf"
    deliverables:
      - dtitle: "Homework Assignment: Weekly Standup Reflection Due"
        dlink: "./Assignments/StandupReflection"
        points: 10
        submission_types: "written"
        rubricpath: "_pages/Assignments/assignment-Standupreflection.md"
      - dtitle: "Software Requirements Report: Requirements Document Due"
        dlink: "./Project/Requirements"
        points: 100
        submission_types: "written"
        rubricpath: "_pages/Project/project-requirements.md"
      - dtitle: "Homework Assignment: Git Due"
        dlink: "./Assignments/git"
        points: 100
  - week: "5"
    date: "0"
    title: "Detailed Design & Design Principles"
    link: "./files/cs375_week6.pdf"
    deliverables:
      - dtitle: "Homework Assignment: Weekly Standup Reflection Due"
        dlink: "./Assignments/StandupReflection"
        points: 10
        submission_types: "written"
        rubricpath: "_pages/Assignments/assignment-Standupreflection.md"
      - dtitle: "Participation: First Self-Assessment Handed Out"
        dlink: "./Assignments/Participation/SelfAssessment"
        points: 10
        submission_types: "written"
      - dtitle: "Software Design: Design Report Handed Out"
        dlink: "./Project/Design"
        points: 100
        submission_types: "written"
        rubricpath: "_pages/Project/project-design.md"

  - week: "6"
    date: "0"
    title: "Industry-Style Design Review"
    link: "./files/cs375_week7.pdf"
    deliverables:
      - dtitle: "Homework Assignment: Weekly Standup Reflection Due"
        dlink: "./Assignments/StandupReflection"
        points: 10
        submission_types: "written"
        rubricpath: "_pages/Assignments/assignment-Standupreflection.md"
      - dtitle: "Participation: First Self-Assessment Due"
        dlink: "./Assignments/Participation/SelfAssessment"
        points: 10
        submission_types: "written"
  - week: "8"
    date: "0"
    title: "Implementation & Professional Coding Practices"
    link: "./files/cs375_week8.pdf"
    deliverables:
      - dtitle: "Homework Assignment: Weekly Standup Reflection Due"
        dlink: "./Assignments/StandupReflection"
        points: 10
        submission_types: "written"
        rubricpath: "_pages/Assignments/assignment-Standupreflection.md"
      - dtitle: "Software Design: Design Report Due"
        dlink: "./Project/Design"
        points: 100
        submission_types: "written"
        rubricpath: "_pages/Project/project-design.md"
  - week: "9"
    date: "0"
    title: "Software Testing Fundamentals"
    link: "./files/cs375_week9.pdf"
    deliverables:
      - dtitle: "Homework Assignment: Weekly Standup Reflection Due"
        dlink: "./Assignments/StandupReflection"
        points: 10
        submission_types: "written"
        rubricpath: "_pages/Assignments/assignment-Standupreflection.md"
  - week: "10"
    date: "0"
    title: "Automation & Continuous Integration"
    link: "./files/cs375_week10.pdf"
    deliverables:
      - dtitle: "Homework Assignment: Weekly Standup Reflection Due"
        dlink: "./Assignments/StandupReflection"
        points: 10
        submission_types: "written"
        rubricpath: "_pages/Assignments/assignment-Standupreflection.md"
      - dtitle: "Software Test Plan: Test Plan Handed Out"
        dlink: "./Project/TestPlan"
        points: 100
        submission_types: "written"
        rubricpath: "_pages/Project/project-testplan.md"
  - week: "11"
    date: "0"
    title: "Maintenance, Refactoring & Technical Debt"
    link: "./files/cs375_week11.pdf"
    deliverables:
      - dtitle: "Homework Assignment: Weekly Standup Reflection Due"
        dlink: "./Assignments/StandupReflection"
        points: 10
        submission_types: "written"
        rubricpath: "_pages/Assignments/assignment-Standupreflection.md"
      - dtitle: "Software Documentation: Final Report Handed Out"
        dlink: "./Project/DocumentationFinalReport"
        points: 100
        submission_types: "written"
  - week: "12"
    date: "0"
    title: "DevOps, Deployment, Reliability & The Role of AI in Software Engineering"
    link: "./files/cs375_week12.pdf"
    deliverables:
      - dtitle: "Participation: Second Self-Assessment Handed Out"
        dlink: "./Assignments/Participation/SelfAssessment"
        points: 10
        submission_types: "written"
      - dtitle: "Homework Assignment: Weekly Standup Reflection Due"
        dlink: "./Assignments/StandupReflection"
        points: 10
        submission_types: "written"
        rubricpath: "_pages/Assignments/assignment-Standupreflection.md"
      - dtitle: "Software Test Plan: Test Plan Due"
        dlink: "./Project/TestPlan"
        points: 100
        submission_types: "written"
        rubricpath: "_pages/Project/project-testplan.md"
      - dtitle: "Homework Assignment: The Overdose Due"
        dlink: "./Assignments/Overdose"
        points: 100
  - week: "13"
    date: "0"
    title: "Project Workshop"
  - week: "14"
    date: "0"
    title: "Project Workshop"
    deliverables:
      - dtitle: "Software Documentation: Final Report Due"
        dlink: "./Project/DocumentationFinalReport"
        points: 100
        submission_types: "written"
      - dtitle: "Participation: Second Self-Assessment Due"
        dlink: "./Assignments/Participation/SelfAssessment"
        points: 10
        submission_types: "written"
  - week: "15"
    date: "0"
    reschedule: "5/12/2026"
    title: "Project Workshop"
    deliverables:
      - dtitle: "Final Presentation: Code and Presentation Due"
        dlink: "./Project/Presentation"
        points: 100
      - dtitle: "Peer Review: Peer Review Survey Due"
        dlink: "./Assignments/PeerReview"
        points: 10
        submission_types: "written"
university:
  semester: "Spring"
  academicyear: "2025-26"
  spring:
    - kname: "Add Deadline"
      kdate: "2026/02/6"
      kdisplay: true
    - kname: "Mid Semester Grades Posted"
      kdate: "2026/03/13"
      kdisplay: false
    - kname: "Drop with a W Deadline"
      kdate: "2026/04/21"
      kdisplay: true
    - kname: "CoSA"
      kdate: "2026/04/29"
      kdisplay: true
    - kname: "Reading Day"
      kdate: "2026/05/13"
      kdisplay: false
    - kname: "Finals Week Begins"
      kdate: "2026/05/14"
      kdisplay: false
    - kname: "Finals Week Ends"
      kdate: "2026/05/20"
      kdisplay: false
    - kname: "Commencement"
      kdate: "2026/05/22"
      kdisplay: false
  springholidays:
    - date: "2026/01/19"
    - date: "2026/03/16"
    - date: "2026/03/17"
    - date: "2026/03/18"
    - date: "2026/03/19"
    - date: "2026/03/20"
---

## Homework

### Assignments

A portion of the grade in the course will be earned by completing individual assignments. Be sure to start them early! Note that [collaboration and sharing rules](#collaboration) differ slightly for labs and assignments.

In addition, a significant portion of the course grade will take the form of a group project, including the design, planning, implementation, testing, documentation, and presentation of your project. You will follow best practices in software engineering and design to accomplish these. It is important that you adhere to these practices so that you remain organized and efficient as a software project team. Part of your grade will evaluate not only your implementation but the extent to which you followed best practice and methodology in the process.

### Class Participation and Classroom Etiquette \[[^1]\]

For classroom attendance, the following rules apply:

- Please be attentive during class. There will be class exercises that involve coding, but class time should be used for learning computer science. It is imperative that technology be used for this purpose during our class time together. **Alternatively, please try to think of this as a safe space away from social media.** We could all use a break, and we are fortunate to have a good excuse to make that space.
- Please follow common courtesy. For instance, you can bring food and drink as long as it's not distracting, but please clean up after yourself if you do. Our janitorial staff deserves the utmost respect and help with their job.
- In-class exercises and "low stakes" activities will take place individually and in groups to assess our progress together. These exercises will be given both synchronously (for example, in-class activities, pair programming exercises) and asynchronously (for example, pre-lab exercises, peer code reviews, book surveys) and will be graded on a participation basis. These are given equal weight and form the basis of the class participation score.
- If a class session is remote, please feel free to make choices that make you most comfortable. For example, I will record these sessions for students who cannot make the session or for those who would benefit from a review of the material. I'd encourage you to enable your video feed if it is available, but if you need leave your video off, you feel free to do so; however, if you find that this becomes necessary on a prolonged basis, please see me to discuss. Please keep your microphone on mute to avoid background noises while others are speaking; however, please do not feel "mic fright" about unmuting to speak up and participate anytime. If, however, you would prefer to communicate via the chat interface (either exclusively or in combination with your audio/video), you should feel free to do that. Whether in-person or remote, all I ask is that you engage as best you can; the material is challenging but fun, and we're all here to learn new things together.

[^1]: This introduction is adapted from Dr. Tralie's CS173 [Course Syllabus](http://www.ctralie.com/Teaching/CS173_S2020/index.html).
