---
layout: default
title: Не работает сайт с подключённым Slon Privacy
description: "Что делать, если сайт не открывается с подключённым Slon Privacy: смена локации, VPN-протокола и другие способы решения проблемы."
lang: ru
permalink: /ru/knowledge/troubleshooting/website-not-working/
---
{% include knowledge-styles.html %}

<section class="app-tab-panel is-active">

  <p><strong>Если отдельный сайт не открывается при подключённом Slon Privacy, это не всегда означает проблему с подключением. Некоторые сайты ограничивают доступ через VPN или для пользователей из определённых стран.</strong></p>

  <div class="guide-note">
    <strong>Почему это происходит</strong>
    <p>Некоторые сайты могут определять использование VPN по косвенным признакам — например, по несоответствию часового пояса устройства выбранной локации или по данным отпечатка браузера. Кроме того, сайт может ограничивать доступ для пользователей из определённых стран.</p>
  </div>

  <section class="guide-step">
    <div class="guide-step-number">1</div>
    <div class="guide-step-content">
      <h2>Смените локацию</h2>
      <p>Сначала выберите сервер в том же или близком к вашему часовом поясе. Если это не помогло — попробуйте другую локацию. <a href="{{ site.baseurl }}/ru/knowledge/about/locations/">Подробнее о доступных локациях Slon Privacy →</a></p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">2</div>
    <div class="guide-step-content">
      <h2>Используйте другой VPN-протокол</h2>
      <p>В настройках Happ или INCY выберите другой доступный протокол и попробуйте подключиться снова.</p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">3</div>
    <div class="guide-step-content">
      <h2>Откройте сайт в режиме инкогнито</h2>
      <p>Это поможет проверить, не связана ли проблема с cookies, кэшем или сохранёнными данными сайта.</p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">4</div>
    <div class="guide-step-content">
      <h2>Ограничьте отслеживание в браузере</h2>
      <p>Можно использовать расширения, блокирующие трекеры и уменьшающие объём данных, доступных сайтам для формирования отпечатка браузера.</p>
    </div>
  </section>

  <div class="guide-warning">
    <strong>Если ничего не помогло</strong>
    <p>Напишите в службу поддержки Slon Privacy. Укажите, какой сайт не открывается и какую локацию вы используете — постараемся разобраться.</p>
  </div>

</section>
