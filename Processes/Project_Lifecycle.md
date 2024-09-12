 # Post-Quantum Cryptography Alliance Project Lifecycle Policy

## I. Overview
This governance policy describes how an open source project (a “Technical Project”) can formally join the Post-Quantum Cryptography Alliance via the Project Proposal Process. It describes the Stages a project may be admitted under, the criteria and expectations for a given stage, and the acceptance criteria for a project to move from one stage to another. It also describes the Annual Review Process through which those changes will be evaluated and made. 

Project progression — movement from one stage to another — allows projects to participate at the most appropriate level for them, given their lifecycle stage. Regardless of stage, all Post-Quantum Cryptography Alliance projects benefit from a deepened alignment with existing projects and access to mentorship, support, and foundation resources.

Capitalized terms not otherwise defined in this Project Lifecycle Policy have the meanings ascribed to them in the Funding Charter of the Post-Quantum Cryptography Alliance.

## II. Project Proposal Process

### Introduction
This governance policy sets forth the proposal process for projects to be accepted into the Post-Quantum Cryptography Alliance. The process is the same for both existing projects seeking to move into the Post-Quantum Cryptography Alliance and new projects to be formed within the Post-Quantum Cryptography Alliance.

### Project Proposal Requirements
Projects must be formally proposed via GitHub. Project proposals submitted to the Post-Quantum Cryptography Alliance should provide the following information to the best of their ability:

* name of the project
* project description (what it does, why it is valuable, origin and history)
* statement on alignment with the Post-Quantum Cryptography Alliance mission
* link to *current* Code of Conduct (if one is adopted already)
* sponsor(s) from the TAC, if identified (a sponsor helps mentor projects)
* project license 
* source control (GitHub by default)
* issue tracker (GitHub by default)
* external dependencies (including licenses)
* release methodology and mechanics
* names of initial committers, if different from those submitting the proposal
* briefly describe the project's leadership team and decision-making process
* link to any documented maintainers or code owners
* link to any documented governance practices
* preferred maturity level (see stages below)
* list of the project's official communication channels (Slack, IRC, mailing lists)
* link to project's website 
* links to social media accounts
* existing financial sponsorship
* infrastructure needs or requests 

Based on the above information, PQCA staff will prepare a technical charter and trademark contribution agreement for the proposed project.

### Project Acceptance Process
* Projects are required to present their proposal at a TAC meeting
* The TAC may request changes to align the project better with the Post-Quantum Cryptography Alliance (e.g., adding a governance document to a repository or adopting a Code of Conduct).The project will need to make these changes to progress further.
* Projects are accepted via a two-thirds supermajority vote of the TAC.
* Satisfaction of the project's initial stage requirements. The TAC will determine the appropriate initial stage. The project can apply for a different stage via the review process. 

## III. Stages - Definitions & Expectations
Every project within the Post-Quantum Cryptography Alliance is classified by a maturity level. It is the responsibility of the project's maintainers to propose an initial maturity level, as well as any subsequent elevations in maturity level. The TAC is responsible for reviewing these proposals and making the final determination. The TAC may downgrade a project's maturity level should the project fail to maintain its established standards.

All projects may attend TAC meetings and contribute work regardless of their stage. 

Projects are divided into “Research Projects” and “Production Projects.” Research projects aim to develop code useful for advancing the science of post-quantum cryptography, while production projects aim to develop secure post-quantum cryptographic code. Neither definition is meant to imply any code quality properties or explicit usage recommendations. Code quality is expected to evolve as a project moves to more mature project levels.

While these tracks are expected to mostly be separate, projects can “switch tracks” with the appropriate TAC approvals (the regular requirements for approval into each stage are still in effect).

### Common Acceptance Criteria
The following set of common acceptance criteria are expected for all project types and stages.
* 2 TAC sponsors to champion the project and provide mentorship as needed
* A presentation at the meeting of the TAC
* Have a charter document with an intellectual property policy that leverages open licenses, including, in the case of contributions of code, the use of one or more licenses approved as “open” by the Open Source Initiative. The staff of the Post-Quantum Cryptography Alliance will assist projects in preparing a technical charter following the Post-Quantum Cryptography Alliance’s standard template.
* In the case of existing projects, an agreement to transfer the project name and electronic account assets (GitHub repo, social media accounts, domain names, etc.) to Linux Foundation Europe for the benefit of the Post-Quantum Cryptography Alliance.
* Adopt the Post Quantum Cryptography Alliance Code of Conduct.
* Upon acceptance, the project must list their stage/status prominently on their website/README

### Research Projects

#### Experimentation Stage
**Definition**
Experimentation Stage projects are research projects that the TAC believes are or have the potential to be important to the ecosystem of Technical Projects or the Post-Quantum Cryptography Alliance ecosystem as a whole. They may be early research projects just getting started, or long-established projects with a relatively small number of updates and/or maintainers. The Experimentation Stage provides a beneficial, neutral home for individuals or companies to collaborate on code that benefits cryptography research.

