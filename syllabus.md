# Syllabus

## CSE 34341 Operating Systems Principles

Spring 2023: Silicon Valley Semester

Instructor: Prof. Patrick Flynn (flynn@nd.edu); office hours TBA

GTA: Lu Niu (lniu@nd.edu); office hours TBA


Web site: [https://github.com/patrick-flynn/CSE34341-SVS-Sp2023](https://github.com/patrick-flynn/CSE34341-SVS-Sp2023)

## Overview

An operating system (OS) is a critical layer of software that manages hardware resources and that provides user programs with a *simple and consistent* interface to the machine. In this course, we will examine the services and abstractions commonly provided by operating systems, and we will study the underlying mechanisms used to implement them. Topics include
+ processes and threads
+ access to shared resources: synchronization, concurrency, deadlocks, hazards
+ CPU scheduling
+ memory management and the memory hierarchy
+ storage and file systems
+ distributed systems, and
+ virtualization.

A good understanding of OS internals offers benefits, whether you intend to work in computer hardware or computer software. 
+ By understanding how an OS works, and making good/efficient use of its abstractions (files, memory), *you will be able to write better software*.
+ *The techniques that you learn here will have applications in every kind of computer system*. The traditional problems that occur in operating systems (like scheduling, synchronization, and resource management) also occur in all sorts of other systems, ranging from small embedded computers to large scale cloud computing systems. 

The concepts presented in class will be explored through **six intensive programming assignments**. The assignments will make use of the C programming language, which the universal language for implementing and accessing operating systems at their lowest level. The projects will give you ample practice with manipulation of pointers, managment of memory, invoking of system services, and dealing with error conditions. The prof and the GTA will offer some technical guidance on these matters --- but **you should expect to spend significant time debugging, consulting reference materials, and revising the projects until they work properly**. There is no way around this requirement, so please budget the time needed to master the assignments.

The learning goals for students in this course are:

- Students will understand the abstractions and services provided by an operating system.
- Students will demonstrate that understanding through implementation of software employing the abstractions and services.
- Students will gain practical experience using and implementing operating system services.

The course materials will test each student's achievement of these goals at several levels. For each topic in the course, students must be able to:

- Describe traditional operating system structures and algorithms.
- Demonstrate in detail how they apply to various programs and data.
- Evaluate the strengths and weaknesses of related structures and algorithms.
- Propose and evaluate a variety of improvements upon traditional methods.
- Implement basic methods in a working computing system.

## Course Communications

The course web page contains the schedule, assignments, and other critical information:
[link](https://github.com/patrick-flynn/CSE34341-SVS-Sp2023)

Canvas will be used as the class gradebook:
[link](https://canvas.nd.edu/courses/64520)

## Textbooks

- Required: Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau, **Operating Systems in Three Easy Pieces**, Arpaci-Dusseau Books, 2019. [http://ostep.org](http://ostep.org)

- Suggested Reference: Kernighan and Ritchie, The C Programming Language, Prentice-Hall, 1988.

## Reading Assignments

The textbook provides the foundation of the course, and it will be important for you to absorb it thoroughly.  To encourage regular reading and preparation for class, **you are required to turn in summary notes on the assigned readings each Monday of the semester by 11:59PM Pacific Time**. Notes will not be required on the MOnday of spring break or Easter Monday.  You will upload these notes in Canvas.  The easiest way to do this is just take notes on paper, and then snap a few photos for upload.  If you prefer to type them out, then attach a PDF instead.

Your notes can be organized in whatever way is appropriate to that chapter and is useful for you. Good things to include may be an outline of the chapter, definition of key terms, a sketch of the systems or data structures being discussed, that sort of thing.  **Along with your notes, you should submit one thoughtful question you would like to discuss that week**. The prof will try to answer a few highlighted questions each week, and steer the lecture to address them.

Grading on notes will be very simple: either one, one-half, or zero points. There will be thireen opportunities to earn a total of twelve points, so you may miss one without penalty.  The first round of notes are due on **Monday, January 23rd**, and then every **Monday at 11:59PM** thereafter.  Late submissions will earn a maximum of one-half point.

## Attendance

To succeed in this class, you should attend and actively participate in all the scheduled lectures. You will get the most out of class if you have done the required readings in advance and actively take notes during class.  Re-articulating, through writing, of the concepts in lecture and readings is essential to your "fixing" the material in memory.

Please refrain from using your laptops for non-class activities, since this [tends to distract others](https://www.insidehighered.com/news/2018/07/27/class-cellphone-and-laptop-use-lowers-exam-scores-new-study-shows) as well as yourself.

## Grading

The course grade will be based on six programming projects, one homework, a midterm, and a final exam. For each assignment, a numeric grade will be assigned. Grades will be made available in Canvas. Projects and homeworks are 60% of the course grade, chapter notes are 10%, and the midterm and final exam are each 15%. At the end of the semester, number grades will be converted to letter grades: 90/80/70 are the usual cutoffs for A/B/C grades, respectively. The instructor will exercise discretion on borderline grades, or to account for a trend of increasing/decreasing grades throughout the semester.

If you believe an error has been made in grading an item, please bring it to the attention of the TA  within seven days of receiving it. (The TA who graded it knows the details best, and so can give you the best explanation.) Factual and clerical errors will of course be cheerfully corrected. If you are unsatisfied with the TA's explanation, you may appeal to the instructor. After seven days, graded items are final and will not be revisited.

Late assignments are not generally accepted.  However, each student may use **one late pass** for one assignment during the semester.  To exercise this option, please email the instructor prior to the deadline.  The late pass will give you an extension of one week on the assignment.  A late pass cannot be used for the final assignment.

## Health and Safety

At the time of writing, classes are to be conducted in person normally and students are expected to attend all classes. Please comply with any public health requirements announced by the local government or the University (e.g., re-imposition of a mask mandate, etc.). If you have a mild illness (or are required to quarantine as a precaution) then you should work with your classmates to capture lecture notes you missed, and continue to complete assignments in the ordinary way. Office hours will be available by Zoom if needed.  If you have a more serious illness, then please contact the instructor when you are able, and we will make alternate arrangements.

## Academic Code of Honor

As a student at Notre Dame, you are bound by the Academic Code of Honor (http://honorcode.nd.edu), which states:

> As a member of the Notre Dame community, I acknowledge that it is my responsibility to learn and abide by principles of intellectual honesty and academic integrity, and therefore I will not participate in or tolerate academic dishonesty.

The purpose of the homeworks and assignments in this course is for each student to gain the discipline and skills in design, programming, and analysis, so that they will be able to work independently in a professional setting. To that end, **all exams, homeworks, and programming assignments are to be completed individually. Each student must write their own code from scratch with their own hands based on their own understanding of the course material.**

You may consult with other students and outside resources in order to better understand concepts and techniques, or to debug localized problems. You may not copy -- and should refrain from viewing -- code from another student or resource, excepting any starter code provided by the instructor.

## Some Campus Resources

If you require an accommodation for a disability, please first contact the Sara Bea Center (sarabeadisabilityservices.nd.edu) for a consultation, and we will be happy to work together on a solution. If you encounter a difficult life situation and don't know what to do, the University Counseling Center (ucc.nd.edu) or the Care and Wellness Consultants (care.nd.edu) can help and also connect you with other campus resources.
