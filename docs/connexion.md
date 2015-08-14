---
layout: page
title: Se connecter au réseau
---

Afin de vous connecter au réseau, il existe différentes méthodes présentent leurs avantages et leurs inconvenants.

## Connexion avec un client web
Nous disposons d'un client web utilisant javascript afin de vous connecter au réseau. Pour cela, rendez vous sur [webirc.ekinetirc.fr.nf](http://webirc.ekinetirc.fr.nf/). Le mot de passe est à renseigner si votre pseudo est enregistrer sur les [services](/docs/services.html).

### Client web alternatif
Un client web alternatif est disponible à l'adresse [ajax.ekinetirc.fr.nf](http://ajax.ekinetirc.fr.nf/). Mais il est recommander d'éviter son utilisation si possible pour des questions de performances.

### Mibbit
Notre réseau est désormais pris en charge par [Mibbit](https://mibbit.com/). Il vous suffit d'indiquer le serveur irc.ekinetirc.fr.nf ou d'utiliser [ce lien](https://chat.mibbit.com/?server=irc.ekinetirc.fr.nf%3A%2B7008).

### Connexion avec d'autres web clients
L'utilisation d'autres webclient est vivement déconseiller. Certains peuvent même être bloqués sur notre réseau suite à des abus. Exception est fait des webclient java qui se connecte depuis votre propre connexion.

## Connexion avec un client IRC
C'est la méthode classique qui consiste à utiliser un client IRC installer sur son ordinateur. C'est aussi la méthode que nous recommandons.  
Voici les informations de connexion :

- Serveur : irc.ekinetirc.fr.nf
- Ports :
  * Non-SSL : 6660 à 6689 ([généralement, on utilise le port 6667](http://www.iana.org/assignments/port-numbers))
  * [SSL](https://fr.wikipedia.org/wiki/Secure_Sockets_Layer) : 6690 à 6699 et 7000 à 7009

Pour l'authentification avec les [services](/docs/services.html), notre réseau prend en charge le [SASL](https://fr.wikipedia.org/wiki/Simple_Authentication_and_Security_Layer).
