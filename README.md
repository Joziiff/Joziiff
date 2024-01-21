<!DOCTYPE html>
<html>
<head>
  <title>هل توافقين على الخروج معي؟</title>
</head>
<body>
  <h1>هل توافقين على الخروج معي؟</h1>
  <button id="yes">نعم</button>
  <button id="no">لا</button>

  <script>
    var yesButton = document.getElementById("yes");
    var noButton = document.getElementById("no");

    yesButton.addEventListener("click", function() {
      alert("رائع! دعنا نحدد موعدًا.");
    });

    noButton.addEventListener("click", function() {
      alert("لا مشكلة. ربما في المرة القادمة.");
    });
  </script>
</body>
</html>
