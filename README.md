<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Hydraulics & Pneumatics Product Catalog</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f5f5f5; }
    header { background: #2263a5; color: #fff; padding: 1em; text-align: center; }
    .container { max-width: 1100px; margin: 2em auto; padding: 2em; background: #fff; border-radius: 10px; }
    h1 { margin-bottom: 0.5em; }
    .products { display: flex; flex-wrap: wrap; gap: 2em; }
    .product { flex: 1 1 350px; background: #f9f9f9; border-radius: 8px; box-shadow: 0 0 10px #eee; padding: 1em; }
    .product img, .product .sketchfab-embed-wrapper { max-width: 100%; border-radius: 6px; }
    .product h2 { font-size: 1.3em; margin: 0.5em 0; }
    .product p { color: #333; }
    .price { color: #2263a5; font-weight: bold; margin-top: 0.5em; }
    .inquiry { display: block; margin: 1em 0 0; padding: 0.5em 1em; background: #2263a5; color: #fff; border: none; border-radius: 4px; cursor: pointer; text-decoration: none; }
    @media (max-width: 700px) {
      .products { flex-direction: column; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Hydraulics & Pneumatics Sales Catalog</h1>
    <p>Quality components for industrial and commercial applications</p>
  </header>
  <div class="container">
    <div class="products">
      <!-- Product 1: Example with Image -->
      <div class="product">
        <img src="hydraulic-cylinder.jpg" alt="Hydraulic Cylinder">
        <h2>Hydraulic Cylinder</h2>
        <p>Heavy-duty cylinder for industrial machinery, high-pressure rating.</p>
        <div class="price">$250.00</div>
        <a href="mailto:sales@yourdomain.com?subject=Inquiry: Hydraulic Cylinder" class="inquiry">Inquire</a>
      </div>
      <!-- Product 2: Example with Sketchfab 3D Embed -->
      <div class="product">
        <div class="sketchfab-embed-wrapper">
          <iframe title="3D Model" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true"
            width="100%" height="300"
            src="https://sketchfab.com/models/your-model-id/embed">
          </iframe>
        </div>
        <h2>Pneumatic Valve (3D Model)</h2>
        <p>Precision control valve, view in 3D for details.</p>
        <div class="price">$180.00</div>
        <a href="mailto:sales@yourdomain.com?subject=Inquiry: Pneumatic Valve" class="inquiry">Inquire</a>
      </div>
      <!-- Product 3: Example with Image -->
      <div class="product">
        <img src="air-compressor.jpg" alt="Air Compressor">
        <h2>Air Compressor</h2>
        <p>Efficient air compressor for shop and field use.</p>
        <div class="price">$550.00</div>
        <a href="mailto:sales@yourdomain.com?subject=Inquiry: Air Compressor" class="inquiry">Inquire</a>
      </div>
      <!-- Add more products as needed -->
    </div>
  </div>
</body>
</html>
