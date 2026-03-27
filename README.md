<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Browser Downloads für Windows</title>
  <style>
    :root {
      --bg: #0f172a;
      --card: #111827;
      --card-2: #1f2937;
      --text: #f8fafc;
      --muted: #cbd5e1;
      --accent: #38bdf8;
      --accent-hover: #0ea5e9;
      --border: rgba(255,255,255,0.08);
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color: var(--text);
      min-height: 100vh;
    }

    .container {
      max-width: 980px;
      margin: 0 auto;
      padding: 48px 20px;
    }

    .hero {
      text-align: center;
      margin-bottom: 36px;
    }

    .hero h1 {
      margin: 0 0 12px;
      font-size: 2.3rem;
    }

    .hero p {
      margin: 0;
      color: var(--muted);
      font-size: 1.05rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 20px;
      align-items: stretch;
    }

    .card {
      height: 100%;
    }

    @media (max-width: 700px) {
      .grid {
        grid-template-columns: 1fr;
      }
    }

    @media (max-width: 700px) {
      .grid {
        grid-template-columns: 1fr;
      }
    }

    .card {
      background: rgba(17, 24, 39, 0.95);
      border: 1px solid var(--border);
      border-radius: 18px;
      padding: 24px;
      box-shadow: 0 12px 30px rgba(0,0,0,0.25);
    }

    .badge {
      display: inline-block;
      padding: 6px 10px;
      border-radius: 999px;
      background: rgba(56, 189, 248, 0.15);
      color: #7dd3fc;
      font-size: 0.85rem;
      margin-bottom: 14px;
    }

    .card h2 {
      margin: 0 0 10px;
      font-size: 1.5rem;
    }

    .card p {
      color: var(--muted);
      line-height: 1.6;
      margin-bottom: 20px;
    }

    .btn {
      display: inline-block;
      text-decoration: none;
      background: var(--accent);
      color: #082f49;
      font-weight: bold;
      padding: 12px 18px;
      border-radius: 12px;
      transition: 0.2s ease;
    }

    .btn:hover {
      background: var(--accent-hover);
      color: white;
    }

    .meta {
      margin-top: 14px;
      font-size: 0.9rem;
      color: #94a3b8;
    }

    .footer {
      margin-top: 28px;
      text-align: center;
      color: #94a3b8;
      font-size: 0.9rem;
    }

    code {
      background: rgba(255,255,255,0.08);
      padding: 2px 6px;
      border-radius: 6px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="hero">
      <h1>DownloadLinks für Windows</h1>
      <p>downloadlinks-de.de – praktische Download-Links für Windows-Programme.</p>
    </div>

    <div class="grid">
      <section class="card">
        <span class="badge">Windows</span>
        <h2>Google Chrome</h2>
        <p>Direkter Download des Chrome-Installers für Windows. Beim Klick startet der Download sofort.</p>
        <a class="btn" href="https://dl.google.com/chrome/install/latest/chrome_installer.exe" download>Chrome direkt herunterladen</a>
        <div class="meta">Datei: <code>chrome_installer.exe</code></div>
      </section>

      <section class="card">
        <span class="badge">Windows 64-Bit</span>
        <h2>Mozilla Firefox</h2>
        <p>Direkter Download der aktuellen Firefox-Version für Windows 64-Bit von Mozilla.</p>
        <a class="btn" href="https://download.mozilla.org/?product=firefox-latest-ssl&os=win64&lang=de" download>Firefox direkt herunterladen</a>
        <div class="meta">Sprache: Deutsch</div>
      </section>

      <section class="card">
        <span class="badge">Windows 64-Bit</span>
        <h2>TeamViewer</h2>
        <p>Direkter Download der aktuellen TeamViewer-Version für Windows 64-Bit.</p>
        <a class="btn" href="https://download.teamviewer.com/download/TeamViewer_Setup_x64.exe" download>TeamViewer herunterladen</a>
        <div class="meta">Datei: <code>TeamViewer_Setup_x64.exe</code></div>
      </section>

      <section class="card">
        <span class="badge">Windows</span>
        <h2>Obsidian</h2>
        <p>Offizielle Downloadseite für Obsidian.</p>
        <a class="btn" href="https://obsidian.md/download" target="_blank">Obsidian herunterladen</a>
        <div class="meta">Offizieller Download</div>
      </section>

      <section class="card">
        <span class="badge">Windows</span>
        <h2>Brave Browser</h2>
        <p>Direkter Download des Brave-Installers für Windows.</p>
        <a class="btn" href="https://laptop-updates.brave.com/latest/winx64" download>Brave direkt herunterladen</a>
        <div class="meta">Datei: BraveSetup.exe</div>
      </section>

      <section class="card">
        <span class="badge">Windows</span>
        <h2>Yealink USB Connect</h2>
        <p>Verwaltungssoftware für Yealink-USB-Geräte wie Headsets, Speakerphones und Webcams.</p>
        <a class="btn" href="https://www.yealink.com/de/product-detail/usb-connect-management" target="_blank">Yealink USB Connect öffnen</a>
        <div class="meta">Offizielle Produktseite</div>
      </section>

      <section class="card">
        <span class="badge">Windows</span>
        <h2>Logi Options+</h2>
        <p>Direkter Download des Logi Options+ Installers für Windows.</p>
        <a class="btn" href="https://download01.logi.com/web/ftp/pub/techsupport/optionsplus/logioptionsplus_installer.exe" download>Logi Options+ direkt herunterladen</a>
        <div class="meta">Datei: logioptionsplus_installer.exe</div>
      </section>

      <section class="card">
        <span class="badge">Windows</span>
        <h2>WhatsApp</h2>
        <p>Direkter Download der WhatsApp Desktop App für Windows.</p>
        <a class="btn" href="https://web.whatsapp.com/desktop/windows/release/x64/WhatsAppSetup.exe" download>WhatsApp direkt herunterladen</a>
        <div class="meta">Datei: WhatsAppSetup.exe</div>
      </section>

      <section class="card">
        <span class="badge">Windows</span>
        <h2>Microsoft 365</h2>
        <p>Offizieller Installer für Microsoft 365. Anmeldung mit Microsoft-Konto erforderlich.</p>
        <a class="btn" href="https://www.office.com/" target="_blank">Microsoft 365 installieren</a>
        <div class="meta">Startet über Office-Webseite</div>
      </section>

      <section class="card">
        <span class="badge">Enterprise</span>
        <h2>Office LTSC 2024</h2>
        <p>Volumenlizenz-Version von Microsoft Office. Download erfolgt über das Office Deployment Tool.</p>
        <a class="btn" href="https://www.microsoft.com/en-us/download/details.aspx?id=49117" target="_blank">Office Deployment Tool herunterladen</a>
        <div class="meta">Installation via Konfiguration (XML)</div>
      </section>
    </div>

    <div class="footer">
      Hinweis: Die Links verweisen auf die offiziellen Download-Quellen der jeweiligen Anbieter.
    </div>

    <div style="margin-top:40px;padding:20px;border-top:1px solid rgba(255,255,255,0.1);font-size:0.85rem;color:#94a3b8;line-height:1.6;text-align:center;">
      <p><strong>Rechtliche Hinweise</strong></p>
      <p>Diese Webseite stellt ausschließlich Verlinkungen zu offiziellen Download-Quellen der jeweiligen Hersteller bereit. Es werden keine Dateien auf diesem Server gehostet.</p>
      <p>Alle Marken, Produktnamen und Logos sind Eigentum der jeweiligen Rechteinhaber.</p>
      <p>Die Nutzung der bereitgestellten Software erfolgt auf eigene Verantwortung. Es wird keine Haftung für Schäden oder Datenverluste übernommen.</p>
      <p>Bitte beachte die Lizenzbedingungen der jeweiligen Softwareanbieter.</p>
      <p>Geplante Domain: <strong>downloadlinks-de.de</strong></p>
    </div>
  </div>
</body>
</html>
