<!doctype html>
<html lang="de">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>BeatGen — KI-ähnlicher Beat aus Text</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <main class="container">
    <h1>BeatGen — Beat aus deinem Text</h1>

    <label for="lyrics">Gib deinen Text ein:</label>
    <textarea id="lyrics" rows="8" placeholder="Hier Text / Lyrics eingeben..."></textarea>

    <div class="controls-row">
      <button id="generateBtn">Beat generieren</button>
      <button id="playBtn" disabled>Play</button>
      <button id="stopBtn" disabled>Stop</button>
      <button id="downloadBtn" disabled>Download Aufnahme</button>
    </div>

    <section class="info" id="infoBox">
      <strong>Status:</strong> idle
      <div id="params"></div>
    </section>

    <footer>
      <small>Kein Server nötig — läuft lokal im Browser. Kopiere die Dateien und öffne <code>index.html</code>.</small>
    </footer>
  </main>

  <script src="app.js"></script>
</body>
</html>
