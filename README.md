<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>USPS Tracking - Your Package</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #004b87;
            text-align: center;
        }
        .tracking-info {
            margin: 20px 0;
        }
        .tracking-info p {
            font-size: 16px;
            color: #555;
        }
        .tracking-number {
            font-weight: bold;
            color: #004b87;
        }
        .status {
            font-size: 18px;
            color: green;
        }
        .package-location {
            font-size: 16px;
            color: #333;
        }
        #package {
            width: 60px;
            height: 60px;
            background-color: #004b87;
            color: white;
            text-align: center;
            line-height: 60px;
            border-radius: 50%;
            position: absolute;
            top: 200px;
            left: -60px;
            animation: movePackage 6s linear infinite;
        }
        @keyframes movePackage {
            0% {
                left: -60px;
            }
            50% {
                left: 80%;
            }
            100% {
                left: -60px;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>USPS Tracking</h1>

        <div class="tracking-info">
            <p><strong>Tracking Number:</strong> <span class="tracking-number">9405 5036 9930 0000 0000 00</span></p>
            <p><strong>Status:</strong> <span class="status">Your package is on its way!</span></p>
            <p><strong>Expected Delivery:</strong> Today</p>
            <p><strong>Package Location:</strong> <span class="package-location">2435 HAMPTON RD, WAUCHULA, FL 33873</span></p>
        </div>

        <div id="package">In Transit</div>
    </div>

</body>
</html>
