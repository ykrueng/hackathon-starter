Arundo Women's 2019 Hackathon Starter Kit

# Requirements
- [Node (current, v10+)](https://nodejs.org/en/download/current/)
- [Yarn](https://yarnpkg.com/lang/en/docs/install/#mac-stable)

# Installation
1. Fork this repo
2. Clone/download your forked repo locally
3. Run the following (within the repo):
```
yarn
yarn dev
```

# Getting Started
- For client side, effective entry point is `src/client/components/App.jsx`
- For server side, effective entry point is `src/server/index.js`

# Example API & Data source (Nest thermostat)
```js
http://localhost:3000/api/thermostat?startDate=2016/11/01&endDate=2016/11/02

# raw data.csv & data.json are located in /src/server/data
```
