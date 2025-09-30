Sarah Sanders - Portfolio

I'm a technical writer with a passion for developer experience, developer community, and documentation. I specialize in creating developer guides, API references, and tutorials that make complex concepts accessible. My goal is to support developers through content that educates and empowers.

## Docker, Inc.

Technical Writer | September 2024 - Present

### Featured work

- [Overhaul of Docker SSO documentation](https://docs.docker.com/enterprise/security/single-sign-on/): Early on
at Docker, I was tasked with overhauling our SSO documentation. The previous documentation was hard to follow,
dense, and developers often complained about the experience. After overhauling, our support team reported
a significant reduction in support tickets related to SSO.
- [Settings management documentation](https://docs.docker.com/enterprise/security/hardened-desktop/settings-management/):
Since releasing Settings management, I have implemented many iterations and improvements for the product
documentation. After receiving feedback from external users and internal stakeholders, I created a settings reference
to serve as a master list of Docker Desktop settings.
- [Implemented standardized troubleshooting guides](https://docs.docker.com/enterprise/troubleshoot/troubleshoot-sso/):
Since joining Docker, I have implemented standardized troubleshooting guide templates, aimed at helping to
reduce developer friction on the platform. Previously, our troubleshooting guides were inconsistent across
product lines and features, and not comprehensive enough to be helpful. Since implementing a standardized format
and adding more comprehensive troubleshooting, the docs and support teams have noted increased ticket deflection
metrics.
- Docs as tests: I introduced the methodology, docs as tests at Docker. This methodology involves testing your
documentation as you would test your product, to ensure documentation stays updated with your product. I started
by building a testing suite using Playwright to validate UI steps in documentation against Docker web applications.
These tests run inside a Docker container, in a daily chron job. When UI steps are outdated, there is a Slack
notification that notifies the team that docs are outdated. This has significantly improved how the docs team
maintains documentation and lessens docs freshness burdens.
- [Docs AI optimizations](https://docs.docker.com/admin/): On any page of the docs site, you can select the
"Page options" button and view the page as plain text. I implemented this, along with llms.txt to help LLMs
crawling our docs site. The goal of this is to hopefully reduce the amount of hallucinations when users are
using external AI systems with our docs site. Additionally, I have created a Docs AI tutor prototype that
is context aware and helps users while they are learning using a Docker guided tutorial. This prototype
is not GA yet. I did write a blog on the prototype to promote Docker Model Runner: [Building an AI tutor with Docker
Model Runner](https://www.docker.com/blog/how-to-build-an-ai-tutor-with-model-runner/).

## Highnote

Senior Technical Writer | March 2023 - September 2024

### Featured work

- [Developed developer education strategy for early stage startup](https://highnote.com/docs): I was the founding
technical writer for Highnote, and during my tenure, a solo technical writer. I developed the company's 
developer education strategy.
- [End-to-end implementation tutorials](https://highnote.com/docs/issuing/templates/commercial-credit): I created
a series of end-to-end implementation tutorials, walking developers through creating an entire card program
on the Highnote platform. These tutorials were often the first pieces of documentation that developers received
or used when learning to use the Highnote platform, and helped reduce onboarding friction.
- [Intro to GraphQL guide](https://highnote.com/docs/basics/graphql-api/using-graphql): Highnote's GraphQL
API proved to be a learning curve for a lot of developers, so I focused on creating resources aimed
at reducing time to first success.
- [Created a Help Center for non-technical users](https://support.highnote.com/hc/en-us): When I joined Highnote,
the entire product was API-first. During my time there, the DevEx team built a dashboard for non-technical
customers so they could interact with the product and maintain their card programs. I anticipated user
friction with our technical documentation, and advocated for the creation of a non-technical Help Center. I created
this from the ground up, as a solo project.
- [Simulation guides](https://highnote.com/docs/issuing/transactions/simulate-transactions): I created simulation
guides for product features to make it easier for developers to learn how to use the feature. Each simulation guide has
an embedded API explorer that allows the developer to edit and run queries directly from the documentation to
their sandbox environment.
- Code snippet validation: I created a GitHub workflow that validated all of the documentation site's GraphQL code snippets
against the API, using introspection. This workflow ensured that all code snippets were 100% accurate, and if they weren't,
I could update them quickly.

## GraphQL Foundation

GraphQL maintainer | Current

### Featured work

- I write and maintain the [GraphQL.js documentation](https://www.graphql-js.org/docs/)
- I contribute to the [GraphQL Foundation's main documentation site](https://graphql.org/learn/)
- I am actively developing an online learning management system to increase GraphQL adoption. This
LMS platform will provide containerized sandbox environments with mock data, pre-written projects, and 
feature dedicated learning paths for different types of users. 

## Speaking and community involvement

- Keynote Speaker, GraphQLConf 2025: "Reimagining Developer Experience for AI-Native Development"
- Keynote Speaker: GraphQLConf 2024
- Conference Speaker: Write the Docs Atlantic 2024
- Technical Blog: Inline Comments @ sarahsanders.dev
- GraphQL Ambassador
- Active advocate and educator in the GraphQL community
- Active community member of Philadelphia developer meetups
