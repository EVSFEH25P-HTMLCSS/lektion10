---
author: Lektion 10
date: MMMM dd, YYYY
paging: "%d / %d"
---

# Lektion 10

Hej och välkommen!

## Dagens agenda

1. Frågor och repetition
2. Introduktion till SEO
3. Gruppövning
4. Eget arbete med handledning

---

# Fråga

För den individuella uppgiften, får man visa funktioner som ej fungerar - typ search bar eller log in?

# Svar

Gärna!

---

# Fråga

Ser schemat för nästa kurs ut som denna med lektioner på tisdagar och torsdagar?

# Svar

Ja, men med några undantag.

---

# Search Engine Optimization

- Teknik för att optimera sökresultat på webben
- Anpassning efter sökmotorer
  - Google
  - Bing
  - DuckDuckGo
- Responsiv design, prestanda, säkerhet

---

# Webcrawlers

- Program som letar och läser av dokument på webben
- Hoppar mellan länkar
- Läser av innehållet
- `robots.txt` som .gitignore för crawlers
- Client-side rendering vs Server-side rendering

---

# Exempel robots.txt

```
User-agent: *
Disallow: /api
Disallow: /staff

Sitemap: https://example.se/sitemap.xml
```

---

# Exempel sitemap.txt

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://example.se/</loc>
    <priority>1.0</priority>
    <changefreq>weekly</changefreq>
  </url>
    <url>
    <loc>https://example.se/services</loc>
    <priority>0.8</priority>
    <changefreq>weekly</changefreq>
  </url>
  <url>
    <loc>https://example.se/privacy-policy</loc>
    <priority>0.5</priority>
    <changefreq>yearly</changefreq>
  </url>
  <url>
    <loc>https://example.se/cookie-policy</loc>
    <priority>0.5</priority>
    <changefreq>yearly</changefreq>
  </url>
</urlset>
```

---

# On-Page tekniker

- Skriv innehåll av kvalitet
- Använd tags med betydelse
- Använd passande tags
- Inkludera keywords i titel
- Utnyttja headings med keywords
- Undvik popups och modals
- Bygg rena och beskrivande URLer
- Ange `alt`-beskrivningar för bilder

---

# Off-Page tekniker

- Bygg ett nätverk av länkar (backlinks)
- Skapa populära media och profiler
- Uppdatera media ofta
- Övervaka trafik, analytics och metrics (Google Analytics)
- Övervaka beteende (Microsoft Clarity)

---

# Gruppövning

Optimera en existerande webbsida för SEO och conversion rate. Presentera era ändringar och val efteråt.

Webbsidan är till ett låtsas-företag. Använd beskrivningen av företaget för att optimera sidan.

[https://github.com/EVSFEH25P-HTMLCSS/seo-exercise](https://github.com/EVSFEH25P-HTMLCSS/seo-exercise)
