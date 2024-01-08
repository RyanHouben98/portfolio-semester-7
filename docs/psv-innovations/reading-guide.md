---
sidebar_position: 1
---

# Reading guide

In this reading guide, the project "PSV Innovations" is described. The document provides an overview of the assignment's overall context and outlines the process we took to reach a final conclusion and product. Additionally, proof of the learning outcomes has been included in this reading guide for easy access to the portfolio, where all details are comprehensively described.

## The assignment

PSV continually seeks fresh and innovative methods to engage with their fans. Several years ago, they initiated a concept called "The Brainport Experience Box." It comprised a small section in the stadium where select individuals were invited to test novel innovative ideas using tablets or VR glasses. Over time, this space was discontinued, with the aim of reaching a broader fan base through these innovative solutions.

To achieve this, PSV intends to introduce these ideas within their official PSV application. This application will allow users to interact with these concepts both within the stadium and from the comfort of their homes. By doing so, they aim to engage nearly all their fans, not limited to the original 13 seats in the experience box.

Furthermore, PSV plans to develop certain ideas exclusively for commercial use, allowing them to charge a nominal fee and generate additional revenue.

At present, PSV lacks a solution for pre-testing new innovative ideas before their integration into the official PSV app. Additionally, there is no platform in place for obtaining insights on tested results or collecting feedback.

**The assignment we got for this semester:**
Create a solution where PSV can deploy their innovative ideas and where test users can test these innovations.

## Description of the process and the results

### Empathize:

Because Branimir and I already had some prior knowledge about this sort of project, because of the previous Smart Mobile semester, so we already knew our stakeholders etc. The only real differences are that we had to make something for a bigger audience (max 1000 people) and we don’t have to make an innovation ourself.

After some meetings with Victor, the other project group (Advanced Media) and Eric we started with making a project plan to initialize the project and set up some early research questions.

### Define:

Because the project is already fairly narrowed down at this point, we came up with the following:

**Problem statement:**
At present, PSV lacks a solution for pre-testing new innovative ideas before their integration into the official PSV app. Additionally, there is no platform in place for obtaining insights on tested results or collecting feedback.

**Goal:**
Assist PSV in creating an all-in-one testing environment where testers can evaluate new innovative ideas and provide feedback. Additionally, support PSV in developing a tool to gain insights from the collected testing information and feedback.

**Main Design challenge:**
How to create a native mobile solution allowing app developers to seamlessly integrate their modules and enabling PSV test users to test these modules, prioritizing user-friendly experience, and emphasizing security measures.

### Ideate:

In the “define” phase of the project we narrowed down that Victor (PO) wants 3 things:

- A dashboard with insights.
- An application where innovations can be tested.
- A feedback system for the innovations.

Based on that we came up with the following sub design challenges:

1. Which native solutions is best for testing the integrated modules?
   • Must work together with the current PSV application.
2. How to make a plugin system that enables app developers to easily intergrade their modules inside the test app.
   • Defined plugin template for new modules.
   • Module should be plug and play.

3. How to make a native mobile application that enables PSV test users to test and vote on modules?
   • Passed modules is 80%+ votes.
4. How to gather useful feedback for the PSV innovation staff, out of the test users on a native mobile application?
   • Find at least 3 solutions to gather feedback other than rating.

### Prototype:

Because we are working on 2 different components I spitted this section in two.

#### Dashboard:

The. First initial idea was a dashboard for the PSV staff where they can monitor all the insights the application (Test application) generates. After some more thinking we expanded this idea with developer accounts.

With these developer accounts, developers can upload their developed innovation in the dashboard. These innovations would then automatically be included in the Test app. Developers could also see the insights of their innovations in the dashboard.

After some research we concluded that the App store does not allow code changes after the deployment, so each time an innovation gets uploaded we must redeploy the application.

We tackled this with adding Iframes. Instead of uploading the whole innovation, they only must upload an Iframe. This Iframe can be included in the test application without redeploying.

This comes with a draw that we lose some native functionality, but because of time we approved this idea with Victor.

#### Application:

The initial goal was to make the application in the same language as the official PSV app, because then we can easily port innovation to the official app.

After discussing this with Victor it seemed that the official app is make in Objective C (iOs) and Java (Android). Because of the time limit we decided to go for react native so we can make a hybrid solution.

### Test:

User tests are on 11 January.

## Proof of the learning outcomes

### Analysis

You can critically and methodically analyze a problem, opportunity, or technology in a smart mobile context.

**Self-assessment: Proficient**
The analysis phase was already clear from the start. Viktor told us about the problem that they cannot test new innovations before they go to the official app. With the debriefing he was clear on what he wanted and who our target audience was (selected testers chosen by PSV).

**Links to portfolio:**

- [Debriefing](./01-analysis/01-debriefing.md)
- [Personas](./01-analysis/02-personas.md)
- [Empathy maps](./01-analysis/03-empathy-maps.md)
- [App workflow](./01-analysis/04-app-workflow.md)

### Advice

Based on relevant analysis, you advice on suitable user interaction and technological design, improvement of designs, research and/or methodology.

**Self-assessment: Proficient**
In the initial phase we talked with victor about a plugin system where developers can upload their innovations. After some research we concluded that this is not possible in the app store, because otherwise we had to redeploy after every innovation upload.

We also advised Victor on the fact that we are making a hybrid solution with react-native because of time shortage.

**Links to portfolio:**

- [Software choices](./02-advice/01-software-choices.md)
- [Research document](./02-advice/02-research-document.md)

### Design

You use a design process to create UX -and technological designs and validate your choices, in a context which is complex and subject to change.

**Self-assessment: Beginning/Proficient**
Because of time shortage Branimir and I agreed on focusing on our strong points. That’s why I lacked a little bit on the design. The media group also designed most part of the application.

**Links to portfolio**

- [High fidelity design](./03-design/01-high-fidelity-designs.md)
- [System architecture](./03-design/02-software-architecture.md)

### Realization:

Based on a relevant design you implement, validate and deploy an interactive and reliable smart mobile product.

**Self-assessment: Proficient/Advanced**
This was my strong point. I made the dashboard and the API that connects everything together. I also helped Branimir with developing the React-Native application. And for the time being the application is still in review in the app and play store.

**Links to portfolio:**

- [Dashboard](./04-realisation/02-dashboard.md)
- [Api](./04-realisation/01-api.md)
- [Application](./04-realisation/03-application.md)

### Manage and control:

You continuously apply methodologies to manage a development process and to assure its quality in direct communication with all stakeholders.

**Self-assessment: Proficient**
Because we had to work together with another group, we had to manage everything a little more. We had to plan meetings with the other group and keep the planning of our own group project in mind. I think we managed pretty well, the group project didn’t suffer under this duo project.

**Links to portfolio**

- [Project plan](./05-manage-and-control/01-projectplan.md)
- [Handover document](./05-manage-and-control/02-hand-over-document.md)
- [User testing](./05-manage-and-control/03-user-testing.md)

### Professional skills:

You demonstrate your professional development as a mobile developer in the form of authentic, professional IT tasks in which both the process and the result are visible.

**Self-assessment: Proficient**
Because we had to work with together with another Advanced Media group this was a little harder. We had to plan a lot together and keep each other updated the whole time. It also made the project more fun and diverse because in the real world there are also multiple teams working on one big project.

**Links to portfolio:**

- [Agile working](./06-professional-skills/01-agile-working.md)
- [Feedpulse](./06-professional-skills/02-feedpulse.md)
