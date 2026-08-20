---
layout: default
title: Telegram недоступен? Как войти в личный кабинет и оплатить подписку
lang: ru
permalink: /ru/knowledge/subscription/payment-without-telegram/
---
{% include knowledge-styles.html %}

<section class="app-tab-panel is-active" aria-labelledby="telegram-unavailable-title">

  <p><strong>Если Telegram временно недоступен, вы всё равно можете войти в личный кабинет Slon Privacy, управлять подпиской и восстановить доступ одним из способов ниже.</strong></p>

  <div class="guide-note">
    <strong>Главное</strong>
    <p>Самый надёжный вариант — заранее привязать к аккаунту электронную почту. Тогда вход в личный кабинет и оплата подписки останутся доступны даже при проблемах с Telegram.</p>
  </div>

  <section class="guide-step">
    <div class="guide-step-number">1</div>
    <div class="guide-step-content">
      <h2 id="telegram-unavailable-title">Войдите через электронную почту</h2>
      <p>Если вы заранее привязали <strong>Email</strong> к профилю Slon Privacy, авторизуйтесь на <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">сайте</a> без использования Telegram.</p>
      <p>После входа вы сможете проверить подписку, продлить её или подключить новое устройство.</p>
      <p><a href="/ru/knowledge/subscription/link-telegram/">Как привязать Telegram и электронную почту →</a></p>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">2</div>
    <div class="guide-step-content">
      <h2>Подключите прокси для Telegram</h2>
      <p>Если электронная почта ещё не привязана, попробуйте восстановить доступ к Telegram через MTProto-прокси Slon Privacy.</p>

      <div class="guide-note">
        <strong>Подключение прокси</strong>
        <p>Нажмите ссылку ниже. Если Telegram установлен на устройстве, приложение предложит добавить прокси автоматически.</p>
        <p>
          <a href="tg://proxy?server=130.49.185.95&amp;port=33443&amp;secret=2d52f5754605c47237b483cd092be6b3">
            <strong>Подключить прокси в Telegram →</strong>
          </a>
        </p>
        <p>Если ссылка не сработала, скопируйте её и откройте вручную:</p>
        <p><code>tg://proxy?server=130.49.185.95&amp;port=33443&amp;secret=2d52f5754605c47237b483cd092be6b3</code></p>
      </div>

      <section class="guide-faq" aria-labelledby="proxy-qr-title">
        <h3 id="proxy-qr-title">QR-код</h3>
        <details>
          <summary>Показать QR-код</summary>
          <p>Отсканируйте QR-код камерой телефона, чтобы подключить прокси в Telegram.</p>
          <img
            class="guide-image guide-image-small"
            src="{{ site.baseurl }}/assets/img/knowledge-base/subscription/telegram-unavailable/proxy-qr.webp"
            alt="QR-код для подключения прокси Slon Privacy"
            loading="lazy">
        </details>
      </section>

      <div class="guide-warning">
        <strong>Важно:</strong> прокси помогает открыть Telegram, но не заменяет привязку Email. После восстановления доступа рекомендуем сразу добавить резервный способ входа.
      </div>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">3</div>
    <div class="guide-step-content">
      <h2>Если прокси не помог</h2>
      <p>Создайте или откройте аккаунт через электронную почту и используйте Slon Privacy для восстановления доступа к Telegram.</p>
      <ul class="guide-simple-list">
        <li>Откройте личный кабинет и авторизуйтесь через <strong>Email</strong>.</li>
        <li>Активируйте бесплатную пробную подписку на <strong>3 дня</strong>, если она ещё доступна для аккаунта.</li>
        <li>Установите Slon Privacy и подключитесь к серверу.</li>
        <li>Откройте Telegram и восстановите доступ к своему аккаунту.</li>
        <li>После входа привяжите Telegram и Email к одному аккаунту.</li>
      </ul>
      <p><a href="/ru/knowledge/subscription/link-telegram/">Как объединить Telegram и Email →</a></p>
    </div>
  </section>

  <div class="guide-success">
    <strong>Совет:</strong> привяжите Telegram и Email сразу после регистрации. Это поможет сохранить доступ к личному кабинету, подписке и настройкам независимо от временных ограничений одного из способов входа.
  </div>

</section>
