# Sprint Develoment Cycle

## Goal
To provide some predictability about what and when features/bugs will be worked on a released.

## Schedule
* Duration: 2 Weeks   Thursday -> Wed
* Testing Time: 2~3 Days.
* Start: Thursday
 * Product Owners deliver their top 5 stories for estimation.
 * Planning / Estimation Session ~ 4 hours
 * Product Owners are allocated a given % of Points per sprint and selected estimated stories up to their %.
 * Development Begins:
  *  Develop -> Code Review -> Test -> Deliver.
* Finish up any un-tested stories.
* End: 2nd Wednesday. Deploy to Production.

## Terminology
* **Story**: A feature or bug or task that requires work to be done.
* **Points**: Level of effort required to complete story.
* **Customer**: The person's using the product.
* **Product Owner**: The person in charge of prioritizing and defining stories.
* **Project Manager**: The person in charge of negotiating & managing the delivery of stories.
* **Developers**: The person's working on stories.

## Points
### General Rules
* No story point should ever value more than half the sprints dev time. 
* Ex: 2 weeks = 10 days which includes 2 days testing, thus 8 days of dev  /2 = 4 days max per story.
* Points are great, but ultimately we want to be deliver high quality features that increase revenue, so lets not get to caught up on the estimate, but focus on the quality of the product. 
 
### Values  (fibonacci because when the #'s get big so do the unknowns)
* 0 ~ 10 Minutes or less, simple changes that just need to be done.
* 1 ~ 1/2 Day.
* 2 ~ 1 Day.
* 3 ~ 2 Day.
* 5 ~ 3-4 Days.
* >5 Any thing longer than this we need to break down.

### Planning Meeting Goals
* Estimate stories.
* Add important details.
* Agree to acceptance tests and note in sub tasks.
* Tag w/ testing method [test-manual, test-unit, test-integration]
 
### Story LifeCycle
* Unstarted: Not started yet.
* Started: In development.
* Finished: Ready for Code Review & Testing. On Develop.
* Delivered: On staging and ready for acceptance.
* Rejected: Failed tests or not accepted by Product Owner, refer to story/tags.
* Accepted: On staging and accepted ready for release.

### Q&A
* Q: What happens w/ unstarted or unfinished stories # of Testing days away from end of sprint?
 * A: Stop working on them and test what is finished. _Deliver what you have, don't delay what you don't_.
