<!DOCTYPE html>
<html lang="fa">
<head>
<meta charset="UTF-8">
<title>MAHAN SHOP</title>

<style>
body {
    margin: 0;
    font-family: sans-serif;
    background: linear-gradient(45deg, #0a0f1c, #111827);
    color: white;
    text-align: center;
}

/* هدر */
header {
    padding: 20px;
    background: #111827;
    box-shadow: 0 0 10px red;
}

h1 {
    color: orange;
}

.small-text {
    font-size: 14px;
    color: gray;
}

/* کارت‌ها */
.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-top: 40px;
}

.card {
    background: #1f2937;
    border-radius: 15px;
    margin: 15px;
    padding: 15px;
    width: 220px;
    box-shadow: 0 0 15px rgba(255,0,0,0.5);
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

.card img {
    width: 100%;
    border-radius: 10px;
}

button {
    margin-top: 10px;
