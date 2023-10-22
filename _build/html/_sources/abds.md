![ab-ds-web-banner](_static/assets/autobahn-design-system.png "aab-ds-web-banner")

# Autobahn Design System
<a href="https://autobahn.security" target="_blank">Autobahn</a> is an all-inclusive cybersecurity platform that reduces the need for human capital with scalable solutions and provides effective prioritization to work on the right vulnerability issues. The product was initially delivered as a proof of concept to the first customers in 2021 by <a href="https://srlabs.de" target="_blank">Security Research Labs</a> cyber security consultancy, and then established as a separate entity.

The business objective was to bring the app to the next level. The decision to move from vueJS to React opened the opportunity to redesign the web app user interface. Strategically it was also the best moment to implement the design system. As the most experienced designer on the team, I was responsible for creating the design system.

- conduct the research
- plan strategically
- build the system
- train team members
- evangelize and maintain the system

## Challenges
- Lack of consistency in the interface and poor usability.
- Limited human resources and ambitious delivery goals.
- Challenging collaboration between the teams due to the missing documentation and clear guidelines.
- Significant issues in the front-end code.

## Key questions
First, we established a set of crucial questions that would guide us through the process:
- Who and how often will be using the design system?
- What technical aspects are essential to be successful?
- How will we ensure that all teams stay up-to-date and on the same page?

## Research and Requirements Definition
During the research phase, I analyzed designsystemsrepo.com, and other publicly available resources. Then I audited the existing UI and considered possible scenarios for the future. As a final part of the research, I conducted a *"Developers and Designers Challenges and Needs Workshop"* to find out the pain points and challenges of the team members.</br></br>

![designsystem-playground](_static/assets/design-system-playground.png "Design System Playground")

The core requirements to decide which design system we will use as a template were: 
- built with **B2B data-heavy products** in mind
- easy to customize and works with **React** 
- well supported in <a href="figma.com/" target="_blank">**Figma**</a> and, preferably in advanced prototyping tools like <a href="https://www.uxpin.com/" target="_blank">UXPin</a> or <a href="https://www.axure.com/" target="_blank">Axure</a>
- well-structured and detailed **documentation**
- support diverse variants of **tables and filters components**

I have discovered that <a href="https://ant.design/" target="_blank">**Ant Design**</a> fills all product needs, and we decided to proceed with it and suggested <a href="https://storybook.js.org/" target="_blank">**Storybook**</a> for the development environment. 


## Building the System and Documenting on the Go
The main strategic challenges during the process were the limited resources and the need to continue developing the next-generation version of the product. Our goal and the biggest challenge was to wireframe and mockup nine new views for the web app while building a design system. To achieve this, I decided to leverage the <a href="https://www.antforfigma.com/" target="_blank">Figma Ant Design Package</a> and use it as our component design base. Next, we iterated over the wireframes with the design and product teams to identify the required components for each view. </br></br>

![ab-designsystem-workflow](_static/assets/ab-ds/ab-designsystem-workflow.png "ab-designsystem-workflow")

After that, I selected the appropriate components from the UI Kit, customized them to our needs, and moved them to the Autobahn Design System. Then, the UI Designers created the final mockups of the views and submitted them for review. At the end of each cycle, we delivered the assets to the design system developers and the web app developers accordingly. </br></br>

![ab-designsystem-mockup](_static/assets/ab-ds/ab-designsystem-mockup.png "ab-designsystem-mockup")
## Maintainance & Socializing the Design System
The design system was documented along the way on Figma Canvas, in the component styling descriptions, as a written guide in Jira, and on the Design System Slack channel. Each team member had full access to the Jira documentation, developers had viewing permission in Figma, and designers assigned to the design system maintenance tasks had full permission to the Figma file. We also established regular meetups with developers to review the Storybook and ensure consistency.