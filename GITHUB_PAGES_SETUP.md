# Настройка GitHub Pages

## Шаги для включения GitHub Pages:

1. Перейдите на GitHub в ваш репозиторий: https://github.com/bogdanchiikk/landing-pages-portfolio

2. Откройте **Settings** (Настройки) в верхнем меню репозитория

3. В левом меню найдите раздел **Pages** (в секции "Code and automation")

4. В разделе **Source** (Источник) выберите:
   - **Branch**: `main`
   - **Folder**: `/ (root)` или `/docs` (если используете папку docs)

5. Нажмите **Save** (Сохранить)

6. Подождите 1-2 минуты, пока GitHub создаст сайт

7. Ваш сайт будет доступен по адресу:
   ```
   https://bogdanchiikk.github.io/landing-pages-portfolio/
   ```

## Доступ к файлам через Pages:

После настройки все ваши лендинги будут доступны:

- Главная страница: `https://bogdanchiikk.github.io/landing-pages-portfolio/`
- Email шаблон: `https://bogdanchiikk.github.io/landing-pages-portfolio/test_email/spim-email.html`
- Другие лендинги: `https://bogdanchiikk.github.io/landing-pages-portfolio/[название-папки]/index.html`

## Важно:

- Файл `.nojekyll` уже добавлен в репозиторий - это нужно для корректной работы статических файлов
- После каждого `git push` изменения автоматически появятся на Pages через 1-2 минуты
