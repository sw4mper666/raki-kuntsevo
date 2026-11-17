# Раки-Кунцево — сайт для GitHub Pages

Статический магазин (3D, каталог, корзина, Supabase Auth, заказы, новости, панель администратора).

## Публикация
1. Создайте публичный репозиторий `raki-kuntsevo` на GitHub.
2. Загрузите файлы `index.html` и `.nojekyll` в корень репозитория.
3. Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save.
4. Откройте `https://USERNAME.github.io/raki-kuntsevo/` (замените USERNAME).
5. В Supabase → Authentication → URL Configuration добавьте точный https-адрес сайта в Redirect URLs и обновите Site URL, если используете email-подтверждение/восстановление пароля.

Не загружайте в публичный репозиторий секретные ключи Supabase. Publishable key допускается в HTML; доступ к данным должен контролироваться политиками RLS.

Админ: bogdanbudnikov737@gmail.com (роль owner уже назначена в Supabase).
