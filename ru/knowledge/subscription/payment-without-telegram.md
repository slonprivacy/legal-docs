---
title: "Telegram недоступен? Как войти в личный кабинет и оплатить подписку"
description: "Что делать, если Telegram временно недоступен: вход через электронную почту, подключение прокси и восстановление доступа к Slon Privacy."
permalink: /ru/knowledge/subscription/payment-without-telegram/
---

<style>
.slon-telegram-unavailable {
  --slon-accent: #19b9aa;
  --slon-accent-hover: #139c90;
  --slon-soft: rgba(25, 185, 170, 0.09);
  --slon-border: rgba(25, 185, 170, 0.28);
  max-width: 860px;
  margin: 0 auto;
}

.slon-telegram-unavailable * {
  box-sizing: border-box;
}

.slon-telegram-unavailable .lead {
  margin-bottom: 2rem;
  font-size: 1.08rem;
  line-height: 1.75;
}

.slon-telegram-unavailable .step-title {
  display: flex;
  align-items: center;
  gap: 0.85rem;
  margin: 2.5rem 0 1rem;
}

.slon-telegram-unavailable .step-number {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 38px;
  height: 38px;
  flex: 0 0 38px;
  border-radius: 50%;
  background: var(--slon-accent);
  color: #fff;
  font-weight: 800;
}

.slon-telegram-unavailable .step-title h2 {
  margin: 0;
  font-size: 1.35rem;
  line-height: 1.35;
}

.slon-telegram-unavailable .slon-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 48px;
  margin: 0.7rem 0;
  padding: 0.8rem 1.15rem;
  border-radius: 12px;
  background: var(--slon-accent);
  color: #fff !important;
  text-decoration: none !important;
  font-weight: 700;
  text-align: center;
}

.slon-telegram-unavailable .slon-button:hover {
  background: var(--slon-accent-hover);
}

.slon-telegram-unavailable .proxy-card {
  margin: 1.25rem 0;
  padding: 1.25rem;
  border: 1px solid var(--slon-border);
  border-radius: 16px;
  background: var(--slon-soft);
}

.slon-telegram-unavailable .proxy-card h3 {
  margin-top: 0;
}

.slon-telegram-unavailable .proxy-link {
  display: block;
  overflow-wrap: anywhere;
  margin: 0.75rem 0 1.25rem;
  padding: 0.9rem 1rem;
  border: 1px solid var(--slon-border);
  border-radius: 10px;
  background: rgba(255,255,255,.72);
  color: inherit;
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  font-size: 0.86rem;
  line-height: 1.55;
  text-decoration: none;
}

.slon-telegram-unavailable .qr {
  display: block;
  width: min(100%, 320px);
  height: auto;
  margin: 0.8rem auto 0;
  padding: 10px;
  border-radius: 16px;
  background: #fff;
}

.slon-telegram-unavailable .qr-caption {
  margin-top: 1.25rem;
  text-align: center;
}

.slon-telegram-unavailable .note {
  margin-top: 2.5rem;
  padding: 1.15rem 1.25rem;
  border-left: 4px solid var(--slon-accent);
  border-radius: 12px;
  background: var(--slon-soft);
}

.slon-telegram-unavailable .note strong {
  display: block;
  margin-bottom: 0.35rem;
}

.slon-telegram-unavailable li {
  margin: 0.55rem 0;
}

@media (max-width: 640px) {
  .slon-telegram-unavailable .step-title {
    align-items: flex-start;
  }

  .slon-telegram-unavailable .step-title h2 {
    font-size: 1.2rem;
  }

  .slon-telegram-unavailable .slon-button {
    display: flex;
    width: 100%;
  }

  .slon-telegram-unavailable .proxy-card {
    padding: 1rem;
  }
}
</style>

<div class="slon-telegram-unavailable">

# Telegram недоступен? Как войти в личный кабинет и оплатить подписку

<p class="lead">
Если доступ к Telegram и личному кабинету через Telegram временно недоступен, воспользуйтесь одним из способов ниже.
</p>

<div class="step-title">
  <span class="step-number">1</span>
  <h2>Войдите через электронную почту</h2>
</div>

Если вы заранее привязали электронную почту к профилю Slon Privacy, авторизуйтесь на сайте без Telegram.

<a class="slon-button" href="https://my.slonprivacy.app/login">Открыть личный кабинет</a>

Подробнее: [Как привязать Telegram и электронную почту](/ru/knowledge/subscription/link-telegram/).

<div class="step-title">
  <span class="step-number">2</span>
  <h2>Подключите прокси для доступа к Telegram</h2>
</div>

Если электронная почта ещё не привязана, подключите наш MTProto-прокси и попробуйте открыть Telegram.

<div class="proxy-card">

<h3>Подключение прокси</h3>

<a class="slon-button" href="tg://proxy?server=130.49.185.95&amp;port=33443&amp;secret=2d52f5754605c47237b483cd092be6b3">Подключить прокси в Telegram</a>

Если Telegram не реагирует на кнопку, откройте ссылку вручную:

<a class="proxy-link" href="tg://proxy?server=130.49.185.95&amp;port=33443&amp;secret=2d52f5754605c47237b483cd092be6b3">tg://proxy?server=130.49.185.95&amp;port=33443&amp;secret=2d52f5754605c47237b483cd092be6b3</a>

<div class="qr-caption">
  <strong>Или отсканируйте QR-код</strong>
  <img
  src="/assets/img/knowledge-base/subscription/telegram-unavailable/proxy-qr.webp"
  alt="QR-код для подключения прокси Slon Privacy" 
>
</div>

</div>

<div class="step-title">
  <span class="step-number">3</span>
  <h2>Если прокси недоступен</h2>
</div>

Если подключиться к Telegram через прокси не удалось:

1. Авторизуйтесь в личном кабинете через электронную почту.
2. Активируйте бесплатную пробную подписку на **3 дня**.
3. Используйте Slon Privacy для восстановления доступа к Telegram.
4. После входа объедините аккаунты.

Подробнее: [Как привязать Telegram и электронную почту](/ru/knowledge/subscription/link-telegram/).

<div class="note">
  <strong>Рекомендуем заранее привязать электронную почту</strong>
  Это позволит войти в личный кабинет и оплатить подписку даже при временной недоступности Telegram.
</div>

</div>
