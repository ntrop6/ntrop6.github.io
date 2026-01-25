---
title: "Doujinshi"
draft: false
layout: "single"
---

<style>
    .post-title, header, h1 {
        display: none !important;
    }

    body {
        background-color: #1e1e1e;
        color: white;
        font-family: sans-serif;
    }

    .doujin-wrapper {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 80px;
        min-height: 80vh;
        padding: 20px;
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
        .text-side {
            text-align: center;
        }
    }
</style>

<div class="doujin-wrapper">
    <div class="text-side">
        <h2>Current Translations</h2>
        <div class="list-item">*number 1*</div>
        <div class="list-item">*number 2*</div>
        <div class="list-item">*number 3*</div>
        <div class="list-item">...</div>
    </div>

    <div class="img-side">
        <img src="https://files.catbox.moe/2ipsk4.jpg" alt="aynı ben">
</div>
