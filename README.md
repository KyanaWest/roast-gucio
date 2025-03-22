# roast-gucio
Website That Roast My Client <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gucio.EXE: The Fake Hacker Files</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: black;
            color: white;
            text-align: center;
        }
        .container {
            margin-top: 50px;
        }
        h1 {
            color: red;
        }
        .roast {
            font-size: 20px;
            margin: 20px auto;
            padding: 20px;
            border: 2px solid red;
            width: 60%;
            background: rgba(255, 0, 0, 0.2);
        }
        .btn {
            background-color: red;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
        }
        .btn:hover {
            background-color: darkred;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🔥 Gucio.EXE: The Fake Hacker Files 🔥</h1>
        <p>Exposing the biggest fraud in cyberspace.</p>
        <div class="roast" id="roastBox">Loading roast...</div>
        <button class="btn" onclick="newRoast()">🔥 Roast Him Again 🔥</button>
    </div>
    <script>
        const roasts = [
            "Bro thinks he's a hacker but probably needs Google to turn on his own PC.",
            "Gucio.EXE? More like Gucio.ERROR 404: Respect Not Found.",
            "You talk big, but the only thing you've ever hacked is your mom’s WiFi password.",
            "Your profile pic looks like it was made in Microsoft Paint by a blindfolded toddler.",
            "You swear you're taking down servers, but the only thing you've ever crashed is your grades.",
            "Your ‘bot army’ is about as real as your social life – completely non-existent.",
            "Gucio.EXE? More like Gucio.UNINSTALLED.",
            "You act like a cyber menace, but we all know you still use Internet Explorer.",
            "You talk like a king but your throne is just a broken gaming chair.",
            "Your so-called ‘hacks’ are weaker than hotel WiFi."
        ];
        function newRoast() {
            document.getElementById("roastBox").innerText = roasts[Math.floor(Math.random() * roasts.length)];
        }
        newRoast();
    </script>
</body>
</html>
