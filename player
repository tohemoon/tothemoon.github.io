<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Player</title>

<style>
body{
    margin:0;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:#fff;
}
.video-frame{
    width:100%;
    height:100vh;
    position:relative;
}
.video-frame img{
    width:100%;
    height:100%;
    object-fit:contain;
}
</style>
</head>
<body>

<a id="playerLink" href="https://arabelllaa.github.io/official/">
    <div class="video-frame">
        <img id="thumbnail">
    </div>
</a>

<script>
const params = new URLSearchParams(window.location.search);

const imageCode = params.get("img") || "VCWQViyFh";

document.getElementById("thumbnail").src =
    "https://cdn.aceimg.com/" + imageCode + ".jpg";
</script>

</body>
</html>
