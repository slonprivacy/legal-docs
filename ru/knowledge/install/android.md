---
layout: default
title: Установка Slon Privacy на Android
lang: ru
permalink: /ru/knowledge/install/android/
---
{% include knowledge-styles.html %}

<div class="app-tabs" data-app-tabs>
  <div class="app-tab-buttons" role="tablist" aria-label="Выбор приложения">
    <button class="app-tab-button" role="tab" aria-selected="true" aria-controls="happ-panel">Happ Plus</button>
    <button class="app-tab-button" role="tab" aria-selected="false" aria-controls="incy-panel">INCY</button>
  </div>

  <section id="happ-panel" class="app-tab-panel is-active" role="tabpanel">
    <h2>Happ Plus</h2>
    <p><strong>Установите Happ, добавьте подписку Slon Privacy и подключитесь к серверу. Обычно настройка занимает не более 2–3 минут.</strong></p>

    <div class="guide-note">
      <strong>Перед началом</strong>
      <p>Убедитесь, что подписка Slon Privacy активна, а телефон подключён к интернету.</p>
      <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Как подписаться →</a>
    </div>

    <section class="guide-video-section" aria-labelledby="happ-video-title">
      <h2 id="happ-video-title">Видеоинструкция</h2>
      <p>Посмотрите весь процесс установки и подключения Happ на Android.</p>
      <video class="guide-video" controls playsinline preload="metadata">
        <source src="{{ site.baseurl }}/assets/video/knowledge-base/android/happ/android-happ-install.mp4" type="video/mp4">
        Ваш браузер не поддерживает воспроизведение видео.
      </video>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Авторизируйтесь</h2>
        <p>Войдите в личный кабинет через <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram-бота</a> или через <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">сайт</a>. Нажмите «Главная», затем нажмите «Подключить устройство».</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/01-connect-device.webp" alt="Кнопка «Подключить устройство» в личном кабинете Slon Privacy" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Установите Happ</h2>
        <p>Выберите устройство <strong>Android</strong> и приложение <strong>Happ Plus</strong>.</p>
        <p>Нажмите <strong>«Открыть в Google Play»</strong>. Если Google Play недоступен, используйте кнопку <strong>«Скачать APK»</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/02-select-android-happ.webp" alt="Выбор Android и Happ на странице установки Slon Privacy" loading="lazy">
        <p>В Google Play установите <strong>«Happ — Proxy Utility»</strong>. Если приложение уже установлено, будет показана кнопка «Открыть».</p>
        <div class="guide-warning"><strong>Важно:</strong> APK следует устанавливать только с проверенных источников. Google Play является приоритетным способом установки.</div>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Добавьте подписку</h2>
        <p>Вернитесь из Google Play в личный кабинет, на страницу установки, и нажмите <strong>«Добавить подписку»</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/03-install-happ.webp" alt="Кнопка «Добавить подписку» на странице установки Slon Privacy" loading="lazy">
        <p>После нажатия «Добавить подписку» приложение Happ откроется автоматически. Дождитесь сообщения «Подписка SLON Privacy успешно обновлена». После этого появится список серверов.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Подключитесь</h2>
        <ul class="guide-simple-list">
          <li>Выберите любой сервер в списке Happ.</li>
          <li>Нажмите большую кнопку питания.</li>
          <li>При первом запуске подтвердите системный запрос Android на создание VPN-подключения.</li>
          <li>Дождитесь изменения статуса подключения.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/04-add-subscription.webp" alt="Список серверов и кнопка подключения в приложении Happ" loading="lazy">
        <div class="guide-warning"><strong>Системный запрос Android — стандартная часть работы Happ.</strong> Без разрешения подключение не запустится.</div>
      </div>
    </section>

    <div class="guide-success">
      <strong>Готово!</strong> После подключения Happ можно свернуть — <strong>Slon Privacy</strong> продолжит работать в фоновом режиме.
    </div>

    <section class="guide-faq" aria-labelledby="happ-faq-title">
      <h2 id="happ-faq-title">Возможные проблемы</h2>

      <details>
        <summary>Happ не открывается после нажатия «Добавить подписку»</summary>
        <p>Убедитесь, что приложение установлено. Закройте браузер и Happ, затем повторите импорт.</p>
      </details>

      <details>
        <summary>Подписка добавилась, но серверов нет</summary>
        <p>Нажмите кнопку обновления рядом с названием подписки. Если это не помогло, добавьте подписку повторно.</p>
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/05-refresh-servers.webp" alt="Кнопка обновления серверов в Happ" loading="lazy">
      </details>

      <details>
        <summary>Сервер не подключается</summary>
        <p>Проверьте интернет без VPN, выберите другой сервер и убедитесь, что разрешение Android на создание VPN-подключения предоставлено.</p>
        <p><strong>Если Android запросит разрешение на создание подключения — обязательно нажмите «Разрешить».</strong> Без этого подключение работать не будет.</p>
      </details>

      <details>
        <summary>Google Play недоступен</summary>
        <p>Используйте кнопку <strong>«Скачать APK»</strong> на официальной странице установки.</p>
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
      <p>Убедитесь, что подписка Slon Privacy активна, а телефон подключён к интернету.</p>
      <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Как подписаться →</a>
    </div>

    <section class="guide-video-section" aria-labelledby="incy-video-title">
      <h2 id="incy-video-title">Видеоинструкция</h2>
      <p>Посмотрите весь процесс установки и подключения INCY на Android.</p>
      <video class="guide-video" controls playsinline preload="metadata">
        <source src="{{ site.baseurl }}/assets/video/knowledge-base/android/incy/android-INCY-install.mp4" type="video/mp4">
        Ваш браузер не поддерживает воспроизведение видео.
      </video>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Авторизируйтесь</h2>
        <p>Войдите в личный кабинет через <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram-бота</a> или на сайте <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">my.slonprivacy.app</a>. Нажмите «Главная», затем нажмите «Подключить устройство».</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/happ/01-connect-device.webp" alt="Кнопка «Подключить устройство» в личном кабинете Slon Privacy" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Установите INCY</h2>
        <p>Выберите устройство <strong>Android</strong> и приложение <strong>INCY</strong>.</p>
        <p>Нажмите <strong>«Открыть в Google Play»</strong>. Если Google Play недоступен, используйте кнопку <strong>«Скачать APK»</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/incy/02-select-android-INCY.webp" alt="Выбор Android и INCY на странице установки Slon Privacy" loading="lazy">
        <p>Установите приложение <strong>INCY</strong>. Если оно уже установлено, будет показана кнопка «Открыть».</p>
        <div class="guide-warning"><strong>Важно:</strong> APK следует устанавливать только с проверенных источников. Google Play является приоритетным способом установки.</div>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Импортируйте подписку</h2>
        <p>Вернитесь на страницу установки Slon Privacy и нажмите <strong>«Добавить подписку»</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/incy/03-import-subscription-INCY.webp" alt="Кнопка «Добавить подписку» на странице установки Slon Privacy" loading="lazy">
        <p>После нажатия кнопки автоматически откроется INCY, а подписка <strong>SLON Privacy</strong> будет импортирована в приложение.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Подключитесь</h2>
        <p>После импорта подписки список серверов появится автоматически. Нажмите большую кнопку питания для подключения.</p>
        <ul class="guide-simple-list">
          <li>При первом запуске подтвердите системный запрос Android на создание VPN-подключения.</li>
          <li>Дождитесь изменения статуса подключения.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/android/incy/04-connect-INCY.webp" alt="Главный экран INCY с кнопкой подключения и списком серверов Slon Privacy" loading="lazy">
        <div class="guide-warning"><strong>Системный запрос Android — стандартная часть работы INCY.</strong> Без разрешения подключение не запустится.</div>
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
        <p>Нажмите кнопку обновления рядом с названием подписки <strong>SLON Privacy</strong>. Если список серверов не появился, добавьте подписку повторно из личного кабинета.</p>
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/android/incy/05-refresh-subscription-INCY.webp" alt="Кнопка обновления подписки в INCY" loading="lazy">
      </details>

      <details>
        <summary>Сервер не подключается</summary>
        <p>Проверьте интернет без VPN, выберите другой сервер и повторите подключение.</p>
        <p>Убедитесь, что INCY получило разрешение Android на создание VPN-подключения. При появлении системного запроса нажмите <strong>«Разрешить»</strong>.</p>
      </details>

      <details>
        <summary>Google Play недоступен</summary>
        <p>Используйте кнопку <strong>«Скачать APK»</strong> на официальной странице установки Slon Privacy.</p>
      </details>

      <details>
        <summary>INCY подключается, но сайты не открываются</summary>
        <p>Отключитесь, выберите другой сервер и подключитесь снова. Также временно отключите другие VPN-приложения, частный DNS и программы, которые могут управлять сетевыми подключениями.</p>
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
