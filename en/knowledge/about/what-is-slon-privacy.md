---
layout: default
title: What Is Slon Privacy?
description: Learn what Slon Privacy is, how the service works, what happens to your internet traffic after you connect, and what data it protects.
lang: en
permalink: /en/knowledge/about/what-is-slon-privacy/
---
{% include knowledge-styles.html %}

<section class="app-tab-panel is-active" aria-labelledby="what-happens">

  <section class="guide-step">
    <div class="guide-step-number">1</div>
    <div class="guide-step-content">
      <h2 id="what-happens">What happens when you open a website?</h2>

      <p>Every time you visit a website or open an app that uses the Internet, your device sends a request. It passes through your internet service provider, several intermediate network nodes, and only then reaches the destination server.</p>

      <p>At first glance, it seems simple: you click a link and the page opens. But several parties are involved in this process.</p>

      <p>Your internet service provider knows that your device is establishing a connection. The website itself sees the IP address the request came from and can determine your approximate location. Websites and apps also often collect technical information about your browser, device, and connection settings.</p>

      <p>Individually, these details may seem insignificant. Together, they can be used to build a fairly detailed digital profile.</p>

      <p>This is where <strong>Slon Privacy</strong> comes in.</p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">2</div>
    <div class="guide-step-content">
      <h2 id="how-it-works">How Slon Privacy works</h2>

      <p>When you connect, a secure tunnel is created between your device and a Slon Privacy server.</p>

      <p>A regular connection looks roughly like this:</p>
      <p><strong>Device → internet service provider → Internet → destination website</strong></p>

      <p>With Slon Privacy connected, the route changes:</p>
      <p><strong>Device → secure Slon Privacy server → Internet → destination website</strong></p>

      <p>Your traffic first reaches a Slon Privacy server and is then forwarded to the website or app.</p>

      <p>As a result, websites see the IP address of the selected Slon Privacy server instead of your real IP address. Your internet service provider can see a connection to our Service, but does not have the usual direct view of the final resources you access.</p>

      <p>Importantly, the connection between your device and the Slon Privacy server is protected by encryption. Data intercepted on this part of the connection cannot simply be opened and read as plain text.</p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">3</div>
    <div class="guide-step-content">
      <h2 id="what-changes">What changes after you connect</h2>

      <p>Services like this are sometimes assumed to make a person completely invisible online. That is not the case.</p>

      <p>Slon Privacy does not make you “invisible” or erase your entire digital footprint. It is designed for more specific purposes:</p>

      <ul class="guide-simple-list">
        <li>hides your real IP address from the websites you visit;</li>
        <li>reduces the amount of information about your network activity available to your internet service provider;</li>
        <li>helps you use public Wi-Fi networks more securely;</li>
        <li>allows you to connect through a server in another country;</li>
        <li>helps you access resources restricted by region or by your internet service provider;</li>
        <li>improves your overall level of privacy when using the Internet.</li>
      </ul>

      <p>Simply put, Slon Privacy does not change the Internet itself. It changes the route your device uses to connect to it.</p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">4</div>
    <div class="guide-step-content">
      <h2 id="what-we-know">What Slon Privacy knows about your connection</h2>

      <p>Because the Service receives and forwards internet traffic, some technical information is available to it as necessary to establish and maintain the connection.</p>

      <p>This includes, for example:</p>

      <ul class="guide-simple-list">
        <li>the IP address you connect from;</li>
        <li>the selected server;</li>
        <li>connection time and technical status;</li>
        <li>the amount of data transferred;</li>
        <li>information required to manage your subscription and limit the number of connected devices.</li>
      </ul>

      <p>However, <strong>Slon Privacy does not keep logs of the websites you visit or your online activity</strong>. We do not store browsing history, analyze the content of user activity, or build advertising profiles based on user traffic.</p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">5</div>
    <div class="guide-step-content">
      <h2 id="what-we-cannot-see">What Slon Privacy cannot see</h2>

      <p>Most websites and apps today use their own secure connections, such as HTTPS and TLS. These technologies encrypt the contents of transmitted data before it passes through intermediate network nodes.</p>

      <p>As a result, Slon Privacy does not gain access to:</p>

      <ul class="guide-simple-list">
        <li>passwords you enter on secure websites;</li>
        <li>full bank card details;</li>
        <li>the contents of messages in messengers with properly implemented encryption;</li>
        <li>the contents of data transmitted through a secure HTTPS connection;</li>
        <li>other information inside properly secured connections.</li>
      </ul>

      <p>Services like this are sometimes portrayed as being able to read all of a user's traffic. In reality, the contents of a properly encrypted connection remain protected.</p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">6</div>
    <div class="guide-step-content">
      <h2 id="anonymity">Can Slon Privacy provide complete anonymity?</h2>

      <p>No. Claiming otherwise would be misleading.</p>

      <p>If you are signed in to Google, Telegram, VK, an online store, or another service, that service still knows which account you are using. Slon Privacy hides your real IP address, but it does not change the information you choose to provide to a website.</p>

      <p>The Service also does not protect you from:</p>

      <ul class="guide-simple-list">
        <li>malicious files and software;</li>
        <li>phishing websites;</li>
        <li>password leaks caused by reusing the same password;</li>
        <li>tracking within an account you are already signed in to;</li>
        <li>information you voluntarily provide to a website or app;</li>
        <li>identification through cookies, advertising identifiers, and browser fingerprinting.</li>
      </ul>

      <p>For this reason, Slon Privacy works best alongside other security measures, such as unique passwords, two-factor authentication, regular system updates, and caution when opening links or downloading files.</p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">7</div>
    <div class="guide-step-content">
      <h2 id="other-country">Why choose a server in another country?</h2>

      <p>Websites determine your approximate location primarily from your IP address. Once connected, they see the IP address of the Slon Privacy server, so they treat the request as coming from the country where the selected server is located.</p>

      <p>This can be useful when a resource:</p>

      <ul class="guide-simple-list">
        <li>is available only in a particular region;</li>
        <li>restricts certain features in specific countries;</li>
        <li>does not open through a particular internet service provider;</li>
        <li>shows different content to users in different regions.</li>
      </ul>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">8</div>
    <div class="guide-step-content">
      <h2 id="public-wifi">Why use Slon Privacy on public Wi-Fi?</h2>

      <p>Open networks in cafés, hotels, airports, and shopping centers are convenient, but they should not be trusted completely.</p>

      <p>Slon Privacy creates a secure tunnel to its server. This makes it significantly more difficult for the Wi-Fi network operator or someone attempting to intercept traffic on the same network to obtain useful information about your connection.</p>

      <p>However, the Service cannot make a dangerous website safe. If you open a fake website yourself and enter your password there, a secure tunnel cannot undo that action.</p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">9</div>
    <div class="guide-step-content">
      <h2 id="free-services">Why a free service may not really be free</h2>

      <p>A reasonable question is: if free alternatives exist, why pay at all?</p>

      <p>The reason is simple. Maintaining servers around the world, network capacity, and infrastructure involves ongoing costs. If users are not paying for the service, its source of revenue is likely somewhere else.</p>

      <p>Some free services display advertising, others collect usage statistics, and some may share anonymized or even personal data with partners. Cases like these occur regularly.</p>

      <p>Free solutions also often come with unstable speeds, overloaded servers, and limited or nonexistent technical support.</p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">10</div>
    <div class="guide-step-content">
      <h2 id="why-slon">Why we created Slon Privacy</h2>

      <p>We wanted to create a service that is convenient to use every day, without unnecessary complexity or exaggerated promises.</p>

      <p>That is why Slon Privacy focuses on practical things:</p>

      <ul class="guide-simple-list">
        <li>simple setup across different devices;</li>
        <li>modern protocols for securing connections;</li>
        <li>stable server performance;</li>
        <li>no logs of the resources you visit;</li>
        <li>multiple payment options, including cryptocurrency;</li>
        <li>support for multiple devices under one subscription;</li>
        <li>ongoing infrastructure development and regular service updates.</li>
      </ul>

      <p>Slon Privacy does not promise absolute anonymity. It provides a secure route to the Internet, hides your real IP address from the resources you visit, and helps you maintain greater control over your network activity.</p>

      <p>For most everyday needs, that is exactly what matters.</p>
    </div>
  </section>

<div class="guide-note">
  <strong>What's next?</strong>
  <p>
    <a href="{{ site.baseurl }}/en/knowledge/about/locations/">View available locations →</a><br>
    <a href="{{ site.baseurl }}/en/knowledge/">Choose an installation guide →</a><br>
    <a href="{{ site.baseurl }}/en/knowledge/subscription/how-to-subscribe/">Get a subscription →</a>
  </p>
</div>

</section>
