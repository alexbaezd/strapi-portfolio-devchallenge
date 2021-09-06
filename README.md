# Strapi application for Porfolio Site (DevChallenges.io)

![Demo](https://github.com/alexbaezd/portfolio-devchallenge/blob/main/portfolio-demo.jpg)

[Portfolio Site](https://github.com/alexbaezd/portfolio-devchallenge)

## Quick start

1.  **Clone a Strapi application**

    ```shell
    # Clone repository and install dependencies
    git clone https://github.com/alexbaezd/strapi-portfolio-devchallenge.git

    cd strapi-portfolio-devchallenge

    npm install
    ```
    
1.  **Open the source code and start editing!**
    
    Create a `.env` file and add 
 
    ```
      CLOUDINARY_NAME=XXXXXXXXXXXX 
      CLOUDINARY_KEY=YYYYYYYYYYYYYY
      CLOUDINARY_SECRET=ZZZZZZZZZZZZZZZZZZ
    ```
 
    Sign up for free on https://cloudinary.com/ and your Dashboard copy your API Key, Secret, etc.

1.  **Start developing.**
  
    ```shell
     yarn develop
     
     npm run develop
    ```
 Your Strapi application is now running at `http://localhost:1337/admin`


*After registration should add some information for the post, projects, your skills, etc.*

*Edit Permissions* 

Settings/Roles(USERS & PERMISSIONS PLUGIN)/public

Check **find and findone** for each application's actions (Blog, Projects, etc).

## Acknowledgements

- [Strapi: Quick Start Guide](https://strapi.io/documentation/developer-docs/latest/getting-started/quick-start.html)
- [Build a static blog with Gatsby and Strapi](https://strapi.io/blog/build-a-static-blog-with-gatsby-and-strapi)

## Deploy

- [Heroku](https://strapi.io/documentation/developer-docs/latest/setup-deployment-guides/deployment/hosting-guides/heroku.html)
