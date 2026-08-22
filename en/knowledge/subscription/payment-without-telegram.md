---
layout: default
title: Telegram Unavailable? How to Sign In and Pay for Your Subscription
description: "What to do if Telegram is unavailable: sign in to Slon Privacy with Email, pay for your subscription, and restore access to Telegram."
lang: en
permalink: /en/knowledge/subscription/payment-without-telegram/
---
{% include knowledge-styles.html %}

<section class="app-tab-panel is-active" aria-labelledby="telegram-unavailable-title">

  <p><strong>If Telegram is temporarily unavailable, you can still sign in to your Slon Privacy account, manage your subscription, and restore access using one of the options below.</strong></p>

  <div class="guide-note">
    <strong>Key point</strong>
    <p>The most reliable option is to link an email address to your account in advance. This way, you can still sign in and pay for your subscription even if Telegram is unavailable.</p>
  </div>

  <section class="guide-step">
    <div class="guide-step-number">1</div>
    <div class="guide-step-content">
      <h2 id="telegram-unavailable-title">Sign in with Email</h2>
      <p>If you have already linked <strong>Email</strong> to your Slon Privacy profile, sign in on the <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">website</a> without using Telegram.</p>
      <p>Once signed in, you can check or renew your subscription and connect a new device.</p>
      <p><a href="{{ site.baseurl }}/en/knowledge/subscription/link-telegram/">How to link Telegram and Email →</a></p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">2</div>
    <div class="guide-step-content">
      <h2>Connect a proxy for Telegram</h2>
      <p>If you have not linked your email yet, try restoring access to Telegram using the Slon Privacy MTProto proxy.</p>

      <div class="guide-note">
        <strong>Connect the proxy</strong>
        <p>Tap the link below. If Telegram is installed on your device, the app will offer to add the proxy automatically.</p>
        <p>
          <a href="tg://proxy?server=130.49.185.95&amp;port=33443&amp;secret=2d52f5754605c47237b483cd092be6b3">
            <strong>Connect proxy in Telegram →</strong>
          </a>
        </p>
        <p>If the link does not work, copy it and open it manually:</p>
        <p><code>tg://proxy?server=130.49.185.95&amp;port=33443&amp;secret=2d52f5754605c47237b483cd092be6b3</code></p>
      </div>

      <section class="guide-faq" aria-labelledby="proxy-qr-title">
        <h3 id="proxy-qr-title">QR code</h3>
        <details>
          <summary>Show QR code</summary>
          <p>Scan the QR code with your phone's camera to connect the proxy in Telegram.</p>
          <img
            class="guide-image guide-image-small"
            src="{{ site.baseurl }}/assets/img/knowledge-base/subscription/telegram-unavailable/proxy-qr.webp"
            alt="QR code for connecting the Slon Privacy proxy"
            loading="lazy">
        </details>
      </section>

      <div class="guide-warning">
        <strong>Important:</strong> the proxy can help you open Telegram, but it does not replace linking your Email. Once access is restored, we recommend adding a backup sign-in method right away.
      </div>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">3</div>
    <div class="guide-step-content">
      <h2>If the proxy does not help</h2>
      <p>Create or open an account using your email address and use Slon Privacy to restore access to Telegram.</p>
      <ul class="guide-simple-list">
        <li>Open your account and sign in with <strong>Email</strong>.</li>
        <li>Activate the <strong>3-day free trial</strong> if it is still available for your account.</li>
        <li>Install Slon Privacy and connect to a server.</li>
        <li>Open Telegram and restore access to your account.</li>
        <li>Once signed in, link Telegram and Email to the same account.</li>
      </ul>
      <p><a href="{{ site.baseurl }}/en/knowledge/subscription/link-telegram/">How to link Telegram and Email →</a></p>
    </div>
  </section>

  <div class="guide-success">
    <strong>Tip:</strong> link Telegram and Email as soon as you register. This helps you keep access to your account, subscription, and settings if one sign-in method becomes temporarily unavailable.
  </div>

</section>
