
<html lang="en">
<head>
    <style>
        iframe {
            width: 100%; 
            height: 600px; 
        }
    </style>
</head>
<body>
    <iframe src="https://example.com"></iframe>
    <script>
        const urlParams = new URLSearchParams(window.location.search)
        const url = urlParams.get('url')
    </script>
</body>
</html>
