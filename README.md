# BloggingCoder - MERN Full Stack APP

Getting started
You can view a live demo over at _____________________

To get the frontend running locally:

Clone this repo
npm install to install all dependencies
npm run dev to start the local server

This is a multi-user blogging platform built with Node, React, Next.js, Express, and MongoDB.

The general page breakdown looks like this:

Home page (URL: /)
List of tags
List of articles pulled from either Feed, Global, or by Tag
Pagination for list of articles
Sign in/Sign up pages (URL: /user/login, /user/register)
Use JWT (store the token in localStorage)
Settings page (URL: /user/settings )
Editor page to create/edit articles (URL: /editor/new, /editor/article-slug-here)
Article page (URL: /article/article-slug-here)
Delete article button (only shown to article's author)
Render markdown from server client side
Comments section at bottom of page
Delete comment button (only shown to comment's author)
Profile page (URL: /profile/username-here, /profile/username-here?favorite=true)
Show basic user info
List of articles populated from author's created articles or author's favorited articles

## Project Description

- User Signup / Signin
- JWT based Authentication System
- Account Activation on User Signup
- Role Based Authorization System
- Perform CRUD (Create, Read, Edit or Remove Blogs) Operations from Admin Dasboard or User Dasboard
- Admin can Add or Remove 'categories' and 'tags'
- Advanced CRUD with Image Upload
- Ability to Search for Blogs and Load more Blogs
- SEO - Search Engine Optimization
- API Development with Node Express and MongoDB
- SSR provided by Next.js
- Blog Author Private Contact Form
- Multiple User Authorization System
- Sendgrid for Sending Emails
- Forgot Password / Reset Password
- Social Login with Google
- DISQUS Commenting System
- Deployed on DigitalOcean

## Tools Used

- [React](https://reactjs.org/) - The front end is powered by React for state management and dynamic rendering.
- [Next.js](https://nextjs.org/) - for SSR (server-side rendering), statically generated pages and SEO.
- [ Node.js](https://nodejs.org/en/) and [Express.js](https://expressjs.com/) - for building the server and interacting with the database.
- [MongoDB](https://www.mongodb.com/) - a schema-less NoSQL database.
- [Mongooose](https://mongoosejs.com/) - the object document modeling (ODM) layer that sits on top of Node's MongoDB driver.
- [DigitalOcean](https://www.digitalocean.com/) - as the deployment platform of choice.

## Demo

- [View Project](______________)
