---
description: Creating new wallet on the Biometric Wallet
---

# Configuration initiale

## **Avant de commencer** <a id="before-start"></a>

{% embed url="https://www.youtube.com/watch?v=-j2pI\_IA3Z4&feature=youtu.be" %}



![D&#x2019;CENT biom&#xE9;trique l&#x2019;Interfaces utilisateur du porte-monnaie](../.gitbook/assets/img-howtouse-dongle.png)

Le porte-monnaie biométrique D'CENT est équipé de 4 boutons pour la navigation.

* **Boutons haut\(∧\)/bas\(∨\)** : se déplacer entre les éléments sélectionnables ou modifier la valeur des chiffres ou des caractères.
* **Bouton OK** : confirme l'élément sélectionné ou la valeur saisie.
* **Bouton de retour** : passer au menu précédent ou annuler l'entrée en cours.

## Step-1 : Select Language & Create Wallet \(**Sélectionner la langue et créer un portefeuille\)**

{% embed url="https://www.youtube.com/watch?v=rpVFENz8H\_0&feature=youtu.be" %}

### **Allumez D'CENT Biometric**

Pour allumer l'appareil, appuyez sur le bouton d'alimentation pendant 3 secondes, situé sur le côté droit.

### **Sélectionner la langue \(**Select Language\)

Utilisez le bouton ∧\(Up\) ou ∨\(Down\) pour sélectionner votre langue et appuyez sur le bouton **OK**.

![](../.gitbook/assets/image%20%28149%29.png)

Langues prises en charge : anglais, coréen, chinois, japonais, espagnol.

{% hint style="info" %}
Après avoir configuré votre portefeuille froid, vous pouvez modifier la langue à partir de l'onglet "Langue" [Setting](setting-menu.md) menu.
{% endhint %}

### **Sélectionner "Create Wallet"**

Pour créer un nouveau porte-monnaie, sélectionnez "Create Wallet" dans le menu.

![](../.gitbook/assets/image%20%2868%29.png)

{% hint style="info" %}
En sélectionnant "Create Wallet", un portefeuille sera créé à partir d'une nouvelle clé privée.  
Si vous souhaitez récupérer un porte-monnaie existant, veuillez vous reporter à la rubrique ici \([here](recovery.md)\).
{% endhint %}

## Step-2 : **Enregistrer le PIN et l'empreinte digitale**

Pour protéger l'accès à votre portefeuille, enregistrez un nouveau code PIN et votre empreinte digitale. Les micrologiciels inférieurs à la version 2.5.5 ne prennent en charge que les codes PIN à 4 chiffres.

### **Enregistrer un nouveau code PIN \(4 à 8 chiffres\)**

Utilisez le bouton ∧\(Haut, augmenter la valeur numérique\) ou ∨\(Bas, diminuer la valeur numérique\) pour saisir votre code PIN. En appuyant sur le bouton OK du portefeuille matériel, vous confirmez la saisie.

![](../.gitbook/assets/1%20%283%29.png)

Lorsque vous avez saisi 4 chiffres, le texte "OK" s'affiche à l'écran. Si vous souhaitez que votre code PIN soit composé de 4 chiffres, appuyez sur le bouton OK du porte-monnaie électronique. 

Si vous souhaitez définir le code PIN sur un chiffre plus long, vous pouvez modifier la valeur \(texte '**OK**'\) à l'écran en appuyant sur le bouton Haut ou Bas. **Votre code PIN peut être défini sur 4, 5, 6, 7 ou 8 chiffres**.

![](../.gitbook/assets/2%20%284%29.png)

Si un écran affiche l'avertissement "**Niveau de sécurité faible**", cela signifie que le code PIN que vous avez saisi est un mot de passe faible. Si vous souhaitez utiliser un tel code PIN, appuyez sur le bouton "OK" du porte-monnaie électronique pour continuer.

### **Vérifiez votre** PIN

Saisissez à nouveau le même code PIN que vous avez défini à l'étape précédente pour en vérifier l'exactitude.

![](../.gitbook/assets/3%20%283%29.png)

 ※ Si les numéros PIN ne correspondent pas, vous devrez recommencer l'enregistrement du PIN.

{% hint style="info" %}
Après avoir configuré votre porte-monnaie électronique, vous pouvez modifier la valeur du code PIN à partir du porte-monnaie biométrique menu [Setting](setting-menu.md).
{% endhint %}

### **Enregistrer l'empreinte digitale \(Register Fingerprint\)**

1\) Pour enregistrer votre empreinte digitale, touchez votre doigt sur le capteur pour le scanner.

![](../.gitbook/assets/image%20%28183%29.png)

Le capteur d'empreintes digitales est situé au milieu, là où se trouvent les boutons de navigation.Vérifiez l'emplacement du capteur d'empreinte digitale \([fingerprint sensor](setting-up.md#before-start)\). 

2\) Modifiez légèrement le positionnement angulaire du même doigt lors du balayage et répétez l'opération jusqu'à atteindre 100 % \(8 balayages corrects\).

![](../.gitbook/assets/image%20%28135%29.png)

### **Vérifier l'empreinte digitale \(**Verify Fingerprint\)

Scannez votre empreinte digitale une dernière fois pour vérifier l'empreinte digitale enregistrée.

![](../.gitbook/assets/image%20%28184%29.png)

※ Si l'empreinte digitale ne correspond pas, vous devrez recommencer l'enregistrement des empreintes digitales.