**Examples**
Alice and Bob published their paper on post-quantum cryptosystems in CCS. They want to make their implementation maximally public so that they can collaborate with others and potentially improve their cryptosystem.
Eve has a new parameter estimation toolkit for isogeny-based cryptosystems. She wants to let others help her extend it to new isogeny-based constructions.
Any research-focused coding project with the goal or potential of expanding and becoming a Labs Stage project.

**Expectations**
This stage does not set requirements for community size or research impact. Experimental projects will receive minimal support from the Foundation. Projects will be reviewed annually; they may also request a status review by submitting a report to the TAC.

**Acceptance Criteria**
To be considered for the Experimentation Stage, the project must meet the common acceptance criteria above.

#### Labs Stage
**Definition**
Labs Stage projects are research-focused coding efforts with long-term support and a large maintainer community.  Typically these projects have substantial academic impact in terms of citations and incorporation in research papers, and production projects or code may be spun out of these projects. While it is not expected that Labs Stage projects produce production code, it is expected that their community resembles that of an Impact Stage project (defined later in this document).

**Examples**
Companies X, Y, and Z maintain implementations of the latest post-quantum SNARKs. Whenever a paper provides a substantial advancement, the maintainers build or obtain a new implementation and test it against their metric suite. Academic papers frequently use benchmarks from this project to show how good their implementations are.
Long-term research code projects with a well-established community of both academics and research engineers.
Projects with considerable impact and/or citations in the cryptography or security communities.

**Expectations**
Labs Stage projects are expected to participate actively in TAC proceedings and have a binding vote on TAC matters requiring a formal vote, such as the election of a TAC representative. They may receive ongoing financial and marketing support from the Foundation and are expected to cross-promote the foundation with their activities.

**Acceptance Criteria**
To graduate from Experimentation Stage status, or for a new project to join as a Labs Stage project, a project must meet the Experimentation Stage criteria plus:
* Have a defined governing body of at least 5 or more members (owners and core maintainers), of which no more than 1/3 is affiliated with the same employer. If there are 5 governing members, 2 may be from the same employer. 
* Have a documented and publicly accessible description of the project's governance and decision-making.
* Identify a minimum set of metrics the project proposes to use to signal project health and maturity. The TAC will use these to evaluate the proposed change in stage and continued health and maturity of the project within their stage. Examples include organizational dependency, commit activity, or other code ownership metrics.
* Have a clear explanation of the project governance and committer process, which are explicitly defined in the technical charter, that is easy to understand for new participants. These are preferably laid out in a GOVERNANCE.md file and reference a CONTRIBUTING.md and OWNERS.md file showing the current and emeritus committers.
* Have a public list of research use cases for at least the primary repo (e.g., ADOPTERS.md or logos on the project website).
* Have a stable API and documentation as to API change procedures
* Other metrics defined by the applying Project during the application process in cooperation with the TAC.
* Receive a two-thirds supermajority vote from the TAC to move to the Labs Stage. 

### Production Projects

#### Incubation Stage
**Definition** 
Incubation Stage projects are projects that the TAC believes are or have the potential to be important to the ecosystem of Technical Projects or the Post-Quantum Cryptography Alliance ecosystem as a whole. They may be early-stage projects just getting started or long-established projects with minimal resource needs. The Incubation Stage provides a beneficial, neutral home for these projects to foster collaborative development and provide a path to deeper alignment with other Post-Quantum Cryptography Alliance projects via the graduation process.

**Examples**
New projects that are designed to extend one or more Post-Quantum Cryptography Alliance projects with functionality or interoperability libraries. 
Independent projects that fit within the Foundation mission and provide the potential for a novel approach to existing functional areas (or are an attempt to meet an unfulfilled need).
Projects commissioned or sanctioned by the Post-Quantum Cryptography Alliance.
Any project that realistically intends to join the Incubation or later stages in the future and wishes to lay the foundations for that transition.

**Expectations**
End users should evaluate Incubation Stage projects carefully, as this stage does not set requirements for community size, governance, or production readiness. Incubation Stage projects will receive minimal support from the Foundation. Projects will be reviewed annually; they may also request a status review by submitting a report to the TAC.

**Acceptance Criteria**
To be considered for the Incubation Stage, the project must meet the common acceptance criteria above.

#### Growth Stage
**Definition** 
The Growth Stage is for projects that are interested in reaching the Impact Stage and have identified a growth plan for doing so. Growth Stage projects will receive mentorship from the TAC and are expected to actively develop their community of contributors, governance, project documentation, and other variables identified in the growth plan that factor into broad success and adoption.

