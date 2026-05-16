
<!DOCTYPE html>
<html>
<head>
<title>Juliet AI</title>
<link rel="stylesheet" href="{{ url_for('static', filename='style.css') }}">
</head>
<body>
<div class="container">
<h1>Juliet AI</h1>
<p>Create kids videos, Shorts, animations and voice content</p>
<input id="prompt" placeholder="Describe your video idea">
<button onclick="generateVideo()">Generate Video</button>
<button onclick="generateVoice()">Generate Voice</button>
<p id="result"></p>
</div>
<script src="{{ url_for('static', filename='script.js') }}"></script>
</body>
</html>
