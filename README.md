# 🎤 Traducteur Speech-to-Text

Application de traduction vocale en temps réel : **Anglais → Français**

## 📋 Description

Application web simple qui transforme la parole en texte, traduit de l'anglais vers le français, et fait lire la traduction en français.

**Fonctionnalités :**
- ✅ Reconnaissance vocale (Speech-to-Text)
- ✅ Traduction automatique (EN → FR)
- ✅ Synthèse vocale (Text-to-Speech)
- ✅ Mode streaming (traduction en temps réel)

## 🚀 Utilisation

### Méthode 1 : Ouvrir directement

1. Ouvrir `simple-voice.html` dans Chrome ou Safari
2. Cliquer sur "▶️ Démarrer"
3. Autoriser le microphone
4. Parler en anglais

### Méthode 2 : Serveur local

```bash
# Python
python3 -m http.server 8000

# Node.js
npx serve
```

Puis ouvrir : `http://localhost:8000/simple-voice.html`

## 📁 Fichiers

- **`simple-voice.html`** - Version simple (reconnaissance vocale uniquement)
- **`debug-voice.html`** - Version avec logs de debug
- **`translator-streaming.html`** - Version complète avec traduction
- **`index.html`** - Ancienne version
- **`test.html`** - Test basique

## 🛠️ Technologies

- **Web Speech API** - Reconnaissance vocale
- **DeepL API** - Traduction (optionnelle)
- **Speech Synthesis API** - Synthèse vocale

## 📝 Notes

- Fonctionne uniquement sur Chrome ou Safari
- Requiert une connexion internet pour la traduction
- Le microphone doit être autorisé

## 📄 Licence

MIT

## ��‍💻 Auteur

Pierre
