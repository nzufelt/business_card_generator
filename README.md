# Business Card generator app
_Designed by: Nick Zufelt_

In this project geared for beginning app development students, the task is to create an app which generates business card designs for the user. Students need to investigate the ways in which someone might misuse their app and seek to design with that in mind.

### Context
This lesson has traditionally been used near the beginning of my iOS app development class. It is a class that is typically taught to 10th, 11th, and 12th grade students who have not taken any previous computer science courses. Before this assignment is started, students have learned the basics of visual app layout, such as visual hierarchies and simple "views" such as text, images, form-type inputs (text boxes, radials/pickers, toggles/checkboxes, and the like), as well as the tools necessary to style these and to combine these into more complicated visual layouts (flex boxes, "stacks" in SwiftUI, etc.). Students have also worked with questions about user data collection: as an app developer, what information do you _need_ to collect to have a functional app, and what rights to privacy and knowledge of your data practices are owed to users. While this isn't strictly necessary experience for this assignment, it does inform my students' experience in the project.

This app was designed to replace a sort of "my first functional app", such as a calculator or a "Mad Libs" type of program. With a few modifications, this project could appear outside of an app development class in similar ways, though it's certaily quite visual in nature, so students would need to have experience building a visual, and not text-only, output from their code.

### Learning Objectives and Assessment
After completing this project, students can:

* make informed arguments about the potential harms their code can cause by thinking through the idea of _user personas_,
* design an app with multiple screens which pass data from one screen to another, and
* make arguments about their visual design choices.

As is often the case in project-based learning, the teacher can be sure that students have met these learning objectives by submitting a project which includes both the app itself as well as the supporting design materials: a drawing of the planned business card design, a collection of user personas, and a list of the fields of data their app will collect from their users.

### Plan
The unit in which this project belongs begins with quick lessons on the technical basics of _form design_, where students create simple forms which take in user input and put that information into some kind of visual layout. 

We also make sure to learn about the notion of _user personas_, including the comparatively newer practice of creating personas of people seeking to exploit either your app or its users. In order to do this, students typically read and watch the following resources:

* The first is [Personas – A Simple Introduction](https://www.interaction-design.org/literature/article/personas-why-and-how-you-should-use-them), by Rikke Friis Dam and Teo Yu Siang. This is a blog post which walks readers through the concept of user personas, a practice in the world of user experience (UX) design.
* The second is [Zoombombing, Technology Ethics & Awful People Being Awful](https://www.youtube.com/watch?v=KI_3sF3SPq8), by Dr. Casey Fiesler. This video essay discusses the concept of _ethical debt_, and how user personas might be used to help mitigate it.

Then, the project itself is broken into three phases: design, structure, and development.

In the **design** stage, students create some user personas, including "traditional" personas of a supposed "typical" user (which in itself presents an interesting discussion opportunity: _what is a "typical" user for your app, and how do you know this?_) as well as "troublesome" personas of people who might seek to exploit your app and/or its users. Often, since students are all designing a similar app as one another, we can do a "gallery walk" of personas and students can view all of them at the end of this stage and throughout the project.

From this information, students begin to flesh out a robust collection of all possible fields of data that you might want to collect from their users to display on a business card, such as first name, last name, title, company, phone number, or email. Students use the user personas to inform their thinking — for example, a user's home address should not be a required field to fill out, but some students may choose to add that as an optional field.

Finally, students create at least one visual design for their business card.

In the **structure** stage, students can receive individual feedback from their peers and their instructor on their design work while they begin to lay out the basic structure of their app: a form which passes data to another screen, which displays this information rather simply. A typical class has me working with individual students, and them partnering up as needed to have their technical and design questions answered.

In the **development** stage, students put all their work together to create a visually complete app, along with feedback from myself and their peers. A typical class period is a "workshop style" with people asking for help as they need it, or seeking out assistance from their peers. I might iunclude "checkpoint assignments" along the way, but for an app this small I usually do not.

After this step is completed, I typically have students reflect on their learning along our course's learning objectives, which include both technical an ethical elements.

### Files and Resources

* [Student handout](Student_handout.md)
* [Personas – A Simple Introduction](https://www.interaction-design.org/literature/article/personas-why-and-how-you-should-use-them), by Rikke Friis Dam and Teo Yu Siang.
* [Zoombombing, Technology Ethics & Awful People Being Awful](https://www.youtube.com/watch?v=KI_3sF3SPq8), by Dr. Casey Fiesler.