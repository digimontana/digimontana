- 👋 Hi, I’m @digimontana
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!DOCTYPE html>
<html lang="en">
  
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" 
            content="IE=edge">
  
    <meta name="viewport" content=
        "width=device-width, initial-scale=1.0">
  
    <title>Spinning Ball Animation</title>
  
    <style>
        * {
            background-color: black;
        }
          
        .ball {
            height: 40px;
            width: 40px;
            border-radius: 100px;
            position: fixed;
            top: 50vh;
            left: 50vw;
            animation: spinBall 0.13s linear infinite;
            box-shadow: inset 0 0 18px #fff, 
                inset 6px 0 18px violet, 
                inset -6px 0 18px #0ff, 
                inset 6px 0 30px violet, 
                inset -6px 0 30px #0ff, 
                0 0 18px #fff, -4px 
                0 18px violet, 4px 0 18px #0ff;
        }
          
        @keyframes spinBall {
            100% {
                transform: rotate(360deg);
            }
        }
    </style>
</head>
  
<body>
    <div class="ball"></div>
</body>
  
</html>
<!---
digimontana/digimontana is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<img src="https://camo.githubusercontent.com/ffbf71edb9eb65671926a8cc42a5a740bf5b799a9b93699a3a0de76e1793a80b/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f54456e586b637348725034596564436868412f67697068792e676966" width="65" style="max-width: 100%;">
