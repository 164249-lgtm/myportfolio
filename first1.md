<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>หน้าปกรายงาน/เอกสาร</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Prompt', sans-serif;
            background-color: #f4f7f6;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .cover-container {
            background-color: #ffffff;
            width: 210mm;
            height: 297mm; /* ขนาดกระดาษ A4 */
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            padding: 50px;
            box-sizing: border-box;
            border: 2px solid #2c3e50;
            position: relative;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .cover-header {
            font-size: 24px;
            color: #2c3e50;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        .cover-title {
            font-size: 40px;
            font-weight: bold;
            color: #34495e;
            margin-bottom: 40px;
            line-height: 1.4;
        }
        .cover-subtitle {
            font-size: 20px;
            color: #7f8c8d;
            margin-bottom: 60px;
        }
        .cover-footer {
            position: absolute;
            bottom: 50px;
            font-size: 16px;
            color: #95a5a6;
            width: 100%;
        }
        .btn-enter {
            display: inline-block;
            margin-top: 20px;
            padding: 15px 30px;
            background-color: #2c3e50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        .btn-enter:hover {
            background-color: #1a252f;
        }
    </style>
</head>
<body>

    <div class="cover-container">
        <div class="cover-header">ชื่อหน่วยงาน / โรงเรียน / บริษัท</div>
        <div class="cover-title">รายงานการปฏิบัติงาน<br>ประจำปีการศึกษา 2569</div>
        <div class="cover-subtitle">จัดทำโดย: ชื่อ - นามสกุล</div>
        <div class="cover-footer">
            <p>เสนอ</p>
            <p>ตำแหน่ง / ฝ่ายที่เกี่ยวข้อง</p>
            <a href="#" class="btn-enter">เข้าสู่เนื้อหา</a>
        </div>
    </div>

</body>
</html>
