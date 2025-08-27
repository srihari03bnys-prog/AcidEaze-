# AcidEaze-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AcidEaze - Herbal Comfort</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(180deg, #f7fff8 0%, #eafaf0 100%);
      color: #1a3d2f;
    }
    header {
      background: linear-gradient(90deg, #2e7d32, #66bb6a);
      color: white;
      padding: 30px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.12);
    }
    header h1 {
      margin: 0;
      font-size: 2.6em;
    }
    header p { font-style: italic; font-size: 1.05em; margin-top:6px; }

    .container { max-width: 980px; margin: 26px auto; padding: 0 16px; }

    section.card {
      padding: 28px;
      background: rgba(255,255,255,0.95);
      margin: 18px 0;
      border-radius: 12px;
      box-shadow: 0 6px 14px rgba(0,0,0,0.06);
    }

    .product-image { text-align: center; margin-bottom: 10px; }
    .product-image img { width: 240px; max-width: 45%; border-radius: 14px; margin: 8px; box-shadow: 0 6px 10px rgba(0,0,0,0.12); }

    h2 { color: #2e7d32; margin-bottom: 10px; }
    ul { line-height: 1.7; }

    .buy-btn {
      display: inline-block;
      padding: 12px 22px;
      margin-top: 12px;
      font-size: 1em;
      color: white;
      background: #2e7d32;
      border-radius: 28px;
      text-decoration: none;
      transition: background 0.25s;
    }
    .buy-btn:hover { background: #1b5e20; }

    table.specs {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    table.specs th, table.specs td {
      border: 1px solid #e6efe7;
      padding: 8px 10px;
      text-align: left;
    }
    table.specs th { background:#f1fbf4; color:#1b4f36; }

    .note { font-size: 0.95em; color: #555; margin-top: 10px; }

    footer {
      text-align: center;
      padding: 18px;
      background: #2e7d32;
      color: white;
      margin-top: 28px;
      border-radius: 0 0 8px 8px;
    }

    /* Buy Now form styling */
    .order-form input, .order-form textarea, .order-form select {
      width: 100%; padding: 8px; margin-bottom: 12px; border-radius: 6px; border: 1px solid #ccc;
    }
    .order-form button {
      background:#007bff; color:white; padding:10px 20px; border:none; border-radius:8px; cursor:pointer;
    }
    .order-form button:hover { background:#0056b3; }

    @media (max-width:700px){
      .product-image img{ width: 46%; max-width:140px; }
    }
  </style>
</head>
<body>
  <header>
    <h1>🌿 AcidEaze</h1>
    <p>Herbal Comfort In Every Sip — Natural relief for acidity & indigestion</p>
  </header>

  <div class="container">

    <section class="card">
      <h2>Our Product</h2>
      <div class="product-image">
        <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Indian_Gooseberries.jpg" alt="Amla (Indian Gooseberry)">
        <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Capsule.png" alt="Green Capsule">
      </div>

      <p><strong>AcidEaze</strong> is available as a <strong>powder</strong> and a <strong>300 mg capsule</strong>. It uses traditional herbal ingredients to help relieve acidity and support digestion.</p>
      <a href="#buy-now" class="buy-btn">🛒 Buy Now</a>
    </section>

    <section class="card">
      <h2>Composition (per 1 capsule — 300 mg)</h2>
      <table class="specs" aria-label="Composition table">
        <thead>
          <tr><th>Ingredient</th><th>Amount per capsule (mg)</th><th>Notes</th></tr>
        </thead>
        <tbody>
          <tr><td>Amla powder</td><td>120 mg</td><td>Rich source of Vitamin C (herbal powder)</td></tr>
          <tr><td>Ajwain (carom seed) powder</td><td>50 mg</td><td>Carminative — relieves gas</td></tr>
          <tr><td>Jeera (cumin) powder</td><td>40 mg</td><td>Cooling, supports digestion</td></tr>
          <tr><td>Saunf (fennel) powder</td><td>30 mg</td><td>Natural antacid/carminative</td></tr>
          <tr><td>Licorice extract</td><td>30 mg</td><td>Supports mucosal healing</td></tr>
          <tr><td>Rock salt</td><td>10 mg</td><td>Digestive mineral (small amount)</td></tr>
          <tr><td>Mishri (crystallized sugar)</td><td>15 mg</td><td>Cooling sweetener</td></tr>
          <tr><td>Microcrystalline cellulose (excipient)</td><td>5 mg</td><td>Capsule filler / flow aid</td></tr>
          <tr><th>Total</th><th>300 mg</th><th></th></tr>
        </tbody>
      </table>
      <p class="note"><strong>Note:</strong> This composition was arranged to total 300 mg (capsule fill). If you will sell commercially, get the final formulation and analytical test report from your production lab for labeling and regulatory compliance.</p>
    </section>

    <section class="card">
      <h2>Approximate Nutrition (per 1 capsule — 300 mg)</h2>
      <table class="specs" aria-label="Nutrition facts">
        <tbody>
          <tr><th>Energy</th><td>≈ 1 kcal</td></tr>
          <tr><th>Total Carbohydrates</th><td>≈ 0.24 g (240 mg)</td></tr>
          <tr><th>Dietary Fiber</th><td>≈ 0.05 g (50 mg)</td></tr>
          <tr><th>Protein</th><td>≈ 0.01 g (10 mg)</td></tr>
          <tr><th>Total Fat</th><td>≈ 0.002 g (2 mg)</td></tr>
          <tr><th>Sugars</th><td>≈ 0.015 g (15 mg) — from mishri</td></tr>
          <tr><th>Sodium</th><td>≈ 4 mg (from 10 mg rock salt)</td></tr>
        </tbody>
      </table>
      <p class="note">These nutrition values are <strong>approximate estimates</strong> for a 300 mg herbal capsule — actual values depend on raw-material assay and processing. For accurate nutrition facts (legal label), please run a lab analysis (nutritional assay) for the final batch.</p>
    </section>

    <section class="card">
      <h2>Key Ingredients & Benefits</h2>
      <ul>
        <li><b>Amla</b> – Vitamin C rich, helps reduce acidity and oxidative stress</li>
        <li><b>Ajwain</b> – Relieves gas and bloating</li>
        <li><b>Jeera</b> – Cooling and gut-friendly</li>
        <li><b>Saunf</b> – Helps soothe stomach, natural antacid</li>
        <li><b>Licorice</b> – Supports mucosal healing</li>
        <li><b>Rock Salt</b> – Trace mineral to aid digestion</li>
      </ul>
    </section>

    <!-- ================= Buy Now Section ================= -->
    <section class="card" id="buy-now">
      <h2>Buy Now</h2>
      <p>Order your <strong>AcidEaze Herbal Capsules</strong> today!</p>

      <!-- Product card -->
      <div>
        <img src="https://commons.wikimedia.org/wiki/Special:FilePath/Capsule.png" 
             alt="AcidEaze Capsule Bottle" style="width:160px; border-radius:12px; box-shadow:0 4px 8px rgba(0,0,0,0.15);">
        <h3>AcidEaze Capsules</h3>
        <p>Natural herbal formula for digestive comfort</p>
        <p><strong>₹299</strong> per bottle (30 capsules)</p>
        <button class="buy-btn" onclick="document.getElementById('order-form').style.display='block'">
          Buy Now
        </button>
      </div>

      <!-- Hidden Order Form -->
      <div id="order-form" style="display:none; margin-top:1.5rem;" class="order-form">
        <h3>Order Form</h3>
        <form>
          <label for="name">Full Name:</label>
          <input type="text" id="name" name="name" required>

          <label for="address">Shipping Address:</label>
          <textarea id="address" name="address" required></textarea>

          <label for="phone">Phone Number:</label>
          <input type="tel" id="phone" name="phone" required>

          <label for="quantity">Quantity:</label>
          <select id="quantity" name="quantity">
            <option value="1">1 Bottle</option>
            <option value="2">2 Bottles</option>
            <option value="3">3 Bottles</option>
          </select>

          <h4>Choose Payment Method:</h4>
          <input type="radio" id="cod" name="payment" value="cod" checked>
          <label for="cod">Cash on Delivery (COD)</label><br>

          <input type="radio" id="upi" name="payment" value="upi">
          <label for="upi">UPI / QR Code</label><br>

          <input type="radio" id="card" name="payment" value="card">
          <label for="card">Credit / Debit Card</label><br><br>

          <button type="submit">Confirm Order</button>
        </form>
      </div>
    </section>

    <footer>
      <p>🌿 AcidEaze – Natural relief for your digestion</p>
      <p style="font-size:0.88em; margin-top:6px;">Tip: to avoid broken images, either host images locally in your project folder or use the Wikimedia links above which are stable and free-to-use (see attribution rules below).</p>
    </footer>
  </div>
</body>
</html>
