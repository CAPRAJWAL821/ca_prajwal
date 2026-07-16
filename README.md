<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ca_prajwal | Chartered Accountant Portfolio</title>
    <style>
        :root {
            --primary: #0f172a;
            --secondary: #2563eb;
            --text: #334155;
            --bg: #f8fafc;
            --white: #ffffff;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg);
            color: var(--text);
            line-height: 1.6;
        }

        header {
            background-color: var(--primary);
            color: var(--white);
            padding: 1rem 2rem;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--white);
        }

        .logo span {
            color: var(--secondary);
        }

        nav a {
            color: var(--white);
            text-decoration: none;
            margin-left: 1.5rem;
            font-size: 0.95rem;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--secondary);
        }

        .hero {
            padding: 8rem 2rem 4rem;
            text-align: center;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: var(--white);
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            color: #94a3b8;
            max-width: 600px;
            margin: 0 auto 2rem;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 4rem 2rem;
        }

        .section-title {
            text-align: center;
            font-size: 2rem;
            color: var(--primary);
            margin-bottom: 3rem;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 50px;
            height: 3px;
            background-color: var(--secondary);
            margin: 10px auto 0;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
        }

        .card {
            background-color: var(--white);
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            color: var(--primary);
            margin-bottom: 1rem;
        }

        .about-text {
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
            font-size: 1.1rem;
        }

        .contact-info {
            text-align: center;
            max-width: 500px;
            margin: 0 auto;
        }

        .contact-item {
            background-color: var(--white);
            padding: 1rem;
            margin-bottom: 1rem;
            border-radius: 6px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.02);
        }

        .contact-item a {
            color: var(--secondary);
            text-decoration: none;
        }

        footer {
            background-color: var(--primary);
            color: #64748b;
            text-align: center;
            padding: 2rem;
            margin-top: 4rem;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            header { flex-direction: column; gap: 1rem; }
            nav a { margin: 0 0.7rem; }
            .hero h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">ca_<span>prajwal</span></div>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About Me</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Prajwal, CA</h1>
        <p>Chartered Accountant & Financial Consultant providing strategic tax planning, auditing, and corporate compliance services.</p>
    </section>

    <section id="about" class="container">
        <h2 class="section-title">About Me</h2>
        <div class="about-text">
            <p>Welcome to my professional portfolio. As a dedicated Chartered Accountant based in Bangalore, I specialize in helping businesses and individuals navigate complex financial landscapes. My goal is to maximize your financial growth while ensuring absolute legal compliance and structural efficiency.</p>
        </div>
    </section>

    <section id="services" style="background-color: #f1f5f9;">
        <div class="container">
            <h2 class="section-title">Professional Services</h2>
            <div class="services-grid">
                <div class="card">
                    <h3>Taxation & Planning</h3>
                    <p>Strategic direct and indirect tax advisory, GST filings, income tax returns, and compliance optimization for individuals and corporates.</p>
                </div>
                <div class="card">
                    <h3>Audit & Assurance</h3>
                    <p>Thorough statutory, internal, and tax audits to ensure financial integrity, risk management, and regulatory compliance.</p>
                </div>
                <div class="card">
                    <h3>Corporate Advisory</h3>
                    <p>Business setup consulting, financial restructuring, financial modeling, and strategic management accounting to scale operations.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="container">
        <h2 class="section-title">Get In Touch</h2>
        <div class="contact-info">
            <div class="contact-item">
                <strong>Email:</strong> <a href="mailto:prajwallonar211@gmail.com">prajwallonar211@gmail.com</a>
            </div>
            <div class="contact-item">
                <strong>Location:</strong> Bangalore, India
            </div>
            <div class="contact-item">
                <strong>LinkedIn:</strong> ://linkedin.com
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 ca_prajwal. All rights reserved.</p>
    </footer>

</body>
</html>
