<!DOCTYPE html>
<html>

<head>
    <title>dnd-probability calculator</title>
    <link href="//cdn.muicss.com/mui-0.10.3/css/mui.min.css" rel="stylesheet" type="text/css" />
    <script src="//cdn.muicss.com/mui-0.10.3/js/mui.min.js"></script>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>Этот сайт позволяет вам посчитать веростяность победы в состязании навыков в Dungeons and Dragons!</header>
    <div class="wrapper">
        <div class="content">
            <div class="relative">
                <input id="player" type="number" placeholder="Бонус игрока">
                <input id="npc" type="number" placeholder="Бонус противника">
                <div class="output"></div>

            </div>
            <div class="button-container">
                <div class="d-output"></div>
            </div>

        </div>
        <div class="spells">

        </div>
        <div class="spells-content">
            <div class="name-container">
                <p class="name"></p>
            </div>
            <div class="description"></div>
        </div>

    </div>
    <script src="scripts.js"></script>
</body>

</html>