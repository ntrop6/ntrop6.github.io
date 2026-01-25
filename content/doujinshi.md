---
title: "Doujinshi"
draft: false
---

<style>
    .post-title, .entry-header, h1 {
        display: none !important;
    }

    body {
        background-color: #1d1e20; 
        color: white;
    }

    .doujin-wrapper {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 80px;
        min-height: 60vh;
        padding: 20px;
        margin-top: 50px;
    }

    .text-side {
        text-align: left;
    }

    .text-side h2 {
        font-size: 32px;
        font-weight: bold;
        margin-bottom: 20px;
        color: #ffffff;
        display: block !important;
    }

    .list-item {
        font-size: 24px;
        font-weight: bold;
        margin-bottom: 10px;
        color: #e0e0e0;
    }

    .img-side img {
        width: 350px;
        height: auto;
        border-radius: 15px;
        object-fit: cover;
        border: 2px solid #333;
    }

    @media (max-width: 768px) {
        .doujin-wrapper {
            flex-direction: column-reverse;
            gap: 40px;
            text-align: center;
        }
        .text-side { text-align: center; }
    }
</style>

<div class="doujin-wrapper">
<div class="text-side">
<h2>Current Translations</h2>
<div class="list-item"><i>*number 1*</i></div>
<div class="list-item"><i>*number 2*</i></div>
<div class="list-item"><i>*number 3*</i></div>
<div class="list-item">...</div>
</div>
<div class="img-side">
<img src="https://files.catbox.moe/2ipsk4.jpg" alt="Seia">
</div>
</div>
