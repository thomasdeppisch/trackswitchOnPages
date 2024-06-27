---
layout: default
---

<script src="https://cdn.rawgit.com/download/polymer-cdn/1.5.0/lib/webcomponentsjs/webcomponents-lite.min.js"></script>
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
<link rel="stylesheet" href="thirdparty/trackswitch-js/trackswitch.min.css" />
<script src="https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4=" crossorigin="anonymous"></script>
<script src="thirdparty/trackswitch-js/trackswitch.min.js"></script>
<script type="text/javascript">
    var settings = {
        onlyradiosolo: true,
        repeat: true,
    };

    jQuery(document).ready(function() {
        jQuery(".player").trackSwitch(settings); 
    });
</script>

# Demo
This page demonstrate how [trackswitch.js](https://github.com/audiolabs/trackswitch.js/) can be used on GitHub pages, using just a markdown file.

We can have an audio player:
<div class="player">
    <ts-track title="Guitar">
        <ts-source src="audio/guitar.wav"></ts-source>
    </ts-track>
    <ts-track title="Drums">
        <ts-source src="audio/drums.wav"></ts-source>
    </ts-track>
</div>

And another one:
<div class="player">
    <ts-track title="Guitar">
        <ts-source src="audio/guitar.wav"></ts-source>
    </ts-track>
    <ts-track title="Drums">
        <ts-source src="audio/drums.wav"></ts-source>
    </ts-track>
</div>

