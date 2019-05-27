## For whit projet, we used Reacstrap 

Adding Bootstrap
Install reactstrap and Bootstrap from NPM. Reactstrap does not include Bootstrap CSS so this needs to be installed as well:

npm install --save bootstrap
npm install --save reactstrap react react-dom

Import Bootstrap CSS in the src/index.js file:

import 'bootstrap/dist/css/bootstrap.css';

Import required reactstrap components within src/App.js file or your custom component files:

import { Button } from 'reactstrap';

## We used AXIOS

Adding Axios:

npm install axios
