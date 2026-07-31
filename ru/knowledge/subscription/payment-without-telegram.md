---
layout: default
title: Telegram недоступен? Как войти в личный кабинет и оплатить подписку
lang: ru
permalink: /ru/knowledge/subscription/payment-without-telegram/
---

<style>
.slon-telegram-unavailable {
  --slon-accent: #55cbb8;
  --slon-accent-dark: #249f90;
  --slon-accent-soft: rgba(85, 203, 184, 0.12);
  --slon-text: #253b52;
  --slon-muted: #66788a;
  --slon-border: rgba(37, 59, 82, 0.11);
  color: var(--slon-text);
}

.slon-telegram-unavailable .slon-lead {
  margin: 0.8rem 0 1.8rem;
  font-size: 1.08rem;
  line-height: 1.75;
}

.slon-telegram-unavailable .slon-intro-card,
.slon-telegram-unavailable .slon-proxy-card,
.slon-telegram-unavailable .slon-recommendation,
.slon-telegram-unavailable .slon-final-card {
  margin: 1.4rem 0;
  padding: 1.25rem 1.35rem;
  border: 1px solid rgba(85, 203, 184, 0.42);
  border-radius: 1rem;
  background: linear-gradient(
    135deg,
    rgba(85, 203, 184, 0.14),
    rgba(85, 203, 184, 0.05)
  );
}

.slon-telegram-unavailable .slon-intro-card p:last-child,
.slon-telegram-unavailable .slon-proxy-card p:last-child,
.slon-telegram-unavailable .slon-recommendation p:last-child,
.slon-telegram-unavailable .slon-final-card p:last-child {
  margin-bottom: 0;
}

.slon-telegram-unavailable .slon-section-title {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin: 2.8rem 0 1.2rem;
}

.slon-telegram-unavailable .slon-section-number {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  flex: 0 0 3rem;
  width: 3rem;
  height: 3rem;
  border: 1.5px solid var(--slon-accent);
  border-radius: 50%;
  color: var(--slon-accent-dark);
  background: #fff;
  font-size: 1.05rem;
  font-weight: 700;
  line-height: 1;
}

.slon-telegram-unavailable .slon-section-title h2 {
  margin: 0;
}

.slon-telegram-unavailable .slon-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 46px;
  margin: 0.7rem 0;
  padding: 0.78rem 1.15rem;
  border: 1px solid var(--slon-accent);
  border-radius: 0.8rem;
  background: var(--slon-accent);
  color: #fff !important;
  text-align: center;
  text-decoration: none !important;
  font-weight: 700;
  transition:
    background 0.2s ease,
    border-color 0.2s ease,
    transform 0.2s ease;
}

.slon-telegram-unavailable .slon-button:hover {
  border-color: var(--slon-accent-dark);
  background: var(--slon-accent-dark);
  transform: translateY(-1px);
}

.slon-telegram-unavailable .slon-benefits {
  list-style: none;
  padding-left: 0;
  margin: 1rem 0 1.4rem;
}

.slon-telegram-unavailable .slon-benefits li {
  position: relative;
  padding-left: 1.45rem;
  margin: 0.62rem 0;
}

.slon-telegram-unavailable .slon-benefits li::before {
  content: "";
  position: absolute;
  left: 0.15rem;
  top: 0.72em;
  width: 0.48rem;
  height: 0.48rem;
  border-radius: 50%;
  background: var(--slon-accent);
  transform: translateY(-50%);
  box-shadow: 0 0 0 4px var(--slon-accent-soft);
}

.slon-telegram-unavailable .slon-steps {
  counter-reset: slon-step;
  list-style: none;
  padding: 0;
  margin: 1.25rem 0 1.8rem;
}

.slon-telegram-unavailable .slon-steps li {
  counter-increment: slon-step;
  position: relative;
  margin: 0 0 0.85rem;
  padding: 1rem 1rem 1rem 3.55rem;
  border: 1px solid var(--slon-border);
  border-radius: 0.85rem;
  background: rgba(255, 255, 255, 0.62);
  line-height: 1.65;
}

