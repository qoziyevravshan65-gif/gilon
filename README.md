<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Click Prank Notification</title>
    <style>
        body {
            background-color: #121212;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        /* Bildirishnoma oynasi (Android/iOS uslubida) */
        .notification-card {
            background: rgba(30, 30, 30, 0.85);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            width: 360px;
            border-radius: 24px;
            padding: 16px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            border: 1px solid rgba(255,255,255,0.1);
            color: #ffffff;
        }

        /* Yuqori qism: Logo va Ilova nomi */
        .notif-header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 8px;
        }

        .app-info {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        /* Soxta Click logotipi (Ko'k aylana) */
        .click-logo {
            width: 24px;
            height: 24px;
            background-color: #00A6FF;
            border-radius: 6px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 11px;
            color: white;
        }

        .app-name {
            font-size: 13px;
            font-weight: 600;
            color: #e0e0e0;
            letter-spacing: 0.5px;
        }

        .notif-time {
            font-size: 12px;
            color: #8e8e93;
        }

        /* Matn qismi */
        .notif-body {
            margin-top: 4px;
        }

        .notif-title {
            font-size: 15px;
            font-weight: bold;
            margin-bottom: 3px;
            color: #ffffff;
        }

        .notif-text {
            font-size: 14px;
            color: #d1d1d6;
            line-height: 1.4;
        }

        .highlight {
            color: #ff453a; /* Pul yechilganda qizil rang */
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="notification-card">
        <div class="notif-header">
            <div class="app-info">
                <div class="click-logo">C</div>
                <span class="app-name">CLICK EVOLUTION</span>
            </div>
            <span class="notif-time">Hozirgina</span>
        </div>
        <div class="notif-body">
            <div class="notif-title">To'lov muvaffaqiyatli bajarildi</div>
            <div class="notif-text">
                Uzkard (*0001) kartangizdan <span class="highlight">-547,000 UZS</span> yechildi. <br>
                Qoldiq: 1,450 UZS. Xizmat: "Davlat Boji".
            </div>
        </div>
    </div>

</body>
</html>
