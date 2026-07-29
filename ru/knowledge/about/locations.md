---
layout: default
title: Список локаций Slon Privacy
lang: ru
permalink: /ru/knowledge/about/locations/
---
{% include knowledge-styles.html %}

<style>
  .slon-locations {
    --slon-accent: #55cbb8;
    --slon-accent-dark: #249f90;
    --slon-accent-soft: rgba(85, 203, 184, 0.12);
  }

  .slon-locations .slon-section-title {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin: 2.8rem 0 1.2rem;
    scroll-margin-top: 6rem;
  }

  .slon-locations .slon-section-number {
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

  .slon-locations .slon-section-title-text {
    display: block;
    min-width: 0;
  }

  .slon-locations .slon-intro {
    margin: 1.5rem 0 2.5rem;
    padding: 1.5rem 1.6rem;
    border: 1px solid rgba(85, 203, 184, 0.32);
    border-radius: 1.25rem;
    background: linear-gradient(
      135deg,
      rgba(85, 203, 184, 0.12),
      rgba(85, 203, 184, 0.04)
    );
  }

  .slon-locations .slon-intro-title {
    margin: 0 0 0.75rem;
    color: var(--slon-accent-dark);
    font-size: 1.15rem;
    font-weight: 700;
  }

  .slon-locations .slon-intro p:last-child {
    margin-bottom: 0;
  }

  .slon-locations ul {
    list-style: none;
    padding-left: 0;
    margin: 1rem 0 1.4rem;
  }

  .slon-locations ul li {
    position: relative;
    padding-left: 1.45rem;
    margin: 0.55rem 0;
  }

  .slon-locations ul li::before {
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

  @media (max-width: 640px) {
    .slon-locations .slon-section-title {
      align-items: flex-start;
      gap: 0.8rem;
      margin-top: 2.2rem;
    }

    .slon-locations .slon-section-number {
      flex-basis: 2.55rem;
      width: 2.55rem;
      height: 2.55rem;
      font-size: 0.95rem;
    }

    .slon-locations .slon-section-title-text {
      padding-top: 0.2rem;
    }

    .slon-locations .slon-intro {
      padding: 1.25rem;
      border-radius: 1rem;
    }
  }
</style>

<div class="slon-locations" markdown="1">

# Одна подписка — все локации

<div class="slon-intro">
  
  <p>Где бы ни находился нужный вам сервис, <strong>Slon Privacy</strong> поможет получить к нему стабильный доступ. Все доступные локации уже включены в подписку — никаких дополнительных тарифов и скрытых ограничений.</p>
</div>

</div>
