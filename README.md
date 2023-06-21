## Setup

1. Install the dependencies
```
npm i -D eslint @bonnasys/valhalla-eslint-configuration-frontend
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@bonnasys/valhalla-eslint-configuration-frontend/react"
  // "extends": "@bonnasys/valhalla-eslint-configuration-frontend/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
