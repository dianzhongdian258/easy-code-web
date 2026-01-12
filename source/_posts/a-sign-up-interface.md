---
title: a sign-up interface
date: 2026-01-12 13:52:20
tags: form
        button
        input
        type

---
<form action="/login" method="POST">
  <h2>user sign-up</h2>
  
  <div class="input-group">
    <label for="username">username：</label>
    <input type="text" id="username" name="username" required>
  </div>
  
  <div class="input-group">
    <label for="password">password：</label>
    <input type="password" id="password" name="password" required>
    <a href=" " class="forgot-link">forgot the password？</a >
  </div>
  
  <div class="remember">
    <label>
      <input type="checkbox" name="remember">
      remember me
    </label>
  </div>


