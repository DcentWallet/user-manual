# Questions fréquentes \(FAQ\) Vais-je perdre

## **mes crypto actifs si je perds mon D'CENT Wallet ?**

Nous fournissons une fonction de récupération en cas de défaillance ou de perte du porte-monnaie. Vous pouvez restaurer l'intégralité du portefeuille en utilisant les 24 mots de récupération fournis lors de la création du portefeuille. Pour plus de détails sur la récupération du portefeuille, veuillez cliquer sur le lien suivant [ici](biometric-wallet/recovery.md). 

## **Les actifs cryptographiques sont-ils stockés dans le portefeuille matériel ?**

L'actif cryptographique lui-même n'est pas stocké dans le portefeuille matériel. Les clés privées sont stockées dans le portefeuille matériel, et seules les autres informations relatives au compte sont gérées. Les actifs cryptographiques existent sur le réseau blockchain, et l'application logicielle lit les informations et affiche le solde calculé. 

## **Comment l'actif est-il récupéré lorsque je récupère mon portefeuille ?**

Il utilise 24 mots de récupération pour recréer la clé privée que le dispositif matériel a stockée dans le passé. Le crypto-actif d'origine n'existe pas dans le portefeuille matériel, mais il existe sur la blockchain. La clé récupérée est utilisée pour récupérer les informations des actifs cryptographiques existant. The recovered key is used to retrieve the information of the existing cryptocurrency asset and display it in the mobile app. Click La clé récupérée est utilisée pour récupérer les informations des actifs crypto-monnaies existant et les afficher dans l'application mobile. Cliquez [ici](biometric-wallet/recovery.md) pour apprendre comment récupérer votre portefeuille pour l'authentification par empreinte digitale de type portefeuille froid \(cold wallet\).

## **Le fabricant de D'CENT\(IoTrust\) connaît-il ma clé privée ?** 

La clé privée du porte-monnaie est générée par la puce de sécurité à l'intérieur du portefeuille hardware lorsque le client reçoit le portefeuille hardware et crée le porte-monnaie. 

La clé privée générée à l'intérieur de la puce de sécurité n'est jamais exposée à l'extérieur. Pour cette raison, la clé privée du client est également inconnue du fabricant.

## **Le fabricant \(IoTrust\) exploite-t-il un serveur ? IoTrust dispose-t-il de mes informations personnelles et de ma clé privée ?** 

IoTrust n'exploite pas de serveur qui gère la clé privée et les renseignements personnels du client. Cependant, IoTrust exploite des serveurs de gestion générale, tels que des serveurs de gestion de micrologiciels \(firmware\) et des serveurs de pages d'accueil, qui sont spécifiquement destinés à la gestion des micrologiciels matériels \(hardware firmware\).

## **Quelles sont les crypto-monnaies supportées par D'CENT Biometric Wallet ?**

