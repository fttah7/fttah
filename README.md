<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>فتاح عمك</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000; /* خلفية سوداء */
            text-align: center;
            margin: 0;
            padding: 0;
            color: #fff;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }
        h1 {
            font-size: 5rem; /* حجم النص كبير */
            color: #ff4500; /* لون النص يشبه النار */
            text-shadow: 0 0 10px #ff4500, 0 0 20px #ff6347, 0 0 30px #ff4500; /* تأثير النار */
            animation: flicker 1.5s infinite; /* تأثير وميض النار */
        }
        @keyframes flicker {
            0%, 19%, 21%, 23%, 25%, 54%, 56
