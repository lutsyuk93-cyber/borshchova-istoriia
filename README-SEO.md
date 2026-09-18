# Борщова історія — GitHub Pages

## Що тут є
- статичний HTML/CSS/JS-сайт;
- SEO title/description;
- Recipe structured data на рецептах;
- robots.txt;
- sitemap.xml;
- 404.html;
- місце для Google Analytics 4;
- сторінки рецептів і порад.

## Публікація на GitHub Pages

1. Створи на GitHub public repository, наприклад `borshchova-istoriia`.
2. Завантаж у repository всі файли з цієї папки.
3. Відкрий `Settings` → `Pages`.
4. У `Build and deployment` вибери `Deploy from a branch`.
5. Branch: `main`, folder: `/ (root)`.
6. Натисни `Save`.
7. Після публікації відкрий адресу виду:
   `https://ТВІЙ-ЛОГІН.github.io/borshchova-istoriia/`
8. Після цього заміни в `robots.txt` і `sitemap.xml`:
   `YOUR-GITHUB-USERNAME` → твій GitHub username
   `YOUR-REPO` → назва repository.

## Google Analytics 4

У файлах HTML залишений закоментований шаблон Google tag.
Після створення GA4 Data Stream:
1. Отримай Measurement ID виду `G-XXXXXXXXXX`.
2. Розкоментуй блок Google Analytics у HTML.
3. Заміни `G-XXXXXXXXXX` на свій ID.
4. Завантаж зміни в GitHub.

Не вигадуй Measurement ID — використовуй той, який видасть Google Analytics.

## Після запуску
1. Перевірити сайт з телефону.
2. Підключити Google Search Console.
3. Додати sitemap.xml.
4. Перевірити індексацію.
5. Потім можна підключити власний домен.

GitHub Pages підтримує HTTPS для github.io-сайтів і custom domains.
