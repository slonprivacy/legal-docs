---
layout: default
title: Install Slon Privacy on Android
description: Step-by-step guide to installing and setting up Slon Privacy on Android with Happ Plus or INCY.
lang: en
permalink: /en/knowledge/install/android/
---
{% include knowledge-styles.html %}

<div class="app-tabs" data-app-tabs>
  <div class="app-tab-buttons" role="tablist" aria-label="Choose an app">
    <button class="app-tab-button" role="tab" aria-selected="true" aria-controls="happ-panel">Happ Plus</button>
    <button class="app-tab-button" role="tab" aria-selected="false" aria-controls="incy-panel">INCY</button>
  </div>

  <section id="happ-panel" class="app-tab-panel is-active" role="tabpanel">
    <h2>Happ Plus</h2>
    <p><strong>Install Happ, add your Slon Privacy subscription, and connect to a server. Setup usually takes no more than 2–3 minutes.</strong></p>

    <div class="guide-note">
      <strong>Before you start</strong>
      <p>Make sure your Slon Privacy subscription is active and your phone is connected to the Internet.</p>
      <a href="{{ site.baseurl }}/en/knowledge/subscription/how-to-subscribe/">How to subscribe →</a>
    </div>

    <section class="guide-video-section" aria-labelledby="happ-video-title">
      <h2 id="happ-video-title">Video guide</h2>
      <p>Watch the complete Happ installation and connection process on Android.</p>
      <video class="guide-video" controls playsinline preload="metadata">
        <source src="{{ site.baseurl }}/assets/video/knowledge-base/android/happ/android-happ-install.mp4" type="video/mp4">
        Your browser does not support video playback.
      </video>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Sign in</h2>
        <p>Sign in to your account through the <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram bot</a> or the <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">website</a>. Tap “Home”, then tap “Connect device”.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/01-connect-device.webp" alt="Connect device button in the Slon Privacy account" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Install Happ</h2>
        <p>Select <strong>Android</strong> as your device and <strong>Happ Plus</strong> as the app.</p>
        <p>Tap <strong>“Open in Google Play”</strong>. If Google Play is unavailable, use the <strong>“Download APK”</strong> button.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/02-select-android-happ.webp" alt="Selecting Android and Happ on the Slon Privacy setup page" loading="lazy">
        <p>Install <strong>“Happ — Proxy Utility”</strong> from Google Play. If the app is already installed, you will see an “Open” button.</p>
        <div class="guide-warning"><strong>Important:</strong> APK files should only be installed from trusted sources. Google Play is the preferred installation method.</div>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Add your subscription</h2>
        <p>Return from Google Play to the setup page in your account and tap <strong>“Add subscription”</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/03-install-happ.webp" alt="Add subscription button on the Slon Privacy setup page" loading="lazy">
        <p>After you tap “Add subscription”, Happ will open automatically. Wait for the message confirming that the SLON Privacy subscription has been successfully updated. The server list will then appear.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Connect</h2>
        <ul class="guide-simple-list">
          <li>Select any server from the Happ list.</li>
          <li>Tap the large power button.</li>
          <li>The first time you connect, approve Android's system request to create a VPN connection.</li>
          <li>Wait for the connection status to change.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/04-add-subscription.webp" alt="Server list and connection button in Happ" loading="lazy">
        <div class="guide-warning"><strong>The Android system request is a standard part of using Happ.</strong> The connection cannot start without this permission.</div>
      </div>
    </section>

    <div class="guide-success">
      <strong>Done!</strong> Once connected, you can minimize Happ — <strong>Slon Privacy</strong> will continue running in the background.
    </div>

    <section class="guide-faq" aria-labelledby="happ-faq-title">
      <h2 id="happ-faq-title">Troubleshooting</h2>

      <details>
        <summary>Happ does not open after I tap “Add subscription”</summary>
        <p>Make sure the app is installed. Close your browser and Happ, then try importing the subscription again.</p>
      </details>

      <details>
        <summary>The subscription was added, but there are no servers</summary>
        <p>Tap the refresh button next to the subscription name. If that does not help, add the subscription again.</p>
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/05-refresh-servers.webp" alt="Refresh servers button in Happ" loading="lazy">
      </details>

      <details>
        <summary>The server will not connect</summary>
        <p>Check that your Internet connection works without the VPN, select another server, and make sure Android has permission to create the VPN connection.</p>
        <p><strong>If Android asks for permission to create the connection, be sure to tap “Allow”.</strong> The connection will not work without it.</p>
      </details>

      <details>
        <summary>Google Play is unavailable</summary>
        <p>Use the <strong>“Download APK”</strong> button on the official setup page.</p>
      </details>

      <details>
        <summary>Having trouble using Happ?</summary>
        <p>Try installing <button type="button" class="guide-inline-tab-link" data-open-app-tab="incy-panel"><strong>INCY</strong></button>. It is compatible with Slon Privacy and may work more reliably on some devices.</p>
      </details>

      <div class="guide-note">
        <strong>What's next?</strong>
        <p><a href="{{ site.baseurl }}/en/knowledge/tips/multiple-devices/">Install Slon Privacy on another device →</a></p>
        <p><a href="{{ site.baseurl }}/en/knowledge/tips/quick-help/">Quick help if you're having problems →</a></p>
      </div>
    </section>
  </section>

  <section id="incy-panel" class="app-tab-panel" role="tabpanel">
    <h2>INCY</h2>
    <p><strong>Install INCY, add your Slon Privacy subscription, and connect to a server. Setup usually takes no more than 2–3 minutes.</strong></p>

    <div class="guide-note">
      <strong>Before you start</strong>
      <p>Make sure your Slon Privacy subscription is active and your phone is connected to the Internet.</p>
      <a href="{{ site.baseurl }}/en/knowledge/subscription/how-to-subscribe/">How to subscribe →</a>
    </div>

    <section class="guide-video-section" aria-labelledby="incy-video-title">
      <h2 id="incy-video-title">Video guide</h2>
      <p>Watch the complete INCY installation and connection process on Android.</p>
      <video class="guide-video" controls playsinline preload="metadata">
        <source src="{{ site.baseurl }}/assets/video/knowledge-base/android/incy/android-INCY-install.mp4" type="video/mp4">
        Your browser does not support video playback.
      </video>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Sign in</h2>
        <p>Sign in to your account through the <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram bot</a> or the <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">website</a>. Tap “Home”, then tap “Connect device”.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/01-connect-device.webp" alt="Connect device button in the Slon Privacy account" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Install INCY</h2>
        <p>Select <strong>Android</strong> as your device and <strong>INCY</strong> as the app.</p>
        <p>Tap <strong>“Open in Google Play”</strong>. If Google Play is unavailable, use the <strong>“Download APK”</strong> button.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/incy/02-select-android-INCY.webp" alt="Selecting Android and INCY on the Slon Privacy setup page" loading="lazy">
        <p>Install the <strong>INCY</strong> app. If it is already installed, you will see an “Open” button.</p>
        <div class="guide-warning"><strong>Important:</strong> APK files should only be installed from trusted sources. Google Play is the preferred installation method.</div>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Import your subscription</h2>
        <p>Return to the Slon Privacy setup page and tap <strong>“Add subscription”</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/incy/03-import-subscription-INCY.webp" alt="Add subscription button on the Slon Privacy setup page" loading="lazy">
        <p>INCY will open automatically and your <strong>SLON Privacy</strong> subscription will be imported into the app.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Connect</h2>
        <p>After the subscription is imported, the server list will appear automatically. Tap the large power button to connect.</p>
        <ul class="guide-simple-list">
          <li>The first time you connect, approve Android's system request to create a VPN connection.</li>
          <li>Wait for the connection status to change.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/incy/04-connect-INCY.webp" alt="INCY home screen with the connection button and Slon Privacy server list" loading="lazy">
        <div class="guide-warning"><strong>The Android system request is a standard part of using INCY.</strong> The connection cannot start without this permission.</div>
      </div>
    </section>

    <div class="guide-success">
      <strong>Done!</strong> Once connected, you can minimize INCY — <strong>Slon Privacy</strong> will continue running in the background.
    </div>

    <section class="guide-faq" aria-labelledby="incy-faq-title">
      <h2 id="incy-faq-title">Troubleshooting</h2>

      <details>
        <summary>INCY does not open after I tap “Add subscription”</summary>
        <p>Make sure the app is installed. Close your browser and INCY, then reopen the setup page and try adding the subscription again.</p>
      </details>

      <details>
        <summary>The subscription was added, but there are no servers</summary>
        <p>Tap the refresh button next to the <strong>SLON Privacy</strong> subscription name. If the server list still does not appear, add the subscription again from your account.</p>
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/android/incy/05-refresh-subscription-INCY.webp" alt="Refresh subscription button in INCY" loading="lazy">
      </details>

      <details>
        <summary>The server will not connect</summary>
        <p>Check that your Internet connection works without the VPN, select another server, and try connecting again.</p>
        <p>Make sure INCY has Android permission to create a VPN connection. If a system prompt appears, tap <strong>“Allow”</strong>.</p>
      </details>

      <details>
        <summary>Google Play is unavailable</summary>
        <p>Use the <strong>“Download APK”</strong> button on the official Slon Privacy setup page.</p>
      </details>

      <details>
        <summary>INCY connects, but websites do not open</summary>
        <p>Disconnect, select another server, and reconnect. Also temporarily disable other VPN apps, Private DNS, and any apps that may manage network connections.</p>
      </details>

      <div class="guide-note">
        <strong>What's next?</strong>
        <p><a href="{{ site.baseurl }}/en/knowledge/tips/multiple-devices/">Install Slon Privacy on another device →</a></p>
        <p><a href="{{ site.baseurl }}/en/knowledge/tips/quick-help/">Quick help if you're having problems →</a></p>
      </div>
    </section>
  </section>
</div>

{% include app-tabs-script.html %}

<script>
document.addEventListener('click', function (event) {
  const trigger = event.target.closest('[data-open-app-tab]');
  if (!trigger) return;

  const panelId = trigger.getAttribute('data-open-app-tab');
  const panel = document.getElementById(panelId);
  if (!panel) return;

  const tabsRoot = trigger.closest('[data-app-tabs]');
  if (!tabsRoot) return;

  tabsRoot.querySelectorAll('[role="tab"]').forEach(function (button) {
    const isTarget = button.getAttribute('aria-controls') === panelId;
    button.setAttribute('aria-selected', isTarget ? 'true' : 'false');
  });

  tabsRoot.querySelectorAll('[role="tabpanel"]').forEach(function (item) {
    item.classList.toggle('is-active', item.id === panelId);
  });

  panel.scrollIntoView({ behavior: 'smooth', block: 'start' });
});
</script>
