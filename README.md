<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Rachana Appani | Cybersecurity</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

    <style>
        body {
            background: linear-gradient(135deg, #0f0f0f, #1a1a1a);
            color: #e0e0e0;
            font-family: 'Poppins', sans-serif;
        }

        .terminal-font {
            font-family: 'Share Tech Mono', monospace;
            color: #00ff88;
        }

        .hero {
            padding: 100px 0;
            text-align: center;
        }

        .glow {
            color: #00ff88;
            text-shadow: 0 0 10px #00ff88;
        }

        .card {
            background-color: #1e1e1e;
            border: 1px solid #00ff88;
            transition: 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 15px #00ff88;
        }

        .section-title {
            color: #00ff88;
            margin-bottom: 30px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .badge-skill {
            background-color: #00ff88;
            color: black;
            margin: 5px;
            padding: 8px 12px;
            font-weight: 500;
        }

        a {
            color: #00ff88;
            text-decoration: none;
        }

        a:hover {
            text-shadow: 0 0 8px #00ff88;
        }

        footer {
            border-top: 1px solid #00ff88;
            padding: 20px 0;
            text-align: center;
            margin-top: 60px;
        }
    </style>
</head>

<body>

<!-- HERO SECTION -->
<section class="hero">
    <h1 class="glow">Rachana Appani</h1>
    <p class="terminal-font">
        > Cybersecurity Analyst | Red Team Enthusiast | SOC & Bug Bounty Focus_
    </p>
    <p>Hyderabad, India | B.Tech - Cybersecurity</p>
</section>

<!-- ABOUT -->
<div class="container">
    <h3 class="section-title">About Me</h3>
    <p>
        Cybersecurity professional with strong interest in both Offensive Security (Bug Bounty / Red Teaming)
        and Defensive Security (SOC / Threat Monitoring).
        I combine vulnerability research with structured monitoring aligned to OWASP, NIST, and ISO 27001 frameworks.
    </p>
</div>

<!-- OFFENSIVE -->
<div class="container mt-5">
    <h3 class="section-title">Offensive Security</h3>
    <div>
        <span class="badge badge-skill">SSRF</span>
        <span class="badge badge-skill">IDOR</span>
        <span class="badge badge-skill">SQL Injection</span>
        <span class="badge badge-skill">XSS</span>
        <span class="badge badge-skill">Broken Access Control</span>
        <span class="badge badge-skill">File Upload</span>
        <span class="badge badge-skill">Subdomain Takeover</span>
    </div>
</div>

<!-- TOOLS -->
<div class="container mt-5">
    <h3 class="section-title">Technical Arsenal</h3>
    <div class="row">
        <div class="col-md-4">
            <div class="card p-3">
                <h5 class="terminal-font">Recon</h5>
                <p>Nmap, Amass, Sublist3r, Gobuster, Dirbuster, DNSRecon</p>
            </div>
        </div>

        <div class="col-md-4">
            <div class="card p-3">
                <h5 class="terminal-font">Web Testing</h5>
                <p>Burp Suite, SQLmap, OWASP ZAP, Nikto, ffuf</p>
            </div>
        </div>

        <div class="col-md-4">
            <div class="card p-3">
                <h5 class="terminal-font">Exploitation</h5>
                <p>Metasploit, Netcat, Hydra, John the Ripper</p>
            </div>
        </div>
    </div>
</div>

<!-- DEFENSIVE -->
<div class="container mt-5">
    <h3 class="section-title">Defensive & SOC Skills</h3>
    <p>
        Threat Intelligence, IOC Enrichment, SIEM (Splunk), Snort IDS/IPS,
        Incident Response, Risk Assessment, Cyber Kill Chain.
    </p>
</div>

<!-- PROJECTS -->
<div class="container mt-5">
    <h3 class="section-title">Projects</h3>
    <ul>
        <li>Cyber Threat Intelligence Dashboard (API-based IOC enrichment)</li>
        <li>Email Spam & Malware Detection System (Python)</li>
    </ul>
</div>

<!-- CONTACT -->
<div class="container mt-5">
    <h3 class="section-title">Connect</h3>
    <p>
        LinkedIn: <a href="#">linkedin.com/in/rachana-appani</a><br>
        Email: rachana.appani05@gmail.com
    </p>
</div>

<footer>
    <p class="terminal-font">> Securing systems. Hunting vulnerabilities. Defending infrastructure.</p>
</footer>

</body>
</html>
