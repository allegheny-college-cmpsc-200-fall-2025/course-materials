# CMPSC 200: Computer Organization

![Vector art of 200 in hex, subtitle of course: Bare Metal in printer's black and white](https://raw.githubusercontent.com/allegheny-college-cmpsc-200-fall-2024/course-materials/media/images/CMPSC%20-%200xC8%20Banner.png)

## Important resources

* [Office hours schedule](https://chompe.rs/office-hours)
* [Course Calendar](https://chompe.rs/200-schedule)
* [Technical Leader directory](https://www.cs.allegheny.edu/teaching/technicalleaders/)

## Syllabus

> Computer hardware must exist, or at least be claimed to exist, before programmers can 
> even envision software for it. Just as cave dwellers didn’t squat with their flint tools 
> chipping out parking brake assemblies for 1967 Buicks, so programmers don’t write software 
> that has no computer upon which to run. 
>
> Mark Stephens (a.k.a. Robert X. Cringely) , _Accidental Empires_

### Course information

#### Meeting times

|Day(s) of Week            |Time          |Purpose     |Location                        |
|--------------------------|--------------|------------|--------------------------------|
|Monday, Wednesday, Friday |11:00 - 11:50 |Activities  |Alden 101                       |
|Friday                    |14:30 - 16:00 |Lab session |Alden 101                       |


### Contact

* Instructor: Douglas Luman
* Email: dluman@allegheny.edu
* Telephone: `+1 814 332 2136`
* Office: Alden Hall, 112 (next to the copier)

### Office hours

|Day(s) of Week            |                    |              |
|--------------------------|--------------------|--------------|
|Monday                    | 10:00 - 11:00      |13:00 - 15:00 |
|Wednesday                 | 10:00 - 11:00      |13:00 - 15:00 |
|Friday                    | 10:00 - 12:00      |12:00 - 13:00 |

### Canonical course description

A study of the low-level operation of computer systems. Participating in hands-on activities that 
often require teamwork, students investigate how computers process instructions in modern computers 
as information is encoded, stored, and executed in a machine’s physical structures. In addition to 
learning how to program in assembly and machine languages, students investigate the design and logical 
operation of processors and the mathematics of machine computation. During a weekly laboratory session, 
students use industry-grade technology to complete projects, reporting on their results through both 
written documents and oral presentations. Students are invited to use their own departmentally approved 
laptop in this course; a limited number of laptops are available for use during class and lab sessions.

### Learning objectives

* Explain how programs written in high-level computer programming languages execute using lower-level computer circuitry
* Identify levels of the Memory Hierarchy and the implications of using the various levels to implement high-performance programs
* Develop C and Assembly language programs which use the appropriate levels of the Memory Hierarchy and processor registers to create performant, executable programs and arithmetic logic units
* Describe and use parallel processing techniques to increase a program’s performance and efficiency
* Integrate hardware and software components using original C and Assembly language code to develop hardware-based, performant computational projects

### Required materials

#### Textbook

This course does not use a standard textbook. Any additional materials required for the course will be provided by the instructor.

#### Platforms

Our work relies on your regular use of:

* [GitHub](https://github.com)
* [Discord](https://discord.com)

#### Hardware

Learning objectives revolve around using common hardware to provide a uniform platform for students. Over the course of the semester, 
you will be provided with three hardware platforms which we will use to complete activities and assignments:

* an assortment of integrated circuits and other parts
* the [PaperPC](https://github.com/Paperdyne/PaperPC)
* the Raspberry Pi Pico W

Assignments will require use of any devices provided and evaluation will be benchmarked to performance on hardware systems, 
_not necessarily personal computers (PCs)_. While you will use your PCs to program the devices, part of our work this semester 
is to understand the limitations and opportunities of environments which require understanding standard physical system 
topology and performance.

The above statement implies that this hardware, when distributed, is as essential to bring to and prepare for class sessions 
as if it were our textbook and course platforms.

### Governance and evaluation

This course's evaluation, participation and, eventually, grades, are governed by the [Course Contract](CODE_OF_CONDUCT.md).

This, however, does not abrogate the role of this syllabus document. Provisions here work together with the contract. 
You should consider the information provided here the basic "givens" of the course.

#### Assignments

All course assignments are assigned and evaluated using the GitHub platform. Your instructor will only assess work reposited there. 

#### Course project

The end-of-semester course project offers a choice: either a hardware- or software-rooted project aimed at exploring
course concepts beyond their in-class representations. In the closing weeks of the semester, your interest in this
project must be expressed in the form of a proposal. This proposal should contain an outline of the concept you
wish to pursue further as well as the key values or principles it tests or extends. The proposal will include several
unexclusive suggestions to give you a start.

### Allegheny College Statement of Community

Allegheny College also expects students and faculty to act according to its Statement of Community:

> Allegheny students and employees are committed to creating an inclusive, respectful and safe residential learning community 
> that will actively confront and challenge racism, sexism, heterosexism, religious bigotry, and other forms of harassment and 
> discrimination. We encourage individual growth by promoting a free exchange of ideas in a setting that values diversity, trust 
> and equality. So that the right of all to participate in a shared learning experience is upheld, Allegheny affirms its commitment 
> to the principles of freedom of speech and inquiry, while at the same time fostering responsibility and accountability in the 
> exercise of these freedoms. This statement does not replace existing personnel policies and codes of conduct.

### Honor Code

All students and faculty at Allegheny College are bound by the Honor Code. Everyone expects that your behavior reflects this commitment. 
Given the eminently shareable and reproducible nature of code, the Department of Computer Science adds the following statement to the 
general college policy:

> It is recognized that an important part of the learning process in any course, and particularly in computer science, derives from 
> thoughtful discussions with teachers, student assistants, and fellow students. Such dialogue is encouraged. However, it is necessary 
> to distinguish carefully between the student who discusses the principles underlying a problem with others, and the student who 
> produces assignments that are identical to, or merely variations on, someone else’s work. It will therefore be understood that all 
> assignments submitted to faculty of the Department of Computer Science are to be the original work of the student submitting the assignment. 
> Appropriate action will be taken when assignments give evidence that they were derived from the work of others.

The above statement, of course, also applies to solutions derived from discussions on Stack Overflow and other similar resources.

#### AI tools

CIS department faculty recognize that use of artificial intelligence (AI) tools such as Github Copilot, GPT, and Claude has emerged 
as a professional skill set in the knowledge and practices our coursework covers. Department faculty maintain a permissive attitude 
toward these tools by recognizing that you can and will use them. We do so considering the following position:

As a skill, using and correctly applying the results derived from AI tools is both context-based and discretion-worthy: these tools 
do not always provide correct or workable answers. Industry veterans and expert users run into many situations in which the responses 
these algorithms provide are plainly incorrect or unfit. In the context of department coursework, accepting an AI-generated answer 
wholesale or as a small part of an assignment may lead to less-than-satisfactory results in the context of both learning and deliverable 
quality.

As a learner, your time at Allegheny is meant to impart the knowledge that enables you to judge the fitness of a given approach, 
regardless of its origin. In the same way that CIS students employ compilers, integrated development environments, and refactoring 
tools, the use of an AI tool is not a substitute for developing the fundamental skills that develop this awareness. Importantly, 
research demonstrates that relying on generated responses reduces a learner’s ability to durably learn these lessons and skills, 
suggesting that you should cautiously embrace the use of AI when you complete CIS coursework <sup>1</sup>.

In courses organized around fundamentals, instructors may prohibit students from using these tools or require students to use 
specific AI tools in order to teach the basic skills and concepts that students need to know to be successful in the field of CIS. 
Even in upper-level courses, assignments may feature requirements that decrease the applicability of a response generated with AI, 
thereby requiring you to thoughtfully consider the benefits, challenges, and fundamental limitations associated with the use of 
AI tools to generate content.

If you are able to use the output of AI tools in your assignments, be prepared to support their use in ways including but not limited to:

* citing instances where code has been generated and clearly defining the tools that generated them
* providing descriptive commentary (including prompts) around generated code either in in-line comments or assignment documentation
* considering improvements to the generated code, documenting specifics about your modifications and reasoning behind them
* revising the generated code or documentation so as to ensure that it is more suitable for the purposes of your assignment

Faculty do not intend these requirements as a “gotcha”; we assume the best of your effort. These guidelines follow industry 
best practices and prepare you for integrating current and future generations of these AI technologies into your computational practice.

> <sup>1</sup> Binglin Chen, Colleen M. Lewis, Matthew West, and Craig Zilles. 2024. Plagiarism in the Age of Generative AI: Cheating Method Change and Learning Loss in an Intro to CS Course. In _Proceedings of
> the Eleventh ACM Conference on Learning @ Scale (L@S '24)_. Association for Computing Machinery, New York, NY, USA, 75–85. https://doi.org/10.1145/3657604.36620

### Classroom ethics

The discipline of computer science, like many others, encourages its members to act according to discipline-specific ethics. Your instructor encourages you 
to take time to review the Association for Computing Machinery (ACM) [Code of Ethics](https://www.acm.org/binaries/content/assets/about/acm-code-of-ethics-booklet.pdf).

### Seeking assistance

#### Assistance with course concepts

Students who struggle to understand knowledge and skills defined in this course are encouraged to seek assistance from instructional staff. To meet 
with me, consult my available office hours (above) and make an appointment.

Historically, students who are successful in my courses visit and discuss course concepts with instructors or TLs early and often. See [above for my office hours](#office-hours) 
or go to [this schedule for Technical Leaders' office hours](https://www.cs.allegheny.edu/teaching/technicalleaders/).

#### Assistance outside of the course

If you find yourself in difficult circumstances which affect your ability to participate in or complete course work, let me know immediately. Full stop.

Do not wait until the end of the semester. 

*It is part of your instructor's job* to make sure that students receive the assistance they need. Do not hesitate to let me know if there is anything your instructor can do 
with respect to your ability to handle your work. This is especially true of our current circumstances. Again, be reminded -- __**it is part of your instructor's job**__ 
to help you access Allegheny College resources that will enable your safety and success.

In many situations, the following list of resources may help:

* [The Maytum Learning Commons](https://sites.allegheny.edu/learningcommons/)
* [Allegheny College Counseling Center](https://sites.allegheny.edu/learningcommons/)
* [The Winslow Health Center](https://sites.allegheny.edu/healthcenter/)
* [Student Life](https://sites.allegheny.edu/studentlife/)

### Special needs and disability

Students with disabilities who need accommodations in this course are encouraged to contact Disability Services at `+1 814-334-2898`. 
Disability Services is part of the Learning Commons, located in Pelletier Library. Should you need accommodations, contact this office as 
soon as possible to ensure that approved accommodations are communicated and implemented as quickly as possible. This serves both you and me 
in providing the best environment for learning and support.
