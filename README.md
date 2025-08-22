<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Pages Site</title>
</head>
<body>
    <script>
        const urlParams = new URLSearchParams(window.location.search);
        const url = urlParams.get('url');   
    
        console.log(`url: ${url}`);
    </script>
</body>
</html>
