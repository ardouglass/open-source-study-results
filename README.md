# Open Source Study Results

The file [results.csv](results.csv) in this repository contains the coded and anonymized survey results from https://opensource.study. This readme documents the columns and the meaning of the data inside them below.

## Columns

Below is a description of each column name and what the contents of those columns means. Square brackets (`[]`) after the name means the question allowed multiple answers and the results may contain strings separated by spaces indicating multiple choices were made. An asterisk (`*`) after the name means the question was required.

### `communication_change`

*Is there anything you would change about the current project communication methods?*

| Answer Choice   | Meaning                                                                                                 |
| --------------- | ------------------------------------------------------------------------------------------------------- |
| `centralize`    | Communication currently occurs across too many platforms and the project would like to use fewer        |
| `something-tbd` | Communication currently feels out of hand, but no specific methods have been considered to resolve this |

### `communication_methods[]*`

*Through what official means do maintainers, contributors, and users communicate about the project?*

| Answer Choice       | Meaning                                 |
| ------------------- | --------------------------------------- |
| `announcement-list` | Mailing list for announcements          |
| `chat`              | Chat platform                           |
| `discussion-list`   | Mailing list for discussion             |
| `email`             | Email directly to or from maintainers   |
| `forum`             | Forums like Discourse or Stack Exchange |
| `office-hours`      | Regularly held office hours             |
| `social`            | Social media                            |
| `tracker`           | Public bug or issue tracker             |
| `website`           | Project website                         |
| `wiki`              | Project specific wiki                   |

### `communication_topics[]*`

*What topics are communicated via the selected communication methods?*

| Answer Choice           | Meaning                     |
| ----------------------- | --------------------------- |
| `bug-reports`           | Bug reports                 |
| `cve-announcements`     | Vulnerability announcements |
| `docs`                  | Documentation               |
| `feature-requests`      | Feature requests            |
| `funding-requests`      | Funding requests            |
| `labor-requests`        | Requests for labor          |
| `open-finances`         | Project finances            |
| `release-announcements` | Release announcements       |
| `roadmap`               | Project roadmap             |
| `support`               | Help and support            |

### `funding_past_change`

*Why did the funding method change?*

| Answer Choice          | Meaning                                                   |
| ---------------------- | --------------------------------------------------------- |
| `limited-time-funding` | A previous method of funding was for a set period of time |
| `sponsorship-ended`    | A sponsorship deal ended                                  |

### `funding_current[]*`

*How is the project currently funded?*

| Answer Choice                | Meaning                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------------------------ |
| `collective-funding`         | Collective donations from individuals on GitHub Sponsors, Open Collective, Patreon, etc.   |
| `collective-sponsor-funding` | Collective donations from organizations on GitHub Sponsors, Open Collective, Patreon, etc. |
| `gov-grant-funding`          | Government grants                                                                          |
| `internal-funding`           | Directly as an internal project of a legal entity                                          |
| `nonprofit-grant-funding`    | Grants from grantmaking non-profit institutions                                            |
| `revenue-other-funding`      | Generating revenue by selling other things, like project T-shirts and stickers             |
| `revenue-product-funding`    | Revenue-generating products, like a pro version with additional functionality              |
| `revenue-support-funding`    | Revenue-generating activities, like paid support or consulting                             |
| `self-funding`               | Self-funded by core contributor(s)                                                         |
| `sponsor-funding`            | Sponsored directly by a for-profit entity                                                  |

### `funding_current_change`

*Is there anything you would change about the current funding methods?*

| Answer Choice           | Meaning                                            |
| ----------------------- | -------------------------------------------------- |
| `grants-too-little`     | Grants do not provide enough funding for stability |
| `less-feast-or-famine`  | Funding is often available, but inconsistent       |
| `more-from-large-users` | Large users are seen as free-riders                |

### `funding_management*`

*How are funds and expenses managed?*

| Answer Choice   | Meaning                                   |
| --------------- | ----------------------------------------- |
| `monarchy`      | A single person makes all decisions       |
| `oligarchy`     | A handful of people make joint decisions  |
| `participatory` | Collective decision-making by many people |
| `none`          | Not applicable                            |

### `funding_past`

*What other funding has the project used in the past, if any?*

