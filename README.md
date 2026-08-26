<h1 data-importer="text" align="center">Hey 👋What's Up?</h1>

# 💫 About Me:
🤖 hi my name ia Louis<br>🌱 I am still learning 


## 🌐 Socials:
[![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:codingluizz@gmail.com) 

# 💻 Tech Stack:
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=flat&logo=csharp&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=flat&logo=dart&logoColor=white) ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=flat&logo=go&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=flat&logo=php&logoColor=white) ![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=flat&logo=lua&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=flat&logo=kotlin&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white) ![Ruby](https://img.shields.io/badge/ruby-%23CC342D.svg?style=flat&logo=ruby&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=Cloudflare&logoColor=white) ![DigitalOcean](https://img.shields.io/badge/DigitalOcean-%230167ff.svg?style=flat&logo=digitalOcean&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=flat&logo=firebase) ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=flat&logo=Flutter&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=flat&logo=Canva&logoColor=white) ![Sketch Up](https://img.shields.io/badge/SketchUp-005F9E?style=flat&logo=sketchup&logoColor=white) ![Sketch](https://img.shields.io/badge/Sketch-FFB387?style=flat&logo=sketch&logoColor=black) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=flat&logo=gitlab&logoColor=white) ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat&logo=Arduino&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white)

animation.add(new AnimationStatic(animation, {
    image: null,                    // image object
    start: { x: 0, y: 0 },          // initial coordonates of the image
    offset: { x: 0, y: 0 },         // offset coordonates in the canvas
    cases: { x: 1, y: 1 },          // number of animations in the sprite
    layer: 0,                       // group assigned to display the sprite - lower value is deeper in the background

    onLoad: function() {},          // triggered after loading image
    onBeforeDraw: function() {},    // triggered before each frame draw
    onHide: function() {},          // triggered while hiding a sprite
    onShow: function() {},          // triggered while showing a sprite
    onClicked: null,                // triggered on a click event on the sprite - null: check click events deeper in the background, empty function : disable click on the sprite area
    onEnter: null,                  // triggered on entering the sprite
    onLeave: null                   // triggered on leaving the sprite
}[, referer]))

animation.add(new AnimationAnimated(animation, {
    image: null,                    // image object
    start: { x: 0, y: 0 },          // initial coordonates of the image
    offset: { x: 0, y: 0 },         // offset coordonates in the canvas
    cases: { x: 1, y: 1 },          // number of animations in the sprite
    layer: 0,                       // group assigned to display the sprite - lower value is deeper in the background

    step: 100,                      // time in ms between two animations
    line: 0,                        // line played ( defined in cases.y )
    order: 1,                       // TODO : play order, not implemented yet
    autorun: false,                 // auto start playing

    onLoad: function() {},          // triggered after loading image
    onBeforeDraw: function() {},    // triggered before each frame
    onAfterDraw: function() {},     // triggered after each frame
    onHide: function() {},          // triggered while hiding a sprite
    onShow: function() {},          // triggered while showing a sprite
    onClicked: null,                // triggered on a click event on the sprite - null: check click events deeper in the background, empty function : disable click on the sprite area
    onEnter: null,                  // triggered on entering the sprite
    onLeave: null                   // triggered on leaving the sprite
}[, referer]))

animation.add(new AnimationCanvas(animation, {
    canvas: null,                   // canvas object
    start: { x: 0, y: 0 },          // initial coordonates of the canvas
    offset: { x: 0, y: 0 },         // offset coordonates in the canvas
    cases: { x: 1, y: 1 },          // number of animations in the canvas
    layer: 0,                       // group assigned to display the canvas - lower value is deeper in the background

    onLoad: function() {},          // triggered after loading image
    onBeforeDraw: function() {},    // triggered before each frame draw
    onHide: function() {},          // triggered while hiding a canvas
    onShow: function() {},          // triggered while showing a canvas
    onClicked: null,                // triggered on a click event on the canvas - null: check click events deeper in the background, empty function : disable click on the canvas area
    onEnter: null,                  // triggered on entering the canvas
    onLeave: null                   // triggered on leaving the canvas
}[, referer]))
