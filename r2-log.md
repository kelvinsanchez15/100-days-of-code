# #100DaysOfCode Log - Round 2 - [Kelvin Sánchez]

The log of my #100DaysOfCode challenge. Started on [October 05, Monday, 2020].

## Objectives / Tasks
- [x] Apply for jobs
- [ ] Train and prepare for jobs interviews 
- [ ] Try freelancing
- [ ] Build strong projects for my portfolio
- [ ] Improve projects README file
- [x] Connect with people / Join more coding communities
- [x] Make Open Source contributions
- [x] Learn PostgreSQL
- [x] Start using TypeScript
- [ ] Learn Enzyme/React testing library
- [ ] Read books and work on my fundamentals (JavaScript, Data Structures) 

## Log

### R2D1
- [x] 5 Kyu "Pagination Helper" kata at codewars
- [x] Update login logic (Note-taking app)
- [x] Generate authentication tokens with JWT

[A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/1af2a5669637ea55713c7167a61c295e34af0200)

### R2D2
- [x] 5 Kyu "Weight for weight" kata at codewars
- [x] Apply for jobs
- [x] Add Font/Image optimization (Portfolio)
- [x] Add auth middleware and create logout route (Note-taking app)

- [Portfolio (Link to issue)](https://github.com/kelvinsanchez15/portfolio/issues/5)
- [A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/4f6a346d10fc9943aacf0ef278c5308247b5856b)

### R2D3
- [x] Hide sensitive data on queries (Note-taking app)
- [x] Create all routes for notes
- [x] Add middleware to delete notes references on user deletion
- [x] Add support for sort, pagination and filter
- [x] Deploy and test API

[A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/dc6075ae119adddf9b2660d799757ac0686e4f15)

### R2D4
- [x] 5 Kyu "Pick peaks" kata at codewars
- [x] Add lazy loading support (Portfolio)
- [x] Improve accessibility by making changes to color contrast

[Portfolio (Link to commit)](https://github.com/kelvinsanchez15/portfolio/commit/746eaa96163d81f4f38cd269b559242fd5ddb400)

### R2D5
One day of fighting hard against Auth in NextJS, I managed to add a JWT token on cookies when logging in but I'm not sure how to query the API with that cookie.

[A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/d119c738391ca9548955b1bc6183d43d1f5da23f)

### R2D6
I was able to identify my note app issue, SWR keeps making request to the API and it returns 401 errors, but I don't want them to appear in the console, I would like to handle them on my own. Redirecting the user to /login for example.

[A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/22808b83ba39fbb48d86e791738439c599f4e133)

### R2D7
Today I made good progress in "Bulletproof Next", an excellent NextJS course by @arunoda
Now I have more clear the differences between Server Side Rendering and Static Generation.

### R2D8
- [x] Update login page
- [x] Crate SWR custom hook to fetch user notes
- [x] Make sign up page
- [x] Add form and post logic to index page

[A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/1ce564eb08e9cfe94cfba1c61ccdd27a0be7d8a4)

### R2D9
I worked on the front end of my note-taking app, made some changes to the API, and narrowed the scope of the project.
It is already taking shape!

![image](https://user-images.githubusercontent.com/4708484/95928335-18a6c880-0d8f-11eb-9820-377c003c3b5c.png)

[A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/1ce564eb08e9cfe94cfba1c61ccdd27a0be7d8a4)

### R2D10
- [x] Create temporal note IDs with uuid library
- [x] Implement optimistic updates on new note creation
- [x] Add divider between notes
- [x] Add relative time support with date-fns library
- [x] Fix margin/padding issue on new note input 

[A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/17362b678221fb2415fc98278fc98dfdbce55518)

### R2D11
Today I learned how to use Cloudinary to handle image upload with serverless functions, I also did a bit of work in terms of the profile page.
I also did a little work on the profile page.

![anote1](https://user-images.githubusercontent.com/4708484/96195608-2ee18f80-0f1b-11eb-8e77-29005c670305.jpg)

[A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/6bec8dda9902ca62b400d2ecc1d211dce960a679)

### R2D12
- [x] Code refactor and format fixes
- [x] Add skeleton layout on note loading
- [x] Revamp signin/signup pages
- [x] Customize theme colors

[A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/8def05e0e396bb84e7748494b5c3e00deea02ce9)

### R2D13
I made some changes and refactor to my note app code, but then I took the day to rest.

When my eyes start to feel tired I force myself to do so.

### R2D14
- [x] Implemented optimistic updates on note patch and delete (with error handling and rollbacks)
- [x] Minor style changes
- [x] Good progress in the user profile section

[A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/b0d06ac81e3d965d0936cac4c7e0319de10703d5)

### R2D15
Yesterday was a tough day and I couldn't code much but today I fought hard with the profile page and made a lot of progress.

React forms are not laughing matter.

[A-note (Link to commit)](https://github.com/kelvinsanchez15/a-note/commit/daa4bd0af999cda82abb665db7a0b669126f68d8)

### R2D16
Today I celebrated my birthday with my family and loved ones, however I used part of the day to study PostgreSQL basics and finally upgrade my old reliable Windows 7 to Windows 10.

### R2D17
My JAMStack note taking app is completed!

Main features:
- [x] Optimistic UI
- [x] Serveless API routes
- [x] JWT Authentication

![a-note Device Mashup](https://user-images.githubusercontent.com/4708484/97116897-bdea6680-16d6-11eb-8f0e-1335fb83be4b.jpg)

[A-note (Link to release)](https://a-note.vercel.app/)

### R2D18 
- [x] Update A-Note readme file
- [x] Add A-Note project info and thumbnail to portfolio
- [x] Update navbar and hero section of portfolio

[Portfolio (Link to commit)](https://github.com/kelvinsanchez15/portfolio/commit/f8234ceda650198965bd9205c5a1e54dd2c49c31)

### R2D19
Invested the day watching the Nextjs conf and migrated my portfolio to Next v10 without problems, gaining access to analytics and new features that I plan to test in the following days.

[Portfolio (Link to commit)](https://github.com/kelvinsanchez15/portfolio/commit/68a7d913be2b8a5778276859889335ae99d38f65)

### R2D20
Today I did some tests putting together NextJS, Prisma, Postgres and NextAuth.

I need to read Prisma documentation more calmly, so that will be tomorrow task.

### R2D21
I kept working on PostgreSQL basics.

So much to avoid doing my own migrations, but at the end Prisma "forced" me to do it because there's a bug on cascade deletions.

### R2D22
I followed the first hour of the PostgreSQL tutorial from @AmigosCode I plan to continue tomorrow.

Also designed a basic schema with users/post/comments relations to practice CRUD operations.

### R2D23
- [x] PostgreSQL lessons
- [x] Set custom .env variable config for Prisma
- [x] Deploy of CRUD example on Vercel

At the end of the day I had a problem with a serverless function, I spent a lot of time looking for a solution. Turns out the function was fine, I was fetching 'localhost'.

### R2D24
I was able to perform some tasks, but got really tired fixing a problem with an 'undeletable' folder. 

After an intense search I found that it was a VS Code extension that generated the problem.

I opened an issue in case it might be of help to others.

### R2D25
I finished doing integration tests with Prisma and started working on my next portfolio project.

I'm glad to know that the issue I reported yesterday was fixed today and helped at least one person.

### R2D26
- [x] Set basic boilerplate 
- [x] Create custom MUI dark theme
- [x] Make components for: Main navbar, Project navbar, Filters, Issues subheader & Issues list

I am revisiting my Issue Tracker project, this time I will use React and implement new features.

I decided to start with the front-end this time using a JSON response from GitHub API as dummy data.

### R2D27
- [x] Start working in database model
- [x] Add and set Prisma + Next-Auth
- [x] Create withSession HOC
- [x] Update navbar to use OAuth data

### R2D28
1. Add new SQL migration
2. Create API endpoints
3. Test it
4. Repeat

That was my loop today. (Also the usual googling about multifield unique indexes and many to many relations)

### R2D29
I've been doing stunts with NextJS's "catch all" API routes to get all the endpoints I need. I couldn't code in the afternoon because a power outage in my area.

### R2D30
Did an hour of coding and then took the day off to rest and read the recently released Dawnshard novella by Brandon Sanderson. I'm currently halfway there, but I'm loving it so far.

### R2D31
Successful created my first PostgreSQL trigger, I needed a parent based 'number' field and a trigger turned out to be a good fit. Also did some work on a database seeder to ease endpoint testing.

### R2D32
- [x] Create user page with profile and repos components
- [x] Make issue/labels m-n relation implicit
- [x] Update issuesList component with database data
- [x] Create main issues page

### R2D33 
I spent half day away from home renewing my ID, but after that I worked creating filters and sorters for my Issue Tracker.

### R2D34
I woke up feeling sick with the flu, however I made good progress on an Issue Sorter dropdown component for my project.

### R2D35
I took yesterday to rest and woke up a little better.

Today I worked on the pagination implementation for my Issue Tracker. 

In the near future I have to refactor the code block where I query my database (It became a monster).

### R2D36
Completed the remaining dropdowns and started working on "POST" pages.
I'm struggling with NextAuth because I couldn't find a good way to mutate the session object without refreshing the page or regaining focus 

### R2D37
Today I received a freelancer job proposal to make a website that serves as a portfolio for architects and designers, the detail is that the client wants me to use Wordpress

### R2D38
- [x] Add Google OAuth provider
- [x] Create custom sign in page
- [x] Deploy to vercel for production testing
- [x] Add linear progress bar between pages
- [x] Create New Repo form page

### R2D39 
Lite coding day, just did a refactor to some endpoints with a session middleware and created a "new issue" form page.

### R2D40
Invested my time migrating some server side rendered pages to use NextJS incremental static regeneration, on static pages you can't access query parameters so I'm using SSR on those who need it.

### R2D41
I made good progress on the components for individual issues, also created an endpoint to be able to do patch and delete actions.

### R2D42
Today I was working on a new logo for a friend's business, as for coding I spent a while making the editable components for my Issue Tracker.

### R2D43
Back to the challenge!, despite not keeping a record I kept working on my side projects. I also started collaborating in the spanish translation of FreeCodeCamp and today translated my first article (awaiting revision).

### R2D44
- [x] Update navbar component
- [x] Make navbar responsive
- [x] Add menu drawer component for smaller devices
- [x] Translate and move to revision another FCC article.

### R2D45
- [x] Remove placeholder icons for unimplemented features
- [x] Update stargazers endpoint
- [x] Add repo star/unstar frontend feature
- [x] Bump MUI and ESLint dependencies to most recent version

### R2D46
Invested some time making an util function to get dynamic styles on labels, using a hex color as input and returning color props for background, text, and border.

### R2D47
Spend the day working on a page responsive layout, making style changes at different breakpoints and several small adjustments.

### R2D48
- [x] Bump some dependencies
- [x] Use NextJS Image component to optimize avatar images
- [x] Fix 'UL' childrens on a list for better screen reader support
- [x] Rename duplicate aria-ids
- [x] Add missing aria-label on some icon buttons

### R2D49
Today I made my first PR to my favorite component library: Material UI, it will improve the integration with Next.js. 

### R2D50
I got some great news, my PR was merged into Material UI and my first two translated articles were published on freeCodeCamp.

PR: https://github.com/mui-org/material-ui/pull/24121

Articles:
- [JavaScript Moderno – Imports, Exports, Let, Const, y Promesas en ES6+](https://www.freecodecamp.org/espanol/news/aprende-javascript-imports-exports-let-const-promisas-es6/
)
- [Encadenamiento Opcional en JavaScript `?.` Explicado - Cómo Funciona y Cuándo Usarlo](https://www.freecodecamp.org/espanol/news/encadenamiento-opcional-en-javascript-explicado/)

### R2D51
- [x] Add markdown support for Issue details and comments
- [x] Use custom syntax highlighter
- [x] Create Link render component to style markdown urls

### R2D52
- [x] Upgrade individual issues grid layout
- [x] Add labels to issue header
- [x] Fix vertically center header action
- [x] Adjust avatar sizes and card header padding

### R2D53
Today I made progress on an original article, fixed some bugs in my Issue Tracker, and added missing features.

### R2D54
I invested the day adding i18n support to my personal portfolio, with Spanish and English which are the languages I currently speak. I'm pretty happy with the results.

### R2D55
I added a Blog section to my portfolio with some articles that I've been translating and writing for @freecodecampES. In the future I want to automate the data fetching process.

### R2D56
- [x] Create lint and format scripts
- [x] Automate pre-commit hooks with Husky
- [x] Change card HTML element from 'div' to 'article'
- [x] Refactor mail API function

### R2D57
I've testing Tailwind CSS for the first time by making a Landing Page, so far I like how intuitive its API is and how fast you can make fully custom desings.

### R2D58
I had a job interview yesterday for a Front End position, It was a pretty good experience and it felt very natural. I just need to wait for results (there are several steps).

### R2D59
I stopped updating my #100DaysOfCode progress recently because I've been working only on translations, but those translation are code related. So... I'm safe right? Just going over the basics.

### R2D60
- [x] Bump dependencies and test
- [x] Closed fixed issues
- [x] Meet with translators and QA
- [x] Add missing translations after merged PR
- [x] Proofreading

### R2D61
I've been preparing for an interview and combining content review with proofreading work is helping me a lot.

### R2D62
- [x] Review CSS selectors
- [x] Review JavaScript and DOM
- [x] Approve HTML, CSS and JS practical exam
- [x] Translation and proofreading work (big surprise coming soon)

### R2D63
After two days of hard work I finished migrating my portfolio to typescript, I learned a lot in the process and I know it will help me in future projects.

### R2D64
I decide to work on some Frontend Mentor challenges to get more practice with Tailwind and Typescript.  
- [x] Set basic boilerplate
- [x] Create basic layout
- [x] Create Card and Header component
- [ ] Create Filter component
- [ ] Make layout responsive

### R2D65
I spent half morning translating the basic JavaScript section of the FCC curriculum, after that I finished the Frontend Mentor challenge.

I need to do some corrections here and there, but it already looks good to me.


