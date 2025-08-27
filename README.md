# 🚍 OMSI 2 Mod-Seite

Dies ist eine **OMSI 2 Mod-Download-Seite**, die auf **GitHub Pages** läuft.  
Mit dieser Struktur kannst du Mods übersichtlich nach Kategorien sortieren (Busse, Maps, Repaints, Sounds, Scripts).

---

## 📂 Projektstruktur
- `index.html` → Startseite mit allen Kategorien
- `busse.html` → Busse
- `maps.html` → Karten
- `repaints.html` → Repaints
- `sounds.html` → Sounds
- `scripts.html` → Scripts
- `style.css` → Design/Layout

---

## 🚀 Deployment (GitHub Pages aktivieren)
1. Repository auf GitHub erstellen (z. B. `omsi-mods`).
2. Dateien hochladen (nicht ZIP, sondern entpackt).
3. Repository öffnen → **Settings → Pages**.
4. Source auswählen: `main` branch, `/ (root)` folder.
5. Speichern → GitHub zeigt dir den Link an, z. B.  
   ```
   https://deinname.github.io/omsi-mods/
   ```

---

## 📝 Neue Mods hinzufügen
1. Wähle die passende Kategorie-Datei (z. B. `busse.html`).
2. Füge einen neuen Block hinzu:

```html
<div class="mod-card">
  <img src="images/deinbus.jpg" alt="Screenshot">
  <h3>Mod-Name</h3>
  <p>Kategorie: Busse</p>
  <p>Beschreibung deines Mods.</p>
  <a href="downloads/deinbus.zip" class="download-btn">Download</a>
</div>
```

3. Commit und pushen → deine Seite ist aktualisiert.

---

✅ Damit hast du eine einfache und übersichtliche OMSI 2 Mod-Seite auf GitHub Pages.

