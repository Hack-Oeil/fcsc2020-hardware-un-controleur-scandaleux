# FCSC 2020 Un contrôleur sCANdALeux

Vous avez récemment acheté un contrôleur universel pour ouvrir votre porte automatiquement. Seulement quand vous l’utilisez, toutes les portes automatiques des habitations alentours s’ouvrent au même moment. Pour percer ce mystère, vous décidez de capturer le signal émis par votre contrôleur.

Vous avez sorti votre radio logicielle préférée et fait une capture du signal émis à 434MHz, avec un taux d’échantillonnage de 1MHz.

Note 1 : Pour ouvrir ce fichier avec numpy, il faut utiliser le format complex64 : numpy.fromfile(<filename>, dtype = numpy.complex64). Pour utiliser le logiciel GNURadio, il faut utiliser le bloc File Source et le format complex. Note 2 : Pour commencer à analyser la capture, vous pouvez utiliser le flowgraph fourni dans GNU


Les fichiers :
- [open-the-door.iq](open-the-door.iq)
- [gr_waterfall_tuto.png](gr_waterfall_tuto.png)

Auteur : ElyKar

Origine : [Un contrôleur sCANdALeux](https://hackropole.fr/fr/challenges/hardware/fcsc2020-hardware-un-controleur-scandaleux/)


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2020-hardware-un-controleur-scandaleux.git

> cd fcsc2020-hardware-un-controleur-scandaleux


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/hardware/fcsc2020-hardware-un-controleur-scandaleux/