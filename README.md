<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#020702">
<title>درع أبوصالح | تحذير أمني</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    min-height: 100vh;
    background: #020702;
    color: #00ff66;
    font-family: Arial, sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    overflow-x: hidden;
}

body::before {
    content: "";
    position: fixed;
    inset: 0;
    pointer-events: none;
    background: repeating-linear-gradient(
        transparent 0px,
        transparent 3px,
        #00ff4110 4px
    );
}

.panel {
    width: 100%;
    max-width: 480px;
    border: 1px solid #00ff66;
    padding: 28px 20px;
    text-align: center;
    border-radius: 15px;
    background: #031003;
    box-shadow: 0 0 25px #00ff4133;
    animation: glow 2s infinite alternate;
}

.icon {
    font-size: 65px;
    margin-bottom: 12px;
}

h1 {
    font-size: 28px;
    text-shadow: 0 0 12px #00ff66;
}

.warning {
    color: #ffcf40;
    font-size: 22px;
    font-weight: bold;
}

.message {
    color: #e0ffe7;
    line-height: 2;
    font-size: 16px;
}

.line {
    height: 1px;
    background: #00ff66;
    margin: 22px 0;
    opacity: .5;
}

button {
    background: #00ff66;
    color: #001500;
    border: 0;
    border-radius: 8px;
    padding: 13px 25px;
    font-size: 17px;
    font-weight: bold;
    cursor: pointer;
}

button:active {
    transform: scale(.97);
}

footer {
    margin-top: 24px;
    color: #7aff9c;
    font-size: 14px;
    line-height: 2;
}

@keyframes glow {
    from {
        box-shadow: 0 0 10px #00ff4122;
    }
    to {
        box-shadow: 0 0 28px #00ff4166;
    }
}
</style>
</head>

<body>
<main class="panel">

    <div class="icon">🛡️</div>

    <h1>درع أبوصالح</h1>

    <div class="warning">⚠️ تنبيه أمني</div>

    <div class="line"></div>

    <p class="message">
        أهلًا بك في صفحة التنبيه الأمني.<br>
        يرجى توخي الحذر عند فتح الروابط
        والملفات مجهولة المصدر.<br>
        حافظ على خصوصيتك ولا تشارك كلمات
        المرور أو رموز التحقق مع الآخرين.
    </p>

    <button onclick="showMessage()">
        فهمت التحذير
    </button>

    <p id="result" class="message"></p>

    <footer>
        صفحة توعوية للأمان الرقمي<br>
        معا تحياتي<br>
        <strong>عبدالله صالح — أبوصالح 💚</strong>
    </footer>

</main>

<script>
function showMessage() {
    document.getElementById("result").textContent =
        "✅ شكرًا لاهتمامك بسلامتك الرقمية.";
}
</script>

</body>
</html>
