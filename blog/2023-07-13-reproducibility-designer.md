---
author: Antonin Delpeuch
title: "Designer seeked for OpenRefine's reproducibility improvements"
---

OpenRefine is hiring a designer to help shape our improvements to OpenRefine's operation history and test those changes with user panels.
<!--truncate-->

[OpenRefine](https://openrefine.org/) is a power tool for working with messy data, popular in a diverse range of communities. It has been serving the needs of journalists, librarians, Wikipedians, scientists for more than 13 years and is taught in many curricula and workshops around the world. OpenRefine is a fiscally sponsored project of [Code for Science & Society Inc](https://codeforscience.org/), a 501(c)(3) charitable organization in the USA.

We are currently working on improving the reproducibility of OpenRefine workflows as part of [a project funded by the Essential Open Source Software for Science programme](https://chanzuckerberg.com/eoss/proposals/improving-openrefines-reproducibility/).
This consists in improving the user experience around OpenRefine's operation history, which tracks all transformations applied on the original data. This work aims to address a range of long standing issues, such as:
- limitations of the Undo/Redo functionality, such as the lack of ability to undo an operation in the middle of the history list ([#183](https://github.com/OpenRefine/OpenRefine/issues/183)) or unintentional loss of work after using the undo feature and
  applying a new operation ([#369](https://github.com/OpenRefine/OpenRefine/issues/369), [#3184](https://github.com/OpenRefine/OpenRefine/issues/3184))
- the difficulty in reusing and sharing OpenRefine workflows, due to the lack of error handling when applying series of operations and the difficulty to adapt a workflow to a new project (for instance, with different column names)
- the lack of support for running OpenRefine workflows as a part of larger pipelines, without using the web UI interactively. This covers, for instance, the lack of import metadata in the JSON export of the history
  ([#460](https://github.com/OpenRefine/OpenRefine/issues/460)).

See the corresponding [GitHub project](https://github.com/orgs/OpenRefine/projects/6) for more issues in the scope of this project.

We are looking for a part-time designer who will
* design changes to the user interface to support those improvements;
* validate those choices by conducting user testing sessions;
* help prioritize follow-up improvements based on user feedback.

Requirements: 
* Experience with designing and testing software
* Ability to work in a fully remote environment
* Good communication skills and fluency in English

Nice to have:
* Familiarity with OpenRefine
* Experience with open source development practices and tools (such as the use of GitHub Issues)

**TODO compensation details**
This role is available immediately and is initially expected to span the remaining duration of this project around reproducibility (1.5 year). We hope to be able to extend this role to work on other areas of the tool as other opportunities arise.

We invite applicants to send their CV and a short motivation statement at **TODO application email address**. Applications will be reviewed on a rolling basis starting on July 30th until the position is filled.

*OpenRefine is fiscally sponsored by Code for Science and Society (CS&S). CS&S is an equal opportunity employer committed to hiring a diverse workforce at all levels of the organization thereby creating a culture that allows us to better serve our clientele, our employees and our communities. We value and encourage the contributions of our colleagues and strive to create an environment where everyone can reach their full potential and drive outstanding results. All qualified applicants will receive consideration for employment without regard to race, national origin, age, sex, religion, disability, sexual orientation, marital status, veteran status, gender identity or expression, or any other basis protected by local, state, or federal law. This policy applies with regard to all aspects of one's employment, including hiring, transfer, promotion, compensation, eligibility for benefits, and termination.*
