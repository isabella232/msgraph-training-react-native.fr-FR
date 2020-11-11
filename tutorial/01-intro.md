<!-- markdownlint-disable MD002 MD041 -->

Ce didacticiel vous apprend à créer une application REACT native qui utilise l’API Microsoft Graph pour récupérer des informations de calendrier pour un utilisateur.

> [!TIP]
> Si vous préférez télécharger simplement le didacticiel terminé, vous pouvez télécharger ou cloner le [référentiel GitHub](https://github.com/microsoftgraph/msgraph-training-react-native).

## <a name="prerequisites"></a>Conditions préalables

Avant de commencer ce didacticiel, les éléments suivants doivent être installés sur votre ordinateur de développement.

- Au moins l’un des éléments suivants :
  - Kit de développement [Android Studio](https://developer.android.com/studio/) **et** [java](https://jdk.java.net) (requis pour exécuter l’exemple sur Android)
  - [Xcode](https://developer.apple.com/xcode/) (requis pour exécuter l’exemple sur iOS)
- [Node.js](https://nodejs.org)

Vous devez également disposer d’un compte Microsoft personnel disposant d’une boîte aux lettres sur Outlook.com ou d’un compte professionnel ou scolaire Microsoft. Si vous n’avez pas de compte Microsoft, vous disposez de deux options pour obtenir un compte gratuit :

- Vous pouvez vous [inscrire pour obtenir un nouveau compte Microsoft personnel](https://signup.live.com/signup?wa=wsignin1.0&rpsnv=12&ct=1454618383&rver=6.4.6456.0&wp=MBI_SSL_SHARED&wreply=https://mail.live.com/default.aspx&id=64855&cbcxt=mai&bk=1454618383&uiflavor=web&uaid=b213a65b4fdc484382b6622b3ecaa547&mkt=E-US&lc=1033&lic=1).
- Vous pouvez vous [inscrire au programme pour les développeurs office 365](https://developer.microsoft.com/office/dev-program) pour obtenir un abonnement gratuit à Office 365.

> [!NOTE]
> Ce didacticiel a été écrit à l’aide de l’interface CLI native de REACT, qui présente des conditions préalables spécifiques en fonction de votre système d’exploitation et des plateformes cibles. Pour obtenir des instructions sur la configuration de votre ordinateur de développement, voir [REACT Native Getting Started](https://reactnative.dev/docs/environment-setup) . Les versions utilisées pour ce didacticiel sont répertoriées ci-dessous. Les étapes de ce guide peuvent fonctionner avec d’autres versions, mais cela n’a pas été testé.
>
> - Android Studio version 4,1 avec le kit de développement logiciel (SDK) Android 9,0
> - Kit de développement Java version 12.0.2
> - Xcode version 12,1
> - Node.js version 14.15.0

## <a name="feedback"></a>Commentaires

Veuillez fournir des commentaires sur ce didacticiel dans le [référentiel GitHub](https://github.com/microsoftgraph/msgraph-training-react-native).
