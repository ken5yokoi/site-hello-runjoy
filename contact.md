---
layout: contact
title: お問い合わせ
description: お問い合わせページです
---

<form
  action="https://formspree.io/f/mwvyanvb"
  method="POST"
  class="p-contactForm"
>

  <label>
    お名前
    <input type="text" name="name" required>
  </label>

  <label>
    メールアドレス
    <input type="email" name="email" required>
  </label>

  <label>
    お問い合わせ内容
    <textarea name="message" rows="8" required></textarea>
  </label>

  <button type="submit" class="p-btn">
    送信する
  </button>

</form>