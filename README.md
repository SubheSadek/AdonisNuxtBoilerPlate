AdonisNuxtBoilerPlate
AdonisNuxtBoilerPlate is a startup project that provides a clean and maintainable code base for building large-scale applications with both an admin panel and app API. This boilerplate uses Adonis.js as the back-end framework and Nuxt.js for front-end development.

Installation
To get started with AdonisNuxtBoilerPlate, you'll need to have the following software installed on your machine:

Node.js (version 12 or higher)
npm or yarn package manager
Once you have these dependencies installed, follow these steps:

Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/username/AdonisNuxtBoilerPlate.git
Navigate to the project directory:

bash
Copy code
cd AdonisNuxtBoilerPlate
Install the dependencies:

Copy code
npm install
or

Copy code
yarn install
Create a copy of the .env.example file and name it .env. Update the file with your environment-specific configuration.

Migrate the database:

Copy code
adonis migration:run
Start the development server:

css
Copy code
adonis serve --dev
Open a new terminal tab and navigate to the client directory:

bash
Copy code
cd client
Install the dependencies:

Copy code
npm install
or

Copy code
yarn install
Start the client development server:

Copy code
npm run dev
or

Copy code
yarn dev
That's it! AdonisNuxtBoilerPlate is now set up and ready to use.

Deployment
To deploy AdonisNuxtBoilerPlate to a production environment, you'll need to follow these steps:

Build the client code:

Copy code
npm run build
or

Copy code
yarn build
Start the server:

makefile
Copy code
NODE_ENV=production adonis serve
