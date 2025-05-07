[![Repository](https://img.shields.io/badge/Repository-fff__discourse__theme-blue?style=flat&logo=github)](https://github.com/bonsaibauer/fff_discourse_theme)  ![License](https://img.shields.io/badge/License-GNU--GENERA--PUBLI--LICENSE-blue)

# 🌍 FFF Discourse Theme

Ein angepasstes Discourse-Theme für das Fridays for Future Forum, basierend auf der **Corporate Identity** von Fridays for Future.

> 🎨 Modernes, klares Design passend zum Wiki und weiteren Tools von FFF.

Ein modernes & sauberes Theme mit einer Reihe von enthaltenen Theme-Komponenten zur Verbesserung deines Forums!

---

## 📥 Installation

1. Navigiere in deinem Discourse-Adminbereich zu:  
   **Admin > Customize > Themes > Install from Git**

2. Füge dort folgendes Repository ein:

```
https://github.com/bonsaibauer/fff_discourse_theme.git
```

3. Klicke auf **"Import"**, dann aktiviere das Theme unter **Themes**.

---

## 🖼️ Screenshots

**Light Mode**  
![image](https://user-images.githubusercontent.com/5862206/214545439-85410d82-9565-4e00-8b23-b2d69a0ee1eb.png)

**Dark Mode**  
![image](https://user-images.githubusercontent.com/5862206/214545506-f44d6165-4f79-416e-a89c-548482d04cea.png)

**Categories Page**  
![image](https://user-images.githubusercontent.com/5862206/214545568-76d38925-55a6-4359-b1c6-bf1010706132.png)

---

## 🔧 Enthaltene Theme-Komponenten

- Dark Light Scheme Toggle
- Clickable Topics
- Discourse Loading Slider
- Discourse Search Banner
- Modern Category + Group Boxes

---

## ⚙️ Tipps & Hinweise

### 🌗 Dark/Light Toggle aktivieren

Damit der Farbwechsel funktioniert, müssen mindestens **zwei Farbschemata** im Adminbereich unter  
`/admin/customize/colors` aktiviert sein – jeweils mit der Option:  
**„color scheme can be selected by users“**.

![image](https://user-images.githubusercontent.com/5862206/214545647-e0544474-b6bf-4b9c-8c64-6a8bfa6ba83a.png)

Danach können Nutzer im Profil zwischen hellem und dunklem Modus wählen:

![image](https://user-images.githubusercontent.com/5862206/214545707-170a6b88-8ccd-4d31-af59-f0834a4fad3c.png)

---

### 🔍 Discourse Search Banner

In den Einstellungen der Komponente `discourse-search-banner` den `plugin-outlet` auf  
**BELOW-SITE-HEADER** setzen, damit das Banner korrekt dargestellt wird.

![image](https://user-images.githubusercontent.com/5862206/214545774-ed8f1322-9a95-4958-bba0-adf7ff6dea3f.png)

---

### 📦 Modern Category + Group Boxes

Damit die Darstellung funktioniert, muss die Einstellung **CATEGORY BOXES WITH SUBCATEGORIES**  
im Adminbereich unter  
`/admin/site_settings/category/all_results?filter=categories` aktiviert werden:

![image](https://user-images.githubusercontent.com/5862206/214545903-c4bd61b9-1893-48e0-84e7-502efc26c46d.png)

Zusätzlich kann die Startseite nach Themen gruppiert werden (max. 5 Gruppenüberschriften).  
Wird keine Gruppierung definiert, erfolgt die Standarddarstellung wie oben.

---

## 🤝 Mitwirken

Issues, Pull Requests oder Verbesserungsvorschläge sind willkommen!

---

## 📎 Download

🔽 [fff_discourse_theme.zip](https://github.com/bonsaibauer/fff_discourse_theme/archive/refs/heads/main.zip)

---

## ℹ️ Weitere Links

|                     |                              |                                                                                                                             |
| ------------------- | ---------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| :eyeglasses:        | **Preview**                  | https://discourse.jordanvidrine.com/                                                                                        |
| :hammer_and_wrench: | **Repository**               | https://github.com/discourse/discourse-air.git                                                                              |
| :question:          | **Install Guide**            | [How to install a theme or theme component](https://meta.discourse.org/t/how-do-i-install-a-theme-or-theme-component/63682) |
| :open_book:         | **New to Discourse Themes?** | [Beginner’s guide to using Discourse Themes](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966)  |
