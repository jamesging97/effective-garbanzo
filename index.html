<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, user-scalable=no">
<style>
  html, body {
      width: 100%;
      height: 100%;
      padding: 0;
      margin: 0;
      overflow: hidden;
  }
  canvas {
      background-color:#121d61;
      //background-image: url(ocean_backround.jpg);
      width: 100%;
      height: 100%;
  }
  img {
    max-width:100%;
    height:auto;
}
</style>
</head>
<body onload="startGame()">
<script>
//document.write("x =", screen.width, " y = ", screen.height);
var myGamePiece = [],
    fish_image = ["white_fish.gif", "orange_fish.gif", "blue_fish.gif"],
    fish_amount = Math.ceil(Math.random() * 14),
    canvas_width = window.innerWidth, canvas_height = window.innerHeight,
    background = document.createElement("canvas");

function startGame() {
    for (i = 0; i < fish_amount; ++i)
    {
          myGamePiece.push(new component(10, 8, fish_image[Math.floor(Math.random() * fish_image.length)]));
          myGamePiece[i].initialSpawn();
    }

    myGameArea.start();
    background.width = canvas_width;
    background.height = canvas_height;
    background.getContext("2d").drawImage("ocean_backround.png",
      canvas_height,
      canvas_width);
}

var myGameArea = {
    canvas : document.createElement("canvas"),
    start : function() {
        this.canvas.width = canvas_width;
        this.canvas.height = canvas_height;
        this.context = this.canvas.getContext("2d");
        document.body.insertBefore(this.canvas, document.body.childNodes[0]);
        this.frameNo = 0;
        this.interval = setInterval(updateGameArea, 100);
        },
    clear : function() {
        this.context.clearRect(0, 0, this.canvas.width, this.canvas.height);
    },
    stop : function() {
        clearInterval(this.interval);
    }
}

function component(width, height, image) {

    this.image = new Image();
    this.image.src = image;
    this.width = width;
    this.height = height;
    this.x = 0;
    this.y = 0;
    this.initialSpawn = function() {
        this.x += Math.floor(Math.random() * canvas_width);
        this.y += Math.floor(Math.random() * canvas_height);
    }
    this.update = function() {
        ctx = myGameArea.context;
        ctx.drawImage(this.image,
          this.x,
          this.y,
          this.width, this.height);
    }
    this.newPos = function() {

        if (Math.random() > 0.5 && (this.x - 1 > canvas_height * 0.09))
        this.x -= 1;
        else if (this.x + 1 < canvas_width - canvas_height * 0.09)
                this.x += 1;
        if (Math.random() > 0.5 && (this.y - 1 > canvas_height * 0.09))
        this.y -= 1;
        else if (this.y + 1 < canvas_height - canvas_height * 0.09)
        this.y += 1;
    }
}

function updateGameArea() {
  myGameArea.clear();
  for (i = 0; i < myGamePiece.length; ++i)
  {
    movement_amount = Math.floor(Math.random() * 600);
    for (j = 0; j < movement_amount; ++j)
    {
      myGamePiece[i].newPos();
      myGamePiece[i].update();
    }
  }
}

</script>

</body>
</html>
