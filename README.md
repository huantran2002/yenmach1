<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Website Test GitHub Pages</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f5f5f5;
}

header{
    background:#2c7be5;
    color:white;
    text-align:center;
    padding:50px 20px;
}

header h1{
    font-size:40px;
    margin-bottom:10px;
}

.container{
    max-width:1000px;
    margin:auto;
    padding:40px 20px;
}

.card{
    background:white;
    padding:25px;
    border-radius:12px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
    margin-bottom:20px;
}

button{
    background:#2c7be5;
    color:white;
    border:none;
    padding:12px 25px;
    border-radius:8px;
    cursor:pointer;
}

button:hover{
    opacity:0.9;
}

footer{
    text-align:center;
    padding:20px;
    background:#222;
    color:white;
    margin-top:30px;
}
</style>
</head>

<body>

<header>
    <h1>Xin Chào GitHub Pages 🚀</h1>
    <p>Website HTML/CSS/JS thuần</p>
</header>

<div class="container">

    <div class="card">
        <h2>Giới thiệu</h2>
        <p>Đây là website thử nghiệm chạy trên GitHub Pages.</p>
    </div>

    <div class="card">
        <h2>Kiểm tra JavaScript</h2>
        <button onclick="showMessage()">Bấm vào đây</button>
    </div>

</div>

<footer>
    © 2026 Website Demo
</footer>

<script>
function showMessage(){
    alert("Chúc mừng! Website của bạn đang hoạt động.");
}
</script>

</body>
</html>
