
# Building my own personal site (Full-stack app)

## Stack
Why Serverless?

[Using ExpressJS & NextJS](https://vercel.com/guides/using-express-with-vercel)

## Initialization

1. Initializing the project with ``npx create-next-app@latest --typescript`` so I don't have to build package.json from scratch...
2. Install ExpressJS ``pnpm i express dotenv``
3. Setup NextJS


## First run

1. Configuring Express.js server to start
   - Copy & Paste your usual starter code to server.ts.
   - add -dev dependency for `"ts-node-dev": "^2.0.0"`
   - Finally, add runnable to `package.json`:  ``"server": "ts-node-dev src/server.ts",`` 
   
2. Setup MongoDB 
    - Create a MongoDB Client in `/services/MongoClient.ts`
    - 
3. Run Next.js frontend