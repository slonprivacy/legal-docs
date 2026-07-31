---
layout: default
title: Установка Slon Privacy на macOS
lang: ru
permalink: /ru/knowledge/install/macos/
---
{% include knowledge-styles.html %}

<section class="app-tab-panel is-active" aria-labelledby="macos-incy-title">
 
  <p><strong>Установите INCY, добавьте подписку Slon Privacy и подключитесь к серверу. Обычно настройка занимает не более 2–3 минут.</strong></p>

  <div class="guide-note">
    <strong>Перед началом</strong>
    <p>Убедитесь, что подписка Slon Privacy активна, а Mac подключён к Интернету.</p>
    <a href="https://legal.slonprivacy.app/ru/knowledge/subscription/how-to-subscribe/" target="_blank" rel="noopener noreferrer">Как подписаться →</a>
  </div>

  <section class="guide-step">
    <div class="guide-step-number">1</div>
    <div class="guide-step-content">
      <h2>Скачайте INCY</h2>
      <p>  <p>Войдите в личный кабинет через <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram-бота</a> или через <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">сайт</a>. Нажмите «Главная», затем нажмите «Подключить устройство».</p> Выберите <strong>macOS</strong>.</p>
      <p>Выберите подходящий способ установки:</p>
      <ul class="guide-simple-list">
        <li><strong>App Store</strong> — рекомендуется большинству пользователей.</li>
        <li><strong>Apple Silicon (.dmg)</strong> — для Mac с процессорами Apple M1, M2, M3 и новее.</li>
        <li><strong>Intel (.dmg)</strong> — для Mac с процессорами Intel.</li>
      </ul>
      <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/03-download-macos.webp" alt="Варианты скачивания INCY для macOS" loading="lazy">
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">2</div>
    <div class="guide-step-content">
      <h2>Установите приложение</h2>
      <p>Если вы скачали версию в формате <strong>.dmg</strong>, откройте файл и перетащите приложение <strong>INCY</strong> в папку <strong>Applications</strong>.</p>
      <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/01-install-macos.webp" alt="Перетаскивание INCY в папку Applications" loading="lazy">
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">3</div>
    <div class="guide-step-content">
      <h2>Добавьте подписку</h2>
      <p>Вернитесь в личный кабинет Slon Privacy и нажмите <strong>«Добавить подписку»</strong>.</p>
      <p>Когда браузер предложит открыть приложение INCY, нажмите <strong>Open Link</strong>. Для удобства можно отметить пункт <strong>Always allow</strong>, чтобы такие ссылки в дальнейшем автоматически открывались в INCY.</p>
      <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/02-open-link-macos.webp" alt="Запрос браузера на открытие ссылки в INCY" loading="lazy">
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">4</div>
    <div class="guide-step-content">
      <h2>Разрешите создание VPN</h2>
      <p>При первом подключении macOS запросит разрешение на создание VPN-конфигурации. Введите пароль администратора Mac и нажмите <strong>OK</strong>.</p>
      <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/04-vpn-permission-macos.webp" alt="Системный запрос macOS на разрешение создания VPN" loading="lazy">
      <div class="guide-warning"><strong>Важно:</strong> предоставьте INCY все запрашиваемые системные разрешения. Без них VPN-подключение не запустится.</div>
    </div>
  </section>

  <section class="guide-step">
    <div class="guide-step-number">5</div>
    <div class="guide-step-content">
      <h2>Подключитесь</h2>
      <ul class="guide-simple-list">
        <li>Выберите любой сервер в списке INCY.</li>
        <li>Нажмите кнопку подключения.</li>
        <li>Дождитесь появления зелёного индикатора вокруг значка.</li>
      </ul>
      <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/05-connected-macos.webp" alt="Успешное подключение Slon Privacy в INCY на macOS" loading="lazy">
    </div>
  </section>

  <div class="guide-success">
    <strong>Готово!</strong> После подключения INCY можно свернуть — <strong>Slon Privacy</strong> продолжит работать в фоновом режиме.
  </div>

  <section class="guide-faq" aria-labelledby="macos-faq-title">
    <h2 id="macos-faq-title">Возможные проблемы</h2>

    <details>
      <summary>Подписка добавилась, но серверов нет</summary>
      <p>Нажмите кнопку обновления подписки, отмеченную на скриншоте, и подождите несколько секунд.</p>
      <p>Если список серверов не появился, полностью закройте INCY, откройте приложение снова и повторите обновление.</p>
      <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/macos/incy/07-refresh-subscription.webp" alt="Кнопка обновления подписки в INCY на macOS" loading="lazy">
    </details>

    <details>
      <summary>INCY не открывается после нажатия «Добавить подписку»</summary>
      <p>Убедитесь, что приложение установлено. Закройте браузер и INCY, затем снова откройте личный кабинет и повторите добавление подписки.</p>
      <p>Когда браузер покажет запрос, нажмите <strong>Open Link</strong>.</p>
    </details>

    <details>
      <summary>Не удаётся подключиться к серверу</summary>
      <p>Проверьте подключение к Интернету без VPN, выберите другой сервер и перезапустите INCY.</p>
      <p>Также убедитесь, что приложению предоставлены все системные разрешения и на Mac не запущено другое VPN-приложение.</p>
    </details>

    <details>
      <summary>macOS снова запрашивает пароль администратора</summary>
      <p>Введите пароль учётной записи администратора и подтвердите запрос. Это системное разрешение необходимо INCY для создания VPN-подключения.</p>
    </details>
  </section>
</section>
