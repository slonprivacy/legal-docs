---
layout: default
title: Как привязать Telegram и Email к аккаунту Slon Privacy
lang: ru
permalink: /ru/knowledge/subscription/link-telegram/
---

<style>
.slon-account-linking {
  --slon-accent: #55cbb8;
  --slon-accent-dark: #249f90;
  --slon-accent-soft: rgba(85, 203, 184, 0.12);
  --slon-text: #253b52;
  --slon-muted: #66788a;
  --slon-border: rgba(37, 59, 82, 0.11);
  color: var(--slon-text);
}

.slon-account-linking .slon-title {
  margin-bottom: 0.8rem;
}

.slon-account-linking .slon-lead {
  margin: 0.8rem 0 1.8rem;
  font-size: 1.08rem;
  line-height: 1.75;
}

.slon-account-linking .slon-intro-card,
.slon-account-linking .slon-recommendation,
.slon-account-linking .slon-final-card {
  margin: 1.4rem 0;
  padding: 1.25rem 1.35rem;
  border: 1px solid rgba(85, 203, 184, 0.42);
  border-radius: 1rem;
  background: linear-gradient(135deg, rgba(85, 203, 184, 0.14), rgba(85, 203, 184, 0.05));
}

.slon-account-linking .slon-intro-card p:last-child,
.slon-account-linking .slon-recommendation p:last-child,
.slon-account-linking .slon-final-card p:last-child {
  margin-bottom: 0;
}

.slon-account-linking .slon-section-title {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin: 2.8rem 0 1.2rem;
}

