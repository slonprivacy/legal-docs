---
layout: default
title: Установка Slon Privacy на Windows
lang: ru
permalink: /ru/knowledge/install/windows/
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
      <p>Убедитесь, что подписка Slon Privacy активна, а компьютер подключён к интернету.</p>
      <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Как подписаться →</a>
    </div>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Авторизируйтесь</h2>
        <p>Войдите в личный кабинет через <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram-бота</a> или через <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">сайт</a>. Нажмите «Главная», затем нажмите «Подключить устройство».</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/happ/01-connect-device-W-Happ.webp" alt="Кнопка «Подключить устройство» в личном кабинете Slon Privacy" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Установите Happ</h2>
        <p>Выберите устройство <strong>Windows</strong> и приложение <strong>Happ</strong>.</p>
        <p>Нажмите кнопку <strong>Windows</strong>. Загрузка установщика начнётся автоматически.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/happ/02-select-W-happ.webp" alt="Выбор Windows и Happ на странице установки Slon Privacy" loading="lazy">
        <p>После завершения загрузки откройте скачанный файл и установите приложение.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Добавьте подписку</h2>
        <p>После установки вернитесь на страницу установки Slon Privacy и нажмите <strong>«Добавить подписку»</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/happ/03-install-W-happ.webp" alt="Кнопка «Добавить подписку» на странице установки Slon Privacy" loading="lazy">
        <p>После нажатия Happ откроется автоматически, а подписка <strong>SLON Privacy</strong> добавится в приложение.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Подключитесь</h2>
        <ul class="guide-simple-list">
          <li>Выберите любой сервер в списке Happ.</li>
          <li>Нажмите большую кнопку подключения.</li>
          <li>Предоставьте приложению все разрешения, которые запросит Windows.</li>
          <li>Дождитесь изменения статуса подключения.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/happ/04-add-subscription-W-Happ.webp" alt="Список серверов и кнопка подключения в приложении Happ на Windows" loading="lazy">
        <div class="guide-warning"><strong>Важно:</strong> предоставьте Happ все запрашиваемые разрешения. Без них подключение может не запуститься.</div>
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
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/happ/05-refresh-servers-W-Happ.webp" alt="Кнопка обновления серверов в Happ на Windows" loading="lazy">
      </details>

      <details>
        <summary>Сервер не подключается</summary>
        <p>Проверьте интернет без VPN, выберите другой сервер и повторите подключение. Убедитесь, что приложению предоставлены все запрашиваемые разрешения.</p>
      </details>

      <details>
        <summary>Ошибка «Failed to start xray: app/proxyman/inbound: failed to start proxy &gt; A required privilege is not held by the client»</summary>
        <p>Предоставьте Happ все запрашиваемые разрешения и полностью перезапустите приложение.</p>
        <p>Проверьте, не запущены ли другие VPN-приложения, прокси-программы или сетевые сервисы. Закройте их и повторите подключение.</p>
      </details>

      <details>
        <summary>Не получается использовать Happ?</summary>
        <p>Попробуйте установить <button type="button" class="guide-inline-tab-link" data-open-app-tab="incy-panel"><strong>INCY</strong></button> — он совместим со Slon Privacy и может работать стабильнее на некоторых компьютерах.</p>
      </details>
    </section>
  </section>

  <section id="incy-panel" class="app-tab-panel" role="tabpanel">
    <h2>INCY</h2>
    <p><strong>Установите INCY, добавьте подписку Slon Privacy и подключитесь к серверу. Обычно настройка занимает не более 2–3 минут.</strong></p>

    <div class="guide-note">
      <strong>Перед началом</strong>
      <p>Убедитесь, что подписка Slon Privacy активна, а компьютер подключён к интернету.</p>
      <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Как подписаться →</a>
    </div>

    <section class="guide-step">
      <div class="guide-step-number">1</div>
      <div class="guide-step-content">
        <h2>Авторизируйтесь</h2>
       <p>Войдите в личный кабинет через <a href="https://t.me/slon_privacy_bot" target="_blank" rel="noopener noreferrer">Telegram-бота</a> или через <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">сайт</a>. Нажмите «Главная», затем нажмите «Подключить устройство».</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/incy/01-connect-device-W-INCY.webp" alt="Кнопка «Подключить устройство» в личном кабинете Slon Privacy" loading="lazy">
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">2</div>
      <div class="guide-step-content">
        <h2>Установите INCY</h2>
        <p>Выберите устройство <strong>Windows</strong> и приложение <strong>INCY</strong>.</p>
        <p>Нажмите кнопку <strong>Windows</strong>. Загрузка установщика начнётся автоматически.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/incy/02-select-W-incy.webp" alt="Выбор Windows и INCY на странице установки Slon Privacy" loading="lazy">
        <p>После завершения загрузки откройте скачанный файл и установите приложение.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">3</div>
      <div class="guide-step-content">
        <h2>Импортируйте подписку</h2>
        <p>После установки вернитесь на страницу установки Slon Privacy и нажмите <strong>«Добавить подписку»</strong>.</p>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/incy/03-install-W-incy.webp" alt="Кнопка «Добавить подписку» на странице установки Slon Privacy" loading="lazy">
        <p>После нажатия INCY откроется автоматически, а подписка <strong>SLON Privacy</strong> будет импортирована в приложение.</p>
      </div>
    </section>

    <section class="guide-step">
      <div class="guide-step-number">4</div>
      <div class="guide-step-content">
        <h2>Подключитесь</h2>
        <ul class="guide-simple-list">
          <li>Выберите любой сервер в списке INCY.</li>
          <li>Нажмите большую кнопку подключения.</li>
          <li>Предоставьте приложению все разрешения, которые запросит Windows.</li>
          <li>Дождитесь изменения статуса подключения.</li>
        </ul>
        <img class="guide-image" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/incy/04-add-subscription-W-incy.webp" alt="Список серверов и кнопка подключения в приложении INCY на Windows" loading="lazy">
        <div class="guide-warning"><strong>Важно:</strong> предоставьте INCY все запрашиваемые разрешения. Без них подключение может не запуститься.</div>
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
        <img class="guide-image guide-image-small" src="{{ site.baseurl }}/assets/img/knowledge-base/windows/incy/05-refresh-servers-W-incy.webp" alt="Кнопка обновления подписки в INCY на Windows" loading="lazy">
      </details>

      <details>
        <summary>Сервер не подключается</summary>
        <p>Проверьте интернет без VPN, выберите другой сервер и повторите подключение. Убедитесь, что приложению предоставлены все запрашиваемые разрешения.</p>
      </details>

      <details>
        <summary>Ошибка «Failed to start xray: app/proxyman/inbound: failed to start proxy &gt; A required privilege is not held by the client»</summary>
        <p>Предоставьте INCY все запрашиваемые разрешения и полностью перезапустите приложение.</p>
        <p>Проверьте, не запущены ли другие VPN-приложения, прокси-программы или сетевые сервисы. Закройте их и повторите подключение.</p>
      </details>

      <details>
        <summary>Не получается использовать INCY?</summary>
        <p>Попробуйте установить <button type="button" class="guide-inline-tab-link" data-open-app-tab="happ-panel"><strong>Happ</strong></button> — он совместим со Slon Privacy и может работать стабильнее на некоторых компьютерах.</p>
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
