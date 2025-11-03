# Sage & Blush Travels

Ett mjukt, feminint och naturligt resebloggsprojekt byggt med **HTML5** och **CSS3** – helt utan JavaScript.  
Webbplatsen är responsiv, tillgänglig och designad för att fungera på olika skärmstorlekar.

---

## Kort projektbeskrivning & skärmdumpar

**Sage & Blush Travels** är en personlig reseblogg som delar lugna, estetiska resor genom  
**Schweiz, Sverige, Rom och Grekland**.  
Projektet består av tre sidor:

| Sida | Innehåll |
|------|-----------|
| `index.html` | Startsida med hero-bild och utvalda destinationer |
| `about.html` | "Om mig"-sida med personlig presentation och värderingar |
| `contact.html` | Kontaktsida med formulär och kontaktuppgifter |

*(Lägg till skärmdumpar här – t.ex. desktop- och mobilvy på startsidan)*  
> ![Skärmdump av startsida](screenshots/home.png)  
> ![Skärmdump av om-sida](screenshots/about.png)

---

## Designbeslut & motivering

**Färgpalett**
- **Blush (#f5c7cf)** – mjuk och feminin grundton  
- **Sage (#7a9e87)** – naturlig accentfärg  
- **Rose (#e89aae)** – används för fokus och länkar  
- **Cream (#fff8f6)** – bakgrund för en varm känsla  
- **Forest (#2f4d3b)** – mörk kontrastfärg för text och rubriker

**Typografi**
- Systemfonter (sans-serif stack) för läsbarhet och prestanda  
- Fluid typografi med `clamp()` för att skalan ska anpassas till skärmstorlek  

**Layout**
- Byggd med **Flexbox** och **CSS Grid**  
- Mobil-först-strategi med två brytpunkter (~600px och ~1024px)  
- Luftig layout och rundade hörn (`border-radius`) för ett mjukt, harmoniskt uttryck  

Motivet bakom designen är att förmedla **lugn, naturlighet och femininitet** – en resa som känns personlig och stillsam snarare än stressig och kommersiell.

---

## CSS-mönster för interaktivitet

1. **Hamburgermeny** – byggd med `:checked`-mönster (checkbox-hack) för att öppna/stänga navigeringen utan JavaScript.  
2. **Expandera “Läs mer”** – `<details>/<summary>` på About-sidan visar extra text vid klick.  
3. **Hover/focus-effekter** – övergångar (`transition`) och animationer på knappar, länkar, bilder och kort för visuell feedback.  
4. **Formulärvalidering** – inbyggd HTML5-validering med `:valid` och `:invalid` för färgfeedback.

Alla mönster fungerar med tangentbord och skärmläsare.

---

## Kända begränsningar & förbättringsidéer

**Begränsningar**
- Bilder hämtas via **Unsplash Source API**, vilket kräver internetanslutning.  
- Inget innehållssystem (alla inlägg är statiska HTML-sidor).  
- Ingen serverlogik – formuläret sparar inte data.

**Förbättringsidéer**
- Skapa en separat **Styleguide-sida** som visar färger, typsnitt och komponenter.  
- Göra varje land till en egen undersida med bildgalleri.  
- Byta till egna optimerade bilder i stället för Unsplash.  
- Implementera `container queries` för ännu bättre responsivitet.  
- Lägg till `prefers-reduced-motion` på fler animationer för extra tillgänglighet.

---

© 2025 **Sage & Blush Travels**  
Projekt av *Ella* för kursmomentet **HTML & CSS**.
