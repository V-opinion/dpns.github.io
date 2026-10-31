---
layout: default
title: Hem
---

# Välkommen till Demokratiska partiet, De Nya Svenskarna (DPNS)

## Senaste inlägg

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>
---
<!-- Links to External Subdomain Pages -->
* [Main Portal](https://www.multireligionvalsystem.eu.org/){:target="_blank"}
* [Den nya svenskarna](https://www.multireligionvalsystem.eu.org/denyasvenskarna){:target="_blank"}
[Follow us on Instagram](https://www.instagram.com/multireligionval/){:target="_blank"}
<hr>
<div align="center" style="margin-top: 40px; padding: 20px; font-family: sans-serif;">
  <p>© 2026 Multi Religion Val. All rights reserved.</p>
  <a href="https://www.instagram.com/multireligionval/" target="_blank" rel="noopener noreferrer" style="text-decoration: none; color: #E1306C; font-weight: bold;">
    📷 Instagram: @multireligionval
  </a>
</div>
  <!-- Social Media Signals Block -->
<div class="social-signals">
    <h3>Follow & Join the Conversation</h3>
    <ul class="social-list">
        <li>
            <a href="https://www.facebook.com/amultireligionelectionsystem" target="_blank" title="Facebook: Multi-Religion Election System">
                <i class="fab fa-facebook-square"></i> Facebook Page influencer
            </a>
        </li>
        <li>
            <a href="https://www.facebook.com/demokratin" target="_blank" title="Facebook: Demokratin">
                <i class="fab fa-facebook-square"></i> Demokratin (Facebook) influencer
            </a>
        </li>
        <li>
            <a href="http://se.linkedin.com/in/solidarity" target="_blank" title="LinkedIn: Solidarity">
                <i class="fab fa-linkedin"></i> LinkedIn influencer
            </a>
        </li>
        <li>
            <a href="http://www.pinterest.com/denyasvenskarna/" target="_blank" title="Pinterest: Denya Svenskarna">
                <i class="fab fa-pinterest-square"></i> Pinterest influencer
            </a>
        </li>
        <li>
            <a href="https://www.instagram.com/multireligionval/" target="_blank" title="Instagram: MultiReligionVal">
                <i class="fab fa-instagram"></i> Instagram influencer
            </a>
        </li>
        <li>
            <a href="https://twitter.com/DPNS" target="_blank" title="Twitter: DPNS">
                <i class="fab fa-twitter"></i> Twitter/X influencer
            </a>
        </li>
        <li>
            <a href="https://www.tiktok.com/@multireligionvalsystem?lang=en" target="_blank" title="TikTok: MultiReligionValSystem">
                <i class="fab fa-tiktok"></i> TikTok influencer
            </a>
        </li>
        <li>
            <a href="https://www.youtube.com/@faith-representatives" target="_blank" title="YouTube: Faith Representatives">
                <i class="fab fa-youtube"></i> YouTube influencer
            </a>
        </li>
        <li>
            <a href="https://www.multireligionvalsystem.eu.org/FNs-barnkonvention/" target="_blank" title="FNs-barnkonvention: MultiReligionVal">
                <i class="fab fa-multireligionvalsystem"></i> multireligionvalsystem influencer
            </a>
        </li>
    </ul>
</div>

<!-- Font Awesome CDN for icons (add in <head>) -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" />
<!-- Add CSS for visual style -->
<style>
    .social-signals h3{color:#4167b0;margin-bottom:9px;}
    .social-list{list-style:none;padding:0;margin:0;}
    .social-list li{margin-bottom:7px;}
    .social-list a{
        color:#33739e; text-decoration:none; font-size:1.09em;
        transition:color 0.17s;
    }
    .social-list a:hover{color:#d47147;}
    .social-list i{margin-right:8px; font-size:1.23em;}
</style>
