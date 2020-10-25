# #100DaysOfCode Log - Round 2 - [Kelvin Sánchez]

The log of my #100DaysOfCode challenge. Started on [October 05, Monday, 2020].

## Objectives / Tasks
- [ ] Apply for jobs
- [ ] Train and prepare for jobs interviews 
- [ ] Try freelancing
- [ ] Build strong projects for my portfolio
- [ ] Improve projects README file
- [ ] Connect with people / Join more coding communities
- [ ] Make Open Source contributions
- [ ] Learn PostgreSQL
- [ ] Start using TypeScript
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

### R2D17: #100DaysOfCode 
My JAMStack note taking app is completed!

Main features:
- [x] Optimistic UI
- [x] Serveless API routes
- [x] JWT Authentication

![a-note Device Mashup](https://user-images.githubusercontent.com/4708484/97116897-bdea6680-16d6-11eb-8f0e-1335fb83be4b.jpg)

[A-note (Link to release)](https://a-note.vercel.app/)






