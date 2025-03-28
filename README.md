# Wnamex
𝐒𝐭𝐮𝐝𝐞𝐧𝐭🎓 
<!DOCTYPE html><html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ismni toping</title>
    <script>
        function checkName() {
            var name = document.getElementById("nameInput").value;
            if (name.toLowerCase() === "salohiddin") {
                let emojis = "😉🙃😇😋😜😵🧐😎😏😒🤔🤫🤝🙋‍♂️ ".repeat(50); // 1000+ emoji
                document.getElementById("result").innerHTML = "I love you all, come closer to me! " + emojis;
            } else {
                document.getElementById("result").innerHTML = "Adashdingiz! U sizdan aqilliroq. U kim?";
            }
        }
    </script>
</head>
<body>
    <h2>Yaratuvchining ismini kiriting:</h2>
    <input type="text" id="nameInput">
    <button onclick="checkName()">Tasdiqlash</button>
    <p id="result"></p>
</body>
</html>
