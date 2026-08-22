---
layout: default
title: Install Slon Privacy on macOS
description: Step-by-step guide to installing and setting up Slon Privacy on macOS with INCY for Apple Silicon and Intel Macs.
lang: en
permalink: /en/knowledge/install/macos/
---
{% include knowledge-styles.html %}

<section class="app-tab-panel is-active">

  <p><strong>Install INCY, add your Slon Privacy subscription, and connect to a server. Setup usually takes no more than 2–3 minutes.</strong></p>

  <div class="guide-note">
    <strong>Before you start</strong>
    <p>Make sure your Slon Privacy subscription is active and your Mac is connected to the Internet.</p>
    <a href="{{ site.baseurl }}/en/knowledge/subscription/how-to-subscribe/">How to subscribe →</a>
  </div>

  <section class="guide-step">
    <div class="guide-step-number">1</div>
    <div class="guide-step-content">
      <h2>Download INCY</h2>
      <p>Sign in to your account through the <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram bot</a> or the <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">website</a>. Click “Home”, then click “Connect device”. Select <strong>macOS</strong>.</p>
      <p>Choose the installation option that matches your Mac:</p>
      <ul class="guide-simple-list">
        <li><strong>App Store</strong> — recommended for most users.</li>
        <li><strong>Apple Silicon (.dmg)</strong> — for Macs with Apple M1, M2, M3, or newer chips.</li>
        <li><strong>Intel (.dmg)</strong> — for Macs with Intel processors.</li>
      </ul>
      <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/03-download-macos.webp" alt="INCY download options for macOS" loading="lazy">
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">2</div>
    <div class="guide-step-content">
      <h2>Install the app</h2>
      <p>If you downloaded the <strong>.dmg</strong> version, open the file and drag <strong>INCY</strong> into the <strong>Applications</strong> folder.</p>
      <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/01-install-macos.webp" alt="Dragging INCY into the Applications folder" loading="lazy">
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">3</div>
    <div class="guide-step-content">
      <h2>Add your subscription</h2>
      <p>Return to your Slon Privacy account and click <strong>“Add subscription”</strong>.</p>
      <p>When your browser asks to open INCY, click <strong>Open Link</strong>. For convenience, you can enable <strong>Always allow</strong> so similar links open in INCY automatically in the future.</p>
      <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/02-open-link-macos.webp" alt="Browser prompt to open a link in INCY" loading="lazy">
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">4</div>
    <div class="guide-step-content">
      <h2>Allow the VPN configuration</h2>
      <p>The first time you connect, macOS will ask for permission to create a VPN configuration. Enter your Mac administrator password and click <strong>OK</strong>.</p>
      <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/04-vpn-permission-macos.webp" alt="macOS system prompt to allow VPN configuration" loading="lazy">
      <div class="guide-warning"><strong>Important:</strong> grant INCY all requested system permissions. The VPN connection cannot start without them.</div>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">5</div>
    <div class="guide-step-content">
      <h2>Connect</h2>
      <ul class="guide-simple-list">
        <li>Select any server from the INCY list.</li>
        <li>Click the connection button.</li>
        <li>Wait for the green indicator to appear around the icon.</li>
      </ul>
      <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/05-connected-macos.webp" alt="Successful Slon Privacy connection in INCY on macOS" loading="lazy">
    </div>
  </section>

  <div class="guide-success">
    <strong>Done!</strong> Once connected, you can minimize INCY — <strong>Slon Privacy</strong> will continue running in the background.
  </div>

  <section class="guide-faq" aria-labelledby="macos-faq-title">
    <h2 id="macos-faq-title">Troubleshooting</h2>

    <details>
      <summary>The subscription was added, but there are no servers</summary>
      <p>Click the subscription refresh button shown in the screenshot and wait a few seconds.</p>
      <p>If the server list still does not appear, completely close INCY, reopen the app, and refresh the subscription again.</p>
      <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/07-refresh-subscription.webp" alt="Refresh subscription button in INCY on macOS" loading="lazy">
    </details>

    <details>
      <summary>INCY does not open after I click “Add subscription”</summary>
      <p>Make sure the app is installed. Close your browser and INCY, then reopen your account and try adding the subscription again.</p>
      <p>When your browser shows the prompt, click <strong>Open Link</strong>.</p>
    </details>

    <details>
      <summary>Unable to connect to a server</summary>
      <p>Check your Internet connection without the VPN, select another server, and restart INCY.</p>
      <p>Also make sure the app has all required system permissions and that no other VPN app is running on your Mac.</p>
    </details>

    <details>
      <summary>macOS asks for the administrator password again</summary>
      <p>Enter the administrator account password and confirm the prompt. INCY needs this system permission to create the VPN connection.</p>
    </details>

    <div class="guide-note">
      <strong>What's next?</strong>
      <p>
        <a href="{{ site.baseurl }}/en/knowledge/tips/multiple-devices/">Install Slon Privacy on another device →</a>
      </p>
      <p>
        <a href="{{ site.baseurl }}/en/knowledge/tips/quick-help/">Quick help if you're having problems →</a>
      </p>
    </div>
  </section>
</section>
