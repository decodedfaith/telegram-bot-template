<h1 align="center"><em>Telegram bot template</em></h1>

<h3 align="center">
  Best way to create a scalable telegram bot with analytics
</h3>

<p

## ✨ Features

-   [x] Admin Panel based on [`Flask-Admin-Dashboard`](https://github.com/jonalxh/Flask-Admin-Dashboard/) ([`Flask-Admin`](https://flask-admin.readthedocs.io/) + [`AdminLTE`](https://adminlte.io/) = ❤️ )
-   [x] Product Analytics System: using [`Amplitude`](https://amplitude.com/) or [`Posthog`](https://posthog.com/) or [`Google Analytics`](https://analytics.google.com)
-   [x] Performance Monitoring System: using [`Prometheus`](https://prometheus.io/) and [`Grafana`](https://grafana.com/)
-   [x] Tracking System: using [`Sentry`](https://sentry.io/)
-   [x] Seamless use of `Docker` and `Docker Compose`
-   [x] Export all users in `.csv` (or `.xlsx`, `.json`, `yaml` from admin panel)
-   [x] Configured CI pipeline from git hooks to github actions
-   [x] [`SQLAlchemy V2`](https://pypi.org/project/SQLAlchemy/) is used to communicate with the database
-   [x] Database Migrations with [`Alembic`](https://pypi.org/project/alembic/)
-   [x] Ability to cache using decorator
-   [x] Convenient validation using [`Pydantic V2`](https://pypi.org/project/pydantic/)
-   [x] Internationalization (i18n) using GNU gettex and [`Babel`](https://pypi.org/project/Babel/)

## 🚀 How to Use

### 🐳 Running in Docker _(recommended method)_

-   configure environment variables in `.env` file

-   start services

    ```bash
    docker compose up -d --build
    ```

-   make migrations

    ```bash
    docker compose exec bot alembic upgrade head
    ```

