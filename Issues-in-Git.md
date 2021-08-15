To successfully manage a project, any project, you have to plan in advance; just reacting

to new inputs and generally doing whatever you feel like is a perfect recipe for disaster.

A GitHub project is no different; you have to keep track of your actions before even thinking about doing them. That’s why GitHub has an awesome feature called Issues. We are going to discuss them in this section and learn how to manage them properly.

During all the sections of this course, you are both the developer and the project manager; but in a big project, you might not be included in the planning phases. However, for now, you are temporarily promoted to project manager and lead developer (in addition to being the only developer), congratulations! One of the duties of the project manager is to plan in advance all the tasks that need to be done. The plans don’t need to be very precise yet (in the real world they never are), but it is necessary to have a list of all the tasks that need to be done. Those tasks can be either new features, bug fixing, or just a team discussion. In GitHub, those tasks are called Issues. 

An issue is used to track new feature development, bug fixing, or new ideas that a team member suggested. They are the brick and mortar of GitHub project management; in theory, no action should be done with an issue being attached to it. The aim of each action you take should be the resolving of an issue.

Long gone are the days where planning the next steps was done by boring team meetings; now you know exactly what will be your next steps, and most importantly, what everybody else is doing. Suggesting new ideas to your coworkers is easier than ever; just open an issue to discuss it with your team without using another app or email client. The biggest plus for using issues is that the history is kept forever—each feature, each bug, and each discussion.

Creating an Issue
The best way to learn about issues is to directly interact with them. Therefore, let’s head back to our GitHub project page and deal with them.

When you open your GitHub project page, you directly arrive on the “Code” part of the project. It is the part where your project files are shown.

# todo add screenshots

Just below the project name are many tabs that show all the sections of your project. You will mostly work on “Code,” “Issues,” “Pull Requests,” and “Projects.” However, for now, let’s focus on Issues. Go ahead and click on issues  to begin. You should arrive at an empty section like the one shown below because your project has no issues yet.


There are many calls to action there about creating a new issue. Click one of them, and you will see a form similar to mine as shown below.


The form is pretty simple; and only the title is mandatory. There is also a comment section below the title, if you need more room to explain. Let’s go ahead and fill our first issue with the basic stuff; don’t change the values on the right side just yet.

For our first issue, we are starting a discussion about the technology we will use for our product. Issues aren’t needed for features and bug tracking only; they are also used to start a discussion and share ideas. Go ahead and fill your first issue like mine as shown below; I titled mine “Data collection”.


Now that we filled out the basic info about the issue, submit it. You will then be redirected to the detailed view of your new issue. It should be similar to my issue shown below,


The first thing to note is that your issue has been given a number. Each issue has a unique number, and those numbers are not recycled. This  means that even if you delete an issue, its number will never be reused. This number is important, as you will see in this section.

The details page also includes a comment section where team members can discuss

the idea. It even includes a limited number of emojis that you can use as a substitute to

commenting. For example, if you agree with someone, giving them a thumbs-up is better

than commenting or writing “me too”! It would clog the communication and stall the

conversation.

At the bottom right side of the page is a “subscribe” button. If you choose to subscribe to an issue, you will receive notifications about the changes done to it. You will also receive new comments and news about milestones reached.

Since you are the only member of the team, you won’t do much discussion. Just add a comment or a reaction image and close the issue. Closing the issue won’t delete it; it will just mark it as completed. Deleting issues is not advised because keeping a history of the project is needed, and issues are the best way to keep track of changes. Also remember; if your repository is public, anyone can read your comments. Hence, please be kind and rewind any unpleasantries that might arise.

After commenting and closing the issue, you will go back to the issue details page, and it will look similar to mine as shown below,

Those are some basic steps that we will need to follow to accomplish our goal. Since you already know how to create issues, I will let you create an issue for each of these bullet points. After you are done, your Issues page should look like mine as shown below.

Before that, we can rename our repo from “to do” to something more data science. Bearing that in mind, I renamed mine to “basic model”, you can rename yours to anything you want.

To this just click on settings , as shown below, choose a different name and click on “rename”

Your issue page should look like mine, as shown below,


As you can see, the tasks are shown in the order in which they were introduced. There’s also no way to distinguish them except for their numbers, and it’s very easy to get lost if there are too many issues. , to have a clearer look at all our tasks, we are going to use Labels.

Labels
Labels are exactly what you expect them to be: texts to help you quickly filter through your issues. Let’s use them directly so you can get familiar with the concept.

As you can see in the figure above, there is a search bar in the Issues page, and you can use it to filter through the issues. However, since we don’t have any labels yet, we can’t do any filtering; just basic search. Click the Labels button next to the search bar to show all the labels available. You will then see a list of the default labels that you can use; check the Figure below for an example of this.


Those are the most commonly used labels in the developers’ community. Still, that doesn’t mean that they are mandatory or immutable; you can change them at will. Only when you are working on an Open Source project is it ill-advised to change them because most developers are used to them.

Since it’s your personal project and you are the project manager, you can add, edit, or remove any label you want. For example, the label “help wanted” will be useless if you work alone in a private setting. You can also use labels to tag the severity of the issue; many projects use labels like “urgent” or “breaking” if the issue is severe. Labels can also be used to differentiate the origin of the issue if the project is big enough. A big project can use the labels “frontend,” “backend,” or “database” to separate issues into groups.

After you made your changes to the labels (although I recommend to only add the new that you need and leave the default ones), get back to your issues and open the details page. Then, apply one or more labels on each one of them by clicking the Labels button. You can check Figure below for an example.


After you add the labels, a notification will appear on the comment section of the Issues page; you can check the figure below  for an example.

Now, go through each one of your issues and apply some labels on them. Then, when you have finished, go back to the Issues page. It should look like mine (as shown below).