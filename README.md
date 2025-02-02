<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>แนะนำสถานที่ท่องเที่ยวในประเทศไทย</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
        }
        header {
            background-color: #ff9800;
            color: white;
            padding: 20px;
            font-size: 28px;
            font-weight: bold;
        }
        .hero {
            background: url('https://source.unsplash.com/1600x600/?thailand,travel') no-repeat center center/cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 36px;
            font-weight: bold;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
        }
        .container {
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .place {
            background: white;
            margin: 15px;
            padding: 15px;
            width: 300px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .place:hover {
            transform: scale(1.05);
        }
        img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>แนะนำสถานที่ท่องเที่ยวในประเทศไทย</header>
    <div class="hero">ค้นพบเมืองไทยที่สวยงาม</div>
    <div class="container">
        <div class="place">
            <h2>ภูเก็ต</h2>
            <img src="https://source.unsplash.com/600x400/?phuket,beach" alt="ภูเก็ต">
            <p>ภูเก็ตเป็นเกาะที่สวยงามของประเทศไทย มีชายหาดที่น่าทึ่งและอาหารทะเลอร่อย</p>
        </div>
        <div class="place">
            <h2>เชียงใหม่</h2>
            <img src="https://source.unsplash.com/600x400/?chiangmai,temple" alt="เชียงใหม่">
            <p>เชียงใหม่เป็นเมืองที่เต็มไปด้วยวัฒนธรรมและวัดที่สวยงาม</p>
        </div>
        <div class="place">
            <h2>กรุงเทพฯ</h2>
            <img src="https://source.unsplash.com/600x400/?bangkok,city" alt="กรุงเทพฯ">
            <p>เมืองหลวงของไทยที่มีแหล่งช้อปปิ้งและอาหารอร่อยมากมาย</p>
        </div>
    </div>
    <footer>© 2025 แนะนำสถานที่ท่องเที่ยวในประเทศไทย</footer>
</body>
</html>
