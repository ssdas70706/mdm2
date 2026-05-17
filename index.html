<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no, viewport-fit=cover">
    <title>國軍MDM V8.1</title>
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <meta name="apple-mobile-web-app-title" content="國軍MDM">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            user-select: none;
            -webkit-user-select: none;
        }

        body {
            background-color: #52c443;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            color: #000000;
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 100vh;
            width: 100vw;
            overflow: hidden;
            padding-top: env(safe-area-inset-top);
            padding-bottom: env(safe-area-inset-bottom);
        }

        /* 上方黑色導覽列 */
        .navbar {
            background-color: #000000;
            width: 100%;
            height: 54px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            color: #ffffff;
            font-size: 18px;
            font-weight: 500;
        }

        .menu-icon {
            position: absolute;
            left: 16px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            width: 22px;
            height: 16px;
        }

        .menu-icon span {
            display: block;
            height: 2.5px;
            width: 100%;
            background-color: #ffffff;
            border-radius: 1px;
        }

        /* 主體內容區塊 */
        .content {
            flex: 1;
            width: 100%;
            max-width: 430px; /* 符合 iPhone 17 Pro Max 寬度 */
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 0 24px;
            position: relative;
        }

        /* iOS 版本號 */
        .ios-version {
            align-self: flex-end;
            font-size: 15px;
            color: #000000;
            margin-top: 4px;
            margin-right: -4px;
        }

        /* 結束時間 */
        .end-time {
            font-size: 25px;
            font-weight: bold;
            margin-top: 4px;
            letter-spacing: 0.5px;
        }

        /* 任務模式大字 */
        .title-banner {
            font-size: 72px;
            font-weight: 900;
            margin-top: 15px;
            letter-spacing: 2px;
        }

        /* 當下手機動態時間 */
        .current-time {
            font-size: 34px;
            font-weight: bold;
            margin-top: 10px;
            letter-spacing: 0.5px;
        }

        /* 按鈕樣式 */
        .btn-container {
            width: 100%;
            margin-top: 20px;
            display: flex;
            flex-direction: column;
            gap: 22px;
        }

        .btn {
            width: 100%;
            height: 48px;
            border-radius: 14px;
            background-color: rgba(255, 255, 255, 0.25);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 18px;
            font-weight: 500;
            text-decoration: none;
        }

        .btn-lock {
            color: rgba(0, 0, 0, 0.35);
        }

        .btn-unlock {
            color: #1c73e8;
        }

        .dot {
            width: 10px;
            height: 10px;
            border-radius: 50%;
            margin-right: 10px;
        }

        .dot-green { background-color: #7ee36b; }
        .dot-red { background-color: #ff3b30; }

        /* 管制標籤白框 */
        .tag-box {
            background-color: #ffffff;
            width: 82%;
            border-radius: 16px;
            padding: 14px 10px;
            margin-top: 45px;
            display: flex;
            flex-direction: column;
            align-items: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }

        .tag-text {
            font-size: 19px;
            font-weight: bold;
            color: #000000;
            line-height: 1.6;
            text-align: center;
            letter-spacing: 1px;
        }

        .tag-id {
            font-size: 28px;
            font-weight: 900;
            color: #000000;
            margin-top: 2px;
            letter-spacing: 0.5px;
        }

        /* 下方詳細資訊 */
        .info-footer {
            width: 100%;
            text-align: center;
            position: absolute;
            bottom: 20px;
            font-size: 18px;
            font-weight: bold;
            line-height: 1.5;
        }

        .warning-text {
            color: #ff3b30;
            font-size: 15px;
            font-weight: 900;
            margin-top: 2px;
            letter-spacing: 4px;
        }
    </style>
</head>
<body>

    <div class="navbar">
        <div class="menu-icon">
            <span></span>
            <span></span>
            <span></span>
        </div>
        國軍MDM V8.1
    </div>

    <div class="content">
        <div class="ios-version">iOS:26.4.2</div>
        <div class="end-time">結束時間:115/5/15 12:00</div>
        <div class="title-banner">任務模式</div>
        
        <div class="current-time" id="liveClock">00/00 00:00:00</div>

        <div class="btn-container">
            <div class="btn btn-lock">
                <span class="dot dot-green"></span>上鎖：進入管制模式
            </div>
            <div class="btn btn-unlock">
                <span class="dot dot-red"></span>解鎖：離開管制模式
            </div>
        </div>

        <div class="tag-box">
            <div class="tag-text">國軍營內民用通信</div>
            <div class="tag-text">資訊器材管制標籤</div>
            <div class="tag-id">C228919127</div>
        </div>

        <div class="info-footer">
            <div>上鎖時間：115/04/29 07:23:59</div>
            <div>設定檔：V2.0 (02/22 15:35:58)</div>
            <div class="warning-text">仿冒必究</div>
        </div>
    </div>

    <script>
        function updateClock() {
            const now = new Date();
            
            // 獲取月份與日期 (補零)
            const month = String(now.getMonth() + 1).padStart(2, '0');
            const date = String(now.getDate()).padStart(2, '0');
            
            // 獲取時分秒 (補零)
            const hours = String(now.getHours()).padStart(2, '0');
            const minutes = String(now.getMinutes()).padStart(2, '0');
            const seconds = String(now.getSeconds()).padStart(2, '0');
            
            // 組合格式: MM/DD HH:MM:SS
            const formattedTime = `${month}/${date} ${hours}:${minutes}:${seconds}`;
            
            document.getElementById('liveClock').textContent = formattedTime;
        }

        // 每秒更新一次時間
        setInterval(updateClock, 1000);
        // 網頁載入時立刻執行一次，避免空白
        updateClock();
    </script>
</body>
</html>
