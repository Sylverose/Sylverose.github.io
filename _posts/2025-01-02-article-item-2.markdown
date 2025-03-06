---
layout: posts
title:  "Responsive dashboard"
date:   2025-01-03 10:18:47 +0000
categories: dev 
highlight_home: dev
tags: Corporate
description: item 2
header:
    overlay_image: assets/img/cp/flow_ex.jpg
    teaser: assets/img/cp/prototype.jpg
    caption: "Owned by [Vitec Aloc A/S](https://www.vitec-aloc.com/loesninger/cockpit/)"
---
# RWD and interaction design

**Problem description**<br>
Cockpit is a private banking solution, that gives an overview of a client's assets in a web format. Originally developed as a desktop site for bank advisors, Cockpit was scheduled to be re-designed into a new software solution for end-users.<br>The goal was to allow customers of financial institutions to view and follow their assets in real time, on a desktop, tablet or smartphone device.<br><br>
I was hired by Vitec Aloc A/S in a role of UX designer, to refine the application in development, primarily with 2 scopes:<br>
✨ *to make the application responsive* <br>
✨ *to reach out to customers, and style the product in their brand (LESS CSS)*
<br><br>
**Solution**<br> Responsive web application, with simplified functionality, aiming to give a quick overview on the go.

<img src="https://www.vitec-aloc.com/media/fy3l1yb4/devices_hvidbg.jpg?width=636&height=477&v=1d95d6d5af69c30">
**On the technical side**<br>
To keep consistency across products, web components (charts, tables, forms etc.) were re-used. This was both an advantage and a disadvantage, as it would narrow the creative options in terms of style, but highly reduce backend development time. <br>
This arrangement was feasible, as all the backend developers were overloaded in the moment. <br><br>
The existing CSS was improved with LESS. I chose to stay at the office, while my dev colleagues were on summer vacation, and used the opportunity to implement a variable system that reduced styling time / project roughly from 5-6 hours, to an average of 5 minutes.
<br><br>


**Results**<br>
A customizable responsive web solution, which included an attractive basic branding package, with possibility for more customization by further development purchase.
<br><br>
<img src="/assets/img/cp/client customizations.jpg"><br><br>
**Challenges**<br>
🧱 Implementing design thinking: I was the first and only UX designer in a company with 50+ years of operation<br>
🧱 Low credibility: the core of the team (primarily developers) were used to autonomy, and had worked very hard on the solution. This created some resistance in accepting a someone hired to introduce a new way of thinking in terms of usability<br>
🧱 Tight time frame: Getting everyone to collaborate posed particularly challenging, as I had to argument the necessity and duration of every meeting <br><br>
**Limitations**<br>
⚠️ Exceeded budget: major downside to a creative process, as it nulifies or blocks most chances for research and user involvement<br>
⚠️ Late team addition: most of the product was implemented when I joined the project, without a design strategy<br>
⚠️ Pressing deadline: a first release was urgently due<br>
⚠️ No access to the real target group: due to Non-Disclosure Agreements from our clients' side, I could not contact and test the prototype or product with the final users<br><br>
**Method**<br>
When you are asked to fit an extensive desktop app, on a small mobile device, after months of development, you know it's not going to be easy. Complex filtering functions, and at times tables with 13 collumns and big numbers may seem impossible to translate to a smartphone screen. <br><br>
How did I do this? By asking the right stakeholders, the right questions. <br>
### Triangulation <br>
One of the above-mentioned limitations was the difficulty to come in contact with the user group. I could contact our clients, but due to NDA they could not disclose their user contact information. The ideal situation in this case, would've been to collaborate with our clients, and split responsibilities. It was also about this time that they individually started hiring UX designers in-house, which made me hope for future delegation of user research assignents - if I couldn't be in contact with the users, they could. <br>
Alternatively, I could've gone Guerilla testing in key locations, this option seemed far too time consuming. I was already being encouraged to use as little time as possible on user contact. <br><br>
My last, less favorite option, was to trust that relevant research had been made primarily to listing accept criteria, and use triangulation as my UX research method. <br><br>
<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*70Xcm-8Wh6RNKfQS"><br><br>
External insights: the product description documents, including accept criteria; a financial expert with experience from the client side, had been assigned to the team with a Product Owner role; client contacts for questions in relation to branding.<br>
Internal knowledge: experience building the original application, however with a different target group; knowledge of existing technical details, primarily components for re-use.<br>
Expert knowledge: my UX and design thinking expertise; borrowed knowledge and sparring with my peers; collaboration with in-house financial experts.<br><br>

