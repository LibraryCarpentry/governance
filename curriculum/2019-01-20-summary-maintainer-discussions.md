# Summary Library Carpentry Maintainer Discussions 14-17 January 2019
_See [Library Carpentry Maintainer Discussions Notes](https://pad.carpentries.org/lc-maintainers)_

## Communication Channels
Many LC Maintainers expressed a preference to using the Maintainers [mailing list](https://carpentries.topicbox.com/groups/maintainers) (due to there being too many channels to follow) but agreed that the [Slack channel](https://carpentries.slack.com/?redir=%2Fmessages%2FC8H5LN44V%2Fdetails%2F) would be helpful if you have an urgent question and need feedback quickly. Search for the Slack Channel #Maintainers. Chris Erdmann agreed to watch the Slack channel and encourage people to post on the mailing list if the threads might be of interest to people not following the Slack channel. All LC Maintainers are encouraged to join these channels, at least the mailing list if you only want to follow one channel.

If you need to engage with the Library Carpentry community about the lessons, you can find multiple channels here:

[https://librarycarpentry.org/contact/](https://librarycarpentry.org/contact/)

Like Slack, Gitter is a chat tool where sometimes members are more likely to respond more immediately, but alternatively, you can use the Topicbox list to reach a broader audience.


## GitHub Repository Workflows & Etiquette
In the past, the LC community did not take advantage of the assigning reviewers and labeling functionality.  A number of Maintainers discussed taking advantage of these features but leaving it to the individual lesson Maintainer groups to decide what is best for their team. For instance, in some cases where there are few Maintainers, it might not make sense to assign a reviewer. Regarding labels, The Carpentries Handbook section on Maintainers includes a number of labels to consider for the lesson Maintainer groups: [https://docs.carpentries.org/topic_folders/maintainers/github_labels.html](https://docs.carpentries.org/topic_folders/maintainers/github_labels.html).

A number of LC Maintainers expressed concern about proper etiquette when responding to submitters of issues and/or pull requests. The Maintainer Onboarding Lesson has a section on the [Social Aspects of Lesson Maintenance](https://carpentries.github.io/maintainer-onboarding/aio.html#preparatory-homework-3) that can help with this concern, particularly a resource on [Learning to Say No](https://opensource.guide/best-practices/#learning-to-say-no).

What happens when your lesson repository is a popular destination for instructor check-in? A number of Maintainers talked about creating an issue and/or pull request where people can accomplish this goal and participate in a lesson discussion. The best example of this is the OpenRefine lesson which is very stable and may suffer lesson bloat due to the number of submissions. In addition, creating an issue where instructors getting ready to teach a lesson can ask questions and get feedback might be an additional option to consider.

Maintainers agreed, do not merge/close pull requests/issues that are your own or someone else's without having the pull request/issue reviewed by another Maintainer. This may not be possible for some of the lessons with only a couple or few Maintainers, so it is up to the individual Maintainer groups to work through additional norms/rules.

Try to respond to issues/pull requests within two days. One Maintainer discussed how they schedule an hour or two every week to spend time on responding to or fixing issues/pull requests. If the level of difficulty is high, at least signal that to the submitter and community that the issue/pull request is being addressed (i.e. WIP is sometimes used to signal that something is work in progress). If there is no response on an issue/pull request for a long duration, Maintainers may choose to label it as 'not doing' and possibly close it.

Easily fixable items can be left to new contributors or Maintainers can sometimes decide to fix them quickly without review if the change is a small misspelling or grammatical change.


## Lesson Statuses
Some of the lessons are listed as stable or beta but have had a number of side discussions regarding substantial improvements. The consensus seems to be that OpenRefine and Shell are the most stable where very few, if any, changes need to happen. After that, Tidy Data seems to be slightly more stable with very few suggestions regarding improvements. Lessons that may need substantial improvements include Intro to Data, Git, SQL, Webscraping, and Python. LC Maintainers may want to signal to the community that a lesson status has changed from stable to beta in the README file of the lesson, header of the lessons, and/or an issue. It is likely that substantial changes will need to be brought to the attention of the [LC Curriculum Advisory Committee](https://librarycarpentry.org/cac/) for feedback/guidance. It might also be helpful to refer to the [lesson design template](http://carpentries.github.io/lesson-example/) if the Maintainers are looking at substantial changes. If you have an experimental lesson, then you definitely want to review the lesson design template but feel free to reach out to [Chris Erdmann](mailto:chris@carpentries.org) if you need additional assistance. Note, the [Etherpad for experimental or conceptual lessons](https://pad.carpentries.org/lc-experimental-lessons) is a place where you can signal to the community where you are at in your lesson development but Chris Erdmann can also help you with connecting with community members if you need to.

## Developing & Testing Lessons
For Maintainers developing lessons, there were questions about testing lessons and determining when they are ready to share. One idea is to test locally, hopefully with other local Instructors/Maintainers. Bug BBQ and/or sprints are excellent ways to develop lessons further with community members.  The Curriculum Advisory Committee is an excellent resource for determining whether a lesson is ready for an 'alpha' status or higher.

## Context/Goals of the Lessons
Some of the attendees of the Maintainer discussions highlighted the importance of including additional context in the lessons, to help learners understand where the lesson fits within their own work and how they can benefit from it. Maintainers can address this by looking at (additional) library uses cases and data that can be included in the lessons. Lesson Maintainers can also think about how their lesson ties in with the other lessons and share this feedback with the Curriculum Advisory Committee.

## Maintainer Leads
A number of Maintainers that had been randomly assigned this role asked what it entails. First, check the [lesson page](https://librarycarpentry.org/lessons/) to see if you have an asterisk * next to your name indicating that you are a lead. If you are a lead, this only means that your sole responsibility is that you ensure that the group meets at least once via a video call. The reason for this is that some of the lessons may need substantial changes and it seemed necessary to have at least one virtual meeting in those cases. Otherwise, Maintainer groups may have one or two members that are more active and ultimately become the de facto lead(s). If this is the case, we can update the website if necessary.

## Instructor Notes
Some Maintainers expressed that the lessons are more like guides, that every instructor brings with them their own perspectives on the lessons. What we haven't necessarily done well as a community is share our perspectives with each other and ultimately take advantage of these perspectives to further develop and refine the lessons. Individual lesson Maintainer groups can collect lesson notes/outlines from instructors, for instance, in a folder called 'instructor_notes' and/or they can also create issues to gather feedback from instructors.

## Surveys
Maintainers wanted to know more about what we have learned from the surveys we have conducted so far, pre and post workshop surveys. For Library Carpentry, a great deal of pre workshop survey data has been collected but less has been collected post workshops. Maintainers expressed interest in learning from survey data though. Maintainers also discussed not being able to see and learn from the data in time before workshops.

## Giving Credit
Library Carpentry lessons have not been formally published via Zenodo (like other Carpentries lessons). This takes advantage of the [GitHub-Zenodo release functionality](https://guides.github.com/activities/citable-code/). Reasons for publishing the lessons include giving credit to contributors and preserving the lessons. With many of the lessons moving to stable (some are already), we will be working with Francois Michonneau (Curriculum Development Lead, Carpentries) in 2019 to publish many of the Library Carpentry lessons.

## Miscellaneous
* Maintainers can contribute to other lessons but be mindful of the current work by lesson Maintainers.
* Forking lessons for local purposes is of course fine but try to contribute back to the shared lessons.
* Work off of the main branch, on a separate branch.
* Create issues/pull requests that are in smaller more manageable chunks.

## Carpentries Resources Mentioned

1. [Carpentries Handbook - Maintainers](https://docs.carpentries.org/topic_folders/maintainers/maintainers.html)
2. [Maintainers Onboarding](https://carpentries.github.io/maintainer-onboarding/index.html)
3. [Curricular aspects of Maintainer Onboarding](https://github.com/LibraryCarpentry/governance/issues/10#issuecomment-453713612)
4. [Library Carpentry Lessons](https://librarycarpentry.org/lessons/) - Lists Maintainers and leads
5. [Library Carpentry Experimental Lessons](https://pad.carpentries.org/lc-experimental-lessons)
6. [Carpentries Handbook - Lesson Development](https://docs.carpentries.org/topic_folders/lesson_development/index.html)


## External Resources Mentioned

1. [Teaching Tech Together](http://teachtogether.tech)
2. GitHub's [Open Source Guides](https://opensource.guide/)
3. [Ten simple rules for collaborative lesson development](https://docs.carpentries.org/topic_folders/lesson_development/index.html)
4. [Making Your Code Citable](https://guides.github.com/activities/citable-code/)
