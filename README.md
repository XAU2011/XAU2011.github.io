<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> 账户收益</title>
    <style>
        body {
            background-color: #292929;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            min-height: 100vh;
        }
        
        .container {
            width: 1600px;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px 0;
        }
        
        #ctrader-plugin-root {
            width: 100%;
            height: 3020px;
            position: relative;
            border: 5px solid #3b3b3b;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <div id="ctrader-plugin-root"></div>
        <script id="init" type="text/javascript" defer src="https://ct.spotware.com/widget.js"></script>
        <script type="text/javascript">
            const script = document.getElementById('init');
            
            script.onload = () => {
                putInitScript('runPlugin');
                runPlugin('ctrader-plugin-root', {
                    "route": "/esp/103543/?lang=zh&theme=dark",
                    "appConfig": {
                        "strategy": {
                            "showStrategyPromotion": true
                        }
                    }
                });
            };
        </script>
    </div>
</body>
</html>
