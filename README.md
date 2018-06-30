# Firebase CRUD as simple todo list with HTML and JQuery/Javscript

This is example of To-Do list using FirebaseDataBase and Jqury, Html, Basically CRUD operation in firebase and HTML,JQuery. You can Add , Edit, Update and Delete To-Do

# Prerequisites

You need to have firebase Account.
* Login to gmail.
* Go to firebase console.
* Create New Project.
* Go to Database in Develop .
* Click on "Get Started" with Realtime Database Start in Test Mode.

# To Run
 
### You need to Clone Or Download zip of this code.

### Need to replace two things in todo.html

Open Your Project You created with DB and go to Overview. Click on "Add Firebase to your web app" You will get code snippet look like below

```
<script src="https://www.gstatic.com/firebasejs/5.0.4/firebase.js"></script>
<script>
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
```
now you have to replace your own code snippet in todo.html and you are good to go :tada:

it would not work if you don't change code snippet add real one.

### If you have done all above changes then just open todo.html in bowser and it's up and Runing you can now add, update and delete ToDo.

:star2:
