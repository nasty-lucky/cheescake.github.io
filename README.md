<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Delightful handcrafted cheesecakes for any occasion">
    <title>Sweet Delights | Premium Cheesecakes</title>
    
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <nav class="main-nav">
            <div class="container nav-container">
                <a href="#" class="logo">Sweet Delights</a>
                <div class="nav-links">
                    <a href="#hero">Home</a>
                    <a href="#about">About</a>
                    <a href="#cheesecakes">Cheesecakes</a>
                    <a href="#testimonials">Testimonials</a>
                    <a href="#contact">Contact</a>
                </div>
                <!-- Cart Icon -->
                <div class="cart-wrapper">
                    <button class="cart-trigger" aria-label="Open shopping cart">
                        <div class="cart-icon">🛒</div>
                        <span class="cart-count">0</span>
                    </button>
                </div>
            </div>
        </nav>
    </header>

    <!-- Cart Modal -->
    <div class="cart-modal" id="cartModal">
        <div class="cart-modal-content">
            <div class="cart-modal-header">
                <h2>Your Cart</h2>
                <button class="close-modal" aria-label="Close cart">&times;</button>
            </div>
            <div class="cart-items">
                <!-- Cart items will be dynamically added here -->
            </div>
            <div class="cart-summary">
                <div class="subtotal">
                    <span>Subtotal:</span>
                    <span class="subtotal-amount">$0.00</span>
                </div>
                <div class="tax">
                    <span>Tax (8%):</span>
                    <span class="tax-amount">$0.00</span>
                </div>
                <div class="total">
                    <span>Total:</span>
                    <span class="total-amount">$0.00</span>
                </div>
                <button class="checkout-btn">Proceed to Checkout</button>
            </div>
        </div>
    </div>

    <!-- Main Content -->
    <main>
        <!-- Hero Section -->
        <section id="hero" class="hero">
            <div class="container hero-container">
                <div class="hero-content">
                    <h1>Handcrafted Cheesecakes</h1>
                    <p class="hero-subtitle">Indulge in pure bliss with our premium artisanal cheesecakes</p>
                    <a href="#cheesecakes" class="cta-button">Explore Our Collection</a>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="about">
            <div class="container">
                <h2 class="section-title">Our Story</h2>
                <div class="about-content">
                    <div class="about-text">
                        <p>Since 2020, we've been crafting the finest cheesecakes using premium ingredients and time-honored recipes. Each creation is made with love and attention to detail.</p>
                    </div>
                    <div class="about-features">
                        <div class="feature-card">
                            <span class="feature-icon">🌟</span>
                            <h3>Premium Quality</h3>
                            <p>Finest ingredients for exceptional taste</p>
                        </div>
                        <div class="feature-card">
                            <span class="feature-icon">🌿</span>
                            <h3>Natural Ingredients</h3>
                            <p>No artificial preservatives</p>
                        </div>
                        <div class="feature-card">
                            <span class="feature-icon">🎨</span>
                            <h3>Artisanal Design</h3>
                            <p>Each cake is a masterpiece</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Cheesecakes Section -->
        <section id="cheesecakes" class="cheesecakes">
            <div class="container">
                <h2 class="section-title">Our Signature Cheesecakes</h2>
                <div class="cheesecakes-grid">
                    <!-- Classic New York -->
                    <div class="cheesecake-card" data-id="classic-ny">
                        <div class="image-container">
                            <img src="https://images.unsplash.com/photo-1524351199678-941a58a3df50" 
                                 alt="Classic New York Cheesecake"
                                 loading="lazy">
                        </div>
                        <div class="cheesecake-info">
                            <h3>Classic New York</h3>
                            <p>Rich and creamy classic recipe</p>
                            <div class="price-cart">
                                <span class="price">$45.00</span>
                                <button class="add-to-cart-btn">
                                    <span class="btn-text">Add to Cart</span>
                                </button>
                            </div>
                        </div>
                    </div>

                    <!-- Raspberry Swirl -->
                    <div class="cheesecake-card" data-id="raspberry-swirl">
                        <div class="image-container">
                            <img src="https://images.unsplash.com/photo-1533134242443-d4fd215305ad" 
                                 alt="Raspberry Swirl Cheesecake"
                                 loading="lazy">
                        </div>
                        <div class="cheesecake-info">
                            <h3>Raspberry Swirl</h3>
                            <p>Sweet and tangy raspberry perfection</p>
                            <div class="price-cart">
                                <span class="price">$48.00</span>
                                <button class="add-to-cart-btn">
                                    <span class="btn-text">Add to Cart</span>
                                </button>
                            </div>
                        </div>
                    </div>

                    <!-- Chocolate Dream -->
                    <div class="cheesecake-card" data-id="chocolate-dream">
                        <div class="image-container">
                            <img src="photo.png" 
                                 alt="Chocolate Dream Cheesecake"
                                 loading="lazy">
                        </div>
                        <div class="cheesecake-info">
                            <h3>Chocolate Dream</h3>
                            <p>Double chocolate indulgence</p>
                            <div class="price-cart">
                                <span class="price">$50.00</span>
                                <button class="add-to-cart-btn">
                                    <span class="btn-text">Add to Cart</span>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section id="testimonials" class="testimonials">
            <div class="container">
                <h2 class="section-title">What Our Customers Say</h2>
                <div class="testimonials-grid">
                    <div class="testimonial-card">
                        <div class="testimonial-content">
                            <p>"The best cheesecake I've ever tasted! Absolutely divine!"</p>
                            <div class="testimonial-author">
                                <span class="author-name">Sarah M.</span>
                                <div class="rating">⭐⭐⭐⭐⭐</div>
                            </div>
                        </div>
                    </div>
                    <div class="testimonial-card">
                        <div class="testimonial-content">
                            <p>"Perfect for special occasions. Everyone loved it!"</p>
                            <div class="testimonial-author">
                                <span class="author-name">Michael R.</span>
                                <div class="rating">⭐⭐⭐⭐⭐</div>
                            </div>
                        </div>
                    </div>
                    <div class="testimonial-card">
                        <div class="testimonial-content">
                            <p>"Exceptional quality and amazing taste. Will order again!"</p>
                            <div class="testimonial-author">
                                <span class="author-name">Emma L.</span>
                                <div class="rating">⭐⭐⭐⭐⭐</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact">
            <div class="container">
                <h2 class="section-title">Contact Us</h2>
                <div class="contact-content">
                    <form class="contact-form">
                        <div class="form-group">
                            <input type="text" id="name" name="name" required placeholder="Your Name">
                        </div>
                        <div class="form-group">
                            <input type="email" id="email" name="email" required placeholder="Your Email">
                        </div>
                        <div class="form-group">
                            <textarea id="message" name="message" required placeholder="Your Message"></textarea>
                        </div>
                        <button type="submit" class="submit-btn">Send Message</button>
                    </form>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-info">
                    <h3>Sweet Delights</h3>
                    <p>Handcrafted cheesecakes made with love</p>
                </div>
                <div class="footer-links">
                    <h4>Quick Links</h4>
                    <a href="#about">About Us</a>
                    <a href="#cheesecakes">Our Cheesecakes</a>
                    <a href="#contact">Contact</a>
                </div>
                <div class="footer-contact">
                    <h4>Contact Info</h4>
                    <p>📞 (555) 123-4567</p>
                    <p>📧 info@sweetdelights.com</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 Sweet Delights. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Cart Item Template -->
    <template id="cart-item-template">
        <div class="cart-item">
            <div class="cart-item-image">
                <img src="" alt="">
            </div>
            <div class="cart-item-info">
                <h3 class="cart-item-title"></h3>
                <div class="cart-item-price"></div>
                <div class="cart-item-controls">
                    <button class="quantity-btn minus">-</button>
                    <span class="quantity">1</span>
                    <button class="quantity-btn plus">+</button>
                    <button class="remove-item">Remove</button>
                </div>
            </div>
        </div>
    </template>

    <!-- Scripts -->
    <script src="app.js"></script>
</body>
</html>
