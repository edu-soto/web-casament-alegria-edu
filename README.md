# Web de Casament / Web de Boda (Bilingual CA / ES)

A modern, fast, responsive bilingual wedding website for **January 30th, 2027**:
- **Cerimònia (12:00 h)**: Església de la Mare de Déu de Pompeia (Barcelona)
- **Aperitiu i Banquet (15:00 h)**: Masia Ca n'Illa (La Garriga)

---

## 🚀 Com veure la web (How to preview)

Aquesta web és 100% autònoma i no requereix instal·lar ni Node.js ni cap dependència de servidor:

1. Obre la carpeta: `C:\Users\Edu\.gemini\antigravity\scratch\wedding-web`
2. Fes **doble clic sobre `index.html`** i s'obrirà directament al teu navegador (Chrome, Edge, Firefox, Safari).

---

## ✏️ Com personalitzar els detalls clau

### 1. Canviar els noms de la parella
Obre `script.js` i canvia els valors de:
- `"hero.names"`
- `"nav.monogram"` (ex: `E & M`)

### 2. Afegir el teu enllaç de Google Forms
A `index.html` (al voltant de la línia 260), busca:
```html
<a id="google-form-link" href="https://docs.google.com/forms" ...>
```
Substitueix `https://docs.google.com/forms` pel link real del teu formulari de Google.

### 3. Codi de Vestimenta (Dress Code)
Hem inclòs una redacció elegant, càlida i no impositiva tant en català com en castellà:
> *"Com que molts ens heu preguntat: serà un casament d'estil formal i elegant (vestit clàssic / vestit de còctel o llarg). Tot i això, no hi ha cap etiqueta rígida: l'únic requisit és que vingueu ben còmodes i amb ganes de gaudir!"*

Si vols ajustar el text, només cal canviar `"dresscode.p1"` i `"dresscode.p2"` a `script.js`.

---

## 🌐 Com publicar la web gratuïtament (Free Hosting)

Pots tenir la web online amb un enllaç públic en menys d'un minut:

1. **Netlify Drop** (El més fàcil, sense comandes):
   - Entra a [app.netlify.com/drop](https://app.netlify.com/drop)
   - Arrossega la carpeta `wedding-web`
   - Obtindràs una URL pública immediatament (ex: `casament-30gener.netlify.app`), on pots afegir el teu domini propi si vols.
2. **GitHub Pages**:
   - Puja aquests arxius a un repositori de GitHub i activa GitHub Pages a `Settings > Pages`.
