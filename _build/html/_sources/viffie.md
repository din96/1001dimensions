![viffie-banner-web](_static/assets/viffie-banner-web.png "viffie-banner-web")

# viffie
viffie is an innovative application that enables users to collaborate, communicate, and interact with each other in real-time, regardless of their physical location. The project was conceived and developed during the Advanced User Experience Training with <a href="https://careerfoundry.com" target="_blank">Career Foundry</a> in 2017, four years ahead of the COVID-pandemic and the surge in remote work.

## Market Research
The objective of the market research was to identify the potential competitors in the market, their strengths and weaknesses, and to establish the business goals for viffie.
- Using Open Intelligence, I scraped a list of the task management, remote work and team collaboration tools available in the market. 
- I created app categories: todo lists, GTP apps (Getting Things Done), Kanban Board Apps, Plain Text todo lists, team-oriented productivity tools, and gamified productivity tools.
- I classified apps by platform support, business model, data management, synchronization, project and task management, collaboration, UI customization, real-time features, and other features.
- From the previously mentioned list I selected the four most notable apps and audited them by class.
- I created a list of potential MVP features. 
- As the last step I mapped the strategy for the alpha release (using the SMART goals method)

::::{grid}
:gutter: 3

:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-marketresearch-1.png
    :group: market-research
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-marketresearch-2.png
    :group: market-research
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-marketresearch-3.png
    :group: market-research
```
:::
::::


## User Research
Viffie is an application that focuses on remote work and team collaboration. Understanding how people work remotely and what they need to succeed in their jobs was crucial to this project. The first step in the user research phase was setting up the hypothesis:

`````{admonition} Hypothesis
:class: tip
As more people are working remotely, there is a demand for a virtual office application that can cater to the diverse needs of team members. To be successful and productive in a traditional office, people need to:
communicate, collaborate, brainstorm, exchange information, experience, expertise and thoughts, analyze, research, evaluate and execute.

Therefore, a virtual office application should provide the following tools: chat, video chat, social media features that can keep track of colleagues' activities, calendar and its variations, timer, pin board, sticky notes, kanban board, word processor, to-do lists, simple drawing tool, mind map, milestones indicator, personal assistant.
`````

Next, I defined the the survey target audience as remote or potential remote workers. The survey was distributed through various channels (bots creators and users forum, open source community IRC channel, large financial enterprise internal chat). The survey questions derived from the core question „How viffie will impact your work?“. I also narrowed down the categories to four topics:
- team integration
- collaboration
- productivity and motivation
- communication
Each category had at least one question in the survey.

The results indicated, among other things, that:
- 46.3% of respondents worked remotely.
- More than 70% of respondents rated the awareness of team members' current activities as an important or very important, supporting the hypothesis that an integrated Mood Board is a key MVP feature.
- The personal calendar was a tool that 72.34% would like to have in their virtual office. Users valued Milestones Tracking and Timers, but more as additional features. Some of the respondents believed that communication tools might enhance their time management.
- More than 50% of respondents found personal assistant a tool that could boost their productivity or motivation.

::::{grid}
:gutter: 3

:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-uresearch-1.png
    :group: u-research
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-uresearch-2.png
    :group: u-research
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-uresearch-3.png
    :group: u-research
```
:::
::::

## User Personas and Experience Map
After conducting interviews and surveys with the focus group, I defined the primary, secondary, and complementary target groups and developed four **User Personas**. The subsequent step was creating a **user experience map** and tasks models identifying the pain points and critical moments of working remotely. This insight enabled a new approach to enhance viffie's MVPs.

::::{grid}
:gutter: 3

:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-experience-map.png
    :group: ux-mapping
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-task-modelling.png
    :group: ux-mapping
```
:::
::::


## MVP
The market and user research data was thoroughly analyzed, providing a clear direction for viffie's development. I based the concept phase on the assumptions derived from the user needs research and business goals analysis. The **MVP features** consisted of:
- Mood Board
- Personal and Team Calendar
- White Board and Sticky Notes 
- Word processor 
- Chat 
- Personal Assistant (bot)


## Information Architecture
The project's next phase involved creating an **information architecture** that could identify the product's key features and provide a framework for developing user-friendly and efficient software. I conducted a **card sorting** test with a user group to ensure that the structure and logic matched their expectations and preferences. Then I created **user flows and diagrams** for the product page and web application.

::::{grid}
:gutter: 3

:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-ia-3.png
    :group: viffie-ai
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-ia-2.png
    :group: viffie-ai
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-ia-1.png
    :group: viffie-ai
```
:::
::::

## Prototyping & Testing
The entire process of creating viffie followed the Lean UX approach of design-validate-iterate. There were six design iterations on the MVP in total. First, I designed a set of paper prototypes and tested them on a group of users. The results of those tests informed the changes implemented during the wireframe design. I designed three wireframe sets for mobile, tablet, and desktop devices and used three different applications (inVision, Marvell App, atomic.io) to build interactive prototypes. Then, I repeated the user tests, removed or improved inefficient elements, revised the concepts, and created new assumptions.

Tests conducted: 
- card sorting 
- A/B
- preference tests 
- click test
- user flows tests with interactive prototypes

::::{grid}
:gutter: 3

:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-mockups-1.png
    :group: viffie-prototype
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-mockups-2.png
    :group: viffie-prototype
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-mockups-3.png
    :group: viffie-prototype
```
:::
::::
::::{grid}
:gutter: 3

:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-mockups-4.png
    :group: viffie-prototype
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-mockups-5.png
    :group: viffie-prototype
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-mockups-6.png
    :group: viffie-prototype
```
:::
::::
::::{grid}
:gutter: 3

:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-test-scenario-1.png
    :group: viffie-prototype
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-abtest-1.png
    :group: viffie-prototype
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-abtest-2.png
    :group: viffie-prototype
```
:::
::::

## User Interface Design 
The visual design of viffie follows the Material Design principles. The key aspects were to create a user interface that appeals to different preferences, minimizes the distraction from work, and ensures that the user interactions facilitate the task flows and are coherent and dynamic.
The deliverables produced during this phase included:
- Inspiration mood board
- UI Kit
- Desktop, tablet, and mobile mockups of the app view

::::{grid}
:gutter: 3

:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-ui-1.png
    :group: viffie-ui
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-ui-2.png
    :group: viffie-ui
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-ui-3.png
    :group: viffie-ui
```
:::
::::
::::{grid}
:gutter: 3

:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-ui-4.png
    :group: viffie-ui
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-ui-5.png
    :group: viffie-ui
```
:::
:::{grid-item-card}
```{thumbnail} /_static/viffie/viffie-ui-6.png
    :group: viffie-ui
```
:::
::::
