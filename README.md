
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>hi hehe</title>
<style>
    body {
        font-family: Arial, sans-serif;
        text-align: center;
        background-color: #333;
        color: #fff;
    }
    #text {
        font-size: 24px;
        margin-bottom: 20px;
    }
    #changeBtn {
        padding: 10px 20px;
        font-size: 16px;
        cursor: pointer;
        background-color: #900;
        color: #fff;
        border: none;
        border-radius: 5px;
        transition: background-color 0.3s ease;
    }
    #changeBtn:hover {
        background-color: #c00;
    }
    #bottomImage {
        margin-top: 50px; /* Adjust margin as needed */
    }
</style>
</head>
<body>
    <h1> HI LOVE <3 </h1>
    <p id="text">NAA RAKOY I ASK HEHE</p>
    <button id="changeBtn">PINDUTA NI TRIXIE MARIE</button>
    
    <div id="bottomImage">
        <img src="1917916_101765293182608_278821_n.jpg">
    </div>

    <script>
        var clickCount = 0;

        document.getElementById('changeBtn').addEventListener('click', function() {
            var textElement = document.getElementById('text');
            clickCount++;
            if (clickCount == 1) {
                textElement.textContent = 'WILL U BE MY VALENTINE???';
            } else if (clickCount == 2) {
                textElement.textContent = 'KAY IF DILI KA';
            } else if (clickCount == 3) {
                textElement.textContent = 'EDI WAG';
                clickCount = 0; // Reset click count after 3 clicks
            }
        });
    </script>
</body>
</html>