.slon-account-linking .slon-section-number {
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

.slon-account-linking .slon-section-title h2 {
  margin: 0;
}

.slon-account-linking .slon-benefits {
  list-style: none;
  padding-left: 0;
  margin: 1rem 0 1.4rem;
}

.slon-account-linking .slon-benefits li {
  position: relative;
  padding-left: 1.45rem;
  margin: 0.62rem 0;
}

.slon-account-linking .slon-benefits li::before {
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

.slon-account-linking .slon-steps {
  counter-reset: slon-step;
  list-style: none;
  padding: 0;
  margin: 1.25rem 0 1.8rem;
}

.slon-account-linking .slon-steps li {
  counter-increment: slon-step;
  position: relative;
  margin: 0 0 0.85rem;
  padding: 1rem 1rem 1rem 3.55rem;
  border: 1px solid var(--slon-border);
  border-radius: 0.85rem;
  background: rgba(255, 255, 255, 0.62);
  line-height: 1.65;
}

.slon-account-linking .slon-steps li::before {
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

.slon-account-linking .slon-video-wrap {
  margin: 1.6rem auto 0.5rem;
  max-width: 480px;
  overflow: hidden;
  border: 1px solid var(--slon-border);
  border-radius: 1rem;
  background: #0f1720;
  box-shadow: 0 12px 30px rgba(37, 59, 82, 0.08);
}

.slon-account-linking .slon-video-wrap video {
  display: block;
  width: 100%;
  height: auto;
  max-height: 78vh;
  background: #0f1720;
}

.slon-account-linking .slon-video-note {
  margin: 0.7rem auto 0;
  max-width: 480px;
  color: var(--slon-muted);
  font-size: 0.92rem;
  line-height: 1.55;
}

.slon-account-linking .slon-recommendation {
  border-left: 4px solid var(--slon-accent);
}

.slon-account-linking .slon-recommendation strong,
.slon-account-linking .slon-final-card strong {
  color: var(--slon-accent-dark);
}

@media (max-width: 640px) {
  .slon-account-linking .slon-lead {
    font-size: 1rem;
  }

  .slon-account-linking .slon-intro-card,
  .slon-account-linking .slon-recommendation,
  .slon-account-linking .slon-final-card {
    padding: 1.1rem;
    border-radius: 0.85rem;
  }

  .slon-account-linking .slon-section-title {
    align-items: flex-start;
    gap: 0.8rem;
    margin-top: 2.2rem;
  }

  .slon-account-linking .slon-section-number {
    flex-basis: 2.55rem;
    width: 2.55rem;
    height: 2.55rem;
    font-size: 0.95rem;
  }

  .slon-account-linking .slon-steps li {
    padding: 0.9rem 0.9rem 0.9rem 3.25rem;
  }

  .slon-account-linking .slon-steps li::before {
    left: 0.85rem;
    top: 0.9rem;
  }

  .slon-account-linking .slon-video-wrap {
    border-radius: 0.8rem;
  }
}
</style>

<div class="slon-account-linking">

<h1 class="slon-title">Как привязать Telegram и Email к аккаунту Slon Privacy</h1>

<p class="slon-lead">
  Добавьте резервный способ входа, чтобы сохранить доступ к личному кабинету Slon Privacy, даже если Telegram или электронная почта временно недоступны.
</p>

<div class="slon-intro-card">
  <strong>Зачем это нужно?</strong>
  <p>
    Привязка Telegram и Email повышает безопасность аккаунта и дает дополнительный способ авторизации. Если один из способов входа окажется заблокирован или временно недоступен, вы сможете воспользоваться вторым.
  </p>
</div>

<div class="slon-section-title">
  <span class="slon-section-number">1</span>
  <h2>Зачем привязывать Telegram и Email</h2>
</div>

<p>
  Иногда доступ к <strong>Telegram</strong> может быть временно ограничен или недоступен. Аналогично могут возникнуть проблемы с доступом к <strong>электронной почте</strong>.
</p>

<p>
  Чтобы вы всегда могли войти в аккаунт Slon Privacy и управлять подпиской, рекомендуем заранее привязать <strong>оба способа авторизации</strong> — Telegram и Email.
</p>

<p>Это позволит:</p>

<ul class="slon-benefits">
  <li>сохранить доступ к аккаунту при недоступности одного из способов входа;</li>
  <li>быстрее восстановить доступ при возникновении проблем;</li>
  <li>безопасно управлять подпиской с любого устройства.</li>
</ul>

<div class="slon-recommendation">
  <strong>Рекомендуем</strong>
  <p>
    Если вы зарегистрировались через <strong>Telegram</strong>, обязательно привяжите <strong>Email</strong>. Если вы зарегистрировались через <strong>Email</strong>, обязательно привяжите <strong>Telegram</strong>.
  </p>
</div>

<div class="slon-section-title">
  <span class="slon-section-number">2</span>
  <h2>Как привязать второй способ входа</h2>
</div>

<p>Следуйте видеоинструкции или выполните несколько простых шагов:</p>

<ol class="slon-steps">
  <li>Перейдите в <strong>Профиль</strong> → <strong>Привязанные аккаунты</strong>.</li>
  <li>Выберите дополнительный способ авторизации — <strong>Telegram</strong> или <strong>Email</strong>.</li>
  <li>Подтвердите вход через выбранный способ авторизации.</li>
  <li>Выберите основной аккаунт и нажмите <strong>«Объединить аккаунты»</strong>.</li>
</ol>

<div class="slon-video-wrap">
  <video controls playsinline preload="metadata">
    <source src="{{ '/assets/video/knowledge-base/subscription/link-telegram-email.mp4' | relative_url }}" type="video/mp4">
    Ваш браузер не поддерживает воспроизведение видео.
  </video>
</div>

<p class="slon-video-note">
  Видео загружается непосредственно с сайта Slon Privacy.
</p>

<div class="slon-section-title">
  <span class="slon-section-number">3</span>
  <h2>После привязки</h2>
</div>

<p>
  После успешной привязки вы сможете входить в личный кабинет <strong>как через Telegram, так и через Email</strong>.
</p>

<p>
  Если один из способов входа окажется временно недоступен, вы сможете воспользоваться вторым без потери доступа к подписке, настройкам и управлению аккаунтом.
</p>

<div class="slon-final-card">
  <strong>Совет</strong>
  <p>
    Привяжите оба способа авторизации сразу после регистрации. Это займет всего несколько минут и поможет избежать проблем с доступом к аккаунту в будущем.
  </p>
</div>

</div>
