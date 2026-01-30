# theFile_01 
<!DOCTYPE html>
<html>
<head>
<title>You Are Looking Inside</title>
<style>
body {
  background:black;
  color:white;
  font-family: monospace;
  text-align:center;
  margin-top:20%;
}
.hidden { display:none; }
</style>
</head>
<body>
<p id="text">You are looking inside.</p>
<script>
setTimeout(() => {
  document.getElementById("text").innerText =
  "The world remembers you.";
}, 5000);
</script>
</body>
</html>
