# Calcul_Reseaux
calculate network, first &amp; last IP with an host IP Address/mask + IP/binary converter

.NOTES
	NAME:	Calcul_réseaux.ps1
    VERSION : 1.0  17/04/2022
    VERSION : 1.1  18/06/2022
	AUTHOR:	Frédéric Puren

VERSION 1.1 :

- Amélioration du script en intégrant une fonction pour le calcul réseau.
- Ajout du scope d'adresse IP d'un second réseau si un VPN est connecté
- 

1 - prend l'adresse IP du PC sur lequel il est lancé et calcul l'adresse IP du réseau, la première et la dernière adresse IP machine et l'adresse de broadcast.
2 - idem mais on rentre l'adresse IP et le masque sous-réseau que l'on souhaite
3 - Convertisseur d'adresse IP Décimal en Binaire
4 - Convertisseur d'adresse IP Binaire en Décimal


Des commentaires additionnels se trouvent dans le script.


sources utilisées pour la création du script powershell : 

- faire un menu : https://wiki-tech.io/Scripting/Powershell/Menu

- pour convertir decimal vers binaire et vice versa : https://devblogs.microsoft.com/scripting/use-powershell-to-easily-convert-decimal-to-binary-and-back/

- séparer des chaines de caractère : https://www.it-connect.fr/powershell-et-split-decouper-une-chaine-de-caracteres/

- extraire une chaine de caractère : https://www.it-connect.fr/powershell-et-substring-extraire-une-chaine-dune-chaine/

- padleft, padright : https://4sysops.com/archives/how-to-add-leading-and-ending-zeroes-to-strings-in-powershell/

- créer une fonction : https://techexpert.tips/fr/powershell-fr/powershell-creation-dune-fonction/
 #>


Screenshot :

![2022-05-13 11_28_30-Window](https://user-images.githubusercontent.com/105367565/168255071-f7fae3aa-83ae-4bbf-ab89-fb848070f66d.png)

![2022-05-13 11_28_51-Window](https://user-images.githubusercontent.com/105367565/168255160-26765251-0209-452a-8a3e-371fef800046.png)
