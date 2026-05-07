<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stealth Cloaker Pro</title>
    <style>
        body {
            font-family: 'Inter', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #0f172a;
            color: #f8fafc;
        }
        .cloaker-container {
            background-color: #1e293b;
            padding: 2.5rem;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            width: 100%;
            max-width: 400px;
            box-sizing: border-box;
        }
        h2 { 
            margin-top: 0; color: #38bdf8; text-align: center; margin-bottom: 1.5rem;
        }
        .form-group {
            margin-bottom: 1.2rem; display: flex; flex-direction: column;
        }
        label {
            font-size: 0.9rem; margin-bottom: 0.4rem; color: #94a3b8;
        }
        input[type="text"], select {
            padding: 12px; background-color: #0f172a; border: 1px solid #334155;
            color: #f8fafc; border-radius: 8px; font-size: 15px; outline: none;
        }
        input[type="text"]:focus, select:focus { border-color: #38bdf8; }
        button {
            width: 100%; padding: 14px; margin-top: 10px; background-color: #38bdf8;
            color: #0f172a; font-weight: bold; border: none; border-radius: 8px;
            font-size: 16px; cursor: pointer; transition: background-color 0.2s;
        }
        button:hover { background-color: #7dd3fc; }
    </style>
</head>
<body>

    <div class="cloaker-container">
        <h2>Stealth Cloaker Pro</h2>
        
        <div class="form-group">
            <label for="urlInput">Target Website URL</label>
            <input type="text" id="urlInput" placeholder="https://example.com" required>
        </div>

        <div class="form-group">
            <label for="proxySelect">Bypass Engine (Proxy)</label>
            <select id="proxySelect">
                <option value="corsproxy">Corsproxy.io (Best for most sites)</option>
                <option value="allorigins">AllOrigins (Alternative fallback)</option>
                <option value="none">Direct / No Proxy (For simple sites)</option>
            </select>
        </div>

        <div class="form-group">
            <label for="tabTitle">Fake Tab Title (Optional)</label>
            <input type="text" id="tabTitle" placeholder="e.g., Google Docs" value="Google">
        </div>

        <div class="form-group">
            <label for="tabIcon">Fake Tab Icon URL (Optional)</label>
            <input type="text" id="tabIcon" placeholder="URL to an image/favicon" value="https://www.google.com/favicon.ico">
        </div>

        <button onclick="cloakURL()">Launch Cloaked Tab</button>
    </div>

    <script>
        function cloakURL() {
            let url = document.getElementById('urlInput').value.trim();
            if (!url) return alert("Please enter a target URL.");

            if (!url.startsWith('http://') && !url.startsWith('https://')) {
                url = 'https://' + url;
            }

            try { new URL(url); } catch (_) { return alert("Invalid URL format."); }

            let proxyChoice = document.getElementById('proxySelect').value;
            let title = document.getElementById('tabTitle').value || 'Home';
            let icon = document.getElementById('tabIcon').value || '';
            
            let finalUrl = url;
            if (proxyChoice === 'corsproxy') {
                finalUrl = 'https://corsproxy.io/?' + encodeURIComponent(url);
            } else if (proxyChoice === 'allorigins') {
                finalUrl = 'https://api.allorigins.win/raw?url=' + encodeURIComponent(url);
            }

            let html = `
            <!DOCTYPE html>
            <html lang="en">
            <head>
                <meta charset="UTF-8">
                <title>${title}</title>
                ${icon ? \`<link rel="icon" type="image/x-icon" href="\${icon}">\` : ''}
                <style>
                    body, html { margin: 0; padding: 0; width: 100%; height: 100%; overflow: hidden; background-color: #ffffff; }
                    iframe { width: 100%; height: 100%; border: none; margin: 0; padding: 0; }
                </style>
            </head>
            <body>
                <iframe src="${finalUrl}" allowfullscreen="true" allow="autoplay; encrypted-media; camera; microphone"></iframe>
            </body>
            </html>
            `;

            let win = window.open('about:blank', '_blank');

            if (win) {
                win.document.open();
                win.document.write(html);
                win.document.close();
            } else {
                alert("Popup blocked! Please allow popups for this site to launch the cloaked tab.");
            }
        }

        document.addEventListener("keypress", function(event) {
            if (event.key === "Enter") {
                event.preventDefault();
                cloakURL();
            }
        });
    </script>
</body>
</html>
