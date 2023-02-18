AdonisNuxtBoilerPlate
AdonisNuxtBoilerPlate is a startup project that provides a clean and maintainable code base for building large-scale applications with both an admin panel and app API. This boilerplate uses Adonis.js as the back-end framework and Nuxt.js for front-end development.

Installation
To get started with AdonisNuxtBoilerPlate, you'll need to have the following software installed on your machine:

Node.js (version 12 or higher)
npm or yarn package manager
Once you have these dependencies installed, follow these steps:

1. Clone the repository to your local machine:
git clone https://github.com/username/AdonisNuxtBoilerPlate.git
Navigate to the project directory:

2. cd AdonisNuxtBoilerPlate
Install the dependencies:

3. npm install
or
yarn install
Create a copy of the .env.example file and name it .env. Update the file with your environment-specific configuration.

4. Migrate the database:
adonis migration:run
Start the development server:

5. css
adonis serve --dev
Open a new terminal tab and navigate to the client directory:

6. cd client
Install the dependencies:

7. npm install
or
yarn install
Start the client development server:

9. npm run dev
or
yarn dev

That's it! AdonisNuxtBoilerPlate is now set up and ready to use.

Deployment
To deploy AdonisNuxtBoilerPlate to a production environment, you'll need to follow these steps:

Build the client code:

npm run build
or

Copy code
yarn build
Start the server:

makefile
NODE_ENV=production adonis serve
