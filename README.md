# E-commerce project

This project is a work in progress and the latest version is deployed [here](https://nextjs-shop-kal-kalhollywood.vercel.app/) using Vercel. It is based on the teachings from [this tutorial](https://www.youtube.com/watch?v=4mOkFXyxfsU&ab_channel=JavaScriptMastery). I chose this project as an opportunity to learn about and use NextJS, Stripe, Sanity and Vercel - none of which I had used previously.

## Key Learnings

- As a headless CMS, Sanity can be used to create a backend database and content management system and you can set up the schema as a JS object.
- You can set up JS files in square brackets [] to have them be dynamically rendered - as with the product slug file in this project. Libraries such as React Router was not required.
- Learned how to use getServerSideProps, getStaticProps and getStaticPaths
- Managing React states using React Context - using useStateContext all over the site to tap into cart items, total price and total quantities.
- Setting up and utilising Stripe for working payment system.
- Deployment with Vercel.
