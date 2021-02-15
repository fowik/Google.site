<html dir="ltr" lang="ru">
  <head>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
    <meta charset="utf-8">
    <title>New tab</title>
    <style>
        html {
            height: 100%;
            width: 100%;
        }
        body {
            background-color: #00000000; /* Цвет фона */
            background: #000000;
            margin: 0;
            color: #ffffffff; /* Цвет текста */
        }
        .image-wrap {
          width: 1500px;
          height: 150px;
          border: 0px solid white;
        }
       .image-wrap2 {
          width: 1500px;
          height: 565px;
          border: 0px solid white;
        }
        .header {
          width: 1500;
          height: 40px;
          border: 2px solid white;
        }
        .image-center{
          display: block;
          margin: auto;
          size: 300px;
        }
        .image-align{
          text-align: center;
        }
        .image-flex{
          display: flex;
          align-items: center;
          justify-content: center;
        }
        input::-webkit-input-placeholder {
          color: #9aa0a6; 
          background: #FFFFFF;
        }
        input:-moz-placeholder {
          color: #9aa0a6; 
          background: #FFFFFF;
        }
        input:-ms-input-placeholder {
          color: color: #9aa0a6; 
          background: #FFFFFF;
        }
        * {box-sizing: border-box;}
        form {
          width: auto;
          margin-right: 30px;
          text-align: bottom;
        }
        input {
          width: 450px;
          height: 42px;
          padding-left: 50px;
          border-radius: 42px;
          border: none;
          background: #FFFFFF;
          outline: none;
          position: relative;
          transition: .0s linear;
        }
        .d7 button {
          width: 42px;
          height: 42px;
          background: none;
          border: none;
          position: absolute;
          top: 322px;
          left: 700px;
        }
        .d7 button:before{
          content: "\f002";
          font-family: FontAwesome;
          color: #9aa0a6;
        }
        a{
          color:#FFFFFF;
          text-decoration:none
        }
        .links-right{
          right:200px;
        }
        {box-sizing: 
          border-box;
          }
        .links-right{
          right: 0px;
        }
        .links-right{
          display: block;
          text-align: right;
        }
        .table {
          display: table; 
          text-align: right;
          }
        .row { 
          display: table-row;
          text-align: right;
          }
        .cell { 
          display: table-cell; 
          text-align: right;
          }
        .navbar {
          text-align: right;
          width: 100%;
        }
        .navbar ul {
          display:inline-block;
        }
        .navbar li {
          float: left;
        }
        .navbar li + li {
           margin-left:10px;
        }
        ul {
          list-style-type: 
          none;
        }
        .center-img {
          display: block;
          margin: 0 auto;
        }
        .s1{
          margin-top:3px;
          color:#9aa0a6;
          height:20px;
          width:20px
        }
        .s2{
          display:inline-block;
          fill:currentColor;
          line-height:24px;
          position:relative;
        }
        .button-settings-right{
          text-align: right;
        }
        .buttons {
          background-color: #FFFFFF;
          border: none;
          color: solid gray;
          padding: 10px;
          text-decoration: none;
          display: inline-block;
          font-size: 14px;
          margin: -8px;
          align="right"
          }
        .buttons1{
          border-radius:24px;
        }
        .button-background{
          background: none;
          border: none;
        }
        .buttons2 {
          background-color: #FFFFFF;
          border: none;
          color: solid gray;
          padding: 5px;
          text-decoration: none;
          display: inline-block;
          font-size: 14px;
          margin: -8px;
          align="right"
          }
        button{
          border: none;
          background: #FFFFFF;
        }
        .button3{
          background: none;
          width: auto;
          height: auto;
        }
        .footer {
          background: #f2f2f2;
          box-sizing: border-box;
          width: auto;
        }
    </style>
  </head>
  <body>
  <div id= "navbar" class = "navbar flex flex-vertical-center">
    <ul>
      <li class = "navitem"><a href = "#" right>Mail</a></li>
      <li class = "navitem"><a href = "#" right>Images</a></li>
      <li class = "navitem"><button type = "submit" class = "button3"><img src="https://sun9-70.userapi.com/impf/wBsedVGDJYdDuAniYRZ6O8ooMIoI-PvDC23yPw/9HWsA52XWhk.jpg?size=18x18&quality=96&proxy=1&sign=48f07e317009075213891babaa593463&type=album"></button></li>
      <li class = "navitem"><div class = "buttons2 buttons1"><button type = "submit">Sign in</button></div></li>
    </ul>
  </div>
  <div id = "main" class = "image-wrap" >
  </div>
  <p>
    <img class="center-img" src="https://spinmodern.com/sm_uploads/2015/09/google-logo-white.png" width = "320" height = "108,25">  
  </p>
    <div class = "d7">
      <form align="center" >
        <input placeholder="Search Google or type a URL">
        <button type="submit"></button>
      </form>
    </div>
    <div class = "image-wrap2" >
    </div>
  <div id="footer">
    <div>
        <p align = "right"><button class = "button-settings-right buttons buttons1 "><i class="fa fa-pencil fa-fw "></i>Settings</button></p>
    </div>
  </div>
  </body>
</html>