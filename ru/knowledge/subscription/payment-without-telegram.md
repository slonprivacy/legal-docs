---
layout: default
title: "Telegram недоступен? Как войти в личный кабинет и оплатить подписку"
description: "Что делать, если Telegram временно недоступен: вход через электронную почту, подключение прокси и восстановление доступа к Slon Privacy."
permalink: /ru/knowledge/subscription/telegram-unavailable/
---

<style>
  .slon-telegram-help {
    --slon-accent: #18b8aa;
    --slon-accent-dark: #10998f;
    --slon-soft: rgba(24, 184, 170, 0.09);
    --slon-border: rgba(24, 184, 170, 0.25);
    --slon-text-muted: #667085;
    max-width: 860px;
    margin: 0 auto;
  }

  .slon-telegram-help * {
    box-sizing: border-box;
  }

  .slon-telegram-help .article-lead {
    margin: 0 0 2rem;
    font-size: 1.08rem;
    line-height: 1.75;
  }

  .slon-telegram-help .step-heading {
    display: flex;
    align-items: center;
    gap: 0.85rem;
    margin: 2.5rem 0 1rem;
  }

  .slon-telegram-help .step-number {
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
    line-height: 1;
  }

  .slon-telegram-help .step-heading h2 {
    margin: 0;
    font-size: 1.35rem;
    line-height: 1.35;
  }

  .slon-telegram-help .action-button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-height: 48px;
    margin: 0.65rem 0;
    padding: 0.8rem 1.15rem;
    border-radius: 12px;
    background: var(--slon-accent);
    color: #fff !important;
    text-decoration: none !important;
    font-weight: 750;
    text-align: center;
    transition: transform 0.15s ease, background 0.15s ease;
  }

  .slon-telegram-help .action-button:hover {
    background: var(--slon-accent-dark);
    transform: translateY(-1px);
  }

  .slon-telegram-help .action-button.secondary {
    background: transparent;
    color: var(--slon-accent-dark) !important;
    border: 1px solid var(--slon-border);
  }

  .slon-telegram-help .proxy-card {
    margin: 1.25rem 0;
    padding: 1.25rem;
    border: 1px solid var(--slon-border);
    border-radius: 16px;
    background: var(--slon-soft);
  }

  .slon-telegram-help .proxy-card h3 {
    margin-top: 0;
  }

  .slon-telegram-help .proxy-url {
    display: block;
    overflow-wrap: anywhere;
    margin: 0.75rem 0 1.25rem;
    padding: 0.9rem 1rem;
    border: 1px solid var(--slon-border);
    border-radius: 10px;
    background: rgba(255, 255, 255, 0.7);
    font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
    font-size: 0.88rem;
    line-height: 1.55;
  }

  .slon-telegram-help .qr-wrap {
    margin-top: 1.25rem;
    text-align: center;
  }

  .slon-telegram-help .qr-wrap img {
    display: block;
    width: min(100%, 320px);
    height: auto;
    margin: 0.75rem auto 0;
    padding: 10px;
    border-radius: 16px;
    background: #fff;
  }

  .slon-telegram-help .info-note {
    margin: 2.5rem 0 0;
    padding: 1.15rem 1.25rem;
    border-left: 4px solid var(--slon-accent);
    border-radius: 12px;
    background: var(--slon-soft);
  }

  .slon-telegram-help .info-note strong {
    display: block;
    margin-bottom: 0.35rem;
  }

  .slon-telegram-help ol {
    padding-left: 1.35rem;
  }

  .slon-telegram-help li {
    margin: 0.55rem 0;
  }

  .slon-telegram-help .muted {
    color: var(--slon-text-muted);
  }

  @media (max-width: 640px) {
    .slon-telegram-help .step-heading {
      align-items: flex-start;
    }

    .slon-telegram-help .step-heading h2 {
      font-size: 1.2rem;
    }

    .slon-telegram-help .action-button {
      display: flex;
      width: 100%;
    }

    .slon-telegram-help .proxy-card {
      padding: 1rem;
    }
  }
</style>

<div class="slon-telegram-help">

# Telegram недоступен? Как войти в личный кабинет и оплатить подписку

<p class="article-lead">
Если доступ к Telegram и личному кабинету через Telegram временно недоступен, воспользуйтесь одним из способов ниже.
</p>

<div class="step-heading">
  <span class="step-number">1</span>
  <h2>Войдите через электронную почту</h2>
</div>

Если вы заранее привязали электронную почту к профилю Slon Privacy, авторизуйтесь на сайте без Telegram.

<a class="action-button" href="https://my.slonprivacy.app/login">Войти в личный кабинет</a>

Инструкция: [Как привязать Telegram и электронную почту](/ru/knowledge/subscription/link-telegram/).

<div class="step-heading">
  <span class="step-number">2</span>
  <h2>Подключите прокси для доступа к Telegram</h2>
</div>

Если электронная почта ещё не привязана, подключите наш MTProto-прокси и попробуйте открыть Telegram.

<div class="proxy-card">

<h3>Подключение прокси</h3>

<a class="action-button" href="tg://proxy?server=130.49.185.95&port=33443&secret=2d52f5754605c47237b483cd092be6b3">Подключить прокси в Telegram</a>

<p class="muted">Если кнопка не сработала, откройте ссылку вручную:</p>

<a class="proxy-url" href="tg://proxy?server=130.49.185.95&port=33443&secret=2d52f5754605c47237b483cd092be6b3">tg://proxy?server=130.49.185.95&amp;port=33443&amp;secret=2d52f5754605c47237b483cd092be6b3</a>

<div class="qr-wrap">
  <strong>Или отсканируйте QR-код</strong>
  <img src="/assets/img/knowledge-base/subscription/telegram-unavailable/proxy-qr.webp" alt="QR-код для подключения MTProto-прокси Slon Privacy">
</div>

</div>

<div class="step-heading">
  <span class="step-number">3</span>
  <h2>Если прокси недоступен</h2>
</div>

Если подключиться к Telegram через прокси не удалось:

1. Авторизуйтесь в личном кабинете через электронную почту.
2. Активируйте бесплатную пробную подписку на **3 дня**.
3. Используйте Slon Privacy для восстановления доступа к Telegram.
4. После входа объедините аккаунты.

Инструкция: [Как привязать Telegram и электронную почту](/ru/knowledge/subscription/link-telegram/).

<div class="info-note">
  <strong>Рекомендуем заранее привязать электронную почту</strong>
  Это позволит войти в личный кабинет и оплатить подписку даже при временной недоступности Telegram.
</div>

</div>
