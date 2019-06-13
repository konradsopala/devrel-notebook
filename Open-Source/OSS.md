# OSS

**Two-way trust is required for open source to be successful. The vendor puts its trust in the community and vice versa. And when that trust fails, open source fails. This is when forks happen.
**

![](/Open-Source/Assets/OSSProjectsMatter.png)

## Table of contents

* [GoldThoughts](#goldthoughts) <br>
* [HealthMetrics](#healthmetrics) <br>
* [Members](#members) <br>
* [Motivation](#motivation) <br>
* [Hacktoberfest](#hacktoberfest) <br>
* [WelcomingCommunity](#welcomingcommunity) <br>
* [OSSMotivtions](#ossmotivations) <br>
* [OSSBlocks](#ossblocks) <br>
* [Documentation](#documentation) <br>
* [OSSProblems](#ossproblems) <br>
* [Strategy](#strategy) <br>
* [ProjectTransition](#projecttransition) <br>
* [ProjectChecklist](#projectchecklist) <br>
* [Engagements](#engagements) <br>
* [Notes](#notes) <br>

### GoldThoughts
* Remember that the number itself isn’t the goal — it’s the process of tracking them over time and finding patterns in the data that can inform project and process improvements.
* “If you have more than 100 code repositories or 100 people that you’re trying to manage, you really can’t have someone doing it manually with spreadsheets anymore. Obviously, people still do it that way. But it starts to become ad hoc and laborious. That’s where tools come into play. They allow you to scale.” 
* “At the end of the day, you need tools to automate your life, otherwise you’re going to waste a lot of time doing things manually.” 

### HealthMetrics

* **Contributor-Breadth**:  the ratio of non-core committers to core committers. This metric indicates how open a community is to contributions from outside
* **Contributor-Demographics**:  gender, age, location, education, and skills over time
* **Contributors**: number of contributors
* **Issue-Response-Rate**: time between a new issue is opened and a maintainer responds
* **Followers**: number of followers
* **Forks**: number of forks
* **Bus-Factor**: the minimum number of developers performing 50% of commits
* **Closed-issues**: number of close issues
* **Code-Commits**: number of code commits
* **Transparency**: number of comments per issue
* **Watchers**: number of watchers
* **Issue-Resolution-Efficiency**: number of closed issues / number of abandoned issue
* **Issues-Submitted-Closed**: issues submitted vs issues closed
* **Code-Merge-Duration**: what's the duration of time between code merge request and code commit
* **CommunityActivity**: frequency of contributions
* **IssueComments**: number of comments per issue
* **NewContributors**: number of new contributors over time
* **OpenIssueAge**: age of an open issue
* **OpenIssues**: number of open issues
* **PRsComments**: number of comments per pull request
* **PRsMadeClosed**: pull request made vs pull requests closed
* **PRsOpen**: number of opened pull requests
* **PRsOverTime**: how many pull requests have been submitted over time
* **NewContributorsMaintainers**: ratio of new contributors to maintainers

### Members

  - **Author**: The person/s or organization that created the project
  - **Owner**: The person/s who has administrative ownership over the organization or repository (not always the same as the original author)
  - **Maintainers**: Contributors who are responsible for driving the vision and managing the organizational aspects of the project. (They may also be authors or owners of the project.)
  - **Contributors**: Everyone who has contributed something back to the project.
  - **Community Members**: People who use the project. They might be active in conversations or express their opinion on the project’s direction.
  
### Motivation

- Extrinsic motivators are great at getting people first exposure, but not for creating long term OSS contributors
- The best way you can incentivise long term contributions is through providing either valuable learning opportunities, or career opportunities

### Hacktoberfest

- Hacktoberfest is not good for long-term OS contribution but is good for raising awareness

**Hacktoberfest Lessons Learnt**


* **Initative coordination**:
  * One person solely responsible for: 
    * Regular communication internally( E-Mail, Confluence, Slack)
    * Regular communication externally (Twitter, Mail, Developer Forum)
    * Designing contributor form
    * Extracting data from the form
    * Creating a final report
    * Writing summary blog post internally and externally
    * Co-ordinating PRs status matrix
    * Sending SWAG


* **GitHub Labelling**
  * "Hacktoberfest PR" labels added to PRs contributed in Hacktoberfest - better navigation and tracking both internally and externally
  * "Hacktoberfest" approved GitHub label

* **PRs Reviewing**
  * X amount of planned time a week for certain team to review their repos Hacktoberfest PRs


* **Nice to have**
  * Repo with Community Repos Hacktoberfest Leaders
  * Acceptance criteria
  * Are must: eg. 1 small and 4 medium PRs

* **Mailing**
  * Some easy to use and automated tool like MailChimp (better tracking and easier outreach) instead of manual emails

* **Any Excel related data storing / analysis**
  * Excel formulas instead of manual values (data then is simply reliable and valuable and we won't mislead ourselves and contributors)
  
### WelcomingCommunity

- Make it easy for someone to use your project
- Clearly explain how to contribute
- When someone new lands on your project, thank them for their interest!
- Be responsive
- Be open-minded about the types of contributions you’ll accept
- Treat your README as a constitution

### OSSMotivtions

* Improving coding skills
* Being a part of community
* Learning new technologies
* Advancing careers
* Advancing software freedom
* Developing new products
* Improving technologies required for job

### OSSBlocks

* It seems difficult to get started / I don't know where to start
* I feel like I don't have the right skills to contribute
* My company doesn't give me time to contribute
* I am too intimidated to contribute
* Lack of resources
* I already contributed to a significant amount of open source
* Lack of interest

### Documentation

- No matter which stage you decide to open source your project, every project should include the following documentation:
    - Open source license
    - README
    - Contributing guidelines
    - Code of conduct
    
    - **LICENSE**: By definition, every open source project must have an open source license. If the project does not have a license, it is not open source.
  - **README**: The README is the instruction manual that welcomes new community members to the project. It explains why the project is useful and how to get started.
  - **CONTRIBUTING**: Whereas READMEs help people use the project, contributing docs help people contribute to the project. It explains what types of contributions are needed and how the process works. While not every project has a CONTRIBUTING file, its presence signals that this is a welcoming project to contribute to.
  - **CODE_OF_CONDUCT**: The code of conduct sets ground rules for participants’ behavior associated and helps to facilitate a friendly, welcoming environment. While not every project has a CODE_OF_CONDUCT file, its presence signals that this is a welcoming project to contribute to.
  - **Other documentation**: There might be additional documentation, such as tutorials, walkthroughs, or governance policies, especially on bigger projects.

### OSSProblems

- Problems encountered in open-source:
  - Unresponsiveness
  - Dismissive responses
  - Unexplained rejection
  - Unwelcoming language or content
  
### Strategy

Creating and documenting an open source strategy is an essential first step to realizing ROI with open source. Crafting a strategy document will help your team understand the business objectives behind your open-source program. 

* Start with the end goal first and then explain how to get there
* Explain your company's approach to open-source and the purpose behind the document.
* Specify how you want developers to consume open source code
* Specify how you want developers to contribute to open source projects and identify projects that are critical to your business strategy

### ProjectTransition

* Ending open-source projects:
  * Whatever you do to end or transfer an open source project, perhaps the most important move you can make is to be candid with users at every step. Being open about your intentions helps establish trust for future work with all potential developer communities.
  * It’s important to always remember that just because your company doesn’t care about the code anymore it  doesn’t mean that the existing community doesn’t care.
  * If your enterprise transfers the project to another group, the users should be kept up to date on what is being done to protect their interests as well.
  * Be sure to openly advise developers and community members about the status of the project with its new operators and give them clear details about how the project is now being maintained if they care to continue to use it.
  * Don’t forget to update your project website, social media channels, and other connected community assets so participants know where to find the moved project and can continue to make their contributions and use the code.
  * Remember to communicate all this information to downstream organizations and users as well. This includes companies, non-profits, and others that are using your code, and who may not be aware of the demise or transfer of the project because they’re not directly involved in the development cycle. You should make efforts to advise them of what is happening through your websites, social media channels, and other outlets, especially if the project is well-known and has had a substantial following.
  
### ProjectChecklist

Considerations

* Evaluate possibility of joining an existing open source project
* Evaluate the company’s ability to launch and maintain the project using the open source model
* Evaluate the likelihood that other companies may join the project from the start
* Evaluate success factors and set appropriate metrics for the open source project

**Business strategy & plan**

* Determine and set goals for your project
* ather reasons for doing it from stakeholder
* Select code to be considered for the project
* Decide whether the project will include all code for an application or just parts of it
* Create a business case for the selected proposal
* Determine if there is executive buy-in for the move
* Plan resource commitments for developers and funding
* Set budgets for costs, including development time, infrastructure and related expenses
* Gather executives and tech staff for project discussions and decision-making
* Debate and finalize project scope and code selection

**Legal Review**

* Consider the impact of open sourcing on your company’s intellectual property
* Ensure full compliance with open source licenses
* Select an open source license for the source code to be released, document all licensing requirements very clearly in your project
* Decide if you need a contributor agreement
* Consider the possible non-software outputs from the community and the appropriate licenses, such as documentation and specifications
* Decide on any trademark related considerations
* Decide whether there are additional factors to build into your plans for an ecosystem, such as conformance testing

**Technical Review**

* Remove critical dependencies on non-public components
* Provide documentation and use case examples
* Remove internal comments, references to other internal code, etc.
* Ensure coding style is consistent
* Update copyright notices in source code files
* Add license notice in source code file
* Add license text as a file in the root directory

**Governance and Processes**

* Define project governance steps and structure
* Set up a code repository, bug reporting, and code testing infrastructure
* Create supporting Slack channels, forums, and Wikis
* Create open lines of communication with contributors for project success

**Branding and Marketing**

* Set marketing strategy to promote an active contributor community
* Design project logo, color scheme, website, collateral, etc.
* Formalize branding guidelines
* Register social media accounts for the project (Twitter, Facebook, LinkedIn, etc.)
* Register domain names for the project

**Launch and Maintain**

* Open project and begin development work and contributions process
* Designate a community manager or community advocate
* Ensure any changes to direction or governance are clearly communicated
* Follow best practices of other similar communities
* Encourage and provide opportunities for face-to-face community building

### Engagements

* A developer can get really involved with a project, the rewards being seeing their changes applied, and their name listed in the change log history.

### Notes

- Documentation is highly valued, frequently overlooked, and a means for establishing inclusive and accessible communities.
- Open source is the default when choosing software.
- Don’t spam as many people as possible. Instead, target your efforts to communities that will benefit from knowing about your project
- When something is cheaper, more people buy it. That’s why open-source companies have such massive and rapid adoption when they achieve product-market fit.
- Hiring managers are moving away from hiring outside consultants, increasingly opting to train existing employees on new open source technologies and help them gain certifications.
- Many organizations are getting involved in open source with the express purpose of attracting developers.
- OSS question: how easy is it for outsiders to contribute to your organization projects