Risk of bias: **HIGH** <br><br>
My motivation for this statement is that the experts consulted on the project offered B2B experience. With an unreachable target group, and a tendency to focus on expert use of the financial app that we were building from, several challenges arised in design thinking for mobile devices, especially in terms of simplifying interactive functions for easier use on the go.<br><br>One example would be the mathematical functions built in the app. You could search or add numbers smaller or bigger than X, by operating with collumn values. An end user might find it time-consuming while they're trying to get a quick overview on their mobile phone, while rushing to their car.<br><br>
A later version of the app was tested with *"family and friends"*. I was not involved in the testing process.<br>
### Prioritizing via participatory innovation
There was no way that we could've simply forced all the data and functionality of the original app, into the new one. Nor would it have made sense. Based on the data provided on user needs, our team established a list of core features. The tablet version replicated the desktop view, so prioritization was done on the collumns shown first in the tables. On smartphones, the space was much more restricted, so some of the collumns were displayed beneath the top ones. Accordeon structures were translated into detail views instead. <br>
### Reaching out to nearby network
I admit that I felt overwhelmed at times, as the only designer. There's a lot of designer communities out there, I considered asking for advice from other designers. However, with an NDA in place, not only on client data, but also on the application design itself, the risk of oversharing was too high. <br><br> Vitec Aloc A/S is part of the Vitec Software Group, that specializes in the acquisition of vertical software companies.<br> So instead, I tried to connect with other Vitec branches, and see if they had any UX designers in-house. Fortunately, I have been able to connect with [Lars Antilla](https://www.linkedin.com/in/lars-anttila/) from the main branch, and [Ingrid Mårtensson](https://www.linkedin.com/in/ingridmartensson/) UX/FE Manager at Vitec Appva AB. Together we founded a UX designer network inside Vitec Software Group, that aims to support designer and anyone interested in UX, through advice and sparring with their peers.<br><br>
One of the most notable advantages of sparring in our internal group was the possibility to share product designs with each other, without worrying about disclosing their key features to anyone outside the corporation. <br><br>And that solved one of my biggest blocks. But not only that: it brought awareness and importance to UX design inside the Vitec Software Group.
### Co-design<br>
A new target group can sometimes mean the necessity to develop extra functionality. One of the most complex components that we had to build, was a portfolio selector, which would toggle a user's related portfolios. The image below is a representation of the final interaction flow. However, this was a result of many sparring sessions at the whiteboard, with fellow developers, and our product owner.<br><br>
<img src="/assets/img/cp/flow_ex.jpg"><br><br>
**Highlights**<br><br>
⭐ Teamwork is golden. The solutions to the problems encountered along the way have been achieved only through close collaboration with my team members and design seriors. <br>
⭐ While I feel like I would've applied a different design strategy, I am satisfied for making the best out of the existing project settings.<br>
⭐ Thanks to the challenges faced, reaching out to my corporate design colleagues has resulted in an internal UX community, with yearly meet-ups, and 'roud-the-clock support for anyone working with UX.
<br><br>
<img src="/assets/img/cp/prototype.jpg"><br><br>
**Reflections**<br>
It's not easy to take on such a big project, especially when so many variables challenge you as a designer. I have a hard time giving up on any assignments, though. I like to believe that together we can find a solution.<br>I wanted to take responsibility for making this project responsive, because the risk of missing delivery was simply too high.<br><br>Tech changes at an overwhelminly fast pace, and often we need external help in order to answer customer demands and stay relevant on the market. 
While the learning curve was steep, I feel a lot of gratitude for my senior designers from the Vitec corporate, who have been my rock in difficult times.<br><br>
If some passages might hint at my dissatisfaction, this is merely my way to express frustration towards the limitations. Sometimes it's hard to assess which talent resources we need on a project, especially when facing a niche assignment.<br><br> While we all wish for an ideal project setting, real life can bring sequential challenges. The takeaway from this is that we need to face them together, as a team, and learn from the experience.<br> With me on the team you can be sure that you'll have a dedicated designer from start to finish.<br><br>
**Disclaimer**<br>
The product and all the rights are owned by [Vitec Aloc A/S](https://www.vitec-aloc.com/). With their permission, I have used screenshots from the product prototype, which shows only mock data.<br><br>You can book at demo of the product on the company's [official website](https://www.vitec-aloc.com/).
