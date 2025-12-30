<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StepStyle - Premium Shoe Store</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
        }

        header {
            background: rgba(255, 255, 255, 0.95);
            padding: 20px 0;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }

        .logo {
            font-size: 28px;
            font-weight: bold;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .nav-links {
            display: flex;
            gap: 30px;
            list-style: none;
        }

        .nav-links a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            transition: color 0.3s;
            cursor: pointer;
        }

        .nav-links a:hover {
            color: #667eea;
        }

        .hero {
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 20px;
            text-align: center;
            color: white;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 30px;
        }

        .video-section {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .video-container {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
        }

        .video-container video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border-radius: 15px;
        }

        .products {
            max-width: 1200px;
            margin: 60px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            font-size: 36px;
            color: white;
            margin-bottom: 40px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .product-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.3);
        }

        .product-image {
            width: 100%;
            height: 250px;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 80px;
        }

        .product-info {
            padding: 20px;
        }

        .product-name {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .product-price {
            font-size: 24px;
            color: #667eea;
            font-weight: bold;
            margin-bottom: 15px;
        }

        .btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            padding: 12px 30px;
            border-radius: 25px;
            font-size: 16px;
            cursor: pointer;
            transition: transform 0.3s, box-shadow 0.3s;
            font-weight: bold;
        }

        .btn:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }

        .contact-section {
            max-width: 800px;
            margin: 60px auto;
            padding: 40px;
            background: white;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #333;
        }

        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 12px;
            border: 2px solid #e0e0e0;
            border-radius: 8px;
            font-size: 16px;
            transition: border-color 0.3s;
        }

        .form-group input:focus,
        .form-group textarea:focus,
        .form-group select:focus {
            outline: none;
            border-color: #667eea;
        }

        .file-upload {
            border: 2px dashed #667eea;
            padding: 30px;
            text-align: center;
            border-radius: 8px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .file-upload:hover {
            background: #f5f7fa;
        }

        .file-upload input {
            display: none;
        }

        footer {
            background: rgba(255, 255, 255, 0.95);
            padding: 40px 20px;
            text-align: center;
            margin-top: 60px;
        }

        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.7);
            z-index: 2000;
            align-items: center;
            justify-content: center;
        }

        .modal-content {
            background: white;
            padding: 40px;
            border-radius: 15px;
            max-width: 500px;
            text-align: center;
            animation: slideIn 0.3s ease-out;
        }

        @keyframes slideIn {
            from {
                transform: translateY(-50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        .close-modal {
            margin-top: 20px;
        }

        .success-icon {
            font-size: 60px;
            color: #4CAF50;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">👟 StepStyle</div>
            <ul class="nav-links">
                <li><a onclick="document.getElementById('home').scrollIntoView({behavior: 'smooth'})">Home</a></li>
                <li><a onclick="document.getElementById('products').scrollIntoView({behavior: 'smooth'})">Products</a></li>
                <li><a onclick="document.getElementById('video').scrollIntoView({behavior: 'smooth'})">Gallery</a></li>
                <li><a onclick="document.getElementById('contact').scrollIntoView({behavior: 'smooth'})">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Step Into Style</h1>
        <p>Discover the perfect shoes for every occasion</p>
        <button class="btn" onclick="document.getElementById('products').scrollIntoView({behavior: 'smooth'})">
            Shop Now
        </button>
    </section>

    <section class="video-section" id="video">
        <h2 class="section-title">Watch Our Collection</h2>
        <div class="video-container">
            <video controls poster="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 800 450'%3E%3Crect fill='%23667eea' width='800' height='450'/%3E%3Ctext x='50%25' y='50%25' dominant-baseline='middle' text-anchor='middle' font-size='60' fill='white'%3E👟 Shoe Collection%3C/text%3E%3C/svg%3E">
                <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
    </section>

    <section class="products" id="products">
        <h2 class="section-title">Featured Products</h2>
        <div class="product-grid">
            <div class="product-card">
                <div class="product-image">👟</div>
                <div class="product-info">
                    <h3 class="product-name">Sport Runner Pro</h3>
                    <p class="product-price">$89.99</p>
                    <button class="btn" onclick="addToCart('Sport Runner Pro', 89.99)">Add to Cart</button>
                </div>
            </div>

            <div class="product-card">
                <div class="product-image">👞</div>
                <div class="product-info">
                    <h3 class="product-name">Classic Leather</h3>
                    <p class="product-price">$129.99</p>
                    <button class="btn" onclick="addToCart('Classic Leather', 129.99)">Add to Cart</button>
                </div>
            </div>

            <div class="product-card">
                <div class="product-image">🥾</div>
                <div class="product-info">
                    <h3 class="product-name">Adventure Boot</h3>
                    <p class="product-price">$149.99</p>
                    <button class="btn" onclick="addToCart('Adventure Boot', 149.99)">Add to Cart</button>
                </div>
            </div>

            <div class="product-card">
                <div class="product-image">👠</div>
                <div class="product-info">
                    <h3 class="product-name">Elegant Heel</h3>
                    <p class="product-price">$99.99</p>
                    <button class="btn" onclick="addToCart('Elegant Heel', 99.99)">Add to Cart</button>
                </div>
            </div>
        </div>
    </section>

    <section class="contact-section" id="contact">
        <h2 class="section-title" style="color: #333;">Contact Us</h2>
        <form id="contactForm" onsubmit="handleSubmit(event)">
            <div class="form-group">
                <label for="name">Full Name</label>
                <input type="text" id="name" name="name" required>
            </div>

            <div class="form-group">
                <label for="email">Email Address</label>
                <input type="email" id="email" name="email" required>
            </div>

            <div class="form-group">
                <label for="phone">Phone Number</label>
                <input type="tel" id="phone" name="phone" required>
            </div>

            <div class="form-group">
                <label for="size">Shoe Size</label>
                <select id="size" name="size" required>
                    <option value="">Select Size</option>
                    <option value="6">6</option>
                    <option value="7">7</option>
                    <option value="8">8</option>
                    <option value="9">9</option>
                    <option value="10">10</option>
                    <option value="11">11</option>
                    <option value="12">12</option>
                </select>
            </div>

            <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" name="message" rows="4" required></textarea>
            </div>

            <div class="form-group">
                <label>Upload Image/Document (Optional)</label>
                <div class="file-upload" onclick="document.getElementById('fileInput').click()">
                    <input type="file" id="fileInput" accept="image/*,.pdf,.doc,.docx">
                    <p>📎 Click to upload or drag and drop</p>
                    <p style="font-size: 14px; color: #666;">Supports: Images, PDF, DOC</p>
                </div>
            </div>

            <button type="submit" class="btn" style="width: 100%;">Submit Inquiry</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 StepStyle. All rights reserved.</p>
        <p>Follow us on social media for exclusive offers!</p>
    </footer>

    <div id="successModal" class="modal">
        <div class="modal-content">
            <div class="success-icon">✓</div>
            <h2>Success!</h2>
            <p id="modalMessage">Your item has been added to cart.</p>
            <button class="btn close-modal" onclick="closeModal()">Close</button>
        </div>
    </div>

    <script>
        function addToCart(productName, price) {
            const modal = document.getElementById('successModal');
            const message = document.getElementById('modalMessage');
            message.textContent = `${productName} ($${price}) has been added to your cart!`;
            modal.style.display = 'flex';
        }

        function handleSubmit(event) {
            event.preventDefault();
            const modal = document.getElementById('successModal');
            const message = document.getElementById('modalMessage');
            message.textContent = 'Thank you for your inquiry! We will contact you soon.';
            modal.style.display = 'flex';
            document.getElementById('contactForm').reset();
        }

        function closeModal() {
            document.getElementById('successModal').style.display = 'none';
        }

        document.getElementById('fileInput').addEventListener('change', function(e) {
            const fileName = e.target.files[0]?.name;
            if (fileName) {
                const uploadDiv = document.querySelector('.file-upload');
                uploadDiv.innerHTML = `<p>✅ File uploaded: ${fileName}</p>`;
            }
        });

        window.onclick = function(event) {
            const modal = document.getElementById('successModal');
            if (event.target === modal) {
                modal.style.display = 'none';
            }
        }
    </script>
</body>
</html>
