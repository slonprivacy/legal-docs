---
layout: default
title: Troubleshooting Slon Privacy on Android and iOS
description: "Quick help with Slon Privacy issues on Android and iOS: Happ or INCY won't connect, the VPN doesn't work on mobile data, or the app is unavailable in the App Store."
lang: en
permalink: /en/knowledge/tips/quick-help/
---
{% include knowledge-styles.html %}

<section class="app-tab-panel is-active">
  <p><strong>Quick solutions to common Slon Privacy connection issues on Android and iOS.</strong></p>

  <section class="guide-faq" aria-labelledby="general-questions-title">
    <h2 id="general-questions-title">General questions</h2>

    <details>
      <summary>1. Tips for all mobile devices (Android / iOS)</summary>

      <ol class="guide-simple-list">
        <li><strong>Check the MAX app.</strong> It may interfere with Happ or INCY. If you are having connection problems, temporarily disable or close it and check Slon Privacy again.</li>
        <li><strong>Remove unnecessary VPN profiles.</strong> Open Settings → VPN — you can quickly find this section using your device settings search. Remove unused VPN profiles, leaving only the one you need, such as Happ or INCY.</li>
        <li><strong>Check permissions.</strong> Make sure Happ or INCY has all requested system permissions.</li>
        <li><strong>Disable Low Power Mode or Battery Saver.</strong> It may restrict the app from running properly in the background.</li>
        <li><strong>Check your mobile carrier services.</strong> If your carrier has an “Internet Protection” feature or a similar service enabled, temporarily disable it.</li>
        <li><strong>Restart your device.</strong> This will reapply network settings and may resolve temporary issues with Happ or INCY.</li>
      </ol>
    </details>

    <details>
      <summary>2. It works on Wi-Fi, but not on mobile data (Android / iOS)</summary>

      <p>Happ or INCY may not have permission to use mobile data. Check the app settings.</p>

      <p><strong>On iOS:</strong> open Settings → Apps, find Happ or INCY, and enable <strong>Cellular Data</strong>.</p>

      <p><strong>On Android:</strong> open Settings → Apps, find Happ or INCY → Mobile data.</p>

      <p>Allow the app to use background data and disable any data-saving restrictions for it.</p>
    </details>

    <details>
      <summary>3. The app is unavailable in the App Store</summary>

      <p>Sometimes the app you need may be unavailable in the Russian App Store. The easiest option is to check both apps: <strong>Happ</strong> and <strong>INCY</strong>. Usually, at least one of them is available to install.</p>

      <p>If both apps are unavailable, you can use an Apple Account set to another region. There are two options:</p>

      <ul class="guide-simple-list">
        <li>
          <strong>Change the region of your main Apple Account.</strong>
          Since April 2026, Apple has simplified this process for Russian users: you can change the region even with active subscriptions and without a linked bank card. After installing Happ or INCY, you can switch the region back to Russia. To update the app later, you may need to temporarily switch to the foreign region again.
          <a href="{{ site.baseurl }}/en/knowledge/tips/russian-app-store/">How to change your region →</a>
        </li>

        <li>
          <strong>Create an additional Apple Account with another region.</strong>
          You can use this account to download and update apps, switching between accounts when necessary.
          <a href="{{ site.baseurl }}/en/knowledge/tips/russian-app-store/">How to create an account →</a>
        </li>
      </ul>
    </details>
  </section>
</section>
