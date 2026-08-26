<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Chromebook Crosshair Builder</title>
    <style>
        body { font-family: sans-serif; text-align: center; padding-top: 50px; background: #121212; color: white; }
        .btn { display: inline-block; padding: 15px 30px; background: #00ff00; color: black; font-weight: bold; text-decoration: none; border-radius: 8px; font-size: 18px; cursor: pointer; }
    </style>
</head>
<body>
    <h1>My Custom Fortnite Crosshair</h1>
    <p>Drag the green button below directly onto your Chromebook Bookmarks Bar:</p>
    <br>
    <a class="btn" href="javascript:(function(){var d=document.getElementById('gfn-xhair');if(d){d.remove();return;}d=document.createElement('div');d.id='gfn-xhair';d.style.position='fixed';d.style.top='50%';d.style.left='50%';d.style.transform='translate(-50%,-50%)';d.style.zIndex='999999';d.style.pointerEvents='none';var color='#00ff00';var size='24px';var thickness='4px';d.innerHTML='<div style=&quot;position:absolute;top:-'+(parseInt(size)/2)+'px;left:-'+(parseInt(thickness)/2)+'px;width:'+thickness+';height:'+size+';background:'+color+';box-shadow:0 0 2px black;&quot;></div><div style=&quot;position:absolute;top:-'+(parseInt(thickness)/2)+'px;left:-'+(parseInt(size)/2)+'px;width:'+size+';height:'+thickness+';background:'+color+';box-shadow:0 0 2px black;&quot;></div>';document.body.appendChild(d);})();">＋ GFN Crosshair</a>
</body>
</html>