| Answer Choice                | Meaning                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------------------------ |
| `collective-funding`         | Collective donations from individuals on GitHub Sponsors, Open Collective, Patreon, etc.   |
| `collective-sponsor-funding` | Collective donations from organizations on GitHub Sponsors, Open Collective, Patreon, etc. |
| `gov-grant-funding`          | Government grants                                                                          |
| `internal-funding`           | Directly as an internal project of a legal entity                                          |
| `nonprofit-grant-funding`    | Grants from grantmaking non-profit institutions                                            |
| `revenue-other-funding`      | Generating revenue by selling other things, like project T-shirts and stickers             |
| `revenue-product-funding`    | Revenue-generating products, like a pro version with additional functionality              |
| `revenue-support-funding`    | Revenue-generating activities, like paid support or consulting                             |
| `self-funding`               | Self-funded by core contributor(s)                                                         |
| `sponsor-funding`            | Sponsored directly by a for-profit entity                                                  |

### `funding_purposes[]*`

*How are funds currently used?*

| Answer Choice           | Meaning                                                    |
| ----------------------- | ---------------------------------------------------------- |
| `bug-bounties`          | Bug bounties                                               |
| `feature-bounties`      | Feature bounties                                           |
| `full-time-pay`         | Full-time pay for one or more people                       |
| `infrastructure`        | Infrastructure costs                                       |
| `part-time-pay`         | Part-time pay for one or more people                       |
| `professional-services` | Professional services (legal, accounting, marketing, etc.) |
| `none`                  | Not applicable                                             |

### `funding_purposes_change`

*Is there anything you would change about how funds are currently used?*

| Answer Choice       | Meaning                                                                              |
| ------------------- | ------------------------------------------------------------------------------------ |
| `fund-contributors` | Project would like to provide some amount of funding to maintainers and contributors |

### `governance_change`

*Is there anything you would like to change about how the project is currently governed?*

| Answer Choice                     | Meaning                                                 |
| --------------------------------- | ------------------------------------------------------- |
| `add-formal-leadership-structure` | Formalize who maintainers actually are                  |
| `better-documented-process`       | Provide written guidance on how the project is governed |
| `expand-decision-making`          | Allow more people to help in decision making            |
| `introduce-proposals-process`     | Create a formal process for proposing project changes   |

### `governance_contributors*`

*Roughly how many people have contributed labor to the project in the past year?*

| Answer Choice | Meaning                                     |
| ------------- | ------------------------------------------- |
| `1`           | This is a solo project                      |
| `2-10`        | A small group worked on this project        |
| `11-50`       | A medium sized group worked on this project |
| `51+`         | This is a large project                     |

### `governance_contributors_decisions*`

*How many of these contributors participate in project decision-making processes?*

| Answer Choice | Meaning                 |
| ------------- | ----------------------- |
| `some`        | A small portion of them |
| `half`        | About half of them      |
| `most`        | Most of them            |
| `all`         | All of them             |

### `governance_disagreements`

*How are disagreements resolved between contributors, maintainers, and/or other participants in collective decision-making processes?*

| Answer Choice | Meaning                             |
| ------------- | ----------------------------------- |
| `bdfl`        | A specific individual has final say |
| `consensus`   | Consensus must be reached           |
| `committee`   | Committees settle disagreements     |
| `majority`    | Majority rule                       |

### `governance_method*`

*How is the project governed?*

| Answer Choice   | Meaning                                   |
| --------------- | ----------------------------------------- |
| `monarchy`      | A single person makes all decisions       |
| `oligarchy`     | A handful of people make joint decisions  |
| `participatory` | Collective decision-making by many people |

### `governance_new_decision_makers`

*What, if any, is the process for becoming someone who may help make decisions for the project?*

| Answer Choice         | Meaning                                                                        |
| --------------------- | ------------------------------------------------------------------------------ |
| `company-internal`    | Must be hired by the project's backing organization to become a decision maker |
| `election`            | Elected by existing decision makers                                            |
| `fully-participatory` | All contributors and users are already welcome to help make decisions          |
| `invitation`          | Existing decision makers will offer invitations to specific contributors       |
| `not-possible`        | Governance will not be expanded                                                |
| `pay-to-play`         | Sponsors making large enough investments may influence the roadmap             |

### `legal_current*`

*What is the project's current legal status?*

| Answer Choice               | Meaning                                                                     |
| --------------------------- | --------------------------------------------------------------------------- |
| `collective`                | Project assets owned by various core contributors                           |
| `corporate-core-project`    | A core project of a for-profit entity, like WordPress                       |
| `corporate-noncore-project` | A non-core project of a for-profit entity, like React                       |
| `education`                 | A university project, like OpenStax                                         |
| `government`                | A government project, like the U.S. Web Design System                       |
| `individual`                | Project assets owned by an individual                                       |
| `nonprofit`                 | Independent nonprofit primarily created for the project                     |
| `nonprofit-nontech-project` | Project of an otherwise non-technology focused nonprofit                    |
| `nonprofit-subsidiary`      | Governed under a larger nonprofit, like projects under the Linux Foundation |

