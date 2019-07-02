This project was bootstrapped with [Create React App] (https://github.com/facebook/create-react-app).

## Available Scripts

Este projeto foi desenvolvido seguindo as Lives do DevPleno React.js

https://www.devpleno.com/devreactjs/

### `npm instal`

 Depois de clonar o repositorio, voce deve instalar as dependecias necessarias.

 Em seuida voce deve alterar o arquivo FireBaseConfig.js com os dados de acesso do seu banco de dados no Fire.
 https://firebase.google.com/docs/web/setup

 Clique em Copiar e cole o snippet do código no HTML do seu aplicativo. O snippet deve ter esta aparência:

<script src="https://www.gstatic.com/firebasejs/5.7.1/firebase.js"></script>
<script>
  // Initialize Firebase
  // TODO: Replace with your project's customized code snippet
  var config = {
    apiKey: "<API_KEY>",
    authDomain: "<PROJECT_ID>.firebaseapp.com",
    databaseURL: "https://<DATABASE_NAME>.firebaseio.com",
    projectId: "<PROJECT_ID>",
    storageBucket: "<BUCKET>.appspot.com",
    messagingSenderId: "<SENDER_ID>",
  };
  firebase.initializeApp(config);
</script>


### `npm start`

Em seguida roda o start.




