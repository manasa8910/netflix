
# Assignment 1 - Netflix 





## 🔗 Links
[Git hub repo link](https://github.com/manasa8910/netflix)

[Hoisted link](https://manasa8910.github.io/netflix/)


## HTML

### Please refer the index.html file in the github repo


#### the final webpage of the netflix landing page

![image](https://github.com/manasa8910/netflix/assets/67619299/f5008522-32bd-4cf6-9b72-d4acc374573b)

The head part of html contains the title and css style tag

```bash
<head>
    <title>Netflix | India</title>
    <style>
      body {
        margin: 0;
        background: url("https://assets.nflxext.com/ffe/siteui/vlv3/8f12b4f0-a894-4d5b-9c36-5ba391c63fbe/44355e66-dbf8-4dd8-ba6b-8e9e32ec6abd/IN-en-20230320-popsignuptwoweeks-perspective_alpha_website_large.jpg");
      }
      #heading {
        height: 20%;
        display: flex;
      }

      h1 {
        font-size: 55px;
        margin: 0;
      }

      #shadow {
        background: rgba(0, 0, 0, 0.7);
        height: 100vh;
      }

      #image {
        width: 40%;
        display: flex;
        justify-content: center;
        padding: 30px;
      }
      #buttons {
        padding: 30px;
        width: 60%;
        text-align: right;
      }

      #main {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        color: white;
        height: 80%;
      }
      #signin {
        background: red;
        padding: 8px 14px;
        border: none;
        color: white;
        font-size: 15px;
        border-radius: 5px;
        font-weight: bold;
      }
      p {
        margin: 13px;
        font-weight: 400;
      }
      #p1 {
        font-size: 28px;
      }
      #p2 {
        font-size: 23px;
      }
    </style>
```

The body contains basic structure of html and classes corresponding to the css styles

```bash
 <body>
    <div id="shadow">
      <div id="heading">
        <div id="image">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/Netflix_2015_logo.svg/2560px-Netflix_2015_logo.svg.png"
            width="150"
            height="50"
          />
        </div>
        <div id="buttons">
          <button id="signin">Sign In</button>&nbsp;&nbsp;&nbsp;
          <button id="signin">Register</button>
        </div>
      </div>

      <div id="main">
        <h1>Unlimited movies, TV shows and more.</h1>
        <p id="p1">Watch anywhere. Cancel anytime.</p>
        <p id="p2">
          Ready to watch? Enter your email to create or restart your membership.
        </p>
      </div>
    </div>
  </body>
```
