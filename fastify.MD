
- Using Fasify for mock server 

```
npm add fastify fastify-cli

```

generate fasify folder project 

```
npx fastify generate . --esm
npm install  --> instal dependency
```

- install cors 

```
 npm install @fastify/cors

import cors from '@fastify/cors'

fastify.register(cors)

```

createing route

```
Now we have a pattern for a route that responds with any mock data we like. First, create a folder in routes with an index.js file. The folder name will determine the top-level path of the route. The index.js file should contain the following:

use strict";

export default async function (fastify) {
  fastify.get("/", async function (request, reply) {{
    return {DATA HERE};{
  });{
}

```

```npm run dev```