# Google Play account deletion URL

Google Play Console wymaga publicznego URL, a nie lokalnego pliku z repozytorium.

## Co zrobic

1. Otworz `account-deletion.html`.
2. Zamien wszystkie wystapienia `YOUR_SUPPORT_EMAIL@example.com` na faktyczny adres kontaktowy do obslugi usuniecia konta.
3. Opublikuj plik jako publiczna strone, np. przez GitHub Pages, Netlify, Vercel, Cloudflare Pages, Google Sites albo zwykly hosting.
4. W Google Play Console wklej publiczny URL do tej strony w sekcji Data safety / Data deletion.

## Minimalne wymaganie Google

Strona musi:

- dzialac bez bledu i byc publicznie dostepna,
- jasno odnosic sie do aplikacji lub dewelopera,
- miec widoczna sciezke zgloszenia usuniecia konta,
- pozwalac uzytkownikowi zglosic usuniecie bez ponownego instalowania aplikacji,
- opisywac dane usuwane i ewentualne dane zachowywane.

Zrodlo: https://support.google.com/googleplay/android-developer/answer/13327111
