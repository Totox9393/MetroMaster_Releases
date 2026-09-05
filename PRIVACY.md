# Politique de confidentialité de MetroMaster

Date d’entrée en vigueur : 4 septembre 2026.

## 1. Éditeur et contact

MetroMaster est édité par Totox Solutions.

Contact relatif à la confidentialité : solutions@totox.fr

## 2. Résumé

MetroMaster ne demande aucun compte utilisateur et n’intègre ni publicité, ni mesure d’audience, ni outil de profilage. L’application ne demande pas l’accès à la position GPS et ne dépose aucun cookie publicitaire.

La ligne, la direction et le point d’arrêt sont choisis manuellement. Les demandes d’horaires transitent par un service MetroMaster hébergé sur Cloudflare Workers afin que la clé PRIM ne soit jamais intégrée à l’application.

## 3. Informations traitées sur l’appareil

L’application traite localement :

- la ligne, la direction et le point d’arrêt choisis pendant l’utilisation ;
- les trajets que l’utilisateur décide d’ajouter à ses favoris ;
- le catalogue des lignes, directions, arrêts et correspondances intégré à l’application ;
- les informations techniques temporaires nécessaires à la vérification et à l’installation des mises à jour.

Les favoris sont enregistrés dans le stockage local de l’application. Ils ne sont pas transmis à Totox Solutions et restent sur l’appareil jusqu’à leur suppression dans MetroMaster, l’effacement des données de l’application ou sa désinstallation.

## 4. Requêtes réseau et destinataires

Lorsqu’une connexion à Internet est disponible, MetroMaster peut communiquer avec :

- le Worker Cloudflare exploité par Totox Solutions pour obtenir les prochains passages et les informations trafic ;
- la plateforme PRIM d’Île-de-France Mobilités, interrogée par ce Worker ;
- GitHub Releases pour rechercher, télécharger et installer les nouvelles versions de MetroMaster.

Pour les prochains passages, l’application envoie au Worker uniquement l’identifiant public de la ligne et la référence technique du point d’arrêt sélectionné. Pour les informations trafic, elle envoie uniquement l’identifiant de la ligne. Le nom d’un favori ou un historique des trajets consultés ne sont pas transmis.

Comme pour toute communication sur Internet, Cloudflare, GitHub et Île-de-France Mobilités peuvent recevoir l’adresse IP et des informations techniques nécessaires à l’acheminement, à la sécurité et au fonctionnement de la requête. Leurs traitements sont régis par leurs propres politiques :

- Cloudflare : <https://www.cloudflare.com/privacypolicy/>
- GitHub : <https://docs.github.com/fr/site-policy/privacy-policies/github-general-privacy-statement>

Les réponses de prochains passages peuvent être mises en cache par Cloudflare pendant 20 secondes et les informations trafic pendant 120 secondes. Ce cache réduit le nombre d’appels à PRIM. Le Worker MetroMaster ne possède pas de base de données de trajets et ne crée aucun profil utilisateur. Cloudflare peut néanmoins conserver des journaux techniques conformément à la configuration de son service et à sa politique de confidentialité.

## 5. Finalités et bases du traitement

Ces échanges servent exclusivement à fournir les horaires et informations trafic demandés, sécuriser l’accès au service, limiter la consommation du quota PRIM et maintenir l’application à jour. Ils reposent sur la fourniture de la fonctionnalité demandée par l’utilisateur et sur l’intérêt légitime de Totox Solutions à assurer la sécurité et la fiabilité du service.

## 6. Données non collectées par Totox Solutions

Dans la version actuelle, Totox Solutions ne collecte pas :

- le nom, l’adresse e-mail, le numéro de téléphone ou l’adresse postale de l’utilisateur ;
- la position GPS ou les déplacements réels ;
- un historique centralisé des lignes, directions, arrêts ou favoris consultés ;
- des identifiants publicitaires, des données de profilage ou des statistiques d’audience ;
- des rapports de plantage transmis automatiquement.

## 7. Conservation et sécurité

Totox Solutions ne conserve pas de base centrale associant un utilisateur à ses consultations. Les éventuels journaux techniques de Cloudflare et GitHub sont conservés selon leurs propres politiques et paramètres de service.

Les communications utilisent HTTPS. La clé PRIM est stockée comme secret côté Cloudflare et n’est incluse ni dans l’application ni dans ses fichiers de mise à jour. Les paquets de mise à jour sont signés et leur signature est vérifiée avant installation.

Aucune transmission sur Internet ne peut toutefois garantir une sécurité absolue. L’utilisateur doit maintenir son système et MetroMaster à jour.

## 8. Droits des utilisateurs

Pour toute question sur la confidentialité ou pour exercer un droit applicable relatif à un traitement placé sous la responsabilité de Totox Solutions, l’utilisateur peut écrire à l’adresse indiquée à la section 1.

En France, l’utilisateur peut également introduire une réclamation auprès de la CNIL : <https://www.cnil.fr/fr/plaintes>.

Les demandes relatives aux traitements propres à Cloudflare, GitHub ou Île-de-France Mobilités doivent être adressées à l’organisme concerné.

## 9. Transferts internationaux

Cloudflare et GitHub sont des prestataires internationaux susceptibles de traiter certaines données techniques hors de l’Espace économique européen, selon les garanties et mécanismes décrits dans leurs politiques respectives.

## 10. Évolution de la politique

Cette politique sera mise à jour avant l’ajout d’un compte, d’un système d’analyse d’usage ou de tout autre traitement nouveau de données personnelles. Sa date d’entrée en vigueur permet d’identifier la version applicable.

## 11. Sources et mentions relatives aux données

Les sources de données, licences et attributions figurent dans [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
