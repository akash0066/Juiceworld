<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>JuiceWorld – Global Cold-Pressed Juices</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html { scroll-behavior: smooth; }
    .hero-bg {
      background: url('https://images.unsplash.com/photo-1585325701961-5938dc45cb86') no-repeat center center/cover;
    }
  </style>
</head>
<body class="text-gray-800 font-sans bg-white">

  <!-- Navbar -->
  <header class="fixed top-0 left-0 w-full bg-white shadow z-50">
    <div class="container mx-auto flex justify-between items-center p-4">
      <h1 class="text-2xl font-bold text-green-600">JuiceWorld</h1>
      <nav class="space-x-4 text-sm font-medium">
        <a href="#home" class="hover:text-green-500">Home</a>
        <a href="#juices" class="hover:text-green-500">Juices</a>
        <a href="#benefits" class="hover:text-green-500">Why Us</a>
        <a href="#testimonials" class="hover:text-green-500">Testimonials</a>
        <a href="#checkout" class="hover:text-green-500">Checkout</a>
        <a href="#contact" class="hover:text-green-500">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="hero-bg h-screen flex items-center justify-center text-center text-white relative">
    <div class="bg-black bg-opacity-60 p-10 rounded" data-aos="fade-up">
      <h2 class="text-5xl font-bold mb-4">Taste Nature, Globally.</h2>
      <p class="text-lg">Premium cold-pressed juices from the finest fruits across continents.</p>
    </div>
  </section>

  <!-- Juices Section -->
  <section id="juices" class="py-20 px-4 bg-yellow-50">
    <div class="container mx-auto text-center">
      <h3 class="text-3xl font-semibold mb-10" data-aos="fade-down">Our Juices by Category</h3>
      <div id="juiceContent" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Mango_juice_in_a_glass.jpg" alt="Mango Magic" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Mango Magic</h4>
      <p class="text-green-600 font-bold">₹120</p>
      <button onclick="addToCart('Mango Magic', 120)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://upload.wikimedia.org/wikipedia/commons/5/57/Pineapple_juice.jpg" alt="Pineapple Kick" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Pineapple Kick</h4>
      <p class="text-green-600 font-bold">₹110</p>
      <button onclick="addToCart('Pineapple Kick', 110)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://images.unsplash.com/photo-1634213439233-2b5e541df7e0" alt="Coconut Recharge" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Coconut Recharge</h4>
      <p class="text-green-600 font-bold">₹100</p>
      <button onclick="addToCart('Coconut Recharge', 100)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://images.unsplash.com/photo-1621421416605-3a52c55f7a91" alt="Green Cleanse" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Green Cleanse</h4>
      <p class="text-green-600 font-bold">₹130</p>
      <button onclick="addToCart('Green Cleanse', 130)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://images.unsplash.com/photo-1590080876178-3d16c651aac7" alt="Lemon Ginger Zing" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Lemon Ginger Zing</h4>
      <p class="text-green-600 font-bold">₹95</p>
      <button onclick="addToCart('Lemon Ginger Zing', 95)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://images.unsplash.com/photo-1582550945154-66ea8fff1b5c" alt="Cucumber Cooler" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Cucumber Cooler</h4>
      <p class="text-green-600 font-bold">₹105</p>
      <button onclick="addToCart('Cucumber Cooler', 105)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/7b/Orange_juice_1_edit1.jpg" alt="Orange Immuno" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Orange Immuno</h4>
      <p class="text-green-600 font-bold">₹140</p>
      <button onclick="addToCart('Orange Immuno', 140)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85c" alt="Turmeric Tonic" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Turmeric Tonic</h4>
      <p class="text-green-600 font-bold">₹135</p>
      <button onclick="addToCart('Turmeric Tonic', 135)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://images.unsplash.com/photo-1609171744479-813fe5b85d38" alt="Beet Booster" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Beet Booster</h4>
      <p class="text-green-600 font-bold">₹125</p>
      <button onclick="addToCart('Beet Booster', 125)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://images.unsplash.com/photo-1615485923126-01e0c163c980" alt="Strawberry Fizz" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Strawberry Fizz</h4>
      <p class="text-green-600 font-bold">₹145</p>
      <button onclick="addToCart('Strawberry Fizz', 145)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://images.unsplash.com/photo-1590080876196-1a68751fdb9e" alt="Lychee Glow" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Lychee Glow</h4>
      <p class="text-green-600 font-bold">₹150</p>
      <button onclick="addToCart('Lychee Glow', 150)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    
    <div class="bg-white shadow-md rounded-lg p-4" data-aos="fade-up">
      <img src="https://images.unsplash.com/photo-1585238341986-51f1e7495a93" alt="Kiwi Mint" class="rounded w-full h-40 object-cover mb-3">
      <h4 class="text-lg font-semibold">Kiwi Mint</h4>
      <p class="text-green-600 font-bold">₹130</p>
      <button onclick="addToCart('Kiwi Mint', 130)" class="mt-2 bg-green-500 text-white px-3 py-1 rounded hover:bg-green-600 text-sm">Add to Cart</button>
    </div>
    </div></div>
    </div>
  </section>

  <!-- Why Choose Us -->
  <section id="benefits" class="py-20 bg-white">
    <div class="container mx-auto text-center max-w-4xl" data-aos="fade-up">
      <h3 class="text-3xl font-semibold mb-6">Why Choose JuiceWorld?</h3>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8 text-left text-lg">
        <div>
          <h4 class="font-bold text-green-600">🍃 Cold-Pressed Freshness</h4>
          <p>Our advanced cold-pressing keeps nutrients alive. No heat. No preservatives.</p>
        </div>
        <div>
          <h4 class="font-bold text-green-600">🌍 Global Fruit Sourcing</h4>
          <p>We bring together exotic fruits from India, Brazil, New Zealand, and beyond.</p>
        </div>
        <div>
          <h4 class="font-bold text-green-600">🔬 Nutritionist Approved</h4>
          <p>All blends are curated by certified nutrition experts for health-first impact.</p>
        </div>
        <div>
          <h4 class="font-bold text-green-600">♻️ Eco-Friendly Packaging</h4>
          <p>100% recyclable bottles. Carbon-neutral supply chain. Love your planet too.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section id="testimonials" class="py-20 bg-green-50 text-center">
    <div class="container mx-auto max-w-3xl" data-aos="fade-up">
      <h3 class="text-3xl font-semibold mb-6">What Our Customers Say</h3>
      <blockquote class="italic text-xl mb-4">"JuiceWorld transformed my mornings. I feel healthier and fresher every day!"</blockquote>
      <p class="font-bold">– Ananya, Bengaluru</p>
      <blockquote class="italic text-xl mt-10 mb-4">"Amazing taste and eco values. Can't start my day without Mango Magic."</blockquote>
      <p class="font-bold">– Lucas, Berlin</p>
    </div>
  </section>

  <!-- Checkout Summary Placeholder -->
  
