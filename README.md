<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="./assets/reset.css">
    <link rel="stylesheet" href="./assets/common.css">
    <script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="//cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.1/jquery-ui.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/split.js/1.5.11/split.min.js"></script>

    <title>nabuki</title>
</head>
<body>
<div class="wrapper">
    <div id="view">
        <iframe src="https://player.twitch.tv/?channel=izblooming&parent=nabuki1201.github.io" frameborder="0" allowfullscreen="true" scrolling="no"></iframe>
    </div>
    <div id="chat">
        <script async src="//client.uchat.io/uchat.js"></script>
        <u-chat room='nabuki' style="width: 100%; height: 100%;"></u-chat>
    </div>
</div>
<script>
    Split(['#view', '#chat'], {
        sizes: [75, 25],
    })
</script>

</body>
</html>
