# OCADE Dictée – téléchargements

Ce dépôt ne contient pas de code : il héberge les fichiers publics d'OCADE Dictée.

- **Versions de l'application** (onglet [Releases](https://github.com/ocade-graciet-system/ocade-dictee-public/releases)) : installateurs Windows, macOS et Linux, et fichiers de mise à jour signés que l'application installe d'elle-même.
- **`models-v2`** : modèles de reconnaissance vocale téléchargés par l'application (Canary 1B v2, Canary 180M Flash, Qwen3-ASR 1.7B, Whisper Large v3 Turbo).
- **`models-v1`** : ancien modèle de reconnaissance vocale, gardé pour les postes qui l'utilisent encore.
- **`build-deps-v1`** : dépendances de construction (ONNX Runtime) utilisées par l'intégration continue.
- **`tools-v1`** : miroir des outils externes (ffmpeg, sous licence LGPL) utilisés par l'application.

## Licences des modèles

Les modèles sont rehébergés à l'identique (même empreinte SHA-256) et restent sous leur propre licence (CC BY 4.0, Apache 2.0 ou MIT) : ils ne sont pas soumis à la licence d'OCADE Dictée. Chaque release de modèles contient `LICENCES-ET-ATTRIBUTIONS.md` (auteur, licence, page d'origine, conversion et modifications de chaque modèle), les textes intégraux des licences et les fichiers `NOTICE` des conversions.

Les noms NVIDIA, OpenAI, Alibaba et Qwen sont cités à titre descriptif : ces éditeurs ne soutiennent ni ne valident OCADE Dictée.

## Installer

Pour installer OCADE Dictée, ouvrez la dernière version dans l'onglet Releases et suivez le guide affiché en haut de la page.

Contact : contact@graciet.info
