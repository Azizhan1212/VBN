<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gourmet Kitchen | Кулинарное совершенство</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <div class="container">
            <div class="logo">
                <i class="fas fa-utensils"></i>
                <h1>Gourmet Kitchen</h1>
            </div>
            <p>Искусство вкусной жизни с 2010 года</p>
        </div>
    </header>
    <nav class="navbar">
        <div class="container">
            <ul>
                <li><a href="#"><i class="fas fa-home"></i> Главная</a></li>
                <li><a href="#"><i class="fas fa-book-open"></i> Рецепты</a></li>
                <li><a href="#"><i class="fas fa-award"></i> Сертификаты</a></li>
                <li><a href="#"><i class="fas fa-phone"></i> Контакты</a></li>
                <li><a href="#"><i class="fas fa-user"></i> О нас</a></li>
            </ul>
        </div>
    </nav>
    <main class="container">
        <section class="hero">
            <div class="hero-content">
                <h2>Премиальная кухня для гурманов</h2>
                <p>Откройте для себя мир изысканных вкусов и авторских рецептов</p>
                <a href="#" class="btn btn-primary">Наши рецепты</a>
                <a href="#certificates" class="btn btn-secondary">Наши сертификаты</a>
            </div>
            <div class="hero-image">
                <img src="https://images.unsplash.com/photo-1606787366850-de6330128bfc?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Изысканная кухня">
            </div>
        </section>
        <section class="features">
            <div class="feature-card">
                <i class="fas fa-star"></i>
                <h3>Проверенные рецепты</h3>
                <p>Только лучшие, проверенные временем рецепты</p>
            </div>
            <div class="feature-card">
                <i class="fas fa-leaf"></i>
                <h3>Эко-продукты</h3>
                <p>Используем органические продукты высшего качества</p>
            </div>
            <div class="feature-card">
                <i class="fas fa-medal"></i>
                <h3>Профессионализм</h3>
                <p>Команда сертифицированных шеф-поваров</p>
            </div>
        </section>
        <section id="certificates" class="certificates">
            <h2 class="section-title">Наши сертификаты и награды</h2>
            <p class="section-subtitle">Мы гордимся нашими достижениями и гарантируем качество</p> 
            <div class="certificate-grid">
                <div class="certificate-card">
                    <div class="certificate-img">
                        <img src="https://images.unsplash.com/photo-1600857544200-b2f666a9a2ec?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Сертификат ISO">
                        <div class="overlay">
                            <a href="#" class="view-btn">Посмотреть</a>
                        </div>
                    </div>
                    <h3>ISO 9001:2015</h3>
                    <p>Международный стандарт качества</p>
                    <span class="cert-date">Выдан: 15.05.2022</span>
                </div>   
                <div class="certificate-card">
                    <div class="certificate-img">
                        <img src="https://images.unsplash.com/photo-1604594849809-dfedbc827105?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Органик сертификат">
                        <div class="overlay">
                            <a href="#" class="view-btn">Посмотреть</a>
                        </div>
                    </div>
                    <h3>Organic Certified</h3>
                    <p>Сертификат органических продуктов</p>
                    <span class="cert-date">Выдан: 10.03.2023</span>
                </div>
                
                <div class="certificate-card">
                    <div class="certificate-img">
                        <img src="https://images.unsplash.com/photo-1541167760496-1628856ab772?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1637&q=80" alt="Награда">
                        <div class="overlay">
                            <a href="#" class="view-btn">Посмотреть</a>
                        </div>
                    </div>
                    <h3>Best Kitchen 2023</h3>
                    <p>Лучшая кухня года по версии GMA</p>
                    <span class="cert-date">Выдан: 28.01.2023</span>
                </div>
            </div>
        </section>
        <section class="testimonials">
            <h2 class="section-title">Отзывы наших клиентов</h2>
            <div class="testimonial-slider">
                <div class="testimonial-card">
                    <img src="https://randomuser.me/api/portraits/women/43.jpg" alt="Мария">
                    <p>"Рецепты от Gourmet Kitchen изменили мое отношение к готовке. Теперь я получаю удовольствие от процесса!"</p>
                    <div class="rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <h4>Мария Иванова</h4>
                </div>
            </div>
        </section>
    </main>
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Gourmet Kitchen</h3>
                    <p>Ваш проводник в мир высокой кухни и гастрономического удовольствия</p>
                </div>
                <div class="footer-section">
                    <h3>Контакты</h3>
                    <p><i class="fas fa-map-marker-alt"></i> Москва, ул. Гастрономическая, 15</p>
                    <p><i class="fas fa-phone"></i> +7 (495) 123-45-67</p>
                    <p><i class="fas fa-envelope"></i> info@gourmet-kitchen.ru</p>
                </div>
                <div class="footer-section">
                    <h3>Подписаться</h3>
                    <form class="subscribe-form">
                        <input type="email" placeholder="Ваш email">
                        <button type="submit"><i class="fas fa-paper-plane"></i></button>
                    </form>
                    <div class="social-icons">
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-facebook"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2023 Gourmet Kitchen. Все права защищены.</p>
                <div class="cert-badges">
                    <img src="https://via.placeholder.com/80x50?text=ISO" alt="ISO Certified">
                    <img src="https://via.placeholder.com/80x50?text=Organic" alt="Organic Certified">
                </div>
            </div>
        </div>
    </footer>
</body>
</html>
