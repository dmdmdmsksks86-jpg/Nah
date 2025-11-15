<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Nah Hub</title>
<style>
    body {
        margin: 0;
        padding: 0;
        background: linear-gradient(120deg, #1c1f26, #111418);
        font-family: Arial, sans-serif;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        color: #fff;
    }

    .card {
        background: rgba(255, 255, 255, 0.12);
        backdrop-filter: blur(10px);
        padding: 40px;
        border-radius: 18px;
        width: 350px;
        text-align: center;
        box-shadow: 0 0 25px rgba(0,0,0,0.4);
        animation: fadein 0.8s ease;
    }

    @keyframes fadein {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }

    h1 {
        font-size: 32px;
        margin-bottom: 10px;
    }

    p {
        opacity: 0.8;
        margin-bottom: 20px;
    }

    button {
        background: #2b7bff;
        border: none;
        padding: 12px 25px;
        font-size: 18px;
        border-radius: 10px;
        cursor: pointer;
        color: #fff;
        transition: 0.2s;
    }

    button:hover {
        background: #1f63d9;
        transform: scale(1.05);
    }
</style>
</head>

<body>
    <div class="card">
        <h1>Nah Hub</h1>
        <p>Nhấn nút bên dưới để copy script.</p>
        
        <button onclick="copyScript()">Copy Script</button>
    </div>

<script>
function copyScript() {
    navigator.clipboard.writeText(
        'loadstring(game:HttpGet("https://example.com/nahhub.lua"))()'
    );
    alert("Đã copy script thành công!");
}
</script>
</body>
</html>
