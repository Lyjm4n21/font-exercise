# font-exercise
HTML
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>JS Bin</title>
</head>
<body>
  <p class="hcc">HTML CSS Course</p>
  <p class="bp">Beginner Pro</p>
  <p class="ic">In this course, we'll learn the skills you need to become a developer.</p>
  <button>Get Started</button>
</body>
</html>

CSS
p {
  font-family: Verdana;
  margin-top: 0;
  margin-bottom: 0;
}
.hcc{
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 1px;
}
.bp {
  color: gray;
  font-size: 15px;
  margin-bottom: 20px;
}
.ic {
  font-size: 15px;
  width: 280px;
  margin-bottom: 20px;
}
button{
  background-color: green;
  color: white;
  border: none;
  border-radius: 4px;
  font-size: 14px;
  padding: 6px 12px;
  cursor: pointer;
}
