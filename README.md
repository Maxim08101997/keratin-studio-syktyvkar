<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Салон красоты</title>

  <!-- AOS CSS -->
  <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet" />

  <style>
    /* ...стили из твоего кода... */
  </style>
</head>
<body>

<header>
  <nav class="navbar">
    <ul>
      <li><a href="#services">Услуги</a></li>
      <li><a href="#gallery">Галерея</a></li>
      <li><a href="#reviews">Отзывы</a></li>
      <li><a href="#contact">Контакты</a></li>
      <li><a href="#form">Запись</a></li>
    </ul>
  </nav>
</header>

<section id="services" data-aos="fade-up">
  <h2>Услуги</h2>
  <div class="services-list">
    <!-- сервисы -->
  </div>
</section>

<section id="gallery" data-aos="fade-up" data-aos-delay="100">
  <h2>Галерея работ</h2>
  <div class="gallery-grid">
    <!-- карточки с реальными фото желательно -->
  </div>
</section>

<section id="reviews" data-aos="fade-up" data-aos-delay="200">
  <h2>Отзывы клиентов</h2>
  <div class="review-list">
    <!-- отзывы -->
  </div>
</section>

<section id="form" data-aos="fade-up" data-aos-delay="300">
  <h2>Записаться на процедуру</h2>
  <form class="contact-form" action="#" method="post" autocomplete="off">
    <!-- форма -->
  </form>
</section>

<footer>
  <div class="footer-container">
    <div>
      <h3>Контакты</h3>
      <p>г. Сыктывкар</p>
      <p>Телефон: +7 908 715 21 90</p>
      <p>Телефон: +7 (950) 308-74-54</p>
    </div>
    <div>
      <h3>Мы в соцсетях</h3>
      <a href="https://vk.com/keratinstudio12" target="_blank" class="social-link" rel="noopener noreferrer">VK: keratinstudio12</a>
    </div>
  </div>
</footer>

<!-- AOS JS -->
<script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
<script>
  AOS.init({
    duration: 800,
    once: true,
  });
</script>

</body>
</html>
