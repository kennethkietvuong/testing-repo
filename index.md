<html>
  <head>
    <title>Typewriter effect</title>
  </head>
  <style>
    body{
      background: navajowhite;
      background-size: cover;
      font-family: 'Trebuchet MS', sans-serif; 
    }
    .container{
      display: inline-block;
    }
    .typed-out{
      overflow: hidden;
      border-right: .15em solid orange;
      white-space: nowrap;
      font-size: 1.6rem;
      width: 0;
      animation: 
        typing 1s steps(20, end) forwards;
        blink .8s infinite;
    }
    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }
    @keyframes blink {
        from { border-color: transparent }
        to { border-color: orange; }
    }
  </style>
<body>
<h1>I'm Matt, I'm a</h1>
<div class="container">
  <div class="typed-out">Web Developer</div>
</div>
</body>
</html>