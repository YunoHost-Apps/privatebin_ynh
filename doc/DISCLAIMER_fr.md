## Informations additionnelles

Les données sont chiffrées et déchiffrées dans le navigateur en utilisant la technologie AES 256bits en mode Galois Counter (GCM).

Ce projet est un fork de ZeroBin, développé à l'origine par Sébastien Sauvage. Il a été ré-écrit pour accepter plus facilement des extensions en rajoutant plus de fonctionnalités. Il reste cependant compatible avec le schéma original de stockage des données Zerobin 0.19. Ainsi toutes les installations peuvent être mises à jour vers ce projet, sans perte de données.

Dans la [documentation de mise à jour](https://github.com/PrivateBin/PrivateBin/wiki/Configuration#zerobincompatibility) de PrivateBin, il est précisé que :

Pour une compatibilité complète avec Zerobin et le déchiffrement de tous les vieux "paste", vous devriez activer cette option. Cependant, ce n'est pas recommandé pour les nouvelles installations car cela affaiblit la sécurité de votre instance PrivateBin.

Ceci signifie que nous avons décidé de supprimer ce répertoire pour permettre la sécurisation des données. Vous pouvez sauvegarder le répertoire 'data', si vous voulez conservez vos données. Mais vous devriez savoir que cela réduit la sécurité de votre application.