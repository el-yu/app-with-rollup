# App setup with Rollup

## Technologies

- React
- Typescript
- SASS
- Prettier
- Rollup

## Usage
This app is not published as an npm module. 
The steps below is just a way to test that app-with-rollup is bundled correctly.

#### 1. Run build
``` 
npm run build 
```

#### 2. Open an existing React project (e.g. my-project)

#### 3. Copy the *dist* folder from app-with-rollup

#### 4. Paste it to the *node_modules* folder of my-project

#### 5. Use the library and run your app

Example:
```
import React from "react";
import ReactDOM from "react-dom";
import { Home } from 'dist'

ReactDOM.render(<Home />, document.getElementById("root"));
```

