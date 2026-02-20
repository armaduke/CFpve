---
layout: default
title: Support Us - Community First
---

<style>
  body {
    background-color: #0a0a0a;
    background-image: url('background.png'); 
    background-size: cover;
    background-attachment: fixed;
    color: #e0e0e0;
    font-family: 'Courier New', Courier, monospace;
    margin: 0;
  }

  header, .project-name, .project-tagline {
    display: none !important;
  }

  .nav-header {
    display: flex; 
    justify-content: space-between; 
    align-items: center; 
    padding: 10px 40px; 
    background: rgba(0,0,0,0.8);
    border-bottom: 2px solid #00d35c; /* Cash App Green accent */
  }

  .nav-links a {
    color: #ff4444;
    text-decoration: none;
    margin-left: 20px;
    font-weight: bold;
  }

  .donation-container {
    background: rgba(20, 20, 20, 0.9); 
    border: 2px solid #ff4444; 
    border-radius: 15px;
    padding: 40px;
    max-width: 600px;
    margin: 50px auto;
    text-align: center;
    box-shadow: 0 0 25px rgba(255, 68, 68, 0.2);
  }

  .button-group {
    display: flex;
    flex-direction: column;
    gap: 15px;
    margin-top: 25px;
  }

  .btn {
    padding: 15px 30px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: 0.3s;
    text-transform: uppercase;
    display: block;
  }

  .cashapp {
    background: #00d35c;
    color: white;
  }

  .cashapp:hover {
    background: #00a348;
    box-shadow: 0 0 15px #00d35c;
  }

  .paypal {
    background: #0070ba;
    color: white;
  }

  .paypal:hover {
    background: #005ea6;
    box-shadow: 0 0 15px #0070ba;
  }

  .perks-list {
    text-align: left;
    background: rgba(255, 255, 255, 0.05);
    padding: 20px;
    border-radius: 10px;
    margin: 20px 0;
  }
</style>

<div class="nav-header">
  <img src="CFZombie 256.png" height="60">
  <div class="nav-links">
    <a href="index.html">HOME</a>
    <a href="rules.html">RULES</a>
    <a href="donations.html">DONATIONS</a>
  </div>
</div>

<div class="donation-container">
  <h1>Support the Server</h1>
  <p>Help keep the apocalypse alive! Donations go directly toward server costs and maintenance.</p>
  
  <div class="perks-list">
    <h2 style="color: #ff4444; margin-top: 0;">Donator Perks:</h2>
    <ul>
      <li>Tier 1 – Survivor ($5/month) Survivor Title in Discord.</li>
      <li>Tier 2 – Infected ($10/month) Infected title in Discord and One of any color DukesGhillies.</li>
      <li>Tier 3 – Mutated ($15/month) Mutated title in Discord and two of any color DukesGhillies.</li>
      <li>Tier 4 – Abomination ($20/month) Abomination title in Discord one of any color DukesGhillies and one DukesNBCClothingCase.</li>
      <li>Tier 5 – Horde ($40/month) Horde title in Discord. This covers you and four friends each Get one of DukesGhillies and one DukesNBCClothingCase.</li>
        
      
    </ul>
  </div>

  <div class="button-group">
    <a href="https://cash.app/$armaduke00" class="btn cashapp">Donate via Cash App</a>
    <a href="https://paypal.me/CFPvEServer" class="btn paypal">Donate via PayPal</a>
  </div>
</div>
