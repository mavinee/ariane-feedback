# Activer Gemini Nano / Enable Gemini Nano

Ariane peut générer ses résumés **100 % en local** grâce à **Gemini Nano**, l'IA
intégrée à Chrome. Aucune donnée ne quitte votre machine. Cette page explique
comment l'activer.

*Ariane can generate its briefings **100% locally** using **Gemini Nano**,
Chrome's built-in AI. No data leaves your machine. This page explains how to
enable it.*

---

## 🇫🇷 Français

### Prérequis
- **Chrome de bureau récent** (Windows 10/11, macOS 13+, Linux, ou ChromeOS sur Chromebook Plus). Non disponible sur Android, iOS, et ChromeOS hors Chromebook Plus.
- **~22 Go d'espace disque libre** (le modèle est volumineux et téléchargé une seule fois).
- **GPU avec plus de 4 Go de VRAM**, *ou* **un CPU avec 16 Go de RAM et 4 cœurs ou plus**.

### Activation (méthode simple)
1. Mettez **Chrome à jour** (menu ⋮ → Aide → À propos de Google Chrome), puis redémarrez-le.
2. Dans les réglages d'Ariane, choisissez **Gemini Nano** (ou laissez **Automatique**).
3. Lancez une restauration de session : Ariane demande le modèle. S'il n'est pas encore présent, Chrome **commence à le télécharger** en arrière-plan.
4. **Laissez Chrome ouvert** le temps du téléchargement (cela peut prendre plusieurs minutes selon la connexion). Réessayez ensuite.

### Vérifier l'état du modèle
- Ouvrez `chrome://on-device-internals` pour voir si le modèle est présent et sa taille.
- (Anciennes versions de Chrome) `chrome://components` → cherchez « Optimization Guide On Device Model » → **Rechercher une mise à jour**.

### Si Gemini Nano reste indisponible (méthode avancée)
Sur certaines versions, l'API doit être activée manuellement via les *flags* :
1. Ouvrez `chrome://flags/#prompt-api-for-gemini-nano` → réglez sur **Enabled**.
2. Ouvrez `chrome://flags/#optimization-guide-on-device-model` → réglez sur **Enabled BypassPerfRequirement**.
3. Cliquez sur **Relaunch** pour redémarrer Chrome.
4. Revenez sur `chrome://on-device-internals` pour suivre/forcer le téléchargement.

### Dépannage
- **« indisponible »** : vérifiez l'espace disque (22 Go) et que votre machine remplit les conditions GPU/CPU.
- **Rien ne se télécharge** : gardez Chrome ouvert et connecté à Internet ; relancez après quelques minutes.
- **Toujours rien ?** Ariane bascule automatiquement sur les autres fournisseurs si vous êtes en mode **Automatique** : modèle local (LM Studio) ou Gemini API (cloud, avec votre clé).

---

## 🇬🇧 English

### Requirements
- **Recent desktop Chrome** (Windows 10/11, macOS 13+, Linux, or ChromeOS on Chromebook Plus). Not available on Android, iOS, or non-Chromebook-Plus ChromeOS.
- **~22 GB of free disk space** (the model is large and downloaded once).
- **A GPU with more than 4 GB of VRAM**, *or* **a CPU with 16 GB of RAM and 4+ cores**.

### Enabling (simple path)
1. **Update Chrome** (⋮ menu → Help → About Google Chrome), then restart it.
2. In Ariane's settings, select **Gemini Nano** (or leave **Automatic**).
3. Restore a session: Ariane requests the model. If it isn't present yet, Chrome **starts downloading it** in the background.
4. **Keep Chrome open** while it downloads (can take several minutes depending on your connection). Then try again.

### Check the model status
- Open `chrome://on-device-internals` to see whether the model is present and its size.
- (Older Chrome) `chrome://components` → find "Optimization Guide On Device Model" → **Check for update**.

### If Gemini Nano stays unavailable (advanced path)
On some versions the API must be enabled manually via flags:
1. Open `chrome://flags/#prompt-api-for-gemini-nano` → set to **Enabled**.
2. Open `chrome://flags/#optimization-guide-on-device-model` → set to **Enabled BypassPerfRequirement**.
3. Click **Relaunch** to restart Chrome.
4. Go back to `chrome://on-device-internals` to track/force the download.

### Troubleshooting
- **"unavailable"**: check free disk space (22 GB) and that your machine meets the GPU/CPU criteria.
- **Nothing downloads**: keep Chrome open and online; retry after a few minutes.
- **Still nothing?** In **Automatic** mode, Ariane automatically falls back to other providers: a local model (LM Studio) or the Gemini API (cloud, with your own key).
