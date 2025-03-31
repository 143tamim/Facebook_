# Facebook_
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook - Log In or Sign Up</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: Helvetica, Arial, sans-serif;
        }
        
        body {
            background-color: #f0f2f5;
            color: #1c1e21;
        }
        
        /* Desktop Layout */
        .container {
            max-width: 980px;
            margin: 0 auto;
            padding: 72px 0 112px;
            display: flex;
            align-items: center;
        }
        
        .left-section {
            padding-right: 32px;
            width: 580px;
        }
        
        .logo {
            height: 106px;
            margin: -28px;
        }
        
        h2 {
            font-size: 28px;
            font-weight: normal;
            line-height: 32px;
            margin: 0;
            padding: 0 0 20px;
        }
        
        .right-section {
            width: 396px;
        }
        
        .login-box {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
        }
        
        /* Mobile Layout */
        @media (max-width: 900px) {
            .container {
                flex-direction: column;
                padding: 20px 0 80px;
                text-align: center;
            }
            
            .left-section {
                padding-right: 0;
                width: 100%;
                margin-bottom: 20px;
            }
            
            .logo {
                height: 70px;
                margin: 0 auto;
                display: block;
            }
            
            h2 {
                font-size: 22px;
                padding: 0 20px 20px;
            }
            
            .right-section {
                width: 100%;
                padding: 0 20px;
            }
        }
        
        /* Common Elements */
        input {
            width: 100%;
            padding: 14px 16px;
            margin-bottom: 12px;
            border: 1px solid #dddfe2;
            border-radius: 6px;
            font-size: 17px;
        }
        
        input:focus {
            outline: none;
            border-color: #1877f2;
            box-shadow: 0 0 0 2px #e7f3ff;
        }
        
        .login-button {
            background-color: #1877f2;
            border: none;
            border-radius: 6px;
            color: #fff;
            font-size: 20px;
            font-weight: bold;
            line-height: 48px;
            padding: 0 16px;
            width: 100%;
            cursor: pointer;
            margin-bottom: 16px;
        }
        
        .login-button:hover {
            background-color: #166fe5;
        }
        
        a {
            color: #1877f2;
            font-size: 14px;
            font-weight: 500;
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
        
        .divider {
            border-bottom: 1px solid #dadde1;
            margin: 20px 0;
        }
        
        .create-button {
            background-color: #42b72a;
            border: none;
            border-radius: 6px;
            color: #fff;
            font-size: 17px;
            font-weight: bold;
            line-height: 48px;
            padding: 0 16px;
            cursor: pointer;
            margin-top: 6px;
            width: 60%;
        }
        
        .create-button:hover {
            background-color: #36a420;
        }
        
        .create-page {
            margin-top: 28px;
            font-size: 14px;
            text-align: center;
        }
        
        .create-page a {
            font-weight: bold;
            color: #1c1e21;
        }
        
        footer {
            background-color: #fff;
            padding: 20px 0;
            font-size: 12px;
            color: #737373;
            text-align: center;
        }
        
        @media (max-width: 500px) {
            .create-button {
                width: 100%;
            }
            
            footer {
                padding: 20px 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="left-section">
            <img class="logo" src="https://static.xx.fbcdn.net/rsrc.php/y8/r/dF5SId3UHWd.svg" alt="Facebook">
            <h2>Facebook helps you connect and share with the people in your life.</h2>
        </div>
        <div class="right-section">
            <div class="login-box">
                <input type="text" placeholder="Email or phone number">
                <input type="password" placeholder="Password">
                <button class="login-button">Log In</button>
                <a href="#">Forgotten password?</a>
                <div class="divider"></div>
                <button class="create-button">Create New Account</button>
            </div>
            <div class="create-page">
                <a href="#">Create a Page</a> for a celebrity, brand or business.
            </div>
        </div>
    </div>
    
    <footer>
        <div>English (UK) · മലയാളം · தமிழ் · ಕನ್ನಡ · हिन्दी · اردو · বাংলা · తెలుగు · Español · Português (Brasil) · Français (France)</div>
        <div>Meta © 2023</div>
    </footer>
</body>
</html>
