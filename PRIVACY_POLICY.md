# Privacy Policy for Ariane Chrome Extension / Politique de Confidentialité

This Privacy Policy explains how **Ariane** collects, uses, and safeguards your information when you use our Chrome Extension. 

*Cette politique de confidentialité explique comment **Ariane** collecte, utilise et protège vos informations lorsque vous utilisez notre extension Chrome.*

---

## English Version (Required for Google Review)

### 1. Introduction
Ariane is a productivity tool designed to save and restore your "flow state" (active tabs, scroll positions, and reading contexts). We are committed to protecting your privacy. **Ariane does not collect, store on external servers, or sell any of your personal data.**

### 2. Data Collection and Usage
To function, Ariane requires specific Chrome permissions. All data gathered by these permissions is stored strictly on your local machine and is never transmitted to us or any third party (except directly to your chosen AI provider, as detailed in Section 3).

*   **Tabs & TabGroups (`tabs`, `tabGroups`, `activeTab`):** Used solely to detect your open tabs, group layouts, and titles in order to save your workspace, restore it later, and generate the AI briefing.
*   **Clipboard Read (`clipboardRead`):** Used to capture the text currently stored in your clipboard *only* when you explicitly save a session (Freeze or Snapshot). This content is used to provide the AI with context about what you were doing. **No background clipboard monitoring is performed.**
*   **Local Storage (`storage`, `unlimitedStorage`):** Used to persist saved sessions, user notes, settings, and base64-encoded visual thumbnails of your active tab on your local machine.
*   **Scripting (`scripting`):** Used to inject local scripts to restore your scroll positions on reopened tabs and display a brief capture confirmation overlay.

### 3. AI Data Processing
Ariane leverages AI models to generate session summaries. Depending on your configuration in the settings console, data processing is handled as follows:
*   **Gemini Nano (Local - Default/Auto):** Processing occurs 100% on your device. No data leaves your machine.
*   **LM Studio (Local):** Requests are sent locally to your self-hosted API endpoint. No data leaves your machine.
*   **Gemini API (Cloud):** Your note, tab titles, tab excerpts, and clipboard hint are sent directly to Google APIs over a secure HTTPS connection. This data is handled in accordance with Google's API Terms of Service and is not used to train Google models (for paid/developer keys). **No third-party server acts as a proxy; the connection is direct from your browser to Google.**

### 4. Data Sharing and Disclosure
We do not share, sell, or trade your data with third parties. We do not use trackers, analytics tools, or telemetry.

### 5. Data Deletion
All session data and configuration keys are stored locally using `chrome.storage.local`. You can delete all your data at any time by:
1. Clicking the "Tout supprimer" (Delete All) button in the side panel.
2. Uninstalling the extension from your browser.

### 6. Contact Information
If you have any questions regarding this Privacy Policy, you can contact us by email at [ariane.extension@gmail.com](mailto:ariane.extension@gmail.com).

---

## Version Française

### 1. Introduction
Ariane est un outil de productivité conçu pour sauvegarder et restaurer votre "état de flow" (onglets actifs, positions de défilement et contextes de lecture). Nous nous engageons à protéger votre vie privée. **Ariane ne collecte, ne stocke sur des serveurs externes et ne vend aucune de vos données personnelles.**

### 2. Collecte et Utilisation des Données
Pour fonctionner, Ariane nécessite des permissions Chrome spécifiques. Toutes les données collectées par ces permissions sont stockées exclusivement sur votre machine locale et ne nous sont jamais transmises (sauf directement à votre fournisseur d'IA sélectionné, voir Section 3).

*   **Onglets et Groupes d'onglets (`tabs`, `tabGroups`, `activeTab`) :** Utilisé uniquement pour détecter vos onglets ouverts, la mise en page de vos groupes et leurs titres afin de sauvegarder votre espace de travail, le restaurer ultérieurement et générer le résumé de session.
*   **Lecture du Presse-papiers (`clipboardRead`) :** Utilisé pour capturer le texte actuellement stocké dans votre presse-papiers *uniquement* lorsque vous sauvegardez volontairement une session (Freeze ou Snapshot). Ce contenu permet d'alimenter l'IA sur votre contexte de travail. **Aucune surveillance du presse-papiers en arrière-plan n'est effectuée.**
*   **Stockage Local (`storage`, `unlimitedStorage`) :** Utilisé pour conserver vos sessions sauvegardées, vos notes utilisateur, vos réglages et des miniatures visuelles (base64) de votre onglet actif sur votre machine.
*   **Scripting (`scripting`) :** Utilisé pour injecter des scripts locaux afin de restaurer la position de défilement (scroll) lors de la réouverture des onglets et afficher une animation de confirmation de capture.

### 3. Traitement des Données par l'IA
Ariane utilise des modèles d'IA pour générer les résumés de session. Selon votre configuration dans la console des réglages, le traitement s'effectue comme suit :
*   **Gemini Nano (Local - Par défaut/Auto) :** Le traitement a lieu à 100% sur votre appareil. Aucune donnée ne quitte votre machine.
*   **LM Studio (Local) :** Les requêtes sont envoyées localement vers votre serveur d'API personnel. Aucune donnée ne quitte votre machine.
*   **API Gemini (Cloud) :** Votre note, les titres et extraits d'onglets, ainsi que le contenu de votre presse-papiers sont envoyés directement aux API Google via une connexion sécurisée (HTTPS). Ces données sont traitées conformément aux conditions d'utilisation de l'API de Google et ne sont pas utilisées pour entraîner les modèles de Google (pour les clés API développeurs). **Aucun serveur intermédiaire n'est utilisé ; la connexion est directe de votre navigateur vers Google.**

### 4. Partage et Divulgation des Données
Nous ne partageons, ne vendons et n'échangeons pas vos données avec des tiers. Nous n'utilisons aucun outil de tracking, d'analyse ou de télémétrie.

### 5. Suppression des Données
Toutes les données de session et clés de configuration sont stockées localement via `chrome.storage.local`. Vous pouvez supprimer l'intégralité de vos données à tout moment :
1. En cliquant sur le bouton "Tout supprimer" dans le panneau latéral.
2. En désinstallant l'extension de votre navigateur.

### 6. Contact
Pour toute question concernant cette politique de confidentialité, vous pouvez nous contacter par e-mail à l'adresse suivante : [ariane.extension@gmail.com](mailto:ariane.extension@gmail.com).
