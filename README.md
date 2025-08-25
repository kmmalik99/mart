<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>USA Marketplace All in One</title>
    <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🛒</text></svg>">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap');

        /* --- Basic Reset & Body Styling --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f4f7f9;
            color: #333;
            line-height: 1.6;
        }

        /* --- Main Container --- */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        /* --- Header Styling --- */
        .header {
            text-align: center;
            padding: 2rem 0;
            border-bottom: 2px solid #e0e6ed;
            margin-bottom: 2rem;
        }

        .header h1 {
            font-size: 2.8rem;
            font-weight: 700;
            color: #1c3d5a;
        }

        .header p {
            font-size: 1.1rem;
            color: #5a7184;
            margin-top: 0.5rem;
        }

        /* --- Marketplace Grid --- */
        .marketplace-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
        }

        /* --- Marketplace Card Styling --- */
        .card {
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
            text-decoration: none;
            color: #333;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 2rem;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.12);
        }

        .card .logo {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .card .card-title {
            font-size: 1.4rem;
            font-weight: 600;
            color: #1c3d5a;
        }
        
        /* Specific brand colors for a nicer touch */
        .amazon:hover { border-bottom: 5px solid #FF9900; }
        .ebay:hover { border-bottom: 5px solid #E53238; }
        .walmart:hover { border-bottom: 5px solid #0071CE; }
        .offerup:hover { border-bottom: 5px solid #1D4ED8; }
        .houzz:hover { border-bottom: 5px solid #4DBC15; }
        .etsy:hover { border-bottom: 5px solid #F16521; }
        .facebook:hover { border-bottom: 5px solid #1877F2; }
        .craigslist:hover { border-bottom: 5px solid #8A2BE2; }
        .poshmark:hover { border-bottom: 5px solid #D6232E; }

    </style>
</head>
<body>

    <div class="container">
        <header class="header">
            <h1>USA Marketplace All in One</h1>
            <p>Your Central Hub for America's Top Online Marketplaces</p>
        </header>

        <main class="marketplace-grid">
            <!-- Marketplaces -->
            <a href="https://www.amazon.com" target="_blank" class="card amazon">
                <div class="logo">📦</div>
                <h2 class="card-title">Amazon</h2>
            </a>
            <a href="https://www.ebay.com" target="_blank" class="card ebay">
                <div class="logo">🛒</div>
                <h2 class="card-title">eBay</h2>
            </a>
            <a href="https://www.walmart.com/marketplace" target="_blank" class="card walmart">
                <div class="logo">🏪</div>
                <h2 class="card-title">Walmart</h2>
            </a>
            <a href="https://offerup.com" target="_blank" class="card offerup">
                <div class="logo">🤝</div>
                <h2 class="card-title">OfferUp</h2>
            </a>
            <a href="https://www.houzz.com" target="_blank" class="card houzz">
                <div class="logo">🛋️</div>
                <h2 class="card-title">Houzz</h2>
            </a>
            <a href="https://www.etsy.com" target="_blank" class="card etsy">
                <div class="logo">🎨</div>
                <h2 class="card-title">Etsy</h2>
            </a>
            <a href="https://www.facebook.com/marketplace" target="_blank" class="card facebook">
                <div class="logo">👍</div>
                <h2 class="card-title">Facebook</h2>
            </a>
            <a href="https://www.craigslist.org" target="_blank" class="card craigslist">
                <div class="logo">📰</div>
                <h2 class="card-title">Craigslist</h2>
            </a>
            <a href="https://poshmark.com" target="_blank" class="card poshmark">
                <div class="logo">👗</div>
                <h2 class="card-title">Poshmark</h2>
            </a>
        </main>
    </div>

</body>
</html>
