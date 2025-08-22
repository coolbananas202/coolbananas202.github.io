
<html lang="en">
<head>
    <style>
        iframe {
            top: 0px;
            left: 0px;
            width: 100%; 
            height: 100%; 
        }
    </style>
</head>
<body>
    <iframe id: "theframe"; src="https://example.com"></iframe>
    <script>
        const urlParams = new URLSearchParams(window.location.search)
        const url = urlParams.get('url')
        
    </script>
</body>
</html>