### `legal_current_change`

*Is there anything you would like to change about the current legal status of the project?*

| Answer Choice          | Meaning                                                                                                     |
| ---------------------- | ----------------------------------------------------------------------------------------------------------- |
| `become-nonprofit`     | Create an independent nonprofit for the project                                                             |
| `fiscal-or-governance` | Change the legal status to one that provides more funding opportunities and/or better collective governance |
| `transfer-ownership`   | Place maintenance and ownership of any existing infrastructure under a new owner                            |

### `legal_current_reason`

*What decision making process, if any, led to the project taking on its current legal status?*

| Answer Choice         | Meaning                                                             |
| --------------------- | ------------------------------------------------------------------- |
| `ecosystem`           | Similar and related projects are structured this way                |
| `funding-requirement` | Required to achieve a specific type of funding                      |
| `historical`          | The project or maintainers have always used their current structure |
| `values`              | Decision makers wanted to align the legal status with their values  |

### `legal_past`

*What other legal status has the project had in the past, if any?*

| Answer Choice               | Meaning                                                                     |
| --------------------------- | --------------------------------------------------------------------------- |
| `collective`                | Project assets owned by various core contributors                           |
| `corporate-core-project`    | A core project of a for-profit entity, like WordPress                       |
| `corporate-noncore-project` | A non-core project of a for-profit entity, like React                       |
| `education`                 | A university project, like OpenStax                                         |
| `government`                | A government project, like the U.S. Web Design System                       |
| `individual`                | Project assets owned by an individual                                       |
| `nonprofit`                 | Independent nonprofit primarily created for the project                     |
| `nonprofit-nontech-project` | Project of an otherwise non-technology focused nonprofit                    |
| `nonprofit-subsidiary`      | Governed under a larger nonprofit, like projects under the Linux Foundation |

### `legal_past_reason`

*Why did the legal status change?*

| Answer Choice          | Meaning                                                             |
| ---------------------- | ------------------------------------------------------------------- |
| `for-fundraising`      | Changing the legal status allowed for new fundraising opportunities |
| `transfered-ownership` | Ownership of project assets and infrastructure changed              |

### `licenses_current_change`

*Is there anything you would like to change about the current license of the project?*

| Answer Choice    | Meaning                                                                  |
| ---------------- | ------------------------------------------------------------------------ |
| `anti-corporate` | Use a license less friendly to businesses                                |
| `better-fit`     | Find a license that is more appropriate for the project's goals          |
| `dual-license`   | Offer the code under multiple licenses depending on the type of end user |
| `forced-pay`     | Adopt a license that requires heavier users to pay for use               |
| `no-evil`        | Use something that restricts use on values, like the Hippocratic License |

### `licenses_current_reason`

*What decision making process, if any, led to the project taking on its current license?*

| Answer Choice          | Meaning                                                     |
| ---------------------- | ----------------------------------------------------------- |
| `community-governance` | Community decision by similar or interrelated projects      |
| `fiscal`               | Financially driven decision                                 |
| `formal-governance`    | Formal decision by maintainers and contributors             |
| `hobby`                | The license choice needed to be friendly to a hobby project |

### `licenses_current[]*`

*What software license does the project currently use?*

The values in this column are all lowercase versions of [SPDX license identifiers](https://spdx.org/licenses/).

### `licenses_enforcement[]*`

*How is the license enforced?*

| Answer Choice           | Meaning                                |
| ----------------------- | -------------------------------------- |
| `contributor-licensing` | Licensing agreements with contributors |
| `litigation`            | Litigation                             |
| `user-licensing`        | Licensing agreements with users        |
| `voluntary`             | Voluntary                              |

### `licenses_past_change_reason`

*Why is this license no longer used?*

| Answer Choice      | Meaning                                      |
| ------------------ | -------------------------------------------- |
| `funding`          | Funding was easier under a different license |
| `less-restrictive` | A less restrictive license was desired       |
| `more-restrictive` | A more restrictive license was desired       |

### `licenses_past[]`

*What other licenses has the project used in the past, if any?*

The values in this column are all lowercase versions of [SPDX license identifiers](https://spdx.org/licenses/).

### `project_age*`

*About how long has the project been active, in years?*

The values in this column are an integer number of years with a minimum of 1.

### `project_type*`

*How would you categorize the project’s intended users?*

| Answer Choice | Meaning             |
| ------------- | ------------------- |
| `P`           | End-users           |
| `L`           | Software developers |
| `PL`          | Both                |
