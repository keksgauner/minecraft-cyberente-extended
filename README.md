# 🦆 CyberEnte Extended

[![Build](https://img.shields.io/github/actions/workflow/status/keksgauner/minecraft-cyberente-extended/build.yml?branch=master&label=Build&style=for-the-badge)](https://github.com/keksgauner/minecraft-cyberente-extended/actions)
[![Release](https://img.shields.io/github/v/release/keksgauner/minecraft-cyberente-extended?label=Release&style=for-the-badge)](https://github.com/keksgauner/minecraft-cyberente/releases)
[![Java](https://img.shields.io/badge/Java-21+-orange?style=for-the-badge&logo=openjdk)](https://jdk.java.net/21/)
[![License](https://img.shields.io/github/license/keksgauner/minecraft-cyberente-extended?style=for-the-badge)](https://github.com/keksgauner/minecraft-cyberente-extended/blob/main/LICENSE)

> 🛠️ Ein maßgeschneidertes **Minecraft Paper-Plugin** für den privaten CyberEnte-Server. Der Bibliotheken für **[Minecraft Paper-Plugin CyberEnte](https://github.com/keksgauner/minecraft-cyberente)** enthält, die für den Betrieb des Plugins erforderlich sind.

---

## 👥 Autoren

- 🐤 [@CyberEnte](https://www.github.com/cyberente)
- 🍪 [@KeksGauner](https://www.github.com/keksgauner)

---

## 📥 Installation

1. Lade die neueste Version von der [**Releases-Seite**](https://github.com/keksgauner/minecraft-cyberente-extended/releases) herunter.
2. Kopiere die `CyberEnte-Extended-paper.jar` in den `plugins`-Ordner deines Paper-Servers.
4. Starte den Server neu.

## 🧪 Kompilieren aus dem Quellcode

**Voraussetzungen:**

- ✅ JDK 21 oder höher
- 🌐 Internetverbindung

**Schritte:**

```bash
git clone https://github.com/keksgauner/minecraft-cyberente-extended.git
cd minecraft-cyberente-extended
./gradlew build
```

🗃️ Das fertige Plugin befindet sich anschließend in `build/libs` und trägt den Namen:
`CyberEnte-Extended-paper.jar`

---

## 🧹 Code-Check & Formatierung

- 🔍 Code prüfen:
  `./gradlew spotlessCheck`

- 🎨 Code formatieren:
  `./gradlew spotlessApply`

---
