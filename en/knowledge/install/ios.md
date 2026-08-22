---
layout: default
title: Install Slon Privacy on iOS
description: Step-by-step guide to installing and setting up Slon Privacy on iPhone and iPad with Happ or INCY.
lang: en
permalink: /en/knowledge/install/ios/
---
{% include knowledge-styles.html %}

<div class="app-tabs" data-app-tabs>
  <div class="app-tab-buttons" role="tablist" aria-label="Choose an app">
    <button class="app-tab-button" role="tab" aria-selected="true" aria-controls="happ-panel">Happ</button>
    <button class="app-tab-button" role="tab" aria-selected="false" aria-controls="incy-panel">INCY</button>
  </div>

  <section id="happ-panel" class="app-tab-panel is-active" role="tabpanel">
    <h2>Happ</h2>
    <p><strong>Install Happ, add your Slon Privacy subscription, and connect to a server. Setup usually takes no more than 2–3 minutes.</strong></p>

    <div class="guide-note">
      <strong>Before you start</strong>
      <p>Make sure your Slon Privacy subscription is active and your iPhone or iPad is connected to the Internet.</p>
      <a href="{{ site.baseurl }}/en/knowledge/subscription/how-to-subscribe/">How to subscribe →</a>
    </div>

    <div class="guide-warning">
      <strong>Note:</strong> if Happ is unavailable in your region, we recommend using
      <button type="button" class="guide-inline-tab-link" data-open-app-tab="incy-panel"><strong>INCY</strong></button>
      or changing the region of your Apple Account.
    </div>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Sign in</h2>
        <p>Sign in to your account through the <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram bot</a> or the <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">website</a>. Tap “Home”, then tap “Connect device”.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/01-connect-device.webp" alt="Connect device button in the Slon Privacy account" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Install Happ</h2>
        <p>Select <strong>iOS</strong> as your device and <strong>Happ</strong> as the app.</p>
        <p>Tap the appropriate App Store button and install the app.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/02-select-IOS-happ.webp" alt="Selecting iOS and Happ on the Slon Privacy setup page" loading="lazy">
        <p>If the app is unavailable in the App Store, use INCY or <a href="{{ site.baseurl }}/en/knowledge/tips/russian-app-store/">change the region of your Apple Account.</a></p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Add your subscription</h2>
        <p>Return from the App Store to the setup page in your account and tap <strong>“Add subscription”</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/03-install-IOS-happ.webp" alt="Add subscription button on the Slon Privacy setup page" loading="lazy">
        <p>Happ will open automatically and your <strong>SLON Privacy</strong> subscription will be added to the app.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Connect</h2>
        <ul class="guide-simple-list">
          <li>Select any server from the Happ list.</li>
          <li>Tap the large power button.</li>
          <li>The first time you connect, allow the app to add a VPN configuration.</li>
          <li>Confirm the action with Face ID, Touch ID, or your device passcode.</li>
          <li>Wait for the connection status to change.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/04-add-subscription.webp" alt="Server list and connection button in Happ on iOS" loading="lazy">
        <div class="guide-warning"><strong>The iOS system request is a standard part of using Happ.</strong> The connection cannot start without this permission.</div>
      </div>
    </section>

    <div class="guide-success">
      <strong>Done!</strong> Once connected, you can minimize Happ — <strong>Slon Privacy</strong> will continue running in the background.
    </div>

    <section class="guide-faq" aria-labelledby="happ-faq-title">
      <h2 id="happ-faq-title">Troubleshooting</h2>

      <details>
        <summary>Happ does not open after I tap “Add subscription”</summary>
        <p>Make sure the app is installed. Close your browser and Happ, then reopen the setup page and try adding the subscription again.</p>
      </details>

      <details>
        <summary>The subscription was added, but there are no servers</summary>
        <p>Tap the refresh button next to the subscription name. If that does not help, add the subscription again. If necessary, contact support through <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">@slon_privacy_bot</a>.</p>
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/05-refresh-servers.webp" alt="Refresh servers button in Happ on iOS" loading="lazy">
      </details>

      <details>
        <summary>The server will not connect</summary>
        <p>Check that your Internet connection works without the VPN, select another server, and make sure Happ is allowed to add a VPN configuration.</p>
        <p><strong>If iOS asks for permission to add a VPN configuration, be sure to tap “Allow”.</strong></p>
      </details>

      <details>
        <summary>Happ is unavailable in the App Store</summary>
        <p>Change the region of your Apple Account or install <button type="button" class="guide-inline-tab-link" data-open-app-tab="incy-panel"><strong>INCY</strong></button>.</p>
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
      <p>Make sure your Slon Privacy subscription is active and your iPhone or iPad is connected to the Internet.</p>
      <a href="{{ site.baseurl }}/en/knowledge/subscription/how-to-subscribe/">How to subscribe →</a>
    </div>

    <section class="guide-video-section" aria-labelledby="incy-video-title">
      <h2 id="incy-video-title">Video guide</h2>
      <p>Watch the complete INCY installation and connection process on iOS.</p>
      <video class="guide-video" controls playsinline preload="metadata">
        <source src="{{ site.baseurl }}/assets/video/knowledge-base/ios/incy/ios-incy-install.mp4" type="video/mp4">
        Your browser does not support video playback.
      </video>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Sign in</h2>
        <p>Sign in to your account through the <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram bot</a> or the <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">website</a>. Tap “Home”, then tap “Connect device”.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/01-connect-device.webp" alt="Connect device button in the Slon Privacy account" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Install INCY</h2>
        <p>Select <strong>iOS</strong> as your device and <strong>INCY</strong> as the app.</p>
        <p>Tap <strong>“App Store”</strong> and install the app.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/incy/02-select-IOS-INCY.webp" alt="Selecting iOS and INCY on the Slon Privacy setup page" loading="lazy">
        <p>If the app is unavailable in the App Store, use Happ or <a href="{{ site.baseurl }}/en/knowledge/tips/russian-app-store/">change the region of your Apple Account.</a></p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Import your subscription</h2>
        <p>Return to the Slon Privacy setup page and tap <strong>“Add subscription”</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/incy/03-import-subscription-IOS-INCY.webp" alt="Add subscription button on the Slon Privacy setup page" loading="lazy">
        <p>INCY will open automatically and your <strong>SLON Privacy</strong> subscription will be imported into the app.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Connect</h2>
        <p>After the subscription is imported, the server list will appear automatically. Select a server and tap the large connection button.</p>
        <ul class="guide-simple-list">
          <li>The first time you connect, allow the app to add a VPN configuration.</li>
          <li>Confirm the action with Face ID, Touch ID, or your device passcode.</li>
          <li>Wait for the connection status to change.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/incy/04-connect-IOS-INCY.webp" alt="INCY home screen with the connection button and Slon Privacy server list on iOS" loading="lazy">
        <div class="guide-warning"><strong>The iOS system request is a standard part of using INCY.</strong> The connection cannot start without this permission.</div>
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
        <p>Tap the refresh button next to the <strong>SLON Privacy</strong> subscription name. If the server list still does not appear, add the subscription again. If necessary, contact support through <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">@slon_privacy_bot</a>.</p>
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/incy/05-refresh-subscription-IOS-INCY.webp" alt="Refresh subscription button in INCY on iOS" loading="lazy">
      </details>

      <details>
        <summary>The server will not connect</summary>
        <p>Check that your Internet connection works without the VPN, select another server, and try connecting again.</p>
        <p>Make sure INCY is allowed to add a VPN configuration. If a system prompt appears, tap <strong>“Allow”</strong>.</p>
      </details>

      <details>
        <summary>INCY is unavailable in the App Store</summary>
        <p>Change the region of your Apple Account or use another compatible app.</p>
      </details>

      <details>
        <summary>INCY connects, but websites do not open</summary>
        <p>Disconnect, select another server, and reconnect. Also temporarily disable other VPN apps and any apps that may manage network connections.</p>
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
