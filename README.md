# mavo-firebase

A Firebase storage backend for Mavo 

# Getting started 

## Sign up for Firebase

<script src="https://www.gstatic.com/firebasejs/3.9.0/firebase.js"></script>
<script>
  // Initialize Firebase
  var config = {
    apiKey: "AIzaSyA7D6JCbW2yrTL6joQ39Tu6LEpkQ4hVyTM",
    authDomain: "testy-a027b.firebaseapp.com",
    databaseURL: "https://testy-a027b.firebaseio.com",
    projectId: "testy-a027b",
    storageBucket: "testy-a027b.appspot.com",
    messagingSenderId: "733501275641"
  };
  firebase.initializeApp(config);
</script>

## How to use

Use the Firebase plugin by including the ```mv-storage``` attribute with the parameter ```firebase```. 

## Example 

```javascript
<section mv-app="firebasetest" mv-storage="firebase">
  <table>
    <tr>
      <td>
        <ul>
          <li property="country" mv-multiple>
            <span property="code">Code</span>
            <span property="name">Name</span>
          </li>
        </ul>
       </td>
    </tr>
  </table>
</section>
```


