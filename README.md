# Zerops + Next.js

![Header Image](public/ZeropsNextjs.png)

A Node.js Next.js example for Zerops

**Features**

- Next.js 14 (App Router)

## Import 

```yaml
project:
  name: recipe-nextjs

services:
  - hostname: app
    type: nodejs@20
    buildFromGit: https://github.com/fxck/zerops-nextjs-nodejs
    enableSubdomainAccess: true
```
