<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Chromebook Crosshair Builder</title>
    <style>
        body { 
            font-family: sans-serif; 
            text-align: center; 
            padding-top: 50px; 
            background: #121212; 
            color: white; 
        }
        .btn { 
            display: inline-block; 
            padding: 15px 30px; 
            background: #00ff00; 
            color: black; 
            font-weight: bold; 
            text-decoration: none; 
            border-radius: 8px; 
            font-size: 18px; 
            cursor: pointer; 
        }
    </style>
</head>
<body>

    <h1>My Custom Fortnite Crosshair</h1>
    <p>Drag the green button below directly onto your Chromebook Bookmarks Bar:</p>

    <!-- This is the draggable bookmarklet link that builds the crosshair -->
    <a class="btn" href="javascript:(function(){   var existing = document.getElementById('gfn-crosshair');   if(existing) { existing.remove(); return; }   var crosshair = document.createElement('div');   crosshair.id = 'gfn-crosshair';   crosshair.style.position = 'fixed';   crosshair.style.top = '50%';   crosshair.style.left = '50%';   crosshair.style.width = '12px';   crosshair.style.height = '12px';   crosshair.style.backgroundColor = '#00ff00';   crosshair.style.borderRadius = '50%';   crosshair.style.transform = 'translate(-50%, -50%)';   crosshair.style.zIndex = '999999';   crosshair.style.pointerEvents = 'none';   document.body.appendChild(crosshair); })();">
        + GFN Crosshair
    </a>

</body>
</html>