Vous pouvez consulter la liste complète de toutes les crypto-monnaies prises en charge sur le lien suivant : [https://dcentwallet.com/SupportedCoin](https://dcentwallet.com/SupportedCoin) 

## **Comment puis-je connecter le porte-monnaie biométrique D'CENT à l'application mobile**?

Le porte-monnaie biométrique D'CENT et l'application mobile se connectent principalement par Bluetooth. 

Si vous utilisez Android, veuillez vous référer [ici](biometric-wallet/android-connect/). 

Si vous utilisez un iPhone, veuillez vous référer [ici](biometric-wallet/iphone-connect.md). 

Sur les téléphones Android, vous pouvez également vous connecter via un câble USB. Cliquez [ici](biometric-wallet/android-connect/android-otg.md) pour savoir comment connecter un câble USB avec un téléphone Android.

## **J'ai plusieurs téléphones. Puis-je télécharger l'application mobile D'CENT sur mon autre téléphone pour utiliser mon porte-monnaie biométrique**?

Vous pouvez utiliser le porte-monnaie biométrique avec plusieurs téléphones. Toutefois, vous ne pouvez utiliser le porte-monnaie biométrique qu'avec un téléphone qui est actuellement connecté par Bluetooth. Si vous avez l'intention d'utiliser le porte-monnaie biométrique avec plusieurs téléphones, assurez-vous de désactiver ou de déconnecter la connexion Bluetooth sur le premier téléphone puis d'établir la connexion Bluetooth sur le deuxième téléphone que vous utiliserez.

## **J'ai perdu mon téléphone / je change de téléphone. Puis-je utiliser le porte-monnaie biométrique sur le nouveau téléphone si je télécharge l'application mobile D'CENT**?

Vous pouvez l'utiliser sur un nouveau téléphone. L'application mobile D'CENT \(mode portefeuille biométrique\) ne contient que des informations accessibles au public telles que les comptes de crypto-monnaies \(adresses publiques\) que vous avez ajoutés pour la gestion.  

D'CENT Mobile App fournit seulement une interface utilisateur pour que vous puissiez obtenir une vue des informations sur les comptes. Notez que chaque fois que vous exécutez D'CENT Mobile App, il se synchronise avec le portefeuille biométrique. Pendant la synchronisation, le portefeuille biométrique fournit les informations correctes du compte \(adresse publique\) à l'application mobile D'CENT, s'assurant que ce que vous voyez sur l'application mobile est l'adresse correcte du compte.

## **Pourquoi mon adresse Bitcoin change-t-elle sans cesse**? 

Dans le cas de Bitcoin, il est recommandé de changer l'adresse une fois qu'elle est utilisée pour protéger un certain niveau de confidentialité, car n'importe qui peut voir les détails de la transaction et le solde lorsque l'adresse est exposée. Cela est proposé dans les spécifications BIP-32 et BIP-44 relatives à Bitcoin, et de nombreuses sociétés de porte-monnaie matériels prennent en charge cette fonction.

Dans le cas de D'CENT, nous fournissons une fonction qui montre la liste des adresses utilisées à partir de l'application mobile pour atténuer l'inconfort de ne pas connaître les adresses Bitcoin précédemment utilisées. 

Pour savoir comment vérifier toutes vos adresses publiques BTC, veuillez cliquer sur [ici](coin-send-receive/how-to-use-coin-account/how-to-view-all-the-btc-public-addresses.md). 

## **Puis-je continuer à utiliser mon adresse Bitcoin avant le changement**?

Comme l'application mobile D'CENT conserve un enregistrement des transactions pour toutes les adresses, il n'y a aucun problème pour continuer à utiliser l'adresse bitcoin avant le changement. Pour plus d'informations sur l'adresse bitcoin, veuillez cliquer [ici](coin-send-receive/how-to-use-coin-account/how-to-view-all-the-btc-public-addresses.md).

## **Pourquoi le transfert d'une grande quantité de bitcoins prend-elle du temps**?

Lors du transfert de bitcoins, des fragments \(petites quantités\) de bitcoins provenant de nombreux blocs sont collectés et transmis. Si votre solde de bitcoins est fragmenté en trop de blocs, il faudra beaucoup de temps pour les collecter et les envoyer tous. Ce n'est pas toujours le cas, mais plus le nombre de bitcoins que vous envoyez est important, plus il est probable qu'ils seront collectés à partir de plusieurs blocs, ce qui prendra généralement plus de temps. 

Si une transaction prend trop de temps, cela peut avoir de multiples effets secondaires. Les clients peuvent penser que la fonction Wallet a cessé de fonctionner et cela augmente en fait les chances d'une erreur. Pour cette raison, D'CENT fournit une méthode pour diviser et transmettre plusieurs transactions si le solde du compte bitcoin est fortement fragmenté. Par exemple, une grande somme de demande de transfert de bitcoin unique peut être divisée en 2 transactions, ainsi le client confirmera deux fois.

## Can I cancel a pending transaction?

Due to the nature of blockchain cryptocurrency protocol, a transaction cannot be canceled or changed once the transaction is broadcasted to the blockchain network. The only option you have is to wait for the pending transaction to complete. If a pending transaction is not validated by the blockchain network for an extended period of time, the pending transaction will get dropped.  
  
However, for an Ethereum transaction, a pending transaction can be canceled by sending a new transaction with a small amount of Ethereum and a higher transaction fee to your own Ethereum address. If the newly sent transaction gets validated first before the previous pending transaction, the pending transaction will be canceled. 

## **L'envoi de Ripple \(XRP\) ne fonctionne pas. Quelles sont les précautions à prendre lors d'un envoi vers un Exchange**?

* Après le transfert, le solde restant sur votre compte doit être d'au moins 20 XRP.  
* Balance avant remittance - \( montant remittance + commission\)&gt; = 20 XRP.  
* De nombreux échanges exigent une étiquette de destination \(tag\) lors du dépôt de XRP en échange. Lorsque vous envoyez de l'argent à un échange, veuillez vous assurer que le Tag de destination est requis avant d'envoyer de l'argent. Si vous ne remplissez pas le Tag, votre argent peut être perdu à jamais ou l'échange peut prendre un temps très long pour récupérer votre fonds. 

## **Pourquoi les 20 XRP restants dans mon portefeuille ne sont-ils pas transférables**?

La Politique de Ripple \([Ripple's policy](https://xrpl.org/reserves.html)\) **nécessite un transfert de 20 XRP ou plus** pour convertir une adresse de portefeuille XRP nouvellement crée en une adresse **activée**. Le coût de l'activation de l'adresse est de 20 XRP et elle sera verrouillée sur le compte XRP, ce qui signifie que le montant de réserve de 20 XRP ne pourra pas être retiré. 

## **Des coins \(pièces\) ont été envoyés dans mon portefeuille, mais le solde n'apparaît pas. Que dois-je faire**?

Dans la plupart des cas, il s'agit d'une erreur de saisie de l'adresse ou d'un long délai dû à des frais de transaction payés trop faibles.

* Si vous avez reçu un coin, veuillez vérifier sur l'application mobile. 
* Essayez de rafraîchir les soldes des comptes en restant sur l'onglet "Compte". Tirez l'écran vers le bas et relâchez pour rafraîchir. 
* Essayez de rechercher l'adresse à partir de Block Explorer et vérifiez si l'envoi ou la réception a réussi.  
  * Vous pouvez rechercher sur le moteur de recherche "bitcoin explorer", "ethereum explorer" ou "XRP explorer".  
  * Habituellement, les explorateurs de blocs suivants sont utilisés : Bitcoin : [https://btc.com](https://btc.com/) Ethereum : [https://etherscan.io](https://etherscan.io/)/ Ripple : [https://bithomp.com/explorer/](https://bithomp.com/explorer/)

## J'ai créé de nombreux comptes mais, à présent, seuls quelques-uns d'entre eux sont réellement utilisés. Ne puis-je pas voir uniquement les comptes que je souhaite voir ?

* Le porte-monnaie biométrique D'CENT affiche toutes les pièces prises en charge. 
* L'application mobile utilise une méthode d'ajout de compte, veuillez donc ajouter uniquement le compte que vous utilisez réellement. Si vous avez ajouté un grand nombre de comptes à des fins de test, vous pouvez supprimer toutes les informations relatives à ces comptes en suivant les instructions ci-dessous.  
  * Pour supprimer toutes les informations relatives aux comptes sur Biometric Wallet, allez dans \[Setting\] -&gt; \[Security\] - &gt; \[Delete Account\]. 
  * N'ajoutez que les comptes que vous voulez voir à partir de l'application mobile.

{% hint style="info" %}
"Supprimer le compte" ne supprime pas les clés privées ni vos actifs cryptographiques. Veillez à vous souvenir ou à noter les comptes dont vous disposez. 
{% endhint %}

## **N'est-il pas vulnérable à la sécurité lorsqu'il est connecté via Bluetooth**?

À l'exception des données de transaction de la blockchain rendues publiques, **TOUTES** les données importantes sont traitées dans la puce de sécurité du porte-monnaie biométrique. Par conséquent, même si la transmission des données dans la communication Bluetooth est suivie, les actifs à l'intérieur du portefeuille froid \(cold wallet\) ne peuvent pas être piratés.

## **Puis-je utiliser mon téléphone portable et le porte-monnaie biométrique D'CENT en utilisant la connexion filaire**?

Pour les téléphones Android, vous pouvez l'utiliser en le connectant avec un câble OTG. Veuillez cliquer ici \([here](biometric-wallet/android-connect/android-otg.md)\) pour plus d'informations.

## **Puis-je envoyer des pièces en utilisant uniquement le porte-monnaie biométrique sans l'application mobile ou un logiciel pour PC** ?

Le porte-monnaie biométrique D'CENT n'ayant pas de fonction de réseau internet, il est nécessaire de communiquer avec un logiciel externe pour transférer les pièces. Nous recommandons d'utiliser l'application mobile D'CENT.

* [iPhone app download ](https://apps.apple.com/kr/app/dcent-hardware-wallet/id1447206611) 
* [Android app download](https://play.google.com/store/apps/details?id=com.kr.iotrust.dcent.wallet)

## Quel est le niveau de sécurité de D'CENT Wallet ? Quelles caractéristiques sont incluses pour renforcer la sécurité ?

D'CENT Wallet est un produit réalisé par des experts de haut niveau qui ont longtemps travaillé dans le développement de puces cryptographiques et de systèmes d'exploitation sécurisés. Les cartes de crédit, les cartes bancaires, les cartes USIM, les TEE, etc. sont développées depuis près de 20 ans et D'CENT Wallet est développé en utilisant les techniques de sécurité apprises sur le terrain.   
  
Ce qui suit est une brève introduction aux considérations de sécurité.  

* Utilisation de la puce de sécurité de la carte à puce \(carte de crédit et secteur bancaire certifiés pour la sécurité\) pour le stockage sécurisé des clés et le traitement sécurisé de la signature de la transaction.  
* L'algorithme d'empreintes digitales est monté sur la carte à puce pour traiter les informations relatives aux empreintes digitales uniquement à l'intérieur de la puce de sécurité. 
* Système d'exploitation propriétaire sécurisé

Le porte-monnaie biométrique D'CENT a été soumis à une inspection de sécurité par un tiers professionnel de l'audit de sécurité, et vous pouvez en vérifier le contenu ici \([here](https://medium.com/dcentwallet/coinspect-audit-of-the-dcent-wallet-b8a6cf50cfa4)\). 

## **Puis-je effectuer la mise à jour du micrologiciel depuis mon téléphone portable** ?

Actuellement, seul l'environnement PC prend en charge la mise à jour du micrologiciel. La mise à jour du micrologiciel à partir de l'environnement mobile est en cours de développement dans la feuille de route à long terme.

## **La mise à jour du firmware s'est arrêtée en plein milieu. Que dois-je faire** ? 

La mise à jour du micrologiciel prend généralement environ 5 minutes. Cela peut prendre jusqu'à 10 minutes. Si la mise à jour ne progresse pas après ce laps de temps, appuyez sur les boutons "Down" et "Power" et maintenez-les enfoncés pour forcer l'arrêt de l'appareil et réessayez. Vous trouverez un guide détaillé ici\([here](biometric-wallet/firmware-update/firmware-trouble-shooting.md)\). 

## **Pourrai-je continuer à gérer mes actifs si D'CENT \(IoTrust\) fait faillite** ?

Bien qu'il soit très peu probable que D'CENT \(IoTrust\) arrête le service de portefeuille, mais si cette situation se produit un jour, vous pourrez continuer à gérer vos actifs de la manière suivante.  

* Les clients peuvent gérer leurs actifs en transférant des fonds vers d'autres portefeuilles que D'CENT.  
* D'CENT mettra l'application mobile ou le logiciel à la disposition du public pour que chacun puisse l'utiliser ou le modifier si le service est arrêté. 
* Nous promouvons continuellement l'intégration avec d'autres portefeuilles de logiciels populaires. Les clients se verront offrir une variété d'options à choisir parmi plusieurs alternatives.  

## **Existe-t-il un moyen pour ma famille d'accéder à mon portefeuille si je décède ou si je ne suis plus en mesure de gérer mon portefeuille pour toute autre raison** ?

Les principales informations qui permettent de gérer votre portefeuille sont le mot de passe, l'empreinte digitale et la carte de récupération. En cas d'urgence, vous pouvez le gérer de la manière suivante. 

* Partager les mots de récupération !
  * Si vous avez partagé les mots de récupération avec votre famille, celle-ci peut les utiliser pour récupérer les biens.  
* Enregistrement d'une deuxième empreinte digitale !
  * Vous pouvez enregistrer jusqu'à deux empreintes digitales sur le porte-monnaie biométrique. Si la deuxième empreinte digitale est enregistrée dans le matériel, elle peut être utilisée pour déverrouiller et accéder aux fonds qu'elle contient. 

{% hint style="info" %}
Veuillez vous enregistrer avec précaution car la deuxième empreinte digitale a également le même pouvoir d'envoyer des Cryptocoins. 
{% endhint %}

## Existe-t-il un autre porte-monnaie que l'application mobile D'CENT que je peux utiliser avec le porte-monnaie biométrique ?

Actuellement, il n'y a pas d'autres portefeuilles disponibles que l'application mobile D'CENT. Puisque nous travaillons avec plusieurs portefeuilles logiciels, l'utilisation du matériel D'CENT avec d'autres portefeuilles n'est pas lointaine.  Nous l'annoncerons séparément lorsque les travaux seront terminés.

## Il existe plusieurs modes de porte-monnaie, tels que le porte-monnaie biométrique, le porte-monnaie à carte et le porte-monnaie logiciel. Utilisent-ils tous la même clé privée ? 

Comme chaque portefeuille est distinct, ils utilisent tous des clés différentes. En supposant que vous utilisez l'application mobile dans les trois modes différents, vous utilisez trois portefeuilles différents avec des clés privées différentes.  

## Comment sauvegarder un portefeuille de type carte ? 

The original Card type wallet can be backed up using a BACKUP Card wallet. More information on a BACKUP Card can be found [here](https://userguide.dcentwallet.com/card-wallet/backupcard-new).

## Puis-je utiliser le portefeuille de type carte sur l'iPhone ? 

Pour l'iPhone 7 ou supérieur et iOS 13 ou supérieur, vous pouvez utiliser le portefeuille de type carte. Vous pouvez en savoir plus  ici \([here](card-wallet/how-to-use-iphone.md)\).

