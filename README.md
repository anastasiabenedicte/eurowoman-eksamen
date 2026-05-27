# Eurowoman – Eksamensprojekt

Et digitalt magasinunivers bygget som eksamensprojekt på multimediedesigneruddannelsen.

**Live site:** [eurowoman-eksamen.netlify.app](https://eurowoman-eksamen.netlify.app)

---

## Om projektet

Projektet er en frontend-fortolkning af Eurowomans nuværende website ([eurowoman.dk](https://www.eurowoman.dk/)), som ligger under medieplatformen mitblad.dk. Målet har været at genskabe og videreudvikle sidens udtryk og struktur — fra redaktionelt indhold og magasinarkiv til e-handel og abonnementsunivers.
## Sider

| Side | Beskrivelse |
|------|-------------|
| Forside | Hero-sektion, magasinnyheder og kampagnebilleder |
| Artikler | Artikliste med kategorifilter og detail-sider |
| Shop | Produktoversigt og produktsider med kurv |
| Kurv | Interaktiv indkøbskurv med Alpine.js store |
| Magasin Arkiv | Arkiv over tidligere udgivelser med filtervisning |
| Redaktion | Om Eurowoman og redaktionen |
| Galleri | Billedgalleri |
| Abonnér | Abonnementsplaner og tilmelding |
| Login | Log ind og registrer konto |

## Teknologier

- **[Astro](https://astro.build/)** — statisk site-generator med komponentbaseret arkitektur
- **[Tailwind CSS](https://tailwindcss.com/)** — utility-first CSS framework
- **[Alpine.js](https://alpinejs.dev/)** — reaktiv UI til kurv, søgning, menuer og overlays

## Funktioner

- Responsivt design (mobil, tablet, desktop)
- Hamburger-menu med slide-in overlay på mobil
- Søgeoverlay med kategorilinks
- Nyhedsbrevs-popup
- Indkøbskurv med persistent Alpine.js store
- Aktiv-tilstand i navigation på alle undersider
- HTML-valideret uden fejl

## Kom i gang

```bash
# Installer afhængigheder
npm install

# Start udviklingsserver
npm run dev

# Byg til produktion
npm run build
```

---

*Eksamensprojekt – Multimediedesigner, 2026*
