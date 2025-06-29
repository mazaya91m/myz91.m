<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>عقارات مزايا</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    header {
      background-color: #004aad;
      color: white;
      text-align: center;
      padding: 20px;
    }

    header img {
      width: 100px;
      margin-bottom: 10px;
    }

    header h1 {
      margin: 10px 0 5px;
      font-size: 24px;
    }

    .social {
      margin-top: 10px;
    }

    .social a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
      font-size: 18px;
    }

    .contact-bar {
      background-color: #ffcc00;
      padding: 15px;
      text-align: center;
    }

    .contact-bar a {
      text-decoration: none;
      color: #000;
      font-weight: bold;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background-color: white;
      margin: 20px 0;
    }

    th, td {
      padding: 10px;
      text-align: center;
      border: 1px solid #ddd;
    }

    th {
      background-color: #004aad;
      color: white;
    }

    @media (max-width: 600px) {
      table, thead, tbody, th, td, tr {
        display: block;
      }

      thead {
        display: none;
      }

      tr {
        margin-bottom: 15px;
        border: 1px solid #ccc;
        padding: 10px;
      }

      td {
        text-align: right;
        position: relative;
        padding-right: 50%;
      }

      td::before {
        content: attr(data-label);
        position: absolute;
        right: 10px;
        top: 10px;
        font-weight: bold;
        color: #004aad;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="شعار مزايا"> <!-- تأكد من رفع صورة الشعار مع الملف -->
    <h1>مزايا للإسكان والتطوير العقاري</h1>
    <div class="social">
      <a href="https://www.snapchat.com/add/MZY.91.M" target="_blank">📸 سناب</a>
      <a href="https://www.tiktok.com/@MZY.91.M" target="_blank">🎵 تيك توك</a>
      <a href="https://www.instagram.com/MZY.91.M" target="_blank">📷 انستقرام</a>
    </div>
  </header>

  <div class="contact-bar">
    📞 للتواصل: <a href="https://wa.me/966591205501" target="_blank">واتساب مباشر</a>
  </div>

  <table>
    <thead>
      <tr>
        <th>نوع العقار</th>
        <th>الموقع</th>
        <th>المساحة</th>
        <th>غرف نوم</th>
        <th>دورات مياه</th>
        <th>السعر</th>
        <th>تواصل</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td data-label="نوع العقار">شقة</td>
        <td data-label="الموقع">أبها - المحالة</td>
        <td data-label="المساحة">230 م²</td>
        <td data-label="غرف نوم">3</td>
        <td data-label="دورات مياه">3</td>
        <td data-label="السعر">480,000 ريال</td>
        <td data-label="تواصل"><a href="https://wa.me/966591205501" target="_blank">واتساب</a></td>
      </tr>
    </tbody>
  </table>

</body>
</html>