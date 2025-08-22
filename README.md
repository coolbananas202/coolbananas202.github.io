
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
    <iframe id: "theframe"; src="https://example.com">
    <script> 
        window.onload = function() {
            const urlParams = new URLSearchParams(window.location.search)
            const url = urlParams.get('url')
            console.error(url)
            if (url){
                const iframe = document.getElementById('theframe');
                iframe.src = url
            }
        }
    </script>
</body>
</html>
