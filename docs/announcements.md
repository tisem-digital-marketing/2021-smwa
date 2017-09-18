# Announcements

Important announcements will be posted here to avoid our inboxes getting clogged up.

If you have questions - direct them to us via [Slack](https://pp4rs.slack.com). There's a 'Direct Message' feature so you can contact us individually as needed, but where possible post messages to a channel that all participants can see.

<!-- !!! note "Student Assignments"
    *Date Posted: 2017-09-18*

    Some people have asked for more detail about the course assignment:

    * Due date: Friday, October 20 at 23:59. (We gave you an extra week)
    * Submission format: Invite @lachlandeer to collaborate on your GitHub repository by the due date.
        * This means, we expect well version controlled work.
        * Tag your final submission using the following git command `git tag -a v1.0 -m "submitted version"`
        * You must have a README.md in the main directory with instructions on how we can build the assignment.
    * Explictly document somewhere what packages we need to install so that your assignment runs on our machine with no issues.
    * Your assignment must execute with either:
        * `snakemake all` (preferred)
        * Pressing `Run all` or `Knit` at *most* 5 times (5 notebooks), that each cannot be too long.
            * Make it clear which order they should run in your README.md. Import functions you write into the notebook rather than clogging them up with a lot of functions.
            * If you want to run knitr or your notebooks from snakemake, contact @lachlandeer for some code to get it to work
    * Discuss with one of us your proposed assignment before you start
        * We can evaluate whether it is do-able within the time frame
        * Don't try and be too fancy, it's more important that it works
    * To pass the course:
        *  Your code must build without errors (unless we find something really weird, then we will reach out to you)
        * Must be version controlled
        * Inputs and outputs must be in separate folders
        * There must be a short writeup of the results you obtain
    * Ask us for help as needed. We rather a simple assignment that builds first time than something complicated that throws us error messages -->

!!! note "We are done!"
    *Date Posted: 2017-09-18*

    The 2017 edition is now over. Thanks to all who attended, and the rest of the instructional team who made it a success.
    Some important pointers:

    * An archived version of the installation guide is permanently available [here](https://pp4rs.github.io/2017-uzh-installation-guide/).
    * An archived course syllabus is [here](./assets/pp4rs-syllabus)
    * This website, and the course materials repo will remain indefintitely.
    * The course material repo may evolve some more over the next week or so as we upload final versions of some files. Use your `git pull`-ing powers to check you have the latest files.

    See you around!

    Lachlan

!!! note "Schedule Updates"
    *Date Posted: 2017-09-10*

    Due to some meetings we cannot avoid, we have pushed the schedule around a little bit.
    Check out the updates [here](./schedule.md)

!!! note "Knabenschiessen"
    *Date Posted: 2017-09-10*

    We will teach Monday afternoon through Knabenschiessen until 1700.
    Lunch may be hard to source, we may decide to order as a larger group.

!!! bug "Ch-Ch-Changes in the Room allocation"
    *Date Posted: 2017-08-31*

    We have again been moved for the Thursday class.

    On Thursday, September 7th we will again be in **RAK-E-6.**

!!! bug "Room re-allocation"
    *Date Posted: 2017-08-31*

    It seems we are not important enough in the University system, so they double booked us.

    Today, 31 August, we are in SOF-E-17 instead, which is the ground floor of the Department of Economics.

!!! bug "Extra Packages for R"
    *Date Posted: 2017-08-22*

    We added some additional packages for the R sessions.

    **If you have already completed the installation guide**: open RStudio and enter the following into the console and press `Return`:

    ```r linenums="1"
    extra_packages <- c("multiwayvcov", "RSQLite", "dbplyr")
    install.packages(extra_packages)
    ```

    **If you have not yet completed the installation guide**: we have added these packages to the instructions, so you can follow it as is.


!!! note "Welcome Message"
    *Date Posted: 2017-08-18*

    Welcome to the course "Programming Practices for Research in Economics" - 2017 edition.

    Please take a look around the [course website](https://pp4rs.github.io/2017-uzh) before the course begins. All the latest information about the course contents, schedule and course locations (which vary day-by day!) are available on these pages.

    We particularly draw your attention to the:

    *  **[Installation Guide](https://pp4rs.github.io/installation-guide)**. These pages walk you through the steps needed to install all the software for the course.
        * We expect you to have completed it before the course begins.
        * We are offering help to individuals struggling with the steps involved in the installation guide in a 'Help Session' before the course begins: Friday, August 25th, between 9.30 and 12.30 in [SOF-E-09](https://www.openstreetmap.org/way/33806996).
            * Note that we expect you have tried to complete the guide yourself, and we will not be there to do it all for you.
            * The guide is modular in nature - with most steps being independent of those before and after.
            * Learning to install software for scientific research on your own machine is an important task in itself - and we want to help you become self-sufficient in this regard.
    * **[Pre-Course Survey](https://goo.gl/forms/EER5ThZwazBzDvxi2)**.
        * Please fill this out before the course begins.

    To avoid clogging up everyone's inboxes with course email, all future important information will be posted on the course's [Announcements page](https://pp4rs.github.io/2017-uzh/announcements) - be sure to check in there regularly. Smaller pieces of information and course chat will take place inside a chat enviroment, called [Slack](https://www.slack.com). Sign up to join the conversation [here](https://pp4rs.slack.com).

    We look forward to seeing you for Monday, August 28th at 9.30am.

    Best,

    the pp4rs team
