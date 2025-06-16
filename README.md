<!DOCTYPE html>
<html lang="kk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Султан & Айдана - Үйлену Тойына Шақыру</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom, #fff6f6, #f0f0ff);
      color: #333;
      text-align: center;
      padding: 20px;
    }
    header {
      padding: 40px 20px 10px;
    }
    h1 {
      font-size: 2.5em;
      margin-bottom: 0.2em;
    }
    h2 {
      font-weight: normal;
      color: #666;
      margin-bottom: 1.5em;
    }
    section {
      max-width: 600px;
      margin: auto;
      background: #ffffffcc;
      border-radius: 16px;
      padding: 30px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .timer {
      font-size: 1.5em;
      font-weight: bold;
      margin: 20px 0;
    }
    .button {
      display: inline-block;
      margin: 10px 5px;
      padding: 12px 24px;
      background-color: #6a5acd;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }
    iframe {
      width: 100%;
      height: 300px;
      border: none;
      border-radius: 12px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Султан & Айдана</h1>
    <h2>Үйлену Тойына Шақыру</h2>
  </header>
  <section>
    <p><strong>Құрметті қонақтар!</strong></p>
    <p>Сіздерді 2025 жылдың 3 тамызы күні сағат 15:00-де өтетін үйлену тойымыздың ақ дастарханымыздың қадірлі қонағы болуға шақырамыз!</p>
    <p><strong>Мекенжай:</strong> "Гүлдер" мейрамханасы, Экибастұз</p>

    <div class="timer" id="countdown"></div>

    <p><em>Тойға арналған жүректен шыққан өлең:</em></p>
    <p>Келіңдер, ағайын, қуанышты күнге,<br>
    Ақ тілектер айтылып, гүл шашылар бірге.<br>
    Султан мен Айдана шаттығын бөлісіп,<br>
    Мәңгілік махаббатпен бастаймыз бірлікте!</p>

    <a class="button" href="https://youtu.be/UQBGVjZEmfU" target="_blank">🎵 Фон Музыка</a>
    <a class="button" href="https://2gis.kz/ekibastuz/geo/70000001061109569" target="_blank">📍 Картаны Көру</a>
    <a class="button" href="https://wa.me/77054074998?text=%D2%9A%D0%B0%D1%82%D1%8B%D1%81%D0%B0%D0%BC%D1%8B%D0%BD!%20%D0%A2%D0%BE%D0%B9%D2%93%D0%B0%20%D0%BA%D0%B5%D0%BB%D0%B5%D0%BC%D1%96%D0%BD%20%E2%9C%8C%EF%B8%8F" target="_blank">📲 Қатысамын (WhatsApp)</a>

    <iframe src="https://2gis.kz/ekibastuz/geo/70000001061109569"></iframe>
  </section>

  <script>
    const eventDate = new Date('2025-08-03T15:00:00');
    const countdownEl = document.getElementById('countdown');

    function updateCountdown() {
      const now = new Date();
      const diff = eventDate - now;

      const days = Math.floor(diff / (1000 * 60 * 60 * 24));
      const hours = Math.floor((diff / (1000 * 60 * 60)) % 24);
      const minutes = Math.floor((diff / (1000 * 60)) % 60);
      const seconds = Math.floor((diff / 1000) % 60);

      countdownEl.textContent = `⏳ ${days} күн ${hours} сағат ${minutes} минут ${seconds} секунд қалды`;
    }

    setInterval(updateCountdown, 1000);
    updateCountdown();
  </script>
</body>
</html>
