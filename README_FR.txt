APPLICATION ANDROID — GESTION SOLDES & COMMISSIONS

Ce dossier contient le projet source Android Studio. L'HTML actuel est intégré à l'application et fonctionne hors ligne dans une WebView. Les données sont conservées localement sur l'appareil via le stockage du navigateur.

POUR CRÉER LE FICHIER APK
1. Installez Android Studio sur un ordinateur (Windows, macOS ou Linux).
2. Ouvrez Android Studio puis choisissez « Open » et sélectionnez le dossier GestionSoldesAndroid.
3. Attendez la synchronisation Gradle et l'installation des composants Android SDK proposés.
4. Dans le menu Build, choisissez « Build Bundle(s) / APK(s) » puis « Build APK(s) ».
5. Android Studio affiche le chemin du fichier APK créé. Copiez-le sur votre téléphone Android.
6. Sur le téléphone, ouvrez le fichier APK et autorisez temporairement l'installation depuis cette source si Android le demande.

NOTES IMPORTANTES
- Le projet utilise minSdk 23 (Android 6.0), mais la compatibilité doit être testée sur le téléphone cible.
- L'application fonctionne hors ligne.
- Les données restent sur le téléphone. Exportez régulièrement une sauvegarde JSON depuis l'application.
- Désinstaller l'application peut supprimer ses données locales. Faites une sauvegarde avant toute désinstallation.
- Ce dossier est le projet source, pas encore un APK compilé/signé.
