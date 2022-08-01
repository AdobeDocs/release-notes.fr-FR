---
title: Dernières notes de mise à jour
description: Découvrez les dernières notes de mise à jour, les nouvelles fonctionnalités et la nouvelle documentation pour les produits et services  [!DNL Experience Cloud] . Trouvez de nouvelles ressources dʼaide et des tutoriels sur  [!DNL Experience Cloud],  [!DNL Creative Cloud for enterprise] et  [!DNL Document Cloud].
doc-type: release notes
last-update: July 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 9186a4065d143b7c02fd87b68b960d3f1a7eb5f2
workflow-type: tm+mt
source-wordcount: '5842'
ht-degree: 92%

---

# Notes de mise à jour d’Adobe Experience Cloud - Juillet 2022

![Bannière](assets/experience-cloud-banner-3.png)

En tant que créateur d’expériences, votre chemin vers la réussite commence avec [Experience League](https://experienceleague.adobe.com/?lang=fr#home). Vous y trouverez une vaste bibliothèque de documents pratiques, des tutoriels autonomes, des vidéos pratiques et des cours pour tous niveaux et rôles. Bénéficiez également des conseils de la communauté internet de pairs et de lʼassistance fournie par un expert lorsque vous en avez besoin.

>[!NOTE]
>
>Pour recevoir une notification mensuelle par e-mail des mises à jour de cette page, abonnez-vous à la [Mise à jour prioritaire des produits Adobe](https://www.adobe.com/subscription/priority-product-update.html). Consultez régulièrement ce site pour rester au courant de ce qui se passe sur Experience League.

Dernière mise à jour : **27 juillet 2022**

* Événements [[!DNL Experience League] ](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - Composants de l’interface centrale et administration](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo) (**Mise à jour le 27 juillet**)
* [[!DNL Adobe Workfront]](#workfront) (**Mise à jour le 27 juillet**)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Plans directeurs en matière d’expérience digitale : tutoriels](#blueprints)

Besoin d’aide ? Rendez-vous sur [Experience League](https://experienceleague.adobe.com/?lang=fr#home) pour trouver de la documentation technique et sur les produits, des cours préparés par Adobe, des tutoriels vidéo, des réponses rapides, des informations provenant de la communauté et des formations dispensées par un instructeur.

## ![Icône](/assets/experience-league.png) Événements [!DNL Experience League] {#events}

Les événements Experience League sont un excellent endroit pour apprendre, interagir et obtenir des réponses d’experts en produits Adobe ! Consultez la page [Événements](https://experienceleague.adobe.com/events/?lang=fr) sur Experience League pour rester à jour en juillet 2022.

Mise à jour le **28 juillet 2022**

| Événement | Type | Description |
| -----------|---------- | ----|
| [Adobe Target](https://atcommunityqacoffeebreak803.splashthat.com/?utm_source=email&amp;utm_medium=Outbound&amp;utm_campaign=coffee_talk_AT&amp;utm_content=220803) | Session Community Q&amp;A Coffee Break  (Pause-café Questions/réponses de la communauté Adobe Target) | Nous serons rejoints par Rachel Booth, conseillère en affaires Premier Support Adobe, alias `@rbooth115`. Elle sera connectée à la communauté Adobe Target pour discuter directement avec vous sur [ce fil](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-8-3-22-8am-pt-rachel-booth/td-p/461694) à propos de vos questions concernant ses domaines d’expertise (personnalisation, optimisation, intégration). <br>**Date :** Mercredi 3 août à 8 heures heure d&#39;été (heure d&#39;été) - 9 heures du matin. - [Détails et enregistrement](https://atcommunityqacoffeebreak803.splashthat.com/?utm_source=email&amp;utm_medium=Outbound&amp;utm_campaign=coffee_talk_AT&amp;utm_content=220803) |
| [Demandez aux experts : flux de données et préparation des données](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=fr) | Experience League LIVE | Durant ces trois dernières sessions portant sur la collecte de données pour Adobe Experience Cloud, nos experts approfondiront les fonctionnalités avancées de collecte de données d’Adobe, notamment les fonctions telles que la préparation de données pour la collecte de données. À la fin de cette session, les participants sauront utiliser les dernières fonctionnalités les plus puissantes de collecte de données issues d’expériences digitales.<br>**Date :** 21 juillet à 9 h (heure du Pacifique) - [Détails](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) |

{style=&quot;table-layout:auto&quot;}

Consultez la page [Événements](https://experienceleague.adobe.com/events/?lang=en) sur Experience League pour rester à jour.

## ![Icône](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] fournit des informations détaillées, des mises à jour de statut et des notifications par e-mail relatives aux produits Adobe. Il prévient également des pannes du service, des perturbations et des activités de maintenance. Consultez le site [status.adobe.com](https://status.adobe.com/fr/).

Pour obtenir les informations les plus récentes, consultez les [notes de mise à jour](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=fr#status) du statut du système Adobe.

## ![Icône](/assets/ec_appicon_24.png) Experience Cloud - Composants et administration de l’interface centrale {#ecloud}

Les [composants de l’interface utilisateur centrale](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=fr) d’Experience Cloud incluent les fonctionnalités disponibles sur la page d’accueil et l’en-tête du produit persistant. Ces fonctionnalités incluent les paramètres de profil utilisateur, les préférences et la recherche. Vous trouverez également de l’aide sur la gestion des utilisateurs et des produits, les attributs du client et les audiences Experience Cloud.

### Mise à jour de l’approvisionnement

>[!IMPORTANT]
>
>Consultez l’avis suivant concernant l’approvisionnement d’Experience Cloud.

Adobe met à jour son approvisionnement pour permettre à tous les clients Experience Cloud d’accéder à des fonctionnalités élémentaires qui facilitent l’interopérabilité entre certains produits Experience Cloud. Les utilisateurs se verront accorder un nouveau droit, Adobe Experience Platform, à leurs organisations Experience Cloud, ainsi que la [!UICONTROL Collecte de données] comme service inclus.

La [!UICONTROL Collecte de données] d’Adobe Experience Platform comprend les [balises](https://experienceleague.adobe.com/docs/tags.html?lang=fr) pour une gestion universelle et simplifiée des balises. Elle offre également une infrastructure de données de transmission en continu fiable, robuste et complète. Les balises permettent de simplifier la collecte de données relatives à l’expérience client et la diffusion d’expériences.

**Modifications dans Admin Console**

Les administrateurs peuvent consulter les modifications ou les ajouts apportés à Admin Console comme suit :

* La fiche produit Adobe Experience Platform dans Admin Console comprendra les éléments suivants :

   * Places
   * Assurance
   * Espace de noms d’identité
   * Sandbox
   * Modèle de données d’expérience
   * Schémas
   * Flux de données
   * Visitor ID (Identifiant visiteur)

   Pour les organisations qui n’utilisent pas actuellement Experience Platform, vous verrez désormais le produit _Adobe Experience Platform_ dans Admin Console, y compris les fonctionnalités énumérées ci-dessus.

   Pour les organisations qui utilisent actuellement Experience Platform, le service _Places_ sera désormais consolidé dans la carte Experience Platform.

* Les cartes produit Collecte de données d’Adobe Experience Platform (anciennement Launch) et Confidentialité continueront d’apparaître séparément des autres fonctionnalités d’Experience Platform.

Pour plus d’informations sur les nouvelles fonctionnalités, consultez leurs pages respectives sur Experience League :

* [Collecte de données](https://experienceleague.adobe.com/docs/analytics/analyze/reports-analytics/reporting-interface/overview-data-collection.html?lang=fr)
* [Places](https://experienceleague.adobe.com/docs/places/using/home.html?lang=fr)
* [Assurance](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/app-implementation/assurance.html?lang=fr)
* [Espace de noms d’identité](https://experienceleague.adobe.com/docs/experience-platform/identity/home.html?lang=fr)
* [Sandbox](https://experienceleague.adobe.com/docs/experience-platform/sandbox/home.html?lang=fr)
* [Modèle de données d’expérience](https://experienceleague.adobe.com/docs/experience-platform/xdm/home.html?lang=fr)
* [Schémas](https://experienceleague.adobe.com/docs/experience-platform/xdm/schema/composition.html?lang=fr)
* [Flux de données](https://experienceleague.adobe.com/docs/experience-platform/edge/datastreams/overview.html?lang=fr)
* [Visitor ID (Identifiant visiteur)](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services.html?lang=fr#section_3C9F6DF37C654D939625BB4D485E4354)
* [Confidentialité](https://experienceleague.adobe.com/docs/experience-platform/privacy/home.html?lang=fr)

### Mise à jour des fonctionnalités

Fonctionnalité publiée : le **11 juillet 2022**

| Fonctionnalité | Description |
| ------- | ------- |
| Widget unifié - Accueil/Accès rapide | **Naviguez plus rapidement :** vous pouvez maintenant personnaliser davantage votre expérience personnelle et choisir les applications du bout des doigts. Utilisez la nouvelle fonctionnalité d’épinglage pour sélectionner les applications qui apparaissent au premier plan et au centre sur votre [!UICONTROL Accès rapide]. <br>**Restez informé grâce à l’épinglage intelligent :** vos nouvelles applications sont désormais plus faciles à trouver. Les applications nouvellement attribuées arborent un badge _Nouveau_ et sont automatiquement épinglées dans [!UICONTROL Accès rapide]. |

{style=&quot;table-layout:auto&quot;}

**Plus de ressources d’aide sur Administration et [!DNL Experience Cloud Central UI Components]**

* [Notes de mise à jour](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=fr) pour les composants de l’interface utilisateur centrale dʼExperience Cloud
* [Gestion des utilisateurs et des produits](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) pour Experience Cloud (administration)
* [Notes de mise à jour](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=fr) du service Places
* Documentation produit pour les fonctionnalités [Personnes : attributs du client et bibliothèque d’audiences](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=fr)
* [Recherche unifiée dʼobjets et dʼentités](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=fr)

## ![Icône](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

Dernières informations de mise à jour et nouvelle documentation pour [!DNL Experience Platform] et le [!UICONTROL SDK mobile] :

Publication prévue le : **27 juillet 2022**

* [Notes de mise à jour d’Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=fr)

### Nouveaux tutoriels et cours sur [!DNL Experience Platform] {#tutorials-platform}

Nouveaux tutoriels vidéo, articles et cours publiés pour [!DNL Experience Platform].

| Publié | Nom | Type | Description | Application |
| -----------| ---------- | ---------- | ---------- |---------- |
| Juillet 2022 | [Surveiller le transfert d’événement](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/monitor.html?lang=fr) | Vidéo | Découvrez comment surveiller le transfert d’événement dans l’interface de collecte de données. | Collecte de données |
| Juillet 2022 | [Surveillance de l’ingestion des données](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-dashboard.html?lang=fr) | Vidéo | Découvrez comment surveiller et suivre les données qui sont ingérées dans Adobe Experience Platform en utilisant le tableau de bord de surveillance. | Collecte de données |
| Juillet 2022 | [Importation de données dʼexemple vers Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/import-sample-data.html?lang=fr) | Article | Découvrez comment configurer un environnement sandbox Experience Platform avec des données d’exemple. À l’aide d’une collection Postman, vous pouvez créer des groupes de champs, des schémas, des jeux de données, puis importer des données d’exemple dans Experience Platform. | Experience Platform |
| Juillet 2022 | [Correspondance de segments recevant des données](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-receiving-data.html?lang=fr) | Vidéo | Avec la correspondance de segments, vos partenaires stratégiques peuvent vous partager des données. Dans cette vidéo, découvrez comment approuver et recevoir les données, et où vous pouvez les voir et les ajouter à vos propres segments. | Experience Platform - Segments |
| Juillet 2022 | [Demandez aux experts - Real-Time CDP Connections](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-06-23-22.html?lang=fr) | Événements Experience League LIVE | Dans cette deuxième session en direct d’une série de trois portant sur la collecte de données, nos experts préférés proposent une analyse approfondie de la plateforme RTCDP [!UICONTROL Connections] d’Adobe, où les clients peuvent transférer des événements vers des destinations non Adobes à l’aide d’un système de gestion des balises côté serveur. | Collecte de données |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Consultez les [Notes de mise à jour et journaux des modifications](https://aep-sdks.gitbook.io/docs/release-notes) pour les SDK Adobe Experience Platform Mobile.

## ![Icône](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Publication suivante le : **20 juillet 2022**

Dernière mise à jour : **13 juillet 2022**

* [Notes de mise à jour](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=fr) d’Adobe Analytics
* [Documentation et tutoriels du produit](https://experienceleague.adobe.com/docs/analytics.html?lang=fr) Adobe Analytics

### AppMeasurement {#appm}

Version : **2.22.4**

* [Notes de mise à jour d’AppMeasurement pour JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=fr)

### Nouveaux tutoriels et cours sur [!DNL Analytics] {#tutorials-analytics}

Nouveaux tutoriels vidéo, articles et cours publiés pour Adobe Analytics.

| Publié | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Juillet 2022 | [Améliorations des flux 2022](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-improvements.html?lang=fr) | Vidéo | Découvrez quelques-unes des principales améliorations apportées à la visualisation des [!UICONTROL flux]. Les améliorations apportées sont les suivantes : possibilité de configurer le début ou la fin du chemin qui vous intéresse, filtrage d’une colonne pour inclure ou exclure un élément spécifique et paramètres avancés préconfigurables. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Dernière mise à jour : **12 juillet 2022**

* [Notes de mise à jour](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=fr) de Customer Journey Analytics
* [Documentation et tutoriels du produit](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=fr) Customer Journey Analytics

### Nouveaux tutoriels et cours sur Customer Journey Analytics {#tutorials-cja}

Nouveaux tutoriels, vidéos ou cours publiés pour CJA.

| Publié | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Juillet 2022 | [Configurer le panneau des éléments suivants et précédents](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/panels/configure-next-previous-item-panel.html?lang=fr) | Vidéo | Découvrez comment configurer le panneau des éléments suivants et précédents dans [!DNL Customer Journey Analytics]. Ce panneau génère des tableaux et des visualisations pour identifier l’élément suivant ou précédent pour une valeur de dimension spécifique. |
| Juillet 2022 | [Créer une annotation](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/annotations/create-an-annotation.html?lang=fr) | Vidéo | Découvrez comment créer une annotation dans vos projets [!DNL Customer Journey Analytics] lors d’événements comme les lancements de campagne, les problèmes de données et les jours fériés. Cette fonction informe vos utilisateurs des variances de mesures sur ces dates ou périodes. |
| Juillet 2022 | [Créer un filtre rapide](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/filters/create-a-quick-filter.html?lang=fr) | Vidéo | Créez des filtres rapides directement dans vos projets [!DNL Customer Journey Analytics] et contournez la complexité du créateur de filtres complet. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Dernière mise à jour : **23 mars 2022**

* [!DNL Streaming Media Analytics] : [notes de mise à jour](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=fr)
* [Documentation et tutoriels du produit](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=fr) [!DNL Streaming Media Analytics]

## ![Icône](/assets/audience-manager.png) Audience Manager {#aam}

Correctifs et améliorations d’Audience Manager :

| Amélioration | Description |
| -----------| ---------- |  
| Programme de validation des sources de données cibles appartenant à d’autres sociétés | Audience Manager a publié une amélioration du [processus dʼintégration des données par lots](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=fr). Pour éviter lʼintégration accidentelle de fichiers et de données dans des sources de données cibles appartenant à dʼautres partenaires, Audience Manager a ajouté une exigence de mappage entre lʼID du partenaire (PID) et les sources de données (DPID) appartenant à dʼautres partenaires. <ul><li>Consultez également le champ __DPID_TARGET_DATA_OWNER_ dans la section [Exigences en matière de nom et de taille de fichier dʼAmazon S3 pour les fichiers de données entrants](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=fr#name-elements).</li><li>Pour plus dʼinformations sur la nouvelle exigence de mappage et comment demander un nouveau mappage, il est recommandé que les consultants internes Adobe et lʼassistance clientèle lisent la section [Gérer lʼaccès à lʼintégration pour les données de deuxième niveau](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=fr).</li><li>Il nʼest _pas_ nécessaire de demander un mappage pour les relations de partage de données existantes. De même, le mappage nʼest _pas_ requis lors de lʼintégration de données dans des sources de données cibles appartenant à votre PID.</li></ul> |

{style=&quot;table-layout:auto&quot;}

Pour obtenir des ressources d’aide autonome, consultez la page [Documentation et tutoriels dʼAudience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=fr) sur Experience League.

## ![Icône](/assets/aem.png) Adobe Experience Manager {#aem}

Nouveaux correctifs, fonctionnalités et mises à jour dans Experience Manager. Adobe recommande aux clients avec des déploiements sur site de déployer le dernier correctif pour garantir des performances et une stabilité optimales et renforcer la sécurité.

Adobe recommande de consulter la page des [mises à jour et feuilles de route Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=fr) afin de se tenir au courant des informations de mise à jour.

### Vidéos de mise à jour des produits

* [Vidéo de présentation de la version de juin 2022](https://video.tv.adobe.com/v/344308/?quality=12) pour un résumé de la version 2022.6.

Vidéos de mise à jour des anciens produits :

* [Vidéo de présentation de la version de mai 2022](https://video.tv.adobe.com/v/343321/?quality=12) pour un résumé des fonctionnalités ajoutées dans la version 2022.5.0 (mai 2022).
* [Vidéo de présentation de la version d’avril 2022](https://video.tv.adobe.com/v/342612?quality=12)
* [Vidéo de présentation de la version de mars 2022](https://video.tv.adobe.com/v/341465)
* [Vidéo de présentation de la version de janvier 2022](https://video.tv.adobe.com/v/340120)
* [Vidéo de présentation de la version de décembre 2021](https://video.tv.adobe.com/v/339278)
* [Vidéo de présentation de la version d’octobre 2021](https://video.tv.adobe.com/v/338253)
* [Vidéo de présentation de la version de septembre 2021](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Sites] as a [!DNL Cloud Service]

Nouvelles fonctionnalités de [!DNL Sites] :

* Une [nouvelle interface utilisateur](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console.html?lang=fr) est désormais disponible pour que les administrateurs et les auteurs de contenu puissent gérer efficacement (publier, annuler la publication, copier et déplacer), rechercher/filtrer et créer des fragments de contenu pour des cas d’utilisation headless.

* Le nouveau [Composant de la table des matières](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/components/tableofcontents.html?lang=fr) fonctionne non seulement avec les [!UICONTROL Composants principaux], mais aussi avec tous les composants, générant automatiquement la table des matières sur les pages de contenu. Et, puisqu’il est rendu côté serveur et entièrement mis en cache par le dispatcher, il est également efficace pour les chargements.

### Experience Manager [!DNL Assets] as a [!DNL Cloud Service]

Nouvelles fonctionnalités de [!DNL Assets] :

* Experience Manager [!DNL Assets] utilise désormais les fonctionnalités d’Adobe Sensei AI pour [faire la distinction entre les couleurs d’une image et appliquer automatiquement les différences sous la forme de balises lors de l’ingestion](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=fr). Ces balises permettent d’améliorer l’expérience de recherche en fonction de la composition des couleurs de l’image. Vous pouvez configurer le nombre de couleurs associées à une image dans une plage comprise entre 1 et 40 afin de pouvoir rechercher ultérieurement des images en fonction de ces couleurs.

### Experience Manager Forms as a Cloud Service

Nouvelles fonctionnalités de [!DNL Forms] :

* [Intégrer les [!UICONTROL formulaires adaptatifs] à Microsoft® Power Automate](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/forms-microsoft-power-automate-integration.html?lang=fr). Vous pouvez désormais configurer un formulaire adaptatif pour qu’il exécute un flux de cloud Microsoft® Power Automate lors de l’envoi. Le formulaire adaptatif configuré envoie les données capturées, les pièces jointes et le document d’enregistrement au flux de cloud Power Automate pour traitement. Il vous permet de créer une expérience de capture de données personnalisée tout en tirant parti de la puissance de Microsoft® Power Automate pour élaborer des logiques commerciales autour des données capturées et automatiser les flux client.

**Assistant de création d’un formulaire adaptatif**. Vous pouvez utiliser un assistant convivial destiné aux utilisateurs professionnels pour créer rapidement un [!UICONTROL formulaire adaptatif]. Cet assistant fournit une navigation rapide dans les onglets pour sélectionner facilement un modèle, un style, des champs et des options d’envoi préconfigurés afin de créer un formulaire adaptatif.

### Experience Manager as a Cloud Service Foundation

Nouveautés :

Comme indiqué dans les notes de mise à jour de mai (2022.5.0), l’option « Ajouter une arborescence » sous l’onglet Distribuer de l’écran d’administration de l’agent de réplication a été supprimée. Les modules avec une arborescence de contenu doivent plutôt être répliqués à l’aide de Gérer la publication ou du flux Publier l’arborescence de contenu.

### [!DNL Cloud Manager]

Nouveautés :

* Les utilisateurs de [!DNL Cloud Manager] ont désormais accès à des tutoriels vidéo utiles à partir de la carte [!UICONTROL Bienvenue] de la page de destination, et ce, à tout moment.

* La fenêtre contextuelle de l’onglet [Restaurer le contenu](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/backup.html?lang=fr) de la page Détails des environnements affiche désormais une liste pratique des commandes git permettant à l’utilisateur d’afficher les modifications localement.

### Nouveaux cours et tutoriels sur Experience Manager {#tutorials-aem}

Nouveaux tutoriels, vidéos et cours publiés le mois dernier.

| Publié | Nom | Type | Description | Applications |
| -----------| ---------- | ---------- | ---------- |---------- |
| Juillet 2022 | [Tirer le meilleur parti de la gestion des workflows d’entreprise](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/workflow.html?lang=fr) | Vidéo | Découvrez les avantages de l’utilisation de workflows pour la gestion de vos ressources et apprenez à les créer rapidement. | AEM - Gestion des workflows dans Adobe Experience Manager |
| Juillet 2022 | [Proposer des expériences headless avec Adobe Experience Manager](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=fr) | Vidéo | Découvrez la gestion de l’expérience headless en utilisant les dernières améliorations du [!UICONTROL Fragment de contenu] d’Experience Manager et la nouvelle API GraphQL pour la diffusion de contenu headless. | Experience Manager [!DNL Sites] |
| Juillet 2022 | [Mettez les métadonnées au service de votre entreprise dans Adobe Experience Manager Assets](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/metadata.html?lang=fr) | Vidéo | Découvrez comment tirer le meilleur parti de vos métadonnées dans AEM Assets en réduisant la charge de travail pour baliser les ressources et en facilitant leur consultation. | Experience Manager [!DNL Assets] |
| Juillet 2022 | [Application iOS](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/ios-swiftui-app.html?lang=fr) | Vidéo | Les exemples d’applications constituent un excellent moyen d’explorer les fonctionnalités headless d’Adobe Experience Manager. Cette application iOS montre comment interroger du contenu en utilisant l’[!UICONTROL API GraphQL] d’AEM à l’aide de requêtes persistantes. | Experience Manager [!DNL Assets], [!DNL Sites] |
| Juillet 2022 | [Application Android™](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/android-app.html?lang=fr) | Vidéo | Cette application Android™ montre comment interroger du contenu en utilisant l’[!UICONTROL API GraphQL] d’AEM. | Experience Manager [!DNL Assets], [!DNL Sites] |
| Juillet 2022 | [Configuration d’OSGi pour Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/deploying/configuring-osgi.html?lang=fr) | Vidéo | Découvrez comment configurer OSGI pour AEM CS. Par exemple, découvrez la gestion des lots OSGi et la gestion des paramètres de configuration des composants OSGi par le biais de fichiers de configuration qui font partie d’un projet de code AEM. | AEM as a Cloud Service |
| Juillet 2022 | [Remplacer les propriétés du modèle de données de formulaire](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/override-fdm-values.html?lang=fr) | Vidéo | Découvrez comment remplacer les propriétés du modèle de données de formulaire pour faciliter le test d’un modèle de données de formulaire avec différents points de terminaison. | AEM [!DNL Forms] |

{style=&quot;table-layout:auto&quot;}

### Informations de mise à jour d’Experience Manager

Toutes les notes de mise à jour d’Experience Manager sont conservées dans les pages suivantes :

* [Informations de mise à jour d’Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=fr)
* [Notes de mise à jour de Cloud Manager d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=fr)
* [Notes de mise à jour du service de conversion automatisée de formulaires](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=fr)
* [Notes de mise à jour du Service Pack 6.5 d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=fr)
* [Notes de mise à jour du pack de correctifs cumulatifs 6.4 d’Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=fr)
* [Notes de mise à jour d’Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=fr)
* [Notes de mise à jour d’Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=fr)
* [Notes de mise à jour de l’appli de bureau Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=fr)
* [Notes de mise à jour d’Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=fr)
* [Notes de mise à jour d’Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=fr)
* [Notes de mise à jour de Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=fr)

### Autres ressources dʼaide pour Experience Manager

* [Guides relatifs à Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=fr)
* [Guide de l’utilisateur de Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=fr)
* [Page dʼaccueil de formation et de support pour Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=fr#previous-updates)
* [Versions plus anciennes de la documentation pour Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Page d’accueil de l’aide de Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=fr)
* [Documentation Experience Manager : mises à jour récentes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=fr#aem-as-a-cloud-service)

## ![Icône](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] est une application déployée sur AEM. Il s’agit d’une puissante solution de gestion de contenu par composant (CCMS) de qualité professionnelle qui permet la prise en charge native de DITA dans Adobe Experience Manager, ce qui permet à AEM de gérer la création et la diffusion de contenu basé sur DITA.

En savoir plus sur les [[!DNL Experience Manager Guides]](https://www.adobe.com/fr/products/xml-documentation-for-experience-manager/features.html).

### Ressources supplémentaires

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=fr) - tutoriels sur Experience League
* Formation et assistance pour [[!DNL Experience Manager Guides] ](https://helpx.adobe.com/fr/support/xml-documentation-for-experience-manager.html) - documentation du produit

## ![Icône](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Voir les liens suivants pour consulter les notes de mise à jour dʼAdobe Commerce :

* [Notes de mise à jour d’Adobe Commerce et de Magento Open Source 2.4.x](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Notes de mise à jour de Cloud Suite](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Nouveaux tutoriels et documents Adobe Commerce {#tutorials-commerce}

| Publié | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Juillet 2022 | [Guide de prise en main d’Adobe Commerce](https://experienceleague.adobe.com/docs/commerce-admin/start/guide-overview.html?lang=fr) | Documentation du produit | Guide destiné aux commerçants et aux administrateurs système qui découvrent Adobe Commerce et Magento Open Source. Obtenez une vue d’ensemble de la plateforme depuis leur perspective et bénéficiez d’informations détaillées sur les fonctionnalités de base qui assurent le bon fonctionnement d’une boutique. |
| Juillet 2022 | [Guide d’utilisation de Page Builder](https://experienceleague.adobe.com/docs/commerce-admin/page-builder/guide-overview.html?lang=fr) | Documentation du produit | Découvrez les fonctionnalités de Page Builder, notamment une présentation en trois parties de la création de composants de contenu de base. Ce guide est destiné aux administrateurs. Ce guide sʼadresse aux utilisateurs déjà familiers avec la configuration et des fonctionnalités de base d’Adobe Commerce. |
| Juillet 2022 | [Guide B2B pour Adobe Commerce](https://experienceleague.adobe.com/docs/commerce-admin/b2b/guide-overview.html?lang=fr) | Guide de l’administrateur | Obtenez des informations détaillées sur l’installation et l’activation de ce module, notamment sur la configuration et la gestion de ses fonctionnalités. |
| Juillet 2022 | [Tutoriels B2B pour Adobe Commerce](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/b2b/company-accounts.html?lang=fr) | Vidéo (multiple) | En savoir plus sur la page [!UICONTROL Entreprises] dans Adobe Commerce. Vous pouvez gérer les comptes de votre entreprise ainsi que les demandes d’approbation en attente qui apparaissent en haut de la liste. |
| Juillet 2022 | [Utilisation de l’outil de correctifs de la qualité](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/quality-patch-tool.html?lang=fr) | Vidéo | En savoir plus sur l’[!UICONTROL Outil de correctifs de la qualité], qui est un outil de ligne de commande qui fournit des correctifs de qualité pour Adobe Commerce et Magento Open Source. |
| Juillet 2022 | [Tableau de bord de l’outil d’analyse à l’échelle du site](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/site-wide-analysis-tool.html?lang=fr) | Vidéo | En savoir plus sur l’outil d’analyse à l’échelle du site. Cette fonctionnalité est un outil en libre-service proactif et un référentiel central qui comprend des informations détaillées sur le système et des recommandations afin d garantir la sécurité et l’opérabilité de votre installation Adobe Commerce. |
| Juillet 2022 | [Utilisation des services de paiement](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/payment-services.html?lang=fr) | Vidéo | Découvrez comment utiliser les [!UICONTROL Services de paiement] afin de réduire les frais généraux d’exploitation et d’augmenter les revenus. |
| Juillet 2022 | [Gérer l’état de la commande](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/orders/order-status.html?lang=fr) | Vidéo | Découvrez comment vérifier le statut et les détails d’une commande, et apprenez à modifier son statut, si nécessaire. |
| Juillet 2022 | [Outils marketing](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/marketing/catalog-price-rules.html?lang=fr) | Vidéo (multiple) | Découvrez comment créer une règle de prix de catalogue et des règles de prix de panier, gérer les règles de produits associés, effectuer une recherche en direct, etc. |
| Juillet 2022 | [Innovations en matière de personnalisation du contenu offrant une valeur ajoutée à votre entreprise](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/content-perosonalization.html?lang=fr) | Vidéo | Consultez les présentations de Skill Builder et découvrez les innovations récentes de la solution de contenu d’Adobe qui vous aident à démocratiser la création de contenu, à simplifier la diffusion omnicanal et à développer la personnalisation. |
| Juillet 2022 | [Gestion de catalogues](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/catalog/seo-url-rewrites.html?lang=fr) | Vidéos | En savoir plus sur la gestion de catalogues dans Adobe Commerce. Créer une catégorie, gérer les produits d’une catégorie, gérer les stocks, et bien plus encore. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/target.png) [!DNL Adobe Target] {#target}

Dernière mise à jour : **30 juin 2022**

* Pour obtenir des informations sur la version préliminaire, consultez la section [Version préliminaire d’Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=fr).
* Pour obtenir des informations à jour, consultez la page [Notes de mise à jour d’Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=fr).

### Nouveaux cours et tutoriels d’Adobe Target {#tutorials-target}

| Publié | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Juillet 2022 | [Création d’audiences](https://experienceleague.adobe.com/docs/target-learn/tutorials/audiences/create-audiences.html?lang=fr) | Vidéo | Découvrez comment créer et enregistrer des audiences personnalisées dans [!DNL Target] pour les utiliser dans vos activités. |
| Juillet 2022 | [Personnaliser et automatiser avec Adobe Target](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/data-and-insights/2022/personalize.html?lang=fr) | Vidéo | Découvrez les concepts de base de l’automatisation et de l’optimisation des fonctionnalités d’Adobe Target à l’aide du [!UICONTROL Ciblage automatique] et des [!UICONTROL Personnalisations automatiques]. |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign offre un moyen intuitif et automatisé d’envoyer des messages individualisés sur des canaux marketing en ligne et hors ligne. Vous pouvez maintenant anticiper ce que souhaitent vos clients à l’aide d’expériences déterminées par leurs habitudes et leurs préférences.

### Dernières mises à jour d’Adobe Campaign

* [Mise à jour de Campaign v7.3](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=fr)
* [Mise à jour de juin du Panneau de Contrôle](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=fr)
* [Tutoriels et cours](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=fr#tutorials-campaign) sur Experience League

### Nouveaux tutoriels et cours sur [!DNL Campaign] {#tutorials-campaign}

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Campaign.

| Publié | Nom | Type | Description | Applications |
| -----------| ---------- | ---------- | ---------- |---------- |
| Juillet 2022 | [Panneau de contrôle pour les modèles d’hébergement hybrides](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-for-hybrid-hosting-models.html?lang=fr) | Vidéo | Découvrez comment activer le panneau de contrôle pour les modèles d’hébergement hybrides Adobe Campaign, accéder au panneau de contrôle et déverrouiller les fonctionnalités clés. | Panneau de contrôle |
| Juillet 2022 | [Surveiller les débits et la latence](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-throughputs-and-latency.html?lang=fr) | Vidéo | Découvrez comment surveiller les débits de diffusion et les latences des messages transactionnels de votre instance Campaign. | Panneau de contrôle |
| Juillet 2022 | [Surveiller les workflows pour optimiser l’utilisation des ressources](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-workflows.html?lang=fr) | Vidéo | Découvrez comment surveiller l’utilisation de l’espace de stockage temporaire de vos workflows et où configurer les paramètres de workflows pour éviter des problèmes liés aux bases de données ou aux workflows sur votre instance. | Panneau de contrôle |
| Juillet 2022 | [Développement et personnalisation de modèles de données dans Adobe Campaign Classic](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/data-models.html?lang=fr) | Vidéo (événements Skill Builder) | Rejoignez cette session avec notre formateur Campaign pour apprendre à développer un schéma de données à l’intérieur d’un modèle de données dans Campaign Classic. | Campaign Classic v7 |
| Juillet 2022 | [Bonnes pratiques et stratégies de diffusion efficaces](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/deliverability-best-practices.html?lang=fr) | Vidéo | Découvrez comment rendre moins chronophage la planification et la production de vos campagnes par e-mail. | Campaign Classic v7 |
| Juillet 2022 | [Améliorez votre marketing cross-canal avec Adobe Campaign Classic](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/cross-channel.html?lang=fr) | Vidéo | Regardez ce webinaire détaillé consacré aux workflows, à l’automatisation, à la personnalisation et à la mesure pour les clients Adobe Campaign Classic. | Campaign Classic v7 |
| Juillet 2022 | [Conseils de pro pour gagner du temps !](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/tips.html?lang=fr) | Vidéo | Commencez votre nouvelle année avec les conseils et astuces d’un pro d’Adobe Campaign ! Découvrez comment optimiser la création et le lancement de vos campagnes et comment offrir des expériences cross-canal plus significatives et personnalisées. | Campaign Classic v7 |
| Juillet 2022 | [Intégrations d’Adobe Campaign à un écosystème marketing](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/integrations.html?lang=fr) | Vidéo | Découvrez les intégrations d’Adobe Campaign à un écosystème marketing. Les solutions marketing cross-canal telles qu’Adobe Campaign ne doivent pas être isolées des autres technologies ou équipes. Ne laissez pas des systèmes disparates entraver la compréhension d’un client et perturber les stratégies cross-canal. | Campaign Classic v7 |
| Juillet 2022 | [Client Adobe Campaign Standard - Microsoft](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/microsoft.html?lang=fr) | Vidéo | L’équipe marketing de Microsoft® vous explique comment elle utilise Adobe Campaign Standard, son architecture et ses principes directeurs, ainsi que ses bonnes pratiques. | Campaign Standard |
| Juillet 2022 | [Client Adobe Campaign - Center Parcs](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/center-parcs.html?lang=fr) | Vidéo | Les clients d’Adobe Campaign vous expliquent comment ils surmontent les défis, s’adaptent à la nouvelle norme, deviennent plus efficaces dans la gestion de leurs campagnes et génèrent une valeur ajoutée significative grâce à Adobe Campaign. | Campaign Classic v7 |
| Juillet 2022 | [Adobe Campaign Classic v7 et v8](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/classic-v7-vs-v8.html?lang=fr) | Vidéo | Nos responsables produits vos présentent les dernières mises à jour et vous expliquent les différences entre la v7 et la v8. | Campaign Classic v7, Campaign v8 |
| Juillet 2022 | [Keynote - Tendances et innovation du parcours client en B2B et B2C](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/keynote.html?lang=fr) | Vidéo | Découvrez les dernières tendances de la gestion des parcours client en B2B et B2C. Découvrez les dernières innovations en matière d’applications de parcours clés et au sein d’Adobe Experience Cloud et Platform. | Marketo, Campaign Classic v7, Campaign v8 |
| Juillet 2022 | [Conseils et astuces pour Adobe Campaign Standard](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/tips-and-tricks.html?lang=fr) | Vidéo | Connectez-vous à votre instance Adobe Campaign Standard et découvrez les bonnes pratiques relatives au ciblage, à la personnalisation et à la lassitude marketing pour une meilleure utilisation d’ACS. | Campaign Standard |
| Juillet 2022 | [Équipe, compétences et conception organisationnelle requises pour prendre en charge le marketing cross-canal](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/team-skills-org-design.html?lang=fr) | Vidéo | Apprenez à vous donner les moyens de vous engager, à votre rythme et en toute liberté. Découvrez l’importance d’une organisation marketing qui prend en charge la planification, l’exécution et la mesure. | Campaign Classic v7, Campaign v8, Campaign Standard |

{style=&quot;table-layout:auto&quot;}

### Ressources d’aide pour Campaign

* Adobe Campaign v8 : [Documentation](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=fr) - [Guides d’implémentation](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=fr)
* Adobe Campaign Standard : [Documentation de Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=fr) - [Calendrier des versions](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=fr)
* Adobe Campaign Classic : [Documentation de Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=fr) - [Tutoriels vidéo](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=fr)
* Panneau de contrôle d’Adobe Campaign : [Documentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en) - Tutoriels vidéo pour [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=fr) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=fr)

## ![Icône](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Journey Optimizer vous permet de gérer des campagnes omnicanales planifiées et des moments de contact individuel pour des millions de clients à partir d’une seule application. L’ensemble du parcours est optimisé grâce à une prise de décision et des informations intelligentes.

### Dernières versions de produit pour Journey Optimizer

Découvrez les dernières fonctionnalités, améliorations et correctifs dans les [Notes de mise à jour de Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=fr).

### Nouveaux tutoriels et cours relatifs à Journey Optimizer {#tutorials-ajo}

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Journey Optimizer.

| Publié | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| Juillet 2022 | [Configurer les règles de fréquence des messages](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/channel-configuration/configure-frequency-rules.html?lang=fr) | Vidéo | Découvrez comment créer, activer, tester et générer des rapports sur les règles de fréquence. Découvrez comment déterminer les règles de fréquence qui seront héritées pour un message. |
| Juillet 2022 | [Configurer, créer et diffuser des messages SMS](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/configure-author-and-deliver-sms-messages.html?lang=fr) | Vidéo | Découvrez comment configurer, créer et inclure des messages SMS dans vos parcours clients. |
| Juillet 2022 | [Prise en charge des mots-clés entrants pour les SMS](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/inbound-keyword-support-for-sms.html?lang=fr) | Vidéo | Découvrez comment fonctionne la prise en charge native des mots-clés entrants (démarrage, arrêt, redémarrage) pour les SMS. |

{style=&quot;table-layout:auto&quot;}

### Ressources supplémentaires pour [!DNL Journey Optimizer]

* [Documentation Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=fr) - [Vidéos pratiques](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=fr)
* [Documentation de la gestion des décisions](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Vidéos pratiques](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=fr)

## ![Icône](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Utilisez Experience Platform pour orchestrer le parcours dʼun client à lʼéchelle des canaux dʼexpérience, en anticipant intelligemment les besoins de chacun en temps réel.

### Dernières mises à jour du produit [!DNL Journey Orchestration]

Découvrez les dernières fonctionnalités, améliorations et correctifs dans les Notes de mise à jour de [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=fr).

#### Ressources supplémentaires pour [!DNL Journey Orchestration]

* [Documentation de Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=fr) - [Notes de mise à jour](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Vidéos pratiques](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=fr) - [Dernières mises à jour de la documentation](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=fr)

## ![Icône](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] est une application complète pour la gestion des leads et les spécialistes du marketing B2B qui cherchent à transformer les expériences client en s’engageant à chaque étape de parcours d’achat complexes.

### Mises à jour de Core Marketo Engage

Consultez la page [calendrier des versions](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=fr) de [!DNL Marketo Engage] pour consulter les informations les plus récentes sur le calendrier des versions et les notes de mise à jour.

### Nouveaux tutoriels et cours sur Marketo {#tutorials-marketo}

Nouveaux tutoriels, vidéos et cours publiés pour Adobe Marketo.

| Publié | Nom | Type | Description |
| -----------| ---------- | ---------- | ---------- |
| 27 juillet 2022 | [Tutoriels sur Marketo Engage](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) | Vidéos | Visitez le [accueil du tutoriel Marketo Engage](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) sur Experience League pour tous les tutoriels anciens et nouveaux. |
| Juillet 2022 | [Expériences B2B avec Marketo Engage et Adobe Experience Cloud](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-experiences.html?lang=fr) | Vidéo | Découvrez les intégrations entre Marketo Engage et l’application Adobe Experience Cloud, ainsi que les problèmes qui seront résolus. | Marketo Engage |
| Juillet 2022 | [Better together - Adobe Marketo Engage et Real-Time CDP](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-campaigns.html?lang=fr) | Vidéo | Découvrez comment orchestrer des campagnes B2B avec Marketo Engage et RT-CDP (édition B2B) et quels en sont les principaux cas d’utilisation et avantages. | Marketo, Real-time Customer Data Platform |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] est une application de gestion du travail unifiée qui permet de partager des idées, créer du contenu, gérer des processus complexes et donner le meilleur de soi-même.

**Accueil du tutoriel Workfront**

**27 juillet 2022**: Visitez Workfront en découvrant [accueil du tutoriel sur Experience League](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/home.html?lang=en) pour tous les articles et vidéos de formation et de tutoriel.

Consultez la page versions de [[!DNL Workfront] ](https://one.workfront.com/s/product-releases) pour obtenir un récapitulatif des dernières informations relatives à lʼensemble des produits.

## ![Icône](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Notes de mise à jour dʼ[!DNL Adobe Advertising Cloud].

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
* [Nouvelles fonctionnalités de  [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Nouvelles fonctionnalités de  [!DNL Advertising Cloud Search]](#adcloud-search)
<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

### Nouvelles fonctionnalités de [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Dernière mise à jour : **27 juillet 2022**

| Fonctionnalité | Description |
| ------- | ----------- |
| [!UICONTROL Inventaire] | (Version du 27 juillet) [!UICONTROL Informations sur les enchères] est un nouvel outil de dépannage qui vous permet d’analyser la composition des transactions pour les transactions privées garanties et non garanties. Grâce aux visualisations de données, cet outil affiche la tendance et les proportions relatives des valeurs reçues pour les attributs d’enchères clés au cours d’une période donnée. |

{style=&quot;table-layout:auto&quot;}

### Nouvelles fonctionnalités de [!DNL Advertising Cloud Search] {#adcloud-search}

Dernière mise à jour : **27 juillet 2022**

| Fonctionnalité | Description |
| ------- | ----------- |
| [!UICONTROL Opérations] | (Fonctionnalité bêta d’opt-in pour tous les annonceurs ; (version du 16 juillet) Vous pouvez désormais créer et gérer des [!DNL Google Ads] performances max des campagnes, notamment la création manuelle de groupes de ressources et le chargement de ressources. Liens vers [!DNL Google Merchant Center] les flux de produit ne sont pas pris en charge.<br><br>Une fois que vous avez souscrit à la version bêta, vous pouvez créer des campagnes avec le [!UICONTROL Type de campagne] &quot;[!UICONTROL Max. performances]&quot; et de configurer des groupes de ressources dans les paramètres de campagne. Vous pouvez également afficher vos campagnes max de performances existantes, avec des données de performances au format tableau et graphique de tendances, au format [!UICONTROL Campagnes] vue. Les données de performances au niveau de la campagne sont également disponibles dans les rapports et dans Adobe Analytics (pour les annonceurs qui disposent d’un [!DNL Analytics] intégration).<br><br>Pour souscrire à la version bêta, contactez votre [!DNL Adobe] l&#39;équipe du compte. |
|  | [!DNL Google Ads] ne fournit plus de données de performances au niveau des annonces pour les campagnes d’achat standard, les annonces de recherche dynamique ou les emplacements. |
| [!UICONTROL Campagnes], [!DNL Advanced Campaign Management], [!UICONTROL Rapports] | (Version du 16 juillet) ([!DNL Google Ads] et [!DNL Microsoft Advertising] (campagnes) La prise en charge suivante est désormais disponible pour les annonces responsives sur le Réseau de Recherche :<ul><li>Le [!UICONTROL Publicités] affiche maintenant des aperçus des annonces responsives sur le Réseau de Recherche.</li><li> (Depuis le 20 juin) Vous pouvez désormais créer des variations d’annonces dynamiques de recherche réactive à l’aide d’un modèle d’annonces spécifiques au moteur de recherche, en fonction du contenu de votre inventaire, à partir de [!UICONTROL Campagnes] > [!UICONTROL Avancé (ACM)].</li><li>Le [!UICONTROL Rapport de variation des publicités] inclut deux nouvelles colonnes personnalisées : &quot;[!UICONTROL Titre créatif],&quot; qui est une liste séparée par des virgules des lignes de titre de la publicité, et &quot;[!UICONTROL Descriptions],&quot; qui est une liste séparée par des virgules des lignes de description de la publicité.</li></ul> |

{style=&quot;table-layout:auto&quot;}

## ![Icône](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nouveaux tutoriels et cours publiés pour Adobe Document Cloud.

| Publié | Nom | Type | Description | Application |
| -----------| ---------- | ---------- | ---------- |---------- |
| Juillet 2022 | [Utilisation du rôle d’approbateur](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/add-an-approver.html?lang=fr) | Vidéo (mise à jour) | Découvrez comment envoyer un document par le biais d’un processus d’approbation. | Adobe Sign |
| Juillet 2022 | [Configurer un formulaire web](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/webform.html?lang=fr) | Vidéo (mise à jour) | Découvrez comment créer un document pouvant être signé électroniquement, directement depuis votre site Web. | Adobe Sign |
| Juillet 2022 | [Utilisation du rôle de délégué](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=fr) | Vidéo (mise à jour) | Description | Adobe Sign |
| Juillet 2022 | [Signature électronique d’un document](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/electronically-sign-a-document.html?lang=fr) | Vidéo (mise à jour) | Signer un document qui vous est envoyé est un jeu d’enfant avec Acrobat Sign. | Adobe Sign |
| Juillet 2022 | [Acrobat Sign pour les administrateurs](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/up-and-running-admin.html?lang=fr) | Vidéo (mise à jour) | Découvrez les sept principaux domaines sur lesquels les administrateurs doivent se concentrer pour démarrer rapidement dans Acrobat Sign. | Adobe Sign |
| Juillet 2022 | [Envoyer pour signature dans Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/send-for-signature-with-outlook.html?lang=fr#) | Vidéo (mise à jour) | Découvrez comment rationaliser les workflows de documents en envoyant un document pour signature directement depuis Microsoft® Outlook. | Adobe Sign |
| Juillet 2022 | [Remplir et signer un formulaire dans Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/fill-and-sign-doc-microsoft-outlook.html?lang=fr) | Vidéo (mise à jour) | Découvrez comment rationaliser les workflows de documents en remplissant et signant un formulaire directement depuis Microsoft® Outlook. | Adobe Sign |
| Juillet 2022 | [Créer et gérer des groupes](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-and-manage-groups.html?lang=fr) | Vidéo (mise à jour) | Découvrez comment créer des groupes, ajouter des utilisateurs et modifier les paramètres. | Adobe Sign |
| Juillet 2022 | [Déléguer la signature à quelqu’un d’autre](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/delegate-signing.html?lang=fr) | Vidéo (mise à jour) | Découvrez comment déléguer la signature d’un document à une autre personne. | Adobe Sign |

{style=&quot;table-layout:auto&quot;}

Pour obtenir de l’aide sur Document Cloud, voir :

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=fr)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=fr)
* [Formation et assistance sur Document Cloud](https://helpx.adobe.com/fr/support/document-cloud.html)

## ![Icône](/assets/creative-cloud-24.png) Adobe Creative Cloud abonnement Entreprise {#creative-cloud}

Consultez les [tutoriels Creative Cloud abonnement Enterprise](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=fr) pour obtenir les derniers tutoriels.

## ![Icône](/assets/experience-league.png) Gestion des données client - Voix {#voices}

[Voix pour la gestion des données client](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=fr) est votre destination en tant que leader et spécialiste des pratiques techniques et marketing de gestion des données client. Cette collection de tutoriels est votre guichet unique pour bénéficier de l’avis de vos pairs, trouver de l’inspiration et découvrir les développements dans le domaine du MarTech. Aucune inscription requise, cliquez et regardez, tout simplement.

## ![Icône](/assets/experience-league.png) Plans directeurs de Digital Experience {#blueprints}

[Les plans directeurs de l’expérience digitale](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=fr) sont des implémentations reproductibles qui vous permettent d’aborder la stratégie et de résoudre rapidement les problèmes établis de l’entreprise. Chaque plan directeur fournit une série d’artefacts expliquant le problème des entreprises à haute valeur ajoutée, les architectures, les étapes d’implémentation, les considérations techniques et les liens vers la documentation pertinente.

[Haut](#events)
