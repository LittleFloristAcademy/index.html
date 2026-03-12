# index.html
Website for Little Florist Academy offering creative flower arranging classes for children, including after-school enrichment programs and events.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Little Florist Academy</title>
  <meta
    name="description"
    content="Little Florist Academy offers floral design classes for kids, after-school programs, birthday parties, and workshops."
  />
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fffafc;
      color: #333;
    }

    .wrap {
      max-width: 900px;
      margin: 0 auto;
      padding: 40px 20px;
      text-align: center;
    }

    h1 {
      font-size: 48px;
      color: #d94f8a;
      margin-bottom: 10px;
    }

    h2 {
      font-size: 24px;
      color: #4a9b5d;
      margin-top: 0;
    }

    p {
      font-size: 18px;
      line-height: 1.6;
    }

    .box {
      background: white;
      border-radius: 14px;
      padding: 24px;
      margin-top: 30px;
      box-shadow: 0 4px 18px rgba(0,0,0,0.08);
    }

    .programs {
      display: grid;
      grid-template-columns: 1fr;
      gap: 18px;
      margin-top: 25px;
    }

    .program {
      background: #fff;
      border: 1px solid #f3d7e4;
      border-radius: 12px;
      padding: 18px;
    }

    .buttons {
      margin-top: 25px;
    }

    .btn {
      display: inline-block;
      margin: 8px;
      padding: 14px 22px;
      border-radius: 10px;
      text-decoration: none;
      font-weight: bold;
    }

    .btn-call {
      background: #d94f8a;
      color: white;
    }

    .btn-email {
      background: #4a9b5d;
      color: white;
    }

    footer {
      margin-top: 40px;
      font-size: 14px;
      color: #666;
    }

    @media (min-width: 700px) {
      .programs {
        grid-template-columns: repeat(3, 1fr);
      }
    }
  </style>
</head>
<body>
  <div class="wrap">
    <h1>Little Florist Academy</h1>
    <h2>Where Kids Learn the Art of Flowers</h2>

    <p>
      Little Florist Academy offers fun, hands-on flower arranging experiences
      for children through after-school programs, birthday parties, and creative workshops.
    </p>

    <div class="buttons">
      <a class="btn btn-call" href="tel:8185773875">Call Molly: 818-577-3875</a>
      <a class="btn btn-email" href="mailto:LittleFloristAcademy@yahoo.com">Email Molly</a>
    </div>

    <div class="box">
      <h3>About the Program</h3>
      <p>
        Led by Molly Houshanian, Little Florist Academy helps children explore
        creativity, color, and design through age-appropriate floral activities
        that are both fun and educational.
      </p>
    </div>

    <div class="box">
      <h3>Our Programs</h3>
      <div class="programs">
        <div class="program">
          <h4>After-School Programs</h4>
          <p>Floral design classes for schools, clubs, and enrichment programs.</p>
        </div>
        <div class="program">
          <h4>Birthday Parties</h4>
          <p>Creative flower arranging parties with fun take-home projects.</p>
        </div>
        <div class="program">
          <h4>Workshops</h4>
          <p>Seasonal and special event workshops for kids and families.</p>
        </div>
      </div>
    </div>

    <div class="box">
      <h3>Contact</h3>
      <p><strong>Molly Houshanian</strong></p>
      <p>Owner / Instructor</p>
      <p>Phone: <a href="tel:8185773875">818-577-3875</a></p>
      <p>Email: <a href="mailto:LittleFloristAcademy@yahoo.com">LittleFloristAcademy@yahoo.com</a></p>
    </div>

    <footer>
      Little Florist Academy · Female Owned & Operated
    </footer>
  </div>
</body>
</html>
