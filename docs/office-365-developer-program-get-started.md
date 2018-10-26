---
title: Configuration d’un abonnement Office 365 Développeur
description: Configurez un abonnement Office 365 Développeur pour créer et tester des solutions indépendamment de votre environnement de production.
ms.date: 03/20/2018
ms.openlocfilehash: 58579946320e32d0b076488e28e5a7166f9774bf
ms.sourcegitcommit: b7da765007f295d17f23b7d4a638af760ecd3b96
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/17/2018
ms.locfileid: "25670378"
---
# <a name="set-up-an-office-365-developer-subscription"></a>Configuration d’un abonnement Office 365 Développeur 

Configurez un abonnement Office 365 Développeur pour créer et tester vos solutions indépendamment de votre environnement de production. L’abonnement est un abonnement Office 365 Enterprise E3 Développeur avec 25 licences utilisateur. Il est valable un an et gratuit pour une utilisation à des fins de développement (codage et test de solutions).

> [!NOTE] 
> Pour configurer un abonnement, vous devez d’abord [rejoindre le programme pour les développeurs Office 365](office-365-developer-program.md). Après avoir rejoint le programme, l’option pour configurer un abonnement s’affiche.

## <a name="set-up-your-subscription"></a>Configurer votre abonnement

1. Pour obtenir un abonnement Office 365 Développeur, sur votre page de profil, sous **Besoin d’un abonnement Office 365 à des fins de développement ?**, choisissez **Configurer un abonnement**.

  ![Configuration de l’abonnement](images/4-set-up-subscription.png)

2. Dans la boîte de dialogue **Configurer votre abonnement Développeur**, créez un nom d’utilisateur et un domaine. Ce compte disposera des autorisations d’administrateur général pour l’abonnement. Vous pouvez choisir n’importe quel nom d’utilisateur ou nom de domaine dans la mesure où il n’est pas déjà utilisé. N’utilisez pas d’espaces.

  ![Formulaire de configuration de l’abonnement](images/5-set-up-form.png)

3. Créez et confirmez un mot de passe.

4. Sélectionnez **Configurer**.

5. Si vous êtes invité à prouver que vous n’êtes pas un robot, suivez les instructions, puis choisissez **Vérifier**.

6. Une fois l’abonnement créé, le nom et la date d’expiration de votre abonnement apparaissent sur votre page de profil.

  > [!IMPORTANT]
  > Notez votre nom d’utilisateur et votre mot de passe, car vous en aurez besoin pour accéder à votre abonnement Développeur.

## <a name="configure-the-subscription"></a>Configuration de l’abonnement