※ Si vous réenregistrez votre empreinte digitale, essayez d'utiliser un autre doigt à la place.

※ Si vous ne pouvez pas enregistrer vos empreintes digitales pour une raison quelconque, vous aurez la possibilité de ne pas le faire. Les empreintes digitales peuvent être enregistrées à partir du menu [Setting](setting-menu.md#enroll-finger) plus tard.

※ Si la vérification des empreintes digitales échoue, votre empreinte digitale ne sera pas enregistrée. 

## Step-3 : **Notez les séquences de mots de récupération \(**Write down the recovery seeds\)

### **Avant de commencer - Que sont les séquences de mots de récupération, recovery seeds \(code mnémonique\)** ?

Les graines de récupération sont les codes que vous utilisez pour récupérer votre portefeuille.

Si votre portefeuille D'CENT Cold Wallet est perdu, volé, endommagé ou effacé et que vous n'avez plus accès à votre portefeuille, l'utilisation des graines de récupération \(**les séquences de mots de récupération est la seule méthode pour récupérer votre portefeuille existant**\).



> **Vous DEVEZ noter tous les mots de récupération sur la carte de récupération et la conserver en lieu sûr \( 24 mots \).**

les Recovery seeds \( 24 mots\) nécessaires à la récupération de votre portefeuille existant n'est affichée qu'une seule fois lors de la configuration initiale.

Si vous perdez votre carte de récupération, nous ne pouvons rien faire pour vous aider à récupérer vos fonds. 

Vous êtes seul responsable de la sécurité de votre carte de récupération dans tous les cas.

{% hint style="danger" %}
Si vous perdez votre carte de récupération, il n'y a aucun autre moyen de récupérer votre portefeuille existant et vos fonds seront perdus.
{% endhint %}

### **Notez les recovery seeds \(24 mots de récupération\) dans les listes.**

1\) Appuyez sur le bouton **OK** uniquement lorsque vous avez bien compris l'avis d'AVERTISSEMENT.

![](../.gitbook/assets/image%20%28159%29.png)

2\) Notez toutes les graines de récupération \(**mots**\) dans l’ordre affiché sur l'écran de votre portefeuille froid **cold wallet**. Appuyez sur le bouton **OK** pour voir la liste de mots suivante.

Il y a 6 listes avec un total de 24 mots et chaque liste a 4 mots montrés. **Assurez-vous que vous les écrivez correctement et dans le même ordre que celui indiqué**. 

![](../.gitbook/assets/image%20%28103%29.png)

3\) Lorsque vous avez noté les 24 mots, appuyez sur le bouton **OK** pour continuer.

![](../.gitbook/assets/image%20%2892%29.png)

### **Vérification des 24 mots de récupération \(**Recovery Seeds Verification\)

Il vous sera demandé de répondre à un simple quiz. Parmi les 24 mots de la liste, il vous sera demandé de saisir 2 mots choisis au hasard pour compléter la vérification.

![Quiz example](../.gitbook/assets/image%20%2849%29.png)

Saisissez le mot correct qui correspond à la question posée.

#### **Entrez les 3 premiers caractères**

![](../.gitbook/assets/image%20%28122%29.png)

※ Comment saisir : Utilisez les boutons Haut/Bas - ∧\(augmentez la valeur de a à z\) ou ∨\(diminuer la valeur de z à a\).

Lorsque vous avez sélectionné le premier caractère, appuyez sur le bouton "OK" pour entrer la valeur. Répétez la saisie des deuxième et troisième caractères.

#### **Recherche d'une suggestion dans la liste affichée**

Dans la liste des mots disponibles, sélectionnez le mot correct à l'aide des boutons ∧/∨ et appuyez sur "OK" pour le choisir comme réponse.

![](../.gitbook/assets/image%20%2856%29.png)

※ Si vous vous apercevez que vous avez noté les mots de manière incorrecte, vous pouvez appuyer sur le bouton "Retour" pour revenir sur les graines de récupération des listes pour les réviser.

## Step-4 : **Terminer la configuration initiale \(Initial setup\)**

![](../.gitbook/assets/image%20%2865%29.png)

Félicitations, vous avez réussi le quiz et votre nouveau porte-monnaie est créé. À partir de votre portefeuille froid, vous pouvez consulter la liste des comptes de pièces disponibles. Vous êtes maintenant prêt à utiliser votre nouveau porte-monnaie avec l'application mobile.

* Comment se connecter avec un téléphone Android \([How to connect with Android phone](android-connect/)\)
* Comment se connecter avec un téléphone iOS \([How to connect with iOS phone](iphone-connect.md)\)

{% hint style="info" %}
Vous pouvez trouver la liste complète des crypto-monnaies supportées par D'CENT Biometric Wallet sur le site suivant: [https://dcentwallet.com/SupportedCoin](https://dcentwallet.com/SupportedCoin)
{% endhint %}

### **Vérifier le dernier firmware**

Une fois que vous avez terminé la configuration initiale, assurez-vous de visiter la page d'accueil de D'CENT Wallet et de vérifier la dernière version du firmware disponible. Une version plus récente du firmware peut inclure un support supplémentaire pour les actifs de cryptocurrency et de nouvelles fonctionnalités du portefeuille.

Pour plus d'informations sur la mise à jour du micrologiciel\(firmware\), consultez le site suivant ici\([here](firmware-update/)\).