.slon-telegram-unavailable .slon-steps li::before {
  content: counter(slon-step);
  position: absolute;
  left: 1rem;
  top: 1rem;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 1.75rem;
  height: 1.75rem;
  border-radius: 50%;
  background: var(--slon-accent);
  color: #fff;
  font-size: 0.86rem;
  font-weight: 700;
}

.slon-telegram-unavailable .slon-proxy-card h3 {
  margin-top: 0;
}

.slon-telegram-unavailable .slon-proxy-link {
  display: block;
  overflow-wrap: anywhere;
  margin: 0.75rem 0 0;
  padding: 0.9rem 1rem;
  border: 1px solid var(--slon-border);
  border-radius: 0.75rem;
  background: rgba(255, 255, 255, 0.68);
  color: inherit;
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  font-size: 0.86rem;
  line-height: 1.55;
  text-decoration: none;
}

.slon-telegram-unavailable .slon-recommendation {
  border-left: 4px solid var(--slon-accent);
}

.slon-telegram-unavailable .slon-recommendation strong,
.slon-telegram-unavailable .slon-final-card strong,
.slon-telegram-unavailable .slon-intro-card strong {
  color: var(--slon-accent-dark);
}

.slon-telegram-unavailable .slon-muted {
  color: var(--slon-muted);
  font-size: 0.94rem;
  line-height: 1.6;
}

@media (max-width: 640px) {
  .slon-telegram-unavailable .slon-lead {
    font-size: 1rem;
  }

  .slon-telegram-unavailable .slon-intro-card,
  .slon-telegram-unavailable .slon-proxy-card,
  .slon-telegram-unavailable .slon-recommendation,
  .slon-telegram-unavailable .slon-final-card {
    padding: 1.1rem;
    border-radius: 0.85rem;
  }

  .slon-telegram-unavailable .slon-section-title {
    align-items: flex-start;
    gap: 0.8rem;
    margin-top: 2.2rem;
  }

  .slon-telegram-unavailable .slon-section-number {
    flex-basis: 2.55rem;
    width: 2.55rem;
    height: 2.55rem;
    font-size: 0.95rem;
  }

  .slon-telegram-unavailable .slon-button {
    display: flex;
    width: 100%;
  }

  .slon-telegram-unavailable .slon-steps li {
    padding: 0.9rem 0.9rem 0.9rem 3.25rem;
  }

  .slon-telegram-unavailable .slon-steps li::before {
    left: 0.85rem;
    top: 0.9rem;
  }
  .slon-telegram-unavailable .slon-qr-image {
  display: block;
  width: 220px;
  max-width: 100%;
  margin: 1.2rem auto 0;
  border-radius: 12px;
  border: 1px solid var(--slon-border);
  background: #fff;
  padding: 10px;
}
  .slon-telegram-unavailable .slon-qr-details {
  margin: 1rem 0;
  border: 1px solid rgba(85, 203, 184, 0.42);
  border-radius: 0.85rem;
  background: rgba(85, 203, 184, 0.06);
  overflow: hidden;
}

.slon-telegram-unavailable .slon-qr-details summary {
  padding: 1rem 1.15rem;
  cursor: pointer;
  color: var(--slon-accent-dark);
  font-weight: 700;
  user-select: none;
}

.slon-telegram-unavailable .slon-qr-details summary:hover {
  background: rgba(85, 203, 184, 0.1);
}

.slon-telegram-unavailable .slon-qr-content {
  padding: 0 1.15rem 1.15rem;
}

.slon-telegram-unavailable .slon-qr-content p {
  margin-top: 0;
}

.slon-telegram-unavailable .slon-qr-image {
  display: block;
  width: 200px;
  max-width: 100%;
  height: auto;
  margin: 1rem auto 0;
  padding: 8px;
  border: 1px solid var(--slon-border);
  border-radius: 0.75rem;
  background: #fff;
}
}
</style>

<div class="slon-telegram-unavailable">

<p class="slon-lead">
  Если Telegram временно недоступен, вы всё равно можете войти в личный кабинет Slon Privacy, управлять подпиской и восстановить доступ одним из способов ниже.