<section id="checkout" class="py-20 bg-white text-center" data-aos="fade-up">
  <h3 class="text-3xl font-semibold mb-6">Checkout</h3>
  <div class="max-w-xl mx-auto text-left bg-gray-50 p-6 rounded shadow">
    <form id="checkoutForm" onsubmit="submitCheckout(event)" class="space-y-4">
      <div>
        <label class="block font-semibold mb-1">Full Name</label>
        <input type="text" required class="w-full px-4 py-2 border rounded" placeholder="John Doe" />
      </div>
      <div>
        <label class="block font-semibold mb-1">Delivery Address</label>
        <textarea required class="w-full px-4 py-2 border rounded" placeholder="123 Main Street, City, Country"></textarea>
      </div>
      <div>
        <label class="block font-semibold mb-1">Payment Method</label>
        <select required class="w-full px-4 py-2 border rounded">
          <option value="card">Credit/Debit Card</option>
          <option value="upi">UPI</option>
          <option value="cod">Cash on Delivery</option>
        </select>
      </div>
      <button type="submit" class="w-full bg-green-600 text-white py-2 rounded hover:bg-green-700">Place Order</button>
    </form>
    <div id="confirmationMessage" class="mt-4 text-green-600 font-bold hidden text-center">✅ Your order has been placed successfully!</div>
  </div>
</section>

    <h3 class="text-3xl font-semibold mb-4">Cart & Checkout</h3>
    <div id="cartSummary" class="mt-6 bg-gray-100 p-6 rounded shadow-md max-w-md mx-auto text-left text-sm">Cart summary will appear here.</div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 px-4 bg-gray-100">
    <div class="container mx-auto text-center max-w-xl" data-aos="zoom-in">
      <h3 class="text-3xl font-semibold mb-4">Contact Us</h3>
      <p>Email: hello@juiceworld.com</p>
      <p>Phone: +91 9876543210</p>
      <p class="text-sm text-gray-600 mt-2">We’re available 7 days a week!</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center text-sm py-6 bg-gray-800 text-white">
    &copy; 2025 JuiceWorld. All rights reserved.
  </footer>

  <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
  <script>AOS.init();</script>


<script>
  let cart = [];

  function addToCart(product, price) {
    cart.push({ name: product, price: price });
    updateCartDisplay();
  }

  function updateCartDisplay() {
    const summary = document.getElementById("cartSummary");
    const total = cart.reduce((sum, item) => sum + item.price, 0);
    const list = cart.map(item => `<li>${item.name} - ₹${item.price}</li>`).join("");
    summary.innerHTML = cart.length
      ? `<ul class="text-left list-disc ml-6 mb-2">${list}</ul><p class='font-semibold'>Total: ₹${total}</p>`
      : "<p>Your cart is empty.</p>";
  }
</script>


<script>
function submitCheckout(e) {
  e.preventDefault();
  document.getElementById("confirmationMessage").classList.remove("hidden");
  cart = [];
  updateCartDisplay();
}
</script>

</body>
</html>
