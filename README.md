# Sister Eller - Hjemmeside

Ellen sin hjemmeside for Sister Eller, en australsk langrennsløper som trener i Norge.

## 🌐 GitHub Pages

Denne nettsiden er konfigurert for GitHub Pages og kan sees på:
**https://maremoo2.github.io/hjemmeside/**

### Slik fungerer GitHub Pages

Når du pusher til `main`-branchen, vil GitHub Pages automatisk publisere siden din. Sørg for at:

1. ✅ **Repoet er offentlig (public)** - Private repos krever betalt GitHub-konto for Pages
2. ✅ **GitHub Pages er aktivert** i repo-innstillinger:
   - Gå til Settings → Pages
   - Under "Source" skal det stå "GitHub Actions"
3. ✅ **index.html ligger i root-mappen** - Siden vår ligger korrekt plassert
4. ✅ **Relative stier for CSS/JS** - Vi bruker `styles.css` (ikke `/styles.css`)

### Vanlige problemer og løsninger

#### 404 - Siden ikke funnet
- **Problem**: GitHub Pages er ikke aktivert eller feiler
- **Løsning**: Sjekk Settings → Pages, og se om workflowen kjørte OK under Actions-fanen

#### CSS/Bilder vises ikke
- **Problem**: Feil stier til ressurser
- **Løsning**: Bruk relative stier som `./styles.css` eller `styles.css` (ikke `/styles.css`)

#### Siden vises ikke for andre
- **Problem**: Repoet er privat
- **Løsning**: Gå til Settings → Danger Zone → Change visibility → Make public

#### Endringer vises ikke
- **Problem**: GitHub Pages cacher siden
- **Løsning**: 
  - Vent 1-2 minutter etter push
  - Sjekk Actions-fanen for å se om deploy er ferdig
  - Bruk inkognitovindu eller tøm browser-cache

### Testing lokalt

For å teste siden lokalt før du pusher:

```bash
# Bruk Python's innebygde webserver
python3 -m http.server 8000

# Eller med Node.js
npx serve .
```

Åpne deretter http://localhost:8000 i nettleseren.

## 🎨 Funksjoner

- ✅ Responsiv design som fungerer på mobil, tablet og desktop
- ✅ Smooth scrolling mellom seksjoner
- ✅ Moderne, elegant design med gradients og animasjoner
- ✅ Feilhåndtering og brukervennlige feilmeldinger
- ✅ Offline/online status-varsling
- ✅ Accessibility (tilgjengelighet) med ARIA-labels
- ✅ **Morro-modus** - Interaktiv animasjonsknapp med 11 forskjellige effekter:
  - 🌈 Rainbow Gradients
  - 🔄 Rotation Animation
  - ⚡ Bounce Effect
  - 🎨 Color Shift
  - 🎉 Party Mode (med konfetti!)
  - 💫 Scale Pulse
  - ⭐ Anime Zoom
  - ⚡ Glitch Effect
  - ✨ Neon Glow
  - 💚 Matrix Rain
  - 🌊 Shake Effect

## 🔧 Teknologi

- HTML5
- CSS3 med moderne features (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript (ingen dependencies)
- Google Fonts (Playfair Display & Inter)

## 📝 Lisens

© 2024 Sister Eller
