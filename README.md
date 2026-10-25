# Кофейная Мануфактура

Статический сайт небольшой обжарочной с автоматическим развёртыванием через GitHub Actions.

![Deploy static site](https://github.com/08fatkar007-blip/4_laba_inf/actions/workflows/deploy.yml/badge.svg)

**Сайт:** https://08fatkar007-blip.github.io/4_laba_inf/

## Как работает автодеплой

При каждом push в ветку `main` запускается workflow `.github/workflows/deploy.yml`:

1. **lint** — проверка HTML-разметки (htmlhint).
2. **deploy** — публикация сайта на GitHub Pages (только если проверка пройдена).
