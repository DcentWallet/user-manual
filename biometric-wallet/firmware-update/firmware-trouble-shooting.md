# Guide de dépannage \(Troubleshooting\)

## **Mon wallet D'CENT a été déconnecté pendant la mise à jour du micrologiciel. L'appareil est bloqué sur un écran et il ne veut pas s'éteindre. Que dois-je faire** ?

Tout d'abord, déconnectez votre porte-monnaie D'CENT de votre PC.

Appuyez et maintenez enfoncés les deux boutons "Down" + "Power" pendant quelques secondes pour forcer l'appareil à s'éteindre.  

Si votre appareil est endommagé pendant la mise à jour du micrologiciel, vous pouvez toujours accéder au mode bootloader en maintenant enfoncés les deux boutons "OK" et "Power" pendant 10 secondes. 

Depuis le mode bootloader, vous pouvez essayer de mettre à jour le firmware pour récupérer votre portefeuille biométrique. 

## **Sur la page Web de mise à jour du micrologiciel de D'CENT, j'ai appuyé sur le bouton "Update Firmware", mais j'ai reçu le message suivant : "Votre D'CENT est déconnecté. Le processus de mise à jour du micrologiciel est annulé". Que dois-je faire** ?

Dans de rares cas, le système Windows ne reconnaît pas le porte-monnaie D'CENT même s'il a été reconnu auparavant. Ce problème peut être résolu en désinstallant le pilote de périphérique et en le réinstallant à nouveau à partir du gestionnaire de périphériques de Windows.

### **Comment accéder au Gestionnaire de périphériques \(méthode n° 1\)**

Appuyez sur **Windows+R** sur votre clavier.

Tapez "**control panel**" et appuyez sur **Enter** pour accéder au Panneau de configuration          \(control panel\).

Pour Windows 10 ou Windows 8, choisissez Matériel et son, recherchez et choisissez Gestionnaire de périphériques. \(**Device Manager**\) 

Pour Windows 10 ou Windows 8, vérifiez sous **Périphériques et imprimantes**. 

Pour Windows 7, vérifiez sous **Système**.

### **Comment accéder rapidement au Gestionnaire de périphériques \(méthode \#2\)**

Appuyez sur **Windows+R** sur votre clavier.  

Tapez "**cmd**" et appuyez sur **Enter** pour lancer l'invite de commande 

\(une fenêtre noire\).



Tapez "**devmgmt**.**msc**" et appuyez sur Enter.

### **Que dois-je faire à partir du Gestionnaire de périphériques** ?

Dans l'écran du gestionnaire de périphériques, recherchez les dispositifs d'interface humaine \(**Human Interface Devices**\)

Vérifiez s'il y a un **périphérique d'entrée USB \(USB Input Device\)** marqué comme étant en erreur \(triangle jaune avec point d'exclamation\). Vous devrez vérifier s'il s'agit bien d'un périphérique D'CENT.

![](../../.gitbook/assets/image%20%28143%29.png)

Cliquez avec le bouton droit de la souris sur ce dispositif et sélectionnez Propriétés \(**Properties**\).

![](../../.gitbook/assets/image%20%2839%29.png)

* Dans la fenêtre Propriétés du périphérique d'entrée USB, sélectionnez **Détails**.
* Sous Propriété, sélectionnez **Hardware Ids**.
* L'ID correct du dispositif pour D'CENT est **PID\_2130**.

  \( Correct device ID for D'CENT is **PID\_2130** \)

Depuis le **Device Manager**, Cliquez avec le bouton droit de la souris sur le périphérique marqué d'une erreur et sélectionnez **Uninstall device**.

![](../../.gitbook/assets/troubleshooot_remove-error-device.png)

Dans le menu supérieur du Gestionnaire de périphériques, appuyez sur **Action** puis sélectionnez Analyser les changements de matériel\(**Scan for hardware changes**\). 

Cela permettra de rechercher tout nouveau périphérique connecté et d'installer automatiquement le pilote pour détecter votre porte-monnaie biométrique.

