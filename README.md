<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alexgram</title>
    <style>
        body {text-align: center; background-color: rgb(136, 91, 7); color: black;}

    </style>
</head>
<body>
    <header>
        <img src="Alexgram_Banner.png" alt="banner">
    </header>
	<script type="module">
  		// Import the functions you need from the SDKs you need
  		import { initializeApp } from "https://www.gstatic.com/firebasejs/10.4.0/firebase-app.js";
  		import { getAnalytics } from "https://www.gstatic.com/firebasejs/10.4.0/firebase-analytics.js";
        import {
            getAuth,
            createUserWithEmailAndPassword,
            signInWithEmailAndPassword,
            onAuthStateChanged,
            signOut
        } from "https://www.gstatic.com/firebasejs/10.4.0/firebase-auth.js";
  		// TODO: Add SDKs for Firebase products that you want to use
  		// https://firebase.google.com/docs/web/setup#available-libraries

  		// Your web app's Firebase configuration
 		 // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  		const firebaseConfig = {
    	    apiKey: "AIzaSyD-BZJg0eBUKsvCgj6FvQ8U4yImGpUvOak",
    	    authDomain: "profileapp-eca7d.firebaseapp.com",
    	    databaseURL: "https://profileapp-eca7d-default-rtdb.firebaseio.com",
    	    projectId: "profileapp-eca7d",
    	    storageBucket: "profileapp-eca7d.appspot.com",
    	    messagingSenderId: "401711441810",
    	    appId: "1:401711441810:web:deb06a3c47633573d9c34b",
    	    measurementId: "G-D8VKHEEYX6"
  		};

  		// Initialize Firebase
  		const app = initializeApp(firebaseConfig);
  		const analytics = getAnalytics(app);
        const auth = getAuth(app);
        <iframe src="https://x.thunkable.com/projectPage/6509ce53a0b8d4619e46e2aa"></iframe>


	</script>
    
</body>
</html>
