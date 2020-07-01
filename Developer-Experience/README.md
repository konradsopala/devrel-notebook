<div align="center">
<br>
<img src="DeveloperExperienceLogo.png"
/>
<br/>
<h1>Developer Experience</h1>
</div>
<br/>
<p align="center">
<a href="https://github.com/DevrelSpace/Devrel-Notebook/tree/master/Developer-Community"><img src="https://img.shields.io/badge/Developer-Community-brightgreen" alt=""/></a>     <a href="https://github.com/DevrelSpace/Devrel-Notebook/tree/master/Developer-Experience"><img src="https://img.shields.io/badge/Developer-Experience-brightgreen" alt=""/></a>   <a href="https://github.com/DevrelSpace/Devrel-Notebook/tree/master/Developer-Evangelism"><img src="https://img.shields.io/badge/Developer-Evangelism-brightgreen" alt=""/></a> <a href="https://github.com/DevrelSpace/Devrel-Notebook/tree/master/Developer-Advocacy"><img src="https://img.shields.io/badge/Developer%20-Advocacy-brightgreen" alt=""/></a> <a href="https://github.com/DevrelSpace/Devrel-Notebook/tree/master/Devrel-Management"><img src="https://img.shields.io/badge/Devrel-Management-brightgreen" alt=""/></a>
</p>

One of the chief concerns in software design and development is to create an intuitive developer experience. However, developers often forget that they actually have two sets of users to consider: the end-user consuming the product, and the other developers using and working on the code itself. Developers know how stuff works. Developer experience has evolved so much through the years that now it can take up to even half a day to setup dev environment while some time ago you opened notepad and you started working. Before you start diving into this document, I want to leave you with one thought:

**You can't assume that developers know what they want to do!**

## Table of Contents

* [Intro](#intro) <br>
* [DeveloperJourney](#developerJourney) <br>
* [DevexPrinciples](#devexPrinciples) <br>
* [API](#api) <br>
* [Docs](#docs) <br>
* [OpenSource](#openSource) <br>
* [Notes](#notes) <br>

### Intro

Working as a Developer Experience Designer / Engineers or leading such people, there are a few key elements and concepts worth remembering. The core thing is using software engineering the way that allows you to **onboard and keep developers happy** while they implement something using your stack. When they use your APIs / SDKs / frameworks and tools, they need to see via different methods that you **put effort in developing those tools**. That will show them **engagement, energy and empathy** you put into that tooling. It's always nice to code something that will **bring your developers** some kind of **surprise**! This way you'll be able to both acquire them and also activate their powers by using your tools.

### DeveloperJourney

Another thing worth diving in is developer journey. A developer journey is the route between a developer with no knowledge of a technology and the same developer that feels confident to use it in production and actively share the expertise acquired.

**Developer Journey Stages**

* Exploration (Connect): **Do I want to use it?**
* Getting started (Engage): **How do I sign up and get started?**
* Guidance (Adopt): **How do I use it?**
* Reference (Advocate) **How do I get help?**

**Developers right now spend too much time on the tooling and workflows compared to the time they spend on software development**

### DevexPrinciples

**Information Architecture**

You should always be thinking as a Developer Experience Engineer about information architecture. Whether it's a design of your API, SDK, repo or API documentation. It should be easy to navigate and intuitive to follow. Always think who you're designing for to make the entry level appropriate. No matter how great your SDK is if you don't have proper information architecture in place, developers won't use it.

Another important thing in that field is information sharing. To be more specific - updates sharing.

Types of changes important for notifying developers:

* New big product launches (**the least important**)
* Additional features & updates (**medium important**)
* Deprecations (**most important**)

Always ask yourself those questions about changes:

* How many users does this impact?
* Will this require them to do additional work?
* Will this break anything?

**Core DX Principles**

Here are some core principles of great developer experience:

* SDKs for many languages
* Dynamic and personalised docs
* Useful design and error codes and messages
* Reliability, transparency and support
* Backwards compatible API updates
* Aligned incentives with developers
* Quality of assets and processes available to developers

### API

![](/Developer-Experience/Assets/APIPhilosophy.png)

The core principle here is to design the API so that it allows programmers to use it in the following way:

* Use **correctly**
  * Use **efficiently**
    * Use **pleasantly**

One of the concepts worth understanding and having in mind when designing APIs with proper Developer Experience is:

**3:30:3 rule**

* 3 seconds to understand the purpose of the API
* 30 seconds to identify the entry point
* 3 minutes to create an account and call the system

APIs are primary interfaces your developers interact with so treat their design as a function. Remember that first impressions stick and your design amplifies your message. On the other hand you should be aware of bad practices too:

* Poor documentation
* Inadequate support
* Assume if you build it they will come
* Poor developer experience
* Unexpected & undocumented releases
* Security complexity
* Exposing your raw underlying data model
* REST APIs that ignore HTTP rules
* Poor error handling (error messages should be humble, human and helpful)

You won't remember about each of those for sure, that's why Developer Betas are a powerful tool for building trust.

### Docs

Documentation sets the tone for your product's Developer Experience. There are a few documentation types that can be mentioned:

* Overview and value proposition
* First-use example
* Tutorials and examples
* Conceptual documentation
* Reference documentation
* Other informal documentation

In order to make those as useful as possible it's important to remember about Docs Navigation that can include following elements:

* Group topics in product sidebars
* Navigate from doc se to doc set
* Allow navigation within content
* Make popular topics easy to access
* Reduce information fragmentation

This way docs would be both **precursory** and **participatory** and its content will be up to date, exemplary and consistent. Also check out those general tips regarding designing docs:

* Show people path to expertise instead of making them experts
* Documentation is a part of the product, not a byproduct of the code
* Good documentation system will make it easy to pivot (internal)

**Begin documenting before you even begin developing**

### OpenSource

Sooner or later taking care of developer experience at your company you'll either need to check out trends in Open Source or even develop something OSS within your company. Here are some key therms in the field:

* **Author**: The person/s or organisation that created the project
* **Owner**: The person/s who has administrative ownership over the organisation or repository (not always the same as the original author)
* **Maintainers**: Contributors who are responsible for driving the vision and managing the organisational aspects of the project. They may also be authors or owners of the project
* **Contributors**: Everyone who has contributed something back to the project.
* **Community Members**: People who use the project. They might be active in conversations or express their opinion on the project’s direction.
* **OSPO - Open Source Programs Office**: Establishes policies, process, tools and culture change around open source engagement. Someone or a team who are advocating for open source.

When it comes to open source projects, documentation is hugely important. No matter which stage you decide to open source your project, every project should include the following documentation:

* **LICENSE**: By definition, every open source project must have an open source license. If the project does not have a license, it is not open source.
* **README**: The README is the instruction manual that welcomes new community members to the project. It explains why the project is useful and how to get started.
* **CONTRIBUTING**: Whereas READMEs help people use the project, contributing docs help people contribute to the project. It explains what types of contributions are needed and how the process works. While not every project has a CONTRIBUTING file, its presence signals that this is a welcoming project to contribute to.
* **CODE_OF_CONDUCT**: The code of conduct sets ground rules for participants’ behavior associated and helps to facilitate a friendly, welcoming environment. While not every project has a CODE_OF_CONDUCT file, its presence signals that this is a welcoming project to contribute to.
* **Other documentation**: There might be additional documentation, such as tutorials, walkthroughs, or governance policies, especially on bigger projects.

**Other important thing in OSS Development is motivation.** Extrinsic motivators are great at getting people first exposure, but not for creating long term OSS contributors. The best way you can incentivise long term contributions is through providing either valuable learning opportunities, or career opportunities. Here are some OSS Motivations:

* Improving coding skills
* Being a part of community
* Learning new technologies
* Advancing careers
* Advancing software freedom
* Developing new products
* Improving technologies required for job

Knowing all this you'll want to be a good OSS Developer Experience engineer for sure, right? That's why you need to make the community that will be using your tools very welcoming:

* Make it easy for someone to use your project
* Clearly explain how to contribute
* When someone new lands on your project, thank them for their interest!
* Be responsive
* Be open-minded about the types of contributions you’ll accept
* Treat your README as a constitution

Having those tips in mind will allow you to get rid of or even prevent some common OSS blockers and problems like:

* It seems difficult to get started / I don't know where to start
* I feel like I don't have the right skills to contribute
* My company doesn't give me time to contribute
* I am too intimidated to contribute
* Lack of resources
* Lack of interest
* Unresponsiveness
* Dismissive responses
* Unexplained rejection
* Unwelcoming language or content

**Open Source Strategy**

Creating and documenting an open source strategy is an essential first step to realising ROI with open source. Crafting a strategy document will help your team understand the business objectives behind your open-source program.

* Start with the end goal first and then explain how to get there
* Explain your company's approach to open-source and the purpose behind the document.
* Specify how you want developers to consume open source code
* Specify how you want developers to contribute to open source projects and identify projects that are critical to your business strategy

**Company Open Source Pipeline**

Let's assume you have something built and you want to open source it. Here's an example pipeline:

* **Legal Review**
  * Consider the impact of open sourcing on your company’s intellectual property
  * Ensure full compliance with open source licenses
  * Select an open source license for the source code to be released, document all licensing requirements very clearly in your project
  * Decide if you need a contributor agreement
  * Consider the possible non-software outputs from the community and the appropriate licenses, such as documentation and specifications
  * Decide on any trademark related considerations
  * Decide whether there are additional factors to build into your plans for an ecosystem, such as conformance testing

* **Technical Review**
  * Remove critical dependencies on non-public components
  * Provide documentation and use case examples
  * Remove internal comments, references to other internal code, etc.
  * Ensure coding style is consistent
  * Update copyright notices in source code files
  * Add license notice in source code file
  * Add license text as a file in the root directory

* **Governance and Processes**
  * Define project governance steps and structure
  * Set up a code repository, bug reporting, and code testing infrastructure
  * Create supporting Slack channels, forums, and Wikis
  * Create open lines of communication with contributors for project success

* **Branding and Marketing**
  * Set marketing strategy to promote an active contributor community
  * Design project logo, color scheme, website, collateral, etc.
  * Formalize branding guidelines
  * Register social media accounts for the project (Twitter, Facebook, LinkedIn, etc.)
  * Register domain names for the project

* **Launch and Maintain**
  * Open project and begin development work and contributions process
  * Designate a community manager or community advocate
  * Ensure any changes to direction or governance are clearly communicated
  * Follow best practices of other similar communities
  * Encourage and provide opportunities for face-to-face community building

* **End Project**
  * Whatever you do to end or transfer an open source project, perhaps the most important move you can make is to be candid with users at every step. Being open about your intentions helps establish trust for future work with all potential developer communities.
  * It’s important to always remember that just because your company doesn’t care about the code anymore it  doesn’t mean that the existing community doesn’t care.
  * If your enterprise transfers the project to another group, the users should be kept up to date on what is being done to protect their interests as well.
  * Be sure to openly advise developers and community members about the status of the project with its new operators and give them clear details about how the project is now being maintained if they care to continue to use it.
  * Don’t forget to update your project website, social media channels, and other connected community assets so participants know where to find the moved project and can continue to make their contributions and use the code.
  * Remember to communicate all this information to downstream organizations and users as well. This includes companies, non-profits, and others that are using your code, and who may not be aware of the demise or transfer of the project because they’re not directly involved in the development cycle. You should make efforts to advise them of what is happening through your websites, social media channels, and other outlets, especially if the project is well-known and has had a substantial following.

**Some loose OSS Notes**

* When something is cheaper, more people buy it. That’s why open-source companies have such massive and rapid adoption when they achieve product-market fit.
* Open source is the default when choosing software
* Many organizations are getting involved in open source with the express purpose of attracting developers
* No contribution is too big or too small

### Notes

* Most of the users uninstall the app if they notice freeze, crash or an error
* Developers tend to stick to using IDEs rather than lightweight desktop editors
* Developers spend almost 50% of their time on legacy code
* Great experience lead to great engagement
* Developer experience has become more complex since developers are using tools to do multiple things rather than a single thing
* We should always be optimising for developer joy
* Help users get started quickly
* A good developer experience is making it so a developer will succeed with intuitive decisions rather than informed decisions
* Basically everyone, but developers especially, hates the feeling that they are being sold something
* C-level people at companies now worry about access to developers more than they worry about access to capital
* It's a huge priority for upper management to increase the productivity of its developers
* Think of developer experience as a buying process funnel (check till which step your developers succeed)
* A developer can get really involved with a project, the rewards being seeing their changes applied, and their name listed in the change log history
* Do not tell people that something with your stack is not advisable, provide preventic solutions and error handling
* You cannot provide your developers with parts of the solution (developer mindset - they want to know all)
* Developer won't use tools that they don't trust
