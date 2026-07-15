# Library Carpentry Governance Committee

### Meeting minutes: 2026-07-15

Attending: Nathaniel Porter, Cody Hennesy, Tim Dennis, Nicky Garland, Eka Grguric

## Agenda

### GenAI Carpentries and instructor training

* Cody reported back on recent Generative AI Carpentries discussions.
* Discussed the role of generative AI in workshops and possible integration into instructor training.
* Eka is developing a nine-hour training on generative AI assessment for scholarly work at the 2026 FORCE11 Scholarly Communication Institute.
* Eka is also teaching a workshop on Docker and self-hosted n8n.
* UBC Library Research Commons is considering contributions to additional machine-learning workshops covering neural networks, classification and clustering, and regression.

Resources:

* [AI Carpentry Community of Practice guest presentation with Elle O’Brien, University of Michigan](https://youtu.be/Ixpc6wFbAqg), recorded June 18
* [AI Carpentry teaching-discussion Etherpad](https://pad.carpentries.org/aic-teaching-discussions)
* [FSCI 2026](https://force11.org/fsci-2026/)
* [Self-hosting n8n](https://docs.n8n.io/deploy/host-n8n)
* [Neural Networks](https://ubc-library-rc.github.io/ml-neural-networks/)
* [Classification and Clustering](https://ubc-library-rc.github.io/ml-classification-clustering/)
* [Regression](https://ubc-library-rc.github.io/ml-regression/)

### LC Pathways follow-up

* User-testing appointments are scheduled for July 24–31.
* Recruitment through the IASSIST email list generated a strong response.
* The team still needs to finalize responsibility for each part of the testing process.

Action items:

* Cody: email the Pathways team to confirm roles and responsibilities for the testing sessions.

### Wikidata lesson update and release

* The Wikidata lesson blog post is ready, but publication is waiting on the related Library Carpentry website pull request.
* Nicky asked whether the Carpentries lesson-release process updates the lesson citation and version information.
* A `CITATION.cff` file can be maintained independently of Zenodo. When present, GitHub displays a citation option in the repository sidebar.
* The current Wikidata update would be an appropriate opportunity to create an official 1.0 release.

Resources:

* [Library Carpentry website pull request #86](https://github.com/LibraryCarpentry/librarycarpentry.org/pull/86)
* [Carpentries lesson-release documentation](https://docs.carpentries.org/resources/curriculum/lesson-release.html)
* [Library Carpentry lesson-adoption policy](https://github.com/LibraryCarpentry/curriculum-advisors/blob/main/policy/lesson-adoption.md)

Action items:

* Nicky: contact Toby to ask that the website pull request be reviewed and moved forward.
* Lesson maintainers: consider completing a formal 1.0 release alongside the Wikidata update.

### Open Science lessons blog post

* The Open Science lessons blog post is also ready.
* Publication was delayed so the post can include the July 15 UCSB workshop on containers.

Resource:

* [UCSB Containers Workshop](https://carpentry.library.ucsb.edu/workshop/2026/07/15/ucsb-containers/)

### Archiving outdated lesson repositories

* Discussed a process for archiving lessons that are no longer maintained, using `library-python` as a possible example.
* An archived repository should include clear documentation in its README and may be renamed using an `-archive` suffix.
* The Carpentries archived website repository provides one possible model.
* LCGC members may need additional GitHub team permissions to manage lesson repositories.
* The Library Carpentry Governance Group has previously agreed to help maintainers manage their lessons on GitHub.

Resources:

* [Library Carpentry Python repository](https://github.com/LibraryCarpentry/library-python)
* [Carpentries archived website repository](https://github.com/carpentries/carpentries.org-archive)
* [Library Carpentry GitHub teams](https://github.com/orgs/LibraryCarpentry/teams)

Action items:

* Cody: test and document the process for updating or archiving the Python lesson repository.
* LCGC: ask Maneesha whether contributors and LCGC members can be added to the appropriate GitHub teams for Library Carpentry repositories.

### Python and R lesson Lab reviews

* The group discussed moving the Library Carpentry Python lesson into the Carpentries Lab review process.
* One reviewer has volunteered, but one or two additional reviewers are needed.
* Nicky is willing to serve as the review editor.
* After the Python review is underway, the group may consider submitting the R lesson for Lab review.

Action items:

* Cody: schedule a meeting with Nicky to begin planning the Python lesson review.
* LCGC: identify one or two additional reviewers for the Python lesson.
* Nicky and Tim: consider whether to advance the R lesson through the Lab after the Python review.

### MarcEdit lesson

* Discussed the request to approve the MarcEdit lesson as Stable.
* The LCGC agreed to approve the lesson for Stable status.

Resource:

* [MarcEdit Lab review discussion](https://github.com/carpentries-lab/reviews/issues/33#issuecomment-4810298695)

### Future topics

* Establishing an annual review process for Library Carpentry lessons.
* Reconsidering whether Carpentries Lab review should be required before a lesson can receive Stable status.
* The group can encourage Lab review by communicating its benefits, including editorial feedback, lesson improvement, and formal credit, while potentially keeping it optional.
* Requiring Lab review may create too much work for lesson maintainers and additional capacity demands for the LCGC’s role in the editorial process.
* Even if Lab review remains optional, the group should consider systematically reviewing and updating Library Carpentry’s core lessons.

Action items:

* Add the Lab requirement and Stable-status policy to the next meeting agenda.
* Discuss whether to develop a prioritized sequence for reviewing Library Carpentry’s core lessons.
* Revisit the possibility of an annual lesson-review process.
