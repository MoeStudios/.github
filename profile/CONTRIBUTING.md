# 🌸 Mitwirken bei MoeStudios 🌸

<div align="center">
  <img src="https://moestudios.de/assets/images/logo.svg" width="150px" alt="MoeStudios Logo">
  <p>Vielen Dank für dein Interesse, zu unseren Projekten beizutragen! ✨</p>
</div>

## 📝 Inhaltsverzeichnis

- [Willkommen](#-willkommen)
- [Entwicklungsumgebung einrichten](#-entwicklungsumgebung-einrichten)
- [Der Beitragsprozess](#-der-beitragsprozess)
- [Codierungsrichtlinien](#-codierungsrichtlinien)
- [Commit-Richtlinien](#-commit-richtlinien)
- [Community und Kommunikation](#-community-und-kommunikation)
- [Abschließende Worte](#-abschließende-worte)

## 👋 Willkommen

Wie ein guter Anime-Protagonist bist du hier, um unsere Software besser zu machen! Bei MoeStudios schätzen wir jeden Beitrag - von Bugfixes über Dokumentation bis hin zu neuen Features. Dieser Leitfaden hilft dir, deinen Weg in unser Projekt zu finden.

## 🔧 Entwicklungsumgebung einrichten

### Voraussetzungen

- [Node.js](https://nodejs.org/) (v20 oder höher)
- [npm](https://www.npmjs.com/) (v10 oder höher)
- [Git](https://git-scm.com/)
- Ein Code-Editor deiner Wahl (wir empfehlen [Visual Studio Code](https://code.visualstudio.com/) mit dem NyanCode-Theme!)

### Einrichtungsschritte

1. **Forke das Repository**:
   Besuche die GitHub-Seite des Projekts und klicke auf den "Fork"-Button.

2. **Klone dein Fork**:
   ```bash
   git clone https://github.com/DEIN-USERNAME/PROJEKTNAME.git
   cd PROJEKTNAME
   ```

3. **Upstream hinzufügen**:
   ```bash
   git remote add upstream https://github.com/MoeStudios/PROJEKTNAME.git
   ```

4. **Abhängigkeiten installieren**:
   ```bash
   npm install
   ```

5. **Entwicklungsserver starten**:
   ```bash
   npm run dev
   ```

## 🚀 Der Beitragsprozess

### 1. Issue auswählen oder erstellen

- Schaue dir vorhandene Issues an oder erstelle ein neues, um deine geplanten Änderungen zu diskutieren.
- Warte auf Feedback vom MoeStudios-Team, bevor du mit größeren Änderungen beginnst.

### 2. Einen Branch erstellen

```bash
git checkout -b feature/deine-feature-beschreibung
```

Verwende eines dieser Präfixe:
- `feature/` - Für neue Features
- `fix/` - Für Bugfixes
- `docs/` - Für Dokumentationsänderungen
- `style/` - Für Design- und UI-Änderungen
- `refactor/` - Für Code-Refactoring

### 3. Änderungen vornehmen

Entwickle deine Änderungen und halte dich dabei an unsere [Codierungsrichtlinien](#-codierungsrichtlinien).

### 4. Commit und Push

```bash
git add .
git commit -m "✨ Füge kawaii Avatarauswahl hinzu"
git push origin feature/deine-feature-beschreibung
```

### 6. Pull Request erstellen

- Gehe zu deinem Fork auf GitHub und klicke auf "Compare & pull request".
- Fülle die PR-Vorlage aus und beschreibe deine Änderungen ausführlich.
- Verlinke verwandte Issues.

### 7. Code-Review

- Ein Mitglied des MoeStudios-Teams wird deinen PR überprüfen.
- Sei offen für Feedback und Änderungsvorschläge.
- Nimm gegebenenfalls Anpassungen vor.

## 📊 Codierungsrichtlinien

### Allgemeine Prinzipien

- **Sauberkeit**: Halte deinen Code sauber und leserlich.
- **Kommentare**: Dokumentiere komplexe Logik mit Kommentaren.
- **Modularität**: Schreibe modularen, wiederverwendbaren Code.

## 📝 Commit-Richtlinien

Wir folgen einem modifizierten [Conventional Commits](https://www.conventionalcommits.org/)-Standard mit Anime-Flair:

```
✨ feat(component): Füge kawaii Loadinganimation hinzu
🐛 fix(api): Behebe Authentifizierungsfehler
📚 docs(readme): Aktualisiere Installationsanweisungen
🎨 style(ui): Verbessere Farbschema
♻️ refactor(core): Optimiere Renderlogik
```

## 💬 Community und Kommunikation

- **GitHub Discussions**: Für längere Diskussionen über Features oder Verbesserungen.

## 🎉 Abschließende Worte

Dein Beitrag macht MoeStudios besser! Wie in jedem guten Anime sind es die gemeinsamen Anstrengungen aller Charaktere, die zum Erfolg führen. Wir freuen uns darauf, deine kreativen Ideen und Verbesserungen zu sehen!

Wenn du Fragen hast, zögere nicht, uns zu kontaktieren.

---

<div align="center">
  <p>Arigatou für deine Unterstützung! 🙏</p>
  <p>一緒に素晴らしいものを作りましょう！ (Issho ni subarashii mono o tsukurimashō!)</p>
  <p>Lasst uns gemeinsam etwas Wunderbares erschaffen!</p>
</div>
