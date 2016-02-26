## Intro {#intro}

Let’s be damn honest here. Estimating is for most of us the worst part of our
job. We didn’t sign up for this. They didn’t teach us this in school. But if you
get it right it will make your life so much better. There’s nothing worse than 
screwing up an estimation and having to deal with either not making a deadline, 
going over budget, working late hours to patch it up and so on.
.

## Process examples {#process-examples}

Having worked in advertisement I witnessed the worst ways to estimate projects
which went pretty much like this:*“Hey, I’ve got a project for you. The
design is finished and needs to be implemented and functional by December 12th 
because that’s when the TV ads go live. How much time do you need? Thanks!
”*

In the example above the process went something like this. Let’s call this
process a**release date centered process:**

1.  Someone sells the project to a client and defines a release date
2.  Someone designs it
3.  Someone implements the design

Instead of having the main focus on the user, this process focuses on the
client getting something done by a deadline. Sometimes there is a lot of time 
and money on the table which gives people involved some slack to actually 
iterate and do some improvements on the UX. But it’s mostly a rush from start to
finish because**the deadline isn’t set by the doers in the project.**

The process I’m the biggest fan of and it’s the one I’m currently working
with these days. It’s a**user centered process.** Since I work in a
multidisciplinary design consultancy which does digital, physical products and 
services, the user is always in focus from start to finish. I’m involved in the 
digital projects and the process looks something like this:

1.  A service designer sells the project to a client by having a workshop where
    they together define the bottleneck of their current product
   
2.  Insight phase where we define user needs and touch points
3.  Design phase with a goal to meet user needs discovered in insight phase
4.  Prototype design with some mock code or a prototyping tool such as 
    [Proto.io][1] or [Framer.js][2] 
5.  Implementation phase

## Estimating in a user centered process {#estimating-in-a-user-centered-
process
}

Let’s say the project is at a point where we know there’s going to
developed a digital service like a website or a web app. But to go further the 
client wants an estimate on how much it is going to cost them. Naturally. Where 
do you take it from here? Let me tell you how we usually do it with a 90% 
success rate.

### User stories {#user-stories}

Maybe you’ve heard of [user stories][3] and maybe you haven’t. It’s the
essential key to making a successfull estimate and a professional offer to the 
client. It should be a central part of any design process, and if you’re a 
developer you’ve probably been using them already in a[Scrum][4] project. I
want to say it should be the first thing you talk about in the first meeting 
with the client. It will help the client tell you what they want in a really 
clear way. If they don’t know then you should help them out and you will figure 
it out together. You could do this in a workshop format like I mentioned earlier.
If you have the resources you should also talk to potential users and listen to 
their needs and plot them in a user story format.

Here is a user story template: *“As a user I would like to ……… so that
I can
……… “.*

When you have a set of user stories ready you will be able to do this:

*   Rate them from crucial to nice-to-have. If there is a limited budget you
    now know what you should focus on.
   
*   You can now design to meet the user stories. Every design decision should
    be taken based to meet a a user story. Each user story will be a design task.
   
*   In the technical implementation phase we can use the user stories in a lean
    project where each user story is a topic with a set of sub tasks to meet the 
    needs of the user story.
   

As you can see from the list above, by having user stories as the core purpose
of the project we should eventually sit with a product which is completely 
centered around meeting needs of the users.

### Estimating a frontend web job based on user stories {#estimating-a-frontend
-web-job-based-on-user-stories
}

As mentioned above, you will use user stories as a topic when creating tasks in
the project. If you as a developer get involved in the project right before the 
implementation phase and you’re assigned to estimate it, the job is extremely 
simple if the designers have centered their work around user stories. If not, 
you have a big job to do. You’ll have to create fake user stories based on 
already designed mockups. This is worst case, but you should do it anyways cause
you’ll probably help the designers find some holes in their UX.

So.. let’s say you have all of your user stories ready and you’re ready to
estimate. Let’s also say that the service you’re creating is a web app for 
managing resources in a team. You have a list of stories like:*“As a user I
want to easily see if an employee has an empty time slot during a certain period
of time so that I can allocate him/her to a project
”*

With the particular user story above, you could possibly end up with a lot of
tasks each with their own sub tasks. Example:

*   Create a calendar which displays an employee’s allocation 
    *   Create a calendar component (14h)
    *   Implement a calendar API (2h)
    *   Task 3 (4h)
    *   Task 4 (2h)
    *   Task 5 (10h)

After you have listed up everything that is needed to fullfill the user needs
in the user story, you end up with a set of hours you can use in your estimate. 
This particular user story will take 32 hours. Now you not only have a number of
hours to tell the client, you also have a reason you’re worth these hours. It 
will be like going to the grocery store for the client. To be able to make an 
apple pie you’ll need some ingredients – some more important than others. But 
they are all there for a purpose, which is to make one delicious pie.

Your estimation and offer document to the client should now consist of these
things:

*   A summary of your understanding of the brief (to make sure you’re seeing
    eye to eye on what needs to be done
    )
*   A summary of the concept (to make sure you let your client know you have
    understood the concept
    )
*   A list of user stories based on the understanding of the brief
*   A list of tasks based on the user stories
*   The actual estimate including: 
    *   The task
    *   Delivery
    *   Hours needed
    *   Cost (hourly rate * hours needed)
*   Summary

PS! The last offer and estimation job I did, which was yesterday, I involved
the client by sending them a link to a Google Document where we finished the 
user story list and the task list together. This really made a huge difference 
as it shifts the game from where I usually would do the estimation job myself 
and send the client a nice PDF where they either would say yes or no. It created
a discussion and understanding. And now they were involved in creating the costs
for themselves rather than me claiming I needed the hours.

 [1]: https://proto.io/
 [2]: http://framerjs.com/
 [3]: https://en.wikipedia.org/wiki/User_story
 [4]: https://en.wikipedia.org/wiki/Scrum_(software_development)