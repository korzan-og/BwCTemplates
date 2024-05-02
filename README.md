## Suggested Github Repository Template

This repository includes the templates that will be used in the github repos for Build with Confluent. Please clone the repo and copy the related template into your own repository. This page also includes the basics a github repo should have.

**Must haves of Github repos**
1. Github repositories should be under the partner's organization name to keep continuity, corporate credibility and long-term maintainability for the partners work.
2. There should be a naming convention for the repository starting with ‘bwc-<name of the solution>’ to have a standardized naming convention.
3. Github repos should follow a uniform and descriptive naming and organization convention.
4. Github repos for solutions should be easy and self-explanatory. If your screenshot/video/gif needs an explanation, either the feature is not obvious or the repo needs work. Assume people who run it don’t know anything about the solutions used.
5. Solution should have a specific repository to clearly indicate the content topics, function, maintenance status, release readiness etc.
6. File structure of the repository should be as follows:
    - README.adoc
    - Terraform folder(if includes the terraform scripts)
    - Ansible folder(if includes the ansible)
    - Utils(if includes the datasets/any other tools for the demo)
    - Well-branded and complete Readme

README might include Confluent branding with Partner Logo and name, title, subtitle, short description, and detailed HOWTO. README should also link to other relevant Confluent/Partner resources, such as documentation, blogs, online talks, other repositories, and so on. 
Readme should include the purpose of the solution, describing how to use the repository, requirements, reference architecture, steps to run the demo and relevant links and people to contact for more information. Readme template could be found here


**Simple / “1-click” setup**
Setup instructions should be as simple as possible, leveraging either Terraform for cloud resources, or gitpod for running docker images in a browser-based hosted development environment. 

The more involved a setup process is, the more costly it is to run the demo, create a video, support a workshop, or otherwise use the repository. Gitpod is a great tool for running containers in a browser, and Terrraform is a great tool for spinning up Confluent and non-Confluent cloud-based resources.

**Basic Diagram**
Simple diagram showing data flow and architecture components of the demo, possibly comparing with and without Confluent. This is something that can be inserted into a slide describing the asset, shown in a booth, or an introduction to a presentation on the asset.

**Short Description**
Single paragraph describing the asset. 

**Long-Form HowTo**
Detailed written description of the asset, including introduction, step-by-step, and summary. Usually the post-setup howto section of the github repository README can serve this purpose. Imagine leading a workshop for this demo. 

**Executive Summary**
Business value proposition of the collateral, including its relationship to other marketing initiatives, solutions, product releases, and so on. This should be in one sentence, one paragraph, and long form if necessary. This is where we can tie the content of the demo to the message being delivered. Imagine this going into a solution brief, nurture email, social media promotion, and so on. 