1. Sur votre page de profil, choisissez le lien [office.com](https://www.office.com/) et connectez-vous avec votre identifiant utilisateur (par exemple, nomutilisateur@domaine.onmicrosoft.com) et le mot de passe indiqués pour votre abonnement Développeur.

   > [!NOTE] 
   > Ne vous connectez pas à votre abonnement avec vos informations d’identification du programme pour les développeurs.

2. Utilisez le lanceur d’applications pour accéder au [Centre d’administration](https://portal.office.com/adminportal/home#/homepage).

3. Dans la page d’accueil du Centre d’administration, choisissez **Accéder à la configuration**. Vous accéderez à la page **Configuration d’Office 365 Enterprise E3 Développeur**.

4. **Personnalisez votre connexion et votre e-mail**. Vous pouvez connecter votre abonnement à un domaine ou simplement utiliser le sous-domaine existant que vous avez créé. Lorsque vous êtes prêt, sélectionnez **Suivant**.

  ![Page de personnalisation de connexion et d’e-mail](images/8a-set-up-personalize.png)

5. **Ajoutez de nouveaux utilisateurs**. Vous pouvez ajouter des utilisateurs. Il peut s’agir d’utilisateurs fictifs dont vous avez besoin pour des tests ou de réels utilisateurs pour vous aider au développement. Lorsque vous êtes prêt, sélectionnez **Suivant**.
    
  > [!NOTE]
  > Si vous voulez ajouter des utilisateurs en bloc, vous pouvez le faire plus tard. Pour plus d’informations, reportez-vous à l’article [Ajouter des utilisateurs individuellement ou en bloc à Office 365 - Aide de l’administrateur](https://support.office.com/fr-FR/article/add-users-individually-or-in-bulk-to-office-365-admin-help-1970f7d6-03b5-442f-b385-5880b9c256ec).

6. **Attribuez des licences aux utilisateurs qui n’en ont pas**. Accordez une licence à tous les utilisateurs devant utiliser l’abonnement. Lorsque vous êtes prêt, sélectionnez **Suivant**.

7. **Partagez les informations d’identification de connexion**. Pour tous les utilisateurs réels qui accéderont à l’abonnement, vous devez leur communiquer leurs informations d’identification de connexion. Vous pouvez choisir une méthode, par exemple, l’e-mail, le téléchargement ou l’impression. Lorsque vous êtes prêt, sélectionnez **Suivant**.

8. **Installez vos applications Office**. Vous avez la possibilité d’installer des applications Office sur votre ordinateur. Lorsque vous êtes prêt, sélectionnez **Suivant**.

  ![Installation d’applications Office](images/11-install-office-apps.png)

   > [!NOTE] 
   > Lors de vos prochains accès au tableau de bord, connectez-vous avec votre compte *nomutilisateur@domaine*. onmicrosoft.com avant d’accéder au tableau de bord.

9. **Vous avez terminé la configuration**. Vous avez terminé la configuration de votre abonnement. Vous pouvez éventuellement évaluer l’expérience. Lorsque vous êtes prêt, sélectionnez **Accéder au Centre d’administration**.
    
   > [!NOTE] 
   > À ce stade, la région de l’abonnement est définie par défaut sur Amérique du Nord, quel que soit votre pays/région. Vous pouvez malgré tout poursuivre la configuration et utiliser votre abonnement Développeur.

## <a name="provision-office-365-services"></a>Configuration des services Office 365

Les services principaux, tels que SharePoint et Exchange, mettront un certain temps à configurer l’abonnement. Au cours de cette étape, certaines icônes du lanceur d’applications et de la page d’accueil affichent le message suivant : **Configuration (Configuration de l’application toujours en cours)**. Cette opération ne dure pas plus d’une heure.

Une fois la configuration terminée, vous pouvez utiliser le nouvel abonnement Office 365 pour le développement et le test. L’abonnement expire au bout d’un an.

Nous vous recommandons également d’activer les options de publication pour vous assurer que vous avez accès aux dernières fonctionnalités d’Office 365 dès que possible. Pour plus d’informations, reportez-vous à l’article [Configurer les options de publications standard et ciblée dans Office 365](https://support.office.com/en-us/article/set-up-the-standard-or-targeted-release-options-in-office-365-3b3adfa4-1777-4ff0-b606-fb8732101f47?ui=en-US&rs=en-US&ad=US).

## <a name="set-up-a-microsoft-azure-account"></a>Configuration d’un compte Microsoft Azure

Pour certaines solutions Office, vous aurez peut-être besoin d’un compte Microsoft Azure pour créer et tester des éléments à l’aide des services Azure. Pour configurer un compte Azure gratuit, reportez-vous à l’article [Créez votre compte gratuit Azure dès aujourd’hui](https://azure.microsoft.com/fr-FR/free/).

## <a name="leave-the-developer-program"></a>Quitter le programme pour les développeurs

Si vous ne souhaitez plus participer au programme pour les développeurs Office 365, vous pouvez mettre fin à votre abonnement et quitter le programme.

  > [!WARNING]
  > Les étapes suivantes effaceront toutes vos informations de profil. Vous perdrez toutes les données stockées dans votre abonnement développeur qui ne sont pas sauvegardées ailleurs.

1. Inscrivez-vous au programme développeur.

2. Choisissez **Supprimer le profil**.

3. Dans la zone de confirmation **Supprimer le profil**, sélectionnez **Supprimer**.

## <a name="see-also"></a>Voir aussi

- [Rejoindre le programme pour les développeurs Office 365](office-365-developer-program.md)
- [Utilisation de votre abonnement pour créer des solutions Office 365](build-office-365-solutions.md)
- [FAQ du programme pour les développeurs Office 365](office-365-developer-program-faq.md)
