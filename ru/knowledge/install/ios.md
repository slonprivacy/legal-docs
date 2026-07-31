---
layout: default
title: Установка Slon Privacy на iOS
lang: ru
permalink: /ru/knowledge/install/ios/
---
{% include knowledge-styles.html %}

<div class="app-tabs" data-app-tabs>
  <div class="app-tab-buttons" role="tablist" aria-label="Выбор приложения">
    <button class="app-tab-button" role="tab" aria-selected="true" aria-controls="happ-panel">Happ</button>
    <button class="app-tab-button" role="tab" aria-selected="false" aria-controls="incy-panel">INCY</button>
  </div>

  <section id="happ-panel" class="app-tab-panel is-active" role="tabpanel">
    <h2>Happ</h2>
    <p><strong>Установите Happ, добавьте подписку Slon Privacy и подключитесь к серверу. Обычно настройка занимает не более 2–3 минут.</strong></p>

    <div class="guide-note">
      <strong>Перед началом</strong>
      <p>Убедитесь, что подписка Slon Privacy активна, а iPhone или iPad подключён к интернету.</p>
    <a href="https://legal.slonprivacy.app/ru/knowledge/subscription/how-to-subscribe/" target="_blank" rel="noopener noreferrer">Как подписаться →</a>
    </div>

    <div class="guide-warning">
      <strong>Внимание:</strong> если приложение Happ недоступно в вашем регионе, рекомендуем использовать
      <button type="button" class="guide-inline-tab-link" data-open-app-tab="incy-panel"><strong>INCY</strong></button>
      либо сменить регион вашего аккаунта Apple.
    </div>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Авторизируйтесь</h2>
        <p>Войдите в личный кабинет через <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram-бота</a> или через <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">сайт</a>. Нажмите «Главная», затем нажмите «Подключить устройство».</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/01-connect-device.webp" alt="Кнопка «Подключить устройство» в личном кабинете Slon Privacy" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Установите Happ</h2>
        <p>Выберите устройство <strong>iOS</strong> и приложение <strong>Happ</strong>.</p>
        <p>Нажмите подходящую кнопку App Store и установите приложение.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/02-select-IOS-happ.webp" alt="Выбор iOS и Happ на странице установки Slon Privacy" loading="lazy">
        <p>Если приложение в App Store недоступно, смените регион аккаунта Apple или используйте другое приложение.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Добавьте подписку</h2>
        <p>Вернитесь из App Store в личный кабинет, на страницу установки, и нажмите <strong>«Добавить подписку»</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/03-install-IOS-happ.webp" alt="Кнопка «Добавить подписку» на странице установки Slon Privacy" loading="lazy">
        <p>После нажатия приложение Happ откроется автоматически, а подписка <strong>SLON Privacy</strong> добавится в приложение.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Подключитесь</h2>
        <ul class="guide-simple-list">
          <li>Выберите любой сервер в списке Happ.</li>
          <li>Нажмите большую кнопку питания.</li>
          <li>При первом подключении разрешите добавление VPN-конфигурации.</li>
          <li>Подтвердите действие с помощью Face ID, Touch ID или кода-пароля устройства.</li>
          <li>Дождитесь изменения статуса подключения.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/04-add-subscription.webp" alt="Список серверов и кнопка подключения в приложении Happ на iOS" loading="lazy">
        <div class="guide-warning"><strong>Системный запрос iOS — стандартная часть работы Happ.</strong> Без разрешения подключение не запустится.</div>
      </div>
    </section>

    <div class="guide-success">
      <strong>Готово!</strong> После подключения Happ можно свернуть — <strong>Slon Privacy</strong> продолжит работать в фоновом режиме.
    </div>

    <section class="guide-faq" aria-labelledby="happ-faq-title">
      <h2 id="happ-faq-title">Возможные проблемы</h2>

      <details>
        <summary>Happ не открывается после нажатия «Добавить подписку»</summary>
        <p>Убедитесь, что приложение установлено. Закройте браузер и Happ, затем снова откройте страницу установки и повторите добавление подписки.</p>
      </details>

      <details>
        <summary>Подписка добавилась, но серверов нет</summary>
        <p>Нажмите кнопку обновления рядом с названием подписки. Если это не помогло, добавьте подписку повторно. При необходимости обратитесь в поддержку через <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">@slon_privacy_bot</a>.</p>
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/05-refresh-servers.webp" alt="Кнопка обновления серверов в Happ на iOS" loading="lazy">
      </details>

      <details>
        <summary>Сервер не подключается</summary>
        <p>Проверьте интернет без VPN, выберите другой сервер и убедитесь, что Happ разрешено добавлять VPN-конфигурацию.</p>
        <p><strong>Если iOS запросит разрешение на добавление VPN-конфигурации — обязательно нажмите «Разрешить».</strong></p>
      </details>

      <details>
        <summary>Happ недоступен в App Store</summary>
        <p>Смените регион аккаунта Apple или установите <button type="button" class="guide-inline-tab-link" data-open-app-tab="incy-panel"><strong>INCY</strong></button>.</p>
      </details>

      <details>
        <summary>Не получается использовать Happ?</summary>
        <p>Попробуйте установить <button type="button" class="guide-inline-tab-link" data-open-app-tab="incy-panel"><strong>INCY</strong></button> — он совместим со Slon Privacy и может работать стабильнее на некоторых устройствах.</p>
      </details>
    </section>
  </section>

  <section id="incy-panel" class="app-tab-panel" role="tabpanel">
    <h2>INCY</h2>
    <p><strong>Установите INCY, добавьте подписку Slon Privacy и подключитесь к серверу. Обычно настройка занимает не более 2–3 минут.</strong></p>

    <div class="guide-note">
      <strong>Перед началом</strong>
      <p>Убедитесь, что подписка Slon Privacy активна, а iPhone или iPad подключён к интернету.</p>
      <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Как подписаться →</a>
    </div>

    <section class="guide-video-section" aria-labelledby="incy-video-title">
      <h2 id="incy-video-title">Видеоинструкция</h2>
      <p>Посмотрите весь процесс установки и подключения INCY на iOS.</p>
      <video class="guide-video" controls playsinline preload="metadata">
        <source src="{{ site.baseurl }}/assets/video/knowledge-base/ios/incy/IOS-INCY-install.MP4" type="video/mp4">
        Ваш браузер не поддерживает воспроизведение видео.
      </video>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Авторизируйтесь</h2>
     <p>Войдите в личный кабинет через <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram-бота</a> или через <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">сайт</a>. Нажмите «Главная», затем нажмите «Подключить устройство».</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/happ/01-connect-device.webp" alt="Кнопка «Подключить устройство» в личном кабинете Slon Privacy" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Установите INCY</h2>
        <p>Выберите устройство <strong>iOS</strong> и приложение <strong>INCY</strong>.</p>
        <p>Нажмите <strong>«App Store»</strong> и установите приложение.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/incy/02-select-IOS-INCY.webp" alt="Выбор iOS и INCY на странице установки Slon Privacy" loading="lazy">
        <p>Если приложение в App Store недоступно, смените регион аккаунта Apple или используйте другое приложение.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Импортируйте подписку</h2>
        <p>Вернитесь на страницу установки Slon Privacy и нажмите <strong>«Добавить подписку»</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/incy/03-import-subscription-IOS-INCY.webp" alt="Кнопка «Добавить подписку» на странице установки Slon Privacy" loading="lazy">
        <p>После нажатия кнопки автоматически откроется INCY, а подписка <strong>SLON Privacy</strong> будет импортирована в приложение.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Подключитесь</h2>
        <p>После импорта подписки список серверов появится автоматически. Выберите сервер и нажмите большую кнопку подключения.</p>
        <ul class="guide-simple-list">
          <li>При первом подключении разрешите добавление VPN-конфигурации.</li>
          <li>Подтвердите действие с помощью Face ID, Touch ID или кода-пароля устройства.</li>
          <li>Дождитесь изменения статуса подключения.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/incy/04-connect-IOS-INCY.webp" alt="Главный экран INCY с кнопкой подключения и списком серверов Slon Privacy на iOS" loading="lazy">
        <div class="guide-warning"><strong>Системный запрос iOS — стандартная часть работы INCY.</strong> Без разрешения подключение не запустится.</div>
      </div>
    </section>

    <div class="guide-success">
      <strong>Готово!</strong> После подключения INCY можно свернуть — <strong>Slon Privacy</strong> продолжит работать в фоновом режиме.
    </div>

    <section class="guide-faq" aria-labelledby="incy-faq-title">
      <h2 id="incy-faq-title">Возможные проблемы</h2>

      <details>
        <summary>INCY не открывается после нажатия «Добавить подписку»</summary>
        <p>Убедитесь, что приложение установлено. Закройте браузер и INCY, затем снова откройте страницу установки и повторите добавление подписки.</p>
      </details>

      <details>
        <summary>Подписка добавилась, но серверов нет</summary>
        <p>Нажмите кнопку обновления рядом с названием подписки <strong>SLON Privacy</strong>. Если список серверов не появился, добавьте подписку повторно. При необходимости обратитесь в поддержку через <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">@slon_privacy_bot</a>.</p>
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/ios/incy/05-refresh-subscription-IOS-INCY.webp" alt="Кнопка обновления подписки в INCY на iOS" loading="lazy">
      </details>

      <details>
        <summary>Сервер не подключается</summary>
        <p>Проверьте интернет без VPN, выберите другой сервер и повторите подключение.</p>
        <p>Убедитесь, что INCY разрешено добавлять VPN-конфигурацию. При появлении системного запроса нажмите <strong>«Разрешить»</strong>.</p>
      </details>

      <details>
        <summary>INCY недоступен в App Store</summary>
        <p>Смените регион аккаунта Apple или используйте другое совместимое приложение.</p>
      </details>

      <details>
        <summary>INCY подключается, но сайты не открываются</summary>
        <p>Отключитесь, выберите другой сервер и подключитесь снова. Также временно отключите другие VPN-приложения и программы, которые могут управлять сетевыми подключениями.</p>
      </details>
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
