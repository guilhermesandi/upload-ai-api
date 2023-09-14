<h1 align="center">upload.ai API</h1>

<div align="center">

[![Linkedin Badge](https://img.shields.io/badge/-Guilherme%20Sandi-292929?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/guilhermesandi/)](https://www.linkedin.com/in/guilhermesandi/)

</div>

<br>

## ✨ Technologies

-   [ ] NodeJS
-   [ ] Typescript
-   [ ] Prisma
-   [ ] Fastify
-   [ ] OpenAI API
-   [ ] Zod
-   [ ] Vercel AI SDK

## 🚀 How to use

```sh
# Clone this repository
git clone https://github.com/guilhermesandi/upload-ai-api

# Go to the root directory of the repository
cd upload-ai-api

# Install the dependencies
npm install

# Fill the .env using .env.example as an example
DATABASE_URL="file:./dev.db"
OPENAI_KEY="yourOpenAIKey"

# Feed the database
npm prisma db seed

# Start the application
npm run dev

# Show database
npm prisma studio
```

Use ```routes.http``` file to send requests (You need to install REST Client extension)