</p>

<div class="slon-intro-card">
  <strong>Главное</strong>
  <p>
    Самый надёжный вариант - заранее привязать к аккаунту электронную почту. Тогда вход в личный кабинет и оплата подписки останутся доступны даже при проблемах с Telegram.
  </p>
</div>

<div class="slon-section-title">
  <span class="slon-section-number">1</span>
  <h2>Войдите через электронную почту</h2>
</div>

<p>
  Если вы заранее привязали <strong>Email</strong> к профилю Slon Privacy, авторизуйтесь на  <a href="https://my.slonprivacy.app/login" target="_blank" rel="noopener noreferrer">сайте</a> без использования Telegram.
</p>

<p>
  После входа вы сможете проверить подписку, продлить её или подключить новое устройство.
</p>

<p>
  Подробнее: <a href="/ru/knowledge/subscription/link-telegram/">как привязать Telegram и электронную почту</a>.
</p>

<div class="slon-section-title">
  <span class="slon-section-number">2</span>
  <h2>Подключите прокси для Telegram</h2>
</div>

<p>
  Если электронная почта ещё не привязана, попробуйте восстановить доступ к Telegram через MTProto-прокси Slon Privacy.
</p>

<div class="slon-proxy-card">
  <h3>Подключение прокси</h3>

  <p>
    Нажмите кнопку ниже. Если Telegram установлен на устройстве, приложение предложит добавить прокси автоматически.
  </p>

  <a class="slon-button" href="tg://proxy?server=130.49.185.95&amp;port=33443&amp;secret=2d52f5754605c47237b483cd092be6b3">
    Подключить прокси в Telegram
  </a>

  <p class="slon-muted">
    Если кнопка не сработала, скопируйте и откройте ссылку вручную:
  </p>

  <a class="slon-proxy-link" href="tg://proxy?server=130.49.185.95&amp;port=33443&amp;secret=2d52f5754605c47237b483cd092be6b3">
    tg://proxy?server=130.49.185.95&amp;port=33443&amp;secret=2d52f5754605c47237b483cd092be6b3
  </a>
</div>

<details class="slon-qr-details">
  <summary>Показать QR-код</summary>

  <div class="slon-qr-content">
    <p>
      Отсканируйте QR-код камерой телефона, чтобы подключить прокси в Telegram.
    </p>

    <img
      src="{{ site.baseurl }}/assets/img/knowledge-base/subscription/telegram-unavailable/proxy-qr.webp"
      alt="QR-код для подключения прокси Slon Privacy"
      class="slon-qr-image"
      loading="lazy">
  </div>
</details>

<div class="slon-recommendation">
  <strong>Важно</strong>
  <p>
    Прокси помогает открыть Telegram, но не заменяет привязку Email. После восстановления доступа рекомендуем сразу добавить резервный способ входа.
  </p>
</div>

<div class="slon-section-title">
  <span class="slon-section-number">3</span>
  <h2>Если прокси не помог</h2>
</div>

<p>
  Создайте или откройте аккаунт через электронную почту и используйте Slon Privacy для восстановления доступа к Telegram.
</p>

<ol class="slon-steps">
  <li>Откройте личный кабинет и авторизуйтесь через <strong>Email</strong>.</li>
  <li>Активируйте бесплатную пробную подписку на <strong>3 дня</strong>, если она ещё доступна для аккаунта.</li>
  <li>Установите Slon Privacy и подключитесь к серверу.</li>
  <li>Откройте Telegram и восстановите доступ к своему аккаунту.</li>
  <li>После входа привяжите Telegram и Email к одному аккаунту.</li>
</ol>

<p>
  Инструкция: <a href="/ru/knowledge/subscription/link-telegram/">как объединить Telegram и Email</a>.
</p>

<div class="slon-final-card">
  <strong>Совет</strong>
  <p>
    Привяжите Telegram и Email сразу после регистрации. Это поможет сохранить доступ к личному кабинету, подписке и настройкам независимо от временных ограничений одного из способов входа.
  </p>
</div>

</div>
