<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SoulSide™ - Áo Cặp Đôi Cao Cấp | Chính Hãng</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    * { font-family: 'Inter', sans-serif; }
    
    .gradient-bg { background: linear-gradient(135deg, #ff6b9d 0%, #c44569 50%, #f8b500 100%); }
    .product-image { transition: transform 0.3s ease; }
    .product-image:hover { transform: scale(1.05); }
    
    .sticky-cta {
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
      background: linear-gradient(90deg, #ff6b9d, #c44569);
      color: white;
      padding: 16px 20px;
      text-align: center;
      z-index: 1000;
      box-shadow: 0 -4px 20px rgba(0,0,0,0.15);
      display: none;
    }
    
    @media (max-width: 768px) {
      .sticky-cta { display: block; }
      body { padding-bottom: 80px; }
    }
    
    .feature-card {
      transition: all 0.3s ease;
      border: 2px solid transparent;
    }
    .feature-card:hover {
      transform: translateY(-4px);
      border-color: #ff6b9d;
      box-shadow: 0 10px 30px rgba(255, 107, 157, 0.2);
    }
    
    .size-option {
      transition: all 0.2s ease;
      cursor: pointer;
    }
    .size-option:hover {
      background: #ff6b9d;
      color: white;
    }
    .size-option.selected {
      background: #c44569;
      color: white;
      border-color: #c44569;
    }
    
    .quantity-btn {
      transition: all 0.2s ease;
    }
    .quantity-btn:hover {
      background: #ff6b9d;
      color: white;
    }
    
    .pulse-animation {
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.05); }
    }
    
    .fade-in {
      animation: fadeIn 0.8s ease-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    
    .review-stars {
      color: #fbbf24;
    }
    
    .trust-badge {
      background: linear-gradient(45deg, #10b981, #059669);
      color: white;
      padding: 8px 16px;
      border-radius: 20px;
      font-size: 12px;
      font-weight: 600;
    }
  </style>
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Header -->
  <header class="bg-white shadow-lg sticky top-0 z-50">
    <div class="max-w-6xl mx-auto px-4 py-4">
      <div class="flex items-center justify-between">
        <div class="flex items-center space-x-3">
          <div class="w-12 h-12 gradient-bg rounded-full flex items-center justify-center">
            <i class="fas fa-heart text-white text-xl"></i>
          </div>
          <div>
            <h1 class="text-2xl font-bold text-gray-800">SoulSide™</h1>
            <p class="text-xs text-gray-500">Couple Fashion Brand</p>
          </div>
        </div>
        
        <div class="flex items-center space-x-4">
          <div class="trust-badge">
            <i class="fas fa-shield-alt mr-1"></i>
            Chính hãng 100%
          </div>
          <div class="hidden md:flex items-center space-x-2 text-sm text-gray-600">
            <i class="fas fa-phone text-pink-500"></i>
            <span>Hotline: 1900-xxxx</span>
          </div>
        </div>
      </div>
    </div>
  </header>

  <!-- Banner -->
  <section class="gradient-bg text-white text-center py-8 fade-in">
    <div class="max-w-4xl mx-auto px-4">
      <h1 class="text-4xl md:text-5xl font-bold mb-4">
        SoulSide™ Collection
        <span class="block text-2xl md:text-3xl font-normal mt-2">Áo Cặp Đôi Giới Hạn</span>
      </h1>
      <div class="flex items-center justify-center space-x-6 mt-6">
        <div class="flex items-center space-x-1">
          <div class="review-stars">
