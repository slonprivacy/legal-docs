---
layout: default
title: Install Slon Privacy on Windows
description: Step-by-step guide to installing and setting up Slon Privacy on Windows with Happ or INCY.
lang: en
permalink: /en/knowledge/install/windows/
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
      <p>Make sure your Slon Privacy subscription is active and your computer is connected to the Internet.</p>
      <a href="{{ site.baseurl }}/en/knowledge/subscription/how-to-subscribe/">How to subscribe →</a>
    </div>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Sign in</h2>
        <p>Sign in to your account through the <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram bot</a> or the <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">website</a>. Click “Home”, then click “Connect device”.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/happ/01-connect-device-W-Happ.webp" alt="Connect device button in the Slon Privacy account" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Install Happ</h2>
        <p>Select <strong>Windows</strong> as your device and <strong>Happ</strong> as the app.</p>
        <p>Click the <strong>Windows</strong> button. The installer will start downloading automatically.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/happ/02-select-W-happ.webp" alt="Selecting Windows and Happ on the Slon Privacy setup page" loading="lazy">
        <p>Once the download is complete, open the downloaded file and install the app.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Add your subscription</h2>
        <p>After installation, return to the Slon Privacy setup page and click <strong>“Add subscription”</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/happ/03-install-W-happ.webp" alt="Add subscription button on the Slon Privacy setup page" loading="lazy">
        <p>Happ will open automatically and your <strong>SLON Privacy</strong> subscription will be added to the app.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Connect</h2>
        <ul class="guide-simple-list">
          <li>Select any server from the Happ list.</li>
          <li>Click the large connection button.</li>
          <li>Grant the app all permissions requested by Windows.</li>
          <li>Wait for the connection status to change.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/happ/04-add-subscription-W-Happ.webp" alt="Server list and connection button in Happ on Windows" loading="lazy">
        <div class="guide-warning"><strong>Important:</strong> grant Happ all requested permissions. The connection may not start without them.</div>
      </div>
    </section>

    <div class="guide-success">
      <strong>Done!</strong> Once connected, you can minimize Happ — <strong>Slon Privacy</strong> will continue running in the background.
    </div>

    <section class="guide-faq" aria-labelledby="happ-faq-title">
      <h2 id="happ-faq-title">Troubleshooting</h2>

      <details>
        <summary>Happ does not open after I click “Add subscription”</summary>
        <p>Make sure the app is installed. Close your browser and Happ, then reopen the setup page and try adding the subscription again.</p>
      </details>

      <details>
        <summary>The subscription was added, but there are no servers</summary>
        <p>Click the refresh button next to the subscription name. If that does not help, add the subscription again. If necessary, contact support through <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">@slon_privacy_bot</a>.</p>
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/happ/05-refresh-servers-W-Happ.webp" alt="Refresh servers button in Happ on Windows" loading="lazy">
      </details>

      <details>
        <summary>The server will not connect</summary>
        <p>Check that your Internet connection works without the VPN, select another server, and try connecting again. Make sure the app has all requested permissions.</p>
      </details>

      <details>
        <summary>Error “Failed to start xray: app/proxyman/inbound: failed to start proxy &gt; A required privilege is not held by the client”</summary>
        <p>Grant Happ all requested permissions and completely restart the app.</p>
        <p>Check whether any other VPN apps, proxy software, or network services are running. Close them and try connecting again.</p>
      </details>

      <details>
        <summary>Having trouble using Happ?</summary>
        <p>Try installing <button type="button" class="guide-inline-tab-link" data-open-app-tab="incy-panel"><strong>INCY</strong></button>. It is compatible with Slon Privacy and may work more reliably on some computers.</p>
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
      <p>Make sure your Slon Privacy subscription is active and your computer is connected to the Internet.</p>
      <a href="{{ site.baseurl }}/en/knowledge/subscription/how-to-subscribe/">How to subscribe →</a>
    </div>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Sign in</h2>
        <p>Sign in to your account through the <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram bot</a> or the <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">website</a>. Click “Home”, then click “Connect device”.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/incy/01-connect-device-W-INCY.webp" alt="Connect device button in the Slon Privacy account" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Install INCY</h2>
        <p>Select <strong>Windows</strong> as your device and <strong>INCY</strong> as the app.</p>
        <p>Click the <strong>Windows</strong> button. The installer will start downloading automatically.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/incy/02-select-W-incy.webp" alt="Selecting Windows and INCY on the Slon Privacy setup page" loading="lazy">
        <p>Once the download is complete, open the downloaded file and install the app.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Import your subscription</h2>
        <p>After installation, return to the Slon Privacy setup page and click <strong>“Add subscription”</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/incy/03-install-W-incy.webp" alt="Add subscription button on the Slon Privacy setup page" loading="lazy">
        <p>INCY will open automatically and your <strong>SLON Privacy</strong> subscription will be imported into the app.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Connect</h2>
        <ul class="guide-simple-list">
          <li>Select any server from the INCY list.</li>
          <li>Click the large connection button.</li>
          <li>Grant the app all permissions requested by Windows.</li>
          <li>Wait for the connection status to change.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/incy/04-add-subscription-W-incy.webp" alt="Server list and connection button in INCY on Windows" loading="lazy">
        <div class="guide-warning"><strong>Important:</strong> grant INCY all requested permissions. The connection may not start without them.</div>
      </div>
    </section>

    <div class="guide-success">
      <strong>Done!</strong> Once connected, you can minimize INCY — <strong>Slon Privacy</strong> will continue running in the background.
    </div>

    <section class="guide-faq" aria-labelledby="incy-faq-title">
      <h2 id="incy-faq-title">Troubleshooting</h2>

      <details>
        <summary>INCY does not open after I click “Add subscription”</summary>
        <p>Make sure the app is installed. Close your browser and INCY, then reopen the setup page and try adding the subscription again.</p>
      </details>

      <details>
        <summary>The subscription was added, but there are no servers</summary>
        <p>Click the refresh button next to the <strong>SLON Privacy</strong> subscription name. If the server list still does not appear, add the subscription again. If necessary, contact support through <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">@slon_privacy_bot</a>.</p>
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/incy/05-refresh-servers-W-incy.webp" alt="Refresh subscription button in INCY on Windows" loading="lazy">
      </details>

      <details>
        <summary>The server will not connect</summary>
        <p>Check that your Internet connection works without the VPN, select another server, and try connecting again. Make sure the app has all requested permissions.</p>
      </details>

      <details>
        <summary>Error “Failed to start xray: app/proxyman/inbound: failed to start proxy &gt; A required privilege is not held by the client”</summary>
        <p>Grant INCY all requested permissions and completely restart the app.</p>
        <p>Check whether any other VPN apps, proxy software, or network services are running. Close them and try connecting again.</p>
      </details>

      <details>
        <summary>Having trouble using INCY?</summary>
        <p>Try installing <button type="button" class="guide-inline-tab-link" data-open-app-tab="happ-panel"><strong>Happ</strong></button>. It is compatible with Slon Privacy and may work more reliably on some computers.</p>
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
