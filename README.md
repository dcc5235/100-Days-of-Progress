# 100 Days of Progress

## Objective
A personal plan I have developed to hold myself accountable to key goals and objectives between the dates of January 18, 2021 - April 26, 2021. I have mapped out a GANTT board on [monday.com](monday.com) to outline this process.

#### Key goals and objectives
1. Hone my skills in JavaScript by building JavaScript-heavy projects. 
2. Have a deeper understanding of React JS through open source.
3. Gain employment by the end of the 100 days.
4. Focus on mental health by curating 100 days of mantras and positive affirmations, as well as practicing mindfulness meditation.
5. Focus on physical health by having a 100 day meal plan and 100 day active plan.

## Calendar
<details><summary>Week 1 Objectives</summary>

Monday, 01/18/20 - Sunday, 01/24/20
1. Morning mantra (see Gantt for details).
2. Complete e-commerce shopping cart from scratch, plan design for single page layout (landing page).
3. Assigned Coding Nexus task (React project).
4. Begin reading Front End Developer's Handbook (https://frontendmasters.com/books/front-end-handbook/2019/#1.1). Finish Chapter 1 by EOW.
5. Physical activity (see Gantt for details).
6. Write Medium article on the JS array helper.
</details>

![](https://scontent.fdpa1-1.fna.fbcdn.net/v/t1.0-9/137224667_1303583540019484_6345447721045545497_o.jpg?_nc_cat=109&ccb=2&_nc_sid=0debeb&_nc_ohc=H0wbjbu0HQMAX-p3IJy&_nc_ht=scontent.fdpa1-1.fna&oh=5f17cba7ff1013d9a2e21ef285fe7e36&oe=60260C10)

<details><summary>Week 2 Objectives</summary>

Monday, 01/25/20 - Sunday, 01/31/20
1. Morning mantra (see Gantt for details).
2. Complete section 3 of 50 days of JS & plan design for single page layout.
3. Assigned Coding Nexus task (React project) from Week 1 Objectives.
4. Front End Developer's Handbook (https://frontendmasters.com/books/front-end-handbook/2019/#1.1). Finish Chapter 2 by EOW.
5. Physical activity (see Gantt for details).
</details>

![](https://scontent.fdpa1-1.fna.fbcdn.net/v/t1.0-9/138294479_1304905026554002_7015728169850880422_n.jpg?_nc_cat=107&ccb=2&_nc_sid=0debeb&_nc_ohc=EC_rUoiUMmIAX_t5xvK&_nc_ht=scontent.fdpa1-1.fna&oh=ac24058b87f3c898306c7a4351d3e42b&oe=60278993)

<details><summary>Week 3 Objectives</summary>

1. Morning mantra (see Gantt for details).
2. Complete section 3 of 50 days of JS & plan design for single page layout.
3. Assigned Coding Nexus task (React project).
4. Front End Developer's Handbook (https://frontendmasters.com/books/front-end-handbook/2019/#1.1). Finish Chapter 3 by EOW.
5. Physical activity (see Gantt for details).
6. Write Medium article on the JS array helper.
</details>

![](https://scontent.fdpa1-1.fna.fbcdn.net/v/t1.0-9/138644498_1304905959887242_3514607475845503786_o.jpg?_nc_cat=110&ccb=2&_nc_sid=0debeb&_nc_ohc=_3LzOV_yxTIAX-ieD1d&_nc_ht=scontent.fdpa1-1.fna&oh=2440948a21c82b5f8d02983a8b207ec2&oe=6027B54E)

<details><summary>Week 4 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 5 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 6 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 7 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 8 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 9 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 10 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 11 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 12 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 13 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

<details><summary>Week 14 Objectives</summary>

1. JavaScript
2. React
3. Application process
4. Mantra and meditation
5. Activity
</details>

## Lessons Learned

<details><summary>Week 1 Lessons Learned</summary>

Date: Jan 18, 2021<br>
What I did: Project up, installation, testing, & reading documentation. I decided to put more focus on carefully reading and understanding the documentation, then implementing what I understood. Today, I installed [Tailwind CSS](https://tailwindcss.com/docs/installation) with npm. Tailwind CSS is a utility-first CSS framework, which means that it provides low-level utility classes that let you build completely custom designs without ever leaving your HTML.

Tailwind automatically removes all unused CSS when building for production, which means your final CSS bundle is the smallest it could possibly be. In fact, most Tailwind projects ship less than 10KB of CSS to the client. Some things to keep in mind with Tailwind: issues with repeating classes which makes readability more difficult.

What went well: Most of the project set up was fairly straight forward. I was able to orgnanize basic project files into folders and get started on the navigation for the e-commerce site. I read several articles about the pros/cons of Tailwind.

What could be improved: I ran into a few hiccups with Tailwind. After installation, none of the preset Tailwind classes I added were initializing on the server. I brought in peers to take a look at the project set up and we were not able to come to a resolution today. We believe that my current version of node.js may have something to do with it.<br>
Moving forward, I will be saving links to the articles I read so I can reference them another time. I am also going to attempt to rubber duck my way through the project more.

<hr>

Date: Jan 19, 2021<br>
What I did: I partnered with a peer to track down the location of the error. Our earlier suspicions about node being outdated was inaccurate. Instead, we found that there was an issue with where the CSS script was pointing. I now have the script pointing to the public directory, instead of the src one. If anyone knows why this works, I am open to feedback. This is the updated script ```<link href="/public/css/tailwind.css" type="text/css" rel="stylesheet">```. Link to the project files are here: ![](https://github.com/dcc5235/Portfolio).

What went well: I decided to make the site a cosmetic e-commerce page where the landing page links users to the product page. I have completed half of the product page and solely used Tailwind to style all elements. I figured out how to change the background image url by editing theme.backgroundImage in the tailwind.config.js file, but this can also be done by injecting ```style``` directly into HTML. 

What could be improved: As a reminder, if you use ```display: flex``` and ```justify-between``` in Tailwind, make sure width is set to 100% by using class ```container```. Otherwise, your elements won't have "free space" left to move. I found some inspiration for landing page ideas [here]( https://business.tutsplus.com/articles/product-landing-page-examples--cms-32174#:~:text=5%20Top%20Product%20Landing%20Page%20Design%20Trends%20for,...%205%20Get%20Bold%20With%20Your%20Images.%20).
</details>

