<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free Fire Tournament</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>🔥 Free Fire Tournament 🔥</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="register.html">Register</a>
            <a href="leaderboard.html">Leaderboard</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <main>
        <h2>Join the Ultimate Free Fire Battle!</h2>
        <p>💰 Entry Fee: ₹50 | 🎁 Weekly Prize: Free Fire Membership | 🏆 Grand Prize: 1000 Diamonds</p>
        <a href="register.html" class="btn">Register Now</a>
    </main>
    <footer>
        <p>© 2025 Free Fire Tournament. All Rights Reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #0e0e0e;
    color: #fff;
    text-align: center;
}
header {
    background: #ff4500;
    padding: 15px;
}
nav a {
    margin: 10px;
    color: white;
    text-decoration: none;
    font-weight: bold;
}
.btn {
    background: #ff4500;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    display: inline-block;
    margin-top: 10px;
    border-radius: 5px;
}
footer {
    background: #222;
    padding: 10px;
    margin-top: 20px;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Register - Free Fire Tournament</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Register for Tournament</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="register.html">Register</a>
            <a href="leaderboard.html">Leaderboard</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <main>
        <h2>Enter Your Details</h2>
        <form action="submit.php" method="POST">
            <label for="name">Player Name:</label>
            <input type="text" name="name" required><br>
            <label for="uid">Free Fire UID:</label>
            <input type="text" name="uid" required><br>
            <label for="phone">WhatsApp Number:</label>
            <input type="text" name="phone" required><br>
            <button type="submit">Register</button>
        </form>
    </main>
    <footer>
        <p>© 2025 Free Fire Tournament. All Rights Reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Leaderboard - Free Fire Tournament</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>🏆 Tournament Leaderboard 🏆</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="register.html">Register</a>
            <a href="leaderboard.html">Leaderboard</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <main>
        <h2>Top Players</h2>
        <table>
            <tr>
                <th>Rank</th>
                <th>Player Name</th>
                <th>Kills</th>
            </tr>
            <tr>
                <td>1</td>
                <td>PlayerX</td>
                <td>50</td>
            </tr>
            <tr>
                <td>2</td>
                <td>PlayerY</td>
                <td>45</td>
            </tr>
            <tr>
                <td>3</td>
                <td>PlayerZ</td>
                <td>40</td>
            </tr>
        </table>
    </main>
    <footer>
        <p>© 2025 Free Fire Tournament. All Rights Reserved.</p>
    </footer>
</body>
</html>
