# Setup

dotenv

- create bcryptjs

```
npm install bcryptjs
```

- create dotenv

```
npm install dotenv
```

- create uuid

```
npm install uuid
```

- create database

```
createdb recovery-site
```

- install dependencies

```
npm install && cd client && npm install
```

- start server in root directory of repository

```
npm run start:dev
```

- start vite server in client directory

```
npm run dev
```

# to test deployment

```
cd client && npm run build
```

browse to localhost:3000 (or whatever server port you used)

# to deploy

- build script for deploy

```
npm install && cd client && npm run build

```

- start script for deploy

```
node server/index.js

```

- environment variables for deploy

```
JWT for jwt secret
DATABASE_URL for postgres database
```

- environment variables for deployed site
