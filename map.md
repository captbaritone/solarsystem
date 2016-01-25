---
title: "Map"
layout: "page"
---

<!-- map made responsive using this guide: http://www.labnol.org/internet/embed-responsive-google-maps/28333/ -->
<style>
    .google-maps {
        position: relative;
        padding-bottom: 75%; // This is the aspect ratio
        height: 0;
        overflow: hidden;
    }
    .google-maps iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100% !important;
        height: 100% !important;
    }
</style>

<div class='google-maps'>
    <iframe
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d100272.84920104512!2d-122.69555621812466!3d38.24409253556621!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80844a8cc2740c4d%3A0xabffb835642d62f2!2sPetaluma%2C+CA!5e0!3m2!1sen!2sus!4v1453686977389"
    width="600" height="450" frameborder="0" style="border:0"
    allowfullscreen></iframe>
</div>
