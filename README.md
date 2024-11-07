# MAE 435: Principles of Automatic Control

## General Information

* Duration: 17 weeks (Aug. 19 - Dec. 9)
* Schedule: Mon. & Wed., 3:00-4:15 p.m.
* Location: 1007 Engineering Building I, Centennial Campus.
* Office Hours: Mon. & Wed., 11:00-12:00, Room 3282 Engineering Building III, Centennial Campus.
* [Syllabus](https://www.dropbox.com/scl/fi/pltajoibr86bn71zab0ji/MAE-435-Syllabus-Fall-2024.pdf?rlkey=s23ix5brw4lgqqallbpyvhq7f&dl=0)

## Instructors

Prof: Dr. Hao Su, Associate Professor (hsu4@ncsu.edu)

Teaching Assistants
* MS. Junxi Zhu, Senior PhD Student (jzhu35@ncsu.edu)
* Dr. Ivan Lopez-Sanchez, Postdoc (ilsanche@ncsu.edu)

## Course Schedule (tentative)

|    Section      |            Week           |                           Monday                          |                       Wednesday                     |            Optional   Text Read          |
|:---------------:|:-------------------------:|:---------------------------------------------------------:|:---------------------------------------------------:|:----------------------------------------:|
|     Modeling    |       1. Aug. 19, 21      | [Course   Overview](#lecture-1-course-overview)           | [Closed-loop Control](#lecture-2-closed-loop-control) |      MCE:   1.1 – 1.5            |
|                 |       2. Aug. 26, 28      | [Introduction to PID Control and Laplace Transform](#lecture-3-laplace-transform-and-pid-control) | [Laplace Transform and Transfer Function](#lecture-4-laplace-transform-and-transfer-function) | SD:   2.2 – 2.3 |
|                 |        3. Sep. 2, 4       | No   Classes (Labor Day)                                  | [Laplace   Transform pairs and Inverse Laplace Transform](#lecture-5-laplace-transform-pairs-and-inverse-laplace-transform) | MCE:   2.1, 2.2 & SD: 2.2 – 2.3 |
|                 |        4. Sep. 9, 11      | [Mechanical System Modeling](#lecture-6-mechanical-system-modeling) | [Electromechanical Systems Modelling](#lecture-7-electromechanical-system-modeling) | MCE: 3.1-3.2 & SD: 6.1-6.6 |
|                 |       5. Sep. 16, 18      | [Project:   MATLAB](#lecture-8-project---introduction-to-matlab) | Career Fair | MCE:   2.3 & SD: 8.1 – 8.3 |
|     Analysis    |       6. Sep. 23, 25      | [Control Block Diagram Signal Flow Graph](#lecture-9-Control-Block-Diagram) | [Project: Simulink Introduction](#lecture-10-Project-Simulink-Introduction)   |      SD:   8.1 – 8.3 & MCE: 5.1 – 5.8    |
|                 |     7. Sep. 30, Oct. 2    | [Time-Domain Analysis (1st order system)](#Lecture-11-Time-Domain-Analysis---1st-Order-Systems) | [Midterm Review](#Lecture-12-Midterm-Review) | MCE:   5.1 – 5.8 |
|                 |        8. Oct. 7, 9       |             [Time-Domin Analysis (2nd order system)](#lecture-13-time-domain-analysis-2nd-order-system)           |          Midterm        |              MCE:   5.1 – 5.8            |
|                 |       9. Oct. 14, 16      |                  Fall Break (no class)                |             [DC Motor Modeling, PID Control and Simulink Implementation](#lecture-14-dc-motor-modeling-pid-control-and-simulink-implementation)              |        MCE:   7.1 & MCE: 7.2 – 7.6       |
|                 |       10. Oct. 21, 23     |                   [Frequency Domain Analysis Part I](#lecture-15-frequency-domain-analysis-part-i---introduction) | [Frequency Domain Analysis Part II](#lecture-16-frequency-domain-analysis-part-ii-bode-plot-overview)        |     MCE:   6.2 – 6.5 & MCE: 7.2 – 7.6    |
|                 |       11. Oct. 28, 30     |            [Midterm Review](#lecture-18---midterm-exam-question-review)          |          [Bode Diagram Concept](#lecture-17---frequency-domain-analysis-part-iii-bode-plot-simple-model)        |              MCE:   7.7 -7. 8            |
|          |        12. Nov. 4, 6      |             [Project - Simulation and Control of Robotic Exoskeleton](#lecture-19---project---simulation-and-control-of-robotic-exoskeleton)            |              [Frequency Domain Analysis Part IV Bode Plot Complex System](#lecture-20---frequency-domain-analysis-part-iv-bode-plot-complex-system)            |             MCE:   7.11 – 7.13           |
|                 |       13. Nov. 11, 13     |      Project:   Bode Diagram: Design and Control    |              Project: Robot System Simulation Implementation             |             MCE:   7.11 – 7.13           |
|     Control            |       14. Nov. 18, 20     |               Lead Compensation Control             |                  Lag Compensation Control                |                     -                    |
|                 |       15. Nov. 25, 27     |                Project:   Control of Robot              |            No   Classes (Thanksgiving Day)          |                     -                    |
|                 |         16. Dec. 2 , 4      |     Final exam Review    |                                                     |                     -                    |
|                 |         17. Dec. 9, 11       |                                               |                   Final Exam                                  |                     -                    |

## Lecture Slides

### Lecture 1: Course Overview
[PDF](https://www.dropbox.com/scl/fi/wovkvwgidfzk44qimz0ao/Lecture-1-Course-Overview.pdf?rlkey=vz7a1g5ahtoqflyi4bp28bjgz&dl=0) | [PPT](https://www.dropbox.com/scl/fi/2lm4z8cqi8326sa9viuzh/Lecture-1-Course-Overview.pptx?rlkey=eso64qwr3v7xxh7irkywj2c5d&dl=0) (updated on 08/23/2024)

### Lecture 2: Closed-loop Control 

[PDF](https://www.dropbox.com/scl/fi/e6lf6tbjkw8wil00zp9uf/Lecture-2-Closed-loop-Control.pdf?rlkey=co5usxwb3n2kq612tipmajz7g&dl=0) | [PPT](https://www.dropbox.com/scl/fi/gv4boo1670bkrxeh0dsv8/Lecture-2-Closed-loop-Control.pptx?rlkey=wxzq9wntitswsqv5xzkfhq7x1&dl=0) (updated on 08/23/2024)

### Lecture 3: Laplace Transform and PID Control

[PDF](https://www.dropbox.com/scl/fi/kd1klqdel4jevlescwnqf/Lecture-3-Laplace-Transform-and-PID-Control.pdf?rlkey=34j2hf05t0g8qo7j740bibi16&dl=0) | [PPT](https://www.dropbox.com/scl/fi/9i5pwqnbtv4ctz98rx77n/Lecture-3-Laplace-Transform-and-PID-Control.pptx?rlkey=016r0hxkk0cms2kx4bqhnlnea&dl=0) (updated on 08/28/2024)

### Lecture 4: Laplace Transform and Transfer Function

[PDF](https://www.dropbox.com/scl/fi/ekh54uvee6rso10u64ail/Lecture-4-Laplace-Transform-and-Transfer-Function.pdf?rlkey=7scg1rb4uwiod13p8f21twix7&dl=0) | [PPT](https://www.dropbox.com/scl/fi/1qs98b3uxg4theqi65mg5/Lecture-4-Laplace-Transform-and-Transfer-Function.pptx?rlkey=2iwmu3dfihbqcigrgiahn2s7c&dl=0)

### Lecture 5: Laplace Transform Pairs and Inverse Laplace Transform

[PDF](https://www.dropbox.com/scl/fi/25goediymcnec3xz9kwsh/Lecture-5-Laplace-Transform-Pairs-and-Inverse-Laplace-Transform.pdf?rlkey=1iwt2uxx8sb3mwesi0dg1dgrb&dl=0) | [PPT](https://www.dropbox.com/scl/fi/z9givuxo4zv75ym0iuxue/Lecture-5-Laplace-Transform-Pairs-and-Inverse-Laplace-Transform.pptx?rlkey=3h14at91wj4k90khfv9rzxeqb&dl=0) (updated on 09/04/2024 after class)

### Lecture 6: Mechanical System Modeling

[PDF](https://www.dropbox.com/scl/fi/tf1oqfojvexrag0aewnum/Lecture-6-Mechanical-System-Modeling.pdf?rlkey=fkog44evjd9gxglajvgu45nmo&dl=0) | [PPT](https://www.dropbox.com/scl/fi/8p6gdt41v70vd8i4q8fdu/Lecture-6-Mechanical-System-Modeling.pptx?rlkey=nrq0a6hsj75yx67a7ffbm3fu3&dl=0) (updated on 09/11/2024)

### Lecture 7: Electromechanical System Modeling

[PDF](https://www.dropbox.com/scl/fi/4xby05l1lj1jvc0yf63g0/Lecture-7-Electromechanical-System-Modeling.pdf?rlkey=jtnjnvif3j25y6nqpzg8h3wno&dl=0) | [PPT](https://www.dropbox.com/scl/fi/k4tkeb182nwu7mbzfanhn/Lecture-7-Electromechanical-System-Modeling.pptx?rlkey=xa3dwv38f5kho267kwj0tg5in&dl=0)

### Lecture 8: Project - Introduction to MATLAB

[PDF](https://www.dropbox.com/scl/fi/42fs0ogumnzbnhqne23zn/Lecture-8-Project-Introduction-to-Matlab.pdf?rlkey=gah24zh8zskwrwbt1mq7y0e0q&dl=0) | [PPT](https://www.dropbox.com/scl/fi/d9wxgbdinw3gm8r3z8lh3/Lecture-8-Project-Introduction-to-Matlab.pptx?rlkey=sqb6a2mli8ezeioctezue6j8k&dl=0)

### Lecture 9: Control Block Diagram

[PDF](https://www.dropbox.com/scl/fi/pgztwc3xocjfo3kt47a77/Lecture-9-Control-Block-Diagram.pdf?rlkey=2g71cvxhhe5u6uyx6jv43119l&dl=0) | [PPT](https://www.dropbox.com/scl/fi/r6hi5xcnmbr5gy23c9mx3/Lecture-9-Control-Block-Diagram.pptx?rlkey=uaegejj5kkn8a6s0ogs58850f&dl=0)

### Lecture 10: Project-Simulink Introduction

[PDF](https://www.dropbox.com/scl/fi/5lplr90hi91adnsyiq2hc/Lecture-11-Time-Domain-Analysis-1st-Order-System.pdf?rlkey=x0z0olh0qmzau2mkdhqlyo0pt&dl=0) | [PPT](https://www.dropbox.com/scl/fi/y8j8gzuwirttojt33qqeh/Lecture-10-Project-Simulink-Introduction-Part-I-Sainan-is-working-on-it.pptx?rlkey=v2vv4moxoqvqrtiptw17e8nmd&dl=0)

### Lecture 11: Time Domain Analysis - 1st Order Systems

[PDF](https://www.dropbox.com/scl/fi/dyx7wue3wimjaro483did/Lecture-10-Project-Simulink-Introduction-Part-I-Sainan-is-working-on-it.pdf?rlkey=8psy1fscnms73wd013tnlvoen&dl=0) | [PPT](https://www.dropbox.com/scl/fi/awyh0vc4chsboz6v4lmvr/Lecture-11-Time-Domain-Analysis-1st-Order-System.pptx?rlkey=i6nto5dp9rlxmic0zi5zjawf6&dl=0)

### Lecture 12: Midterm Review

[PDF](https://www.dropbox.com/scl/fi/017rf8gjhxou493rqct8u/Lecture-12-Midterm-Review-with-Homework-Problem.pdf?rlkey=9fys4x281twv6s6nxpvr56o54&dl=0) | [PPT](https://www.dropbox.com/scl/fi/50hugruc9rt2brqifbn5f/Lecture-12-Midterm-Review-with-Homework-Problem.pptx?rlkey=fdp8gmhkk2axmlumhvuak6n53&dl=0)

### Lecture 13: Time Domain Analysis (2nd Order System)

[PDF](https://www.dropbox.com/scl/fi/34u3cq3oxhds59poeay5w/Lecture-13-Time-Domain-Analysis-2nd-Order-System.pdf?rlkey=d77qx3s4wi4jm0alyj9kpqa3l&dl=0) | [PPT](https://https://www.dropbox.com/scl/fi/oxbyfnpx5lbm5ywh7v5it/Lecture-13-Time-Domain-Analysis-2nd-Order-System.pptx?rlkey=rtkl03yj9i7xffdoua8a9yioi&dl=0)

### Lecture 14: DC Motor Modeling, PID Control and Simulink Implementation

[PDF](https://www.dropbox.com/scl/fi/ulwll16ax2qwfgy4y1nt9/Lecture-14-Project-DC-Motor-Modeling-PID-Control-and-Simulink-Implementation.pdf?rlkey=t15yk7x3lw4jme1vl3gv4jsbp&dl=0) | [PPT](https://www.dropbox.com/scl/fi/s7tekqva7ctpc1yo282gq/Lecture-14-Project-DC-Motor-Modeling-PID-Control-and-Simulink-Implementation.pptx?rlkey=v34wtk5wbjw18a3fqt1t0xg5w&dl=0)

### Lecture 15: Frequency Domain Analysis Part I - Introduction

[PDF](https://www.dropbox.com/scl/fi/jkvnisytiej1wzlvev5lx/Lecture-15-Frequency-Domain-Analysis-Part-I-Introduction.pdf?rlkey=3v78o8bv8imgiol2da3hpir80&dl=0) | [PPT](https://www.dropbox.com/scl/fi/oi22wm6zmaljeaz4l6g07/Lecture-15-Frequency-Domain-Analysis-Part-I-Introduction.pptx?rlkey=1ak0ud2m9ulbix6p6r6gefnr8&dl=0)

### Lecture 16: Frequency Domain Analysis Part II Bode Plot Overview

[PDF](https://www.dropbox.com/scl/fi/fz9zdhkhsba82z7dlwnp3/Lecture-16-Frequency-Domain-Analysis-Part-II-Bode-Plot-Overview.pdf?rlkey=awt1y88hm9hgm1q1682q18596&dl=0) | [PPT](https://www.dropbox.com/scl/fi/6rouinnunx8msfz6r6hk4/Lecture-16-Frequency-Domain-Analysis-Part-II-Bode-Plot-Overview.pptx?rlkey=i87bwx38efw7ws3cl4mi5s0w2&dl=0)

### Lecture 17 - Frequency Domain Analysis Part III Bode Plot Simple Model

[PDF](https://www.dropbox.com/scl/fi/lcu55cubnlzyjphcz44vv/Lecture-17-Frequency-Domain-Analysis-Part-III-Bode-Plot-Simple-Model.pdf?rlkey=akt20vtmsx590az52600ohdv3&dl=0) | [PPT](https://www.dropbox.com/scl/fi/y4l5mfqhyqf8as876ca6a/Lecture-17-Frequency-Domain-Analysis-Part-III-Bode-Plot-Simple-Model.pptx?rlkey=ua5a2qj0t8c1zntdpu27si1jn&dl=0)

### Lecture 18 - Midterm Exam Question Review

[PDF](https://www.dropbox.com/scl/fi/ksbyr1lvliu0wcq46uy89/Lecture-18-Midterm-Exam-Question-Review.pdf?rlkey=9n7v7uypo5ka3wgezfcbni3hw&dl=0) | [PPT](https://www.dropbox.com/scl/fi/trirxdh1jz1ys4eogbl1b/Lecture-18-Midterm-Exam-Question-Review.pptx?rlkey=erwhvyjx09i0janwcnn4560nb&dl=0)

### Lecture 19 - Project - Simulation and Control of Robotic Exoskeleton

[PDF](https://www.dropbox.com/scl/fi/5u4yq4k66wl1jeub3575c/Lecture-19-Project-Simulation-and-Control-of-Robotic-Exoskeleton.pdf?rlkey=9sgsb8703vz7k0iqm6tn8x6z6&dl=0) | [PPT](https://www.dropbox.com/scl/fi/897n50hb6q50fkssp3uvl/Lecture-19-Project-Simulation-and-Control-of-Robotic-Exoskeleton.pptx?rlkey=c654xpv5jvbpgdav72jeqxwul&dl=0)

DC motor bandwidth code: [Link](https://www.dropbox.com/scl/fo/5mm4n42a4uonj1l0loj4c/AD-JQQVkD2RUW1j9Nws20_8?rlkey=qyn7jqd8wezghf0wpwmz7fe5i&dl=0)

Hip Exoskeleton Bandwidth code: [Link](https://www.dropbox.com/scl/fo/21d5n94tnfo1c8ki11bex/AFLmkKX1dQys3TqJInazmxo?rlkey=8w9en2wb32pakghdjzyfaqz84&dl=0)


### Lecture 20 - Frequency Domain Analysis Part IV Bode Plot Complex System

[PDF](https://www.dropbox.com/scl/fi/whjd9cc32qdu62k60c8ns/Lecture-20-Frequency-Domain-Analysis-Part-IV-Bode-Plot-Complex-System.pdf?rlkey=5tahtuca23nd14bu98s38brna&dl=0) | [PPT](https://www.dropbox.com/scl/fi/jaka603vr38vurvjodoc1/Lecture-20-Frequency-Domain-Analysis-Part-IV-Bode-Plot-Complex-System.pptx?rlkey=93iqr98jsryjmb06i5o2imgio&dl=0)


<br>

## Supplementary Materials

* Math Foundations - Tables of calculus, complex number, ODE: [PDF](https://www.dropbox.com/scl/fi/gkygsq1mhyw52tymibwe4/Math-Foundations-Tables-of-calculus-complex-number-ODE.pdf?rlkey=ygjmxdt3lcvxdgnutqk10fptn&dl=0) | [PPT](https://www.dropbox.com/scl/fi/76ehrk8rfkocxdcbsyqn2/Math-Foundations-Tables-of-calculus-complex-number-ODE.pptx?rlkey=t5gqnn4iob37zdakzkjyykee3&dl=0) (updated on 08/28/2024)

## Resources

### Books
* Katsuhiko Ogata, Modern Control Engineering (MCE), any recent edition (recommend the 5th version), Pearson Prentice-Hall, Upper Saddle River, NJ.
* K. Ogata, System Dynamics (SD), 4th ed., Prentice Hall, Upper Saddle River, NJ, 2004.
### Papers

### Videos

## FAQ