In order to support their active development, projects in the Growth Stage have a higher level of access to Foundation resources, which will be agreed upon and reviewed on a yearly basis. A project's progress toward its growth plan goals will be reviewed on a yearly basis, and the TAC may ask the project to move to the Incubation Stage if progress on the plan drops off or stalls.

**Examples**
Projects that are on their way or very likely to become Growth or Impact Stage projects.
Projects that have developed new growth targets or other community metrics for success.
Projects that are looking to create a lifecycle plan (maintainership succession, contributor programs, version planning, etc.)
Projects that need more active support from the Foundation or TAC mentorship to reach their goals. 

**Expectations**
Projects in the Growth Stage are generally expected to move out of the Growth Stage within two years. Depending on their growth plans, projects may cycle through the Incubation, Growth, or Impact Stages as needed.

**Acceptance Criteria**
To be considered for Growth Stage, the project must meet the Incubation Stage requirements as well as the following:
* Develop a growth plan, which will be done in conjunction with their project mentor(s) at the TAC.
* Document that it is being used successfully in production by at least two independent end users who are of adequate quality and scope in the TAC's judgment.
* Demonstrate a substantial ongoing flow of commits and merged contributions.
* Have a stable API and documentation as to API change procedures
* Demonstrate that the current level of community participation is sufficient to meet the goals outlined in the growth plan.
* Since these metrics can vary significantly depending on a project's type, scope, and size, the TAC has final judgment over the level of activity adequate to meet these criteria.
* Receive a two-thirds supermajority vote of the TAC to move to the Growth Stage. 

#### Impact Stage
**Definition**
The Impact Stage is for projects that have reached their growth goals and are now in a sustaining cycle of development, maintenance, and long-term support. Impact Stage projects are commonly used in enterprise production environments and have large, well-established project communities.     

**Examples**
Projects that have publicly documented release cycles and plans for Long Term Support ("LTS").
Projects that have themselves become platforms for other projects.
Projects that are able to attract a healthy number of committers on the basis of its production usefulness (not simply 'developer popularity').
Projects that have several high-profile or well-known end-user implementations.

**Expectations**
Impact Stage projects are expected to participate actively in TAC proceedings and have a binding vote on TAC matters requiring a formal vote, such as the election of a TAC representative. They receive ongoing financial and marketing support from the Foundation and are expected to cross-promote the foundation along with their activities.

**Acceptance Criteria**
To graduate from the Incubation or Growth Stages, or for a new project to join as an Impact Stage project, a project must meet the Growth Stage criteria plus:
* Have a defined governing body of at least 5 or more members (owners and core maintainers), of which no more than 1/3 is affiliated with the same employer. If there are 5 governing members, 2 may be from the same employer. 
* Have a documented and publicly accessible description of the project's governance, decision-making, and release processes.
* Identify a minimum set of metrics the project proposes to use to signal project health and maturity. The TAC will use these to evaluate the proposed change in stage and continued health and maturity of the project within their stage. Examples include organizational dependency, commit activity, or other code ownership metrics.
* Explicitly define a project governance and committer process. This is preferably laid out in a GOVERNANCE.md file and references a CONTRIBUTING.md and OWNERS.md file showing the current and emeritus committers.
* Have a public list of project adopters for at least the primary repo (e.g., ADOPTERS.md or logos on the project website).
* Other metrics as defined by the applying Project during the application process in cooperation with the TAC.
* Receive a two-thirds supermajority vote from the TAC to move to the Impact Stage. Projects can move directly from the Incubation Stage to the Impact Stage if they demonstrate sufficient maturity and have met all requirements. 

#### Emeritus Stage
**Definition**
Emeritus Stage projects are projects that the maintainers feel have reached or are nearing end-of-life. Emeritus Stage projects have contributed to the ecosystem but are not necessarily recommended for modern development, as there may be more actively maintained choices. The Foundation appreciates the contributions of these projects and their communities, and the role they have played in moving the ecosystem forward. 

**Examples**
Projects that are "complete" by the maintainers' standards.
Projects that do not plan to release major versions in the future.

**Expectations**
Projects in this stage are not in active development. Their maintainers may infrequently monitor their repositories and may only push updates to address security issues, if at all. Emeritus Stage projects should clearly state their status and what any user or contributor should expect regarding response or support. If there is an alternative project the maintainers recommend, it should be listed as well. The foundation will continue to hold the IP and any trademarks and domains, but the project does not draw on foundation resources. 

**Acceptance Criteria**
Projects may be granted Emeritus Stage status via a two-thirds supermajority vote from the TAC and with approval from project ownership. In cases where project ownership is lacking, only a two-thirds supermajority vote from the TAC is required.

## IV. Annual Review Process
The TAC shall develop an annual review process to determine whether projects are in the stage that accurately reflects their needs and goals.

The TAC shall review this document on an annual basis. Changes to this document can be proposed and accepted at any time through issues on the PQCA GitHub repository.