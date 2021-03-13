# CORS problem 

### Description

Access to XMLHttpRequest at 'https://judao.hans.systems/COMP4537/personal_project/fetchQuestionsFromDB' 
from origin 'http://judao.hans.systems' has been blocked by CORS policy:
No 'Access-Control-Allow-Origin' header is present on the requested resource.

### Solving

#### Using express:

Install cors module and app.use it

#### Using http:

`npm install cors`

```js
const cors = require('cors')

const app = express()

// allow cors
app.use(cors())
```

