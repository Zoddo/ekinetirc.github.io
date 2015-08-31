---
layout: page
title: Session limit exceeded
---

<!--
        WARNING: L'URL de cette page est envoyé par les services lors de déconnexion pour excès de sessions.
                    Merci de faire attention si elle doit-être renommé.
-->

Si vous arrivez sur cette page, c'est certainement car vous avez essayer de vous connecter sur le réseau, mais ce genre de message est apparu :
<pre><code>-OperServ- The session limit for your IP xx.xx.xx.xx has been exceeded.
-OperServ- Please visit http://ekinetirc.fr.nf/docs/session_limit.html for more information about session limits.
ERROR: Closing Link: pseudo[xx.xx.xx.xx] hub.fr.ekinetirc.com (OperServ (Session limit exceeded))
</code></pre>ou
<pre><code>*** You are banned from EkiNetIrc (Session limit exceeded (ID: XXXXXXXXXX)) Email gline@ekinetirc.com for more information.
ERROR: Closing Link: pseudo[xx.xx.xx.xx] (User has been banned from EkiNetIrc (Session limit exceeded (ID: XXXXXXXXXX)))
</code></pre>

Comme l'indique ce message, cela est du au fait que nous limitons le nombre de sessions par IP afin de limiter le spam.

Actuellement, le nombre de session est limiter à **3 sessions par IP**. Cette limite peut-être réduite temporairement lors d'attaque sur le réseau ou en cas d'abus.

Si les services sont obligés de "*kill*" (forcer la déconnexion) trop de sessions, un bannissement temporaire sur votre IP peut-être mis en place, provoquant l'affichage du deuxième message d'exemple.

## Que faire ?
Si ce n'est pas vous qui connectez toutes ces sessions sur notre réseau, votre ordinateur est probablement infecté. Nous ne pouvons alors pas vous aider et vous conseillons plutôt d'en parler avec une personne compétante.
Sinon, essayez de voir si il est vraiment utile de connecter toutes ces sessions ! Si vous avez une bonne raison, vous pouvez nous [contacter](/contact.html) et demander une exception à condition que votre adresse IP soit fixe.

Si vous avez accidentellement été banni, attendez juste quelques minutes. Les bannissements pour cette raison sont très courts (5 minutes).

**Note :** Si cela se produit et que vous avez été déconnecté à cause d'un problème réseau mais que l'ancienne session est restée active, vous pouvez la déconnecter en tapant cette commande :
<pre><code>/ns recover <u>pseudo</u>
</code></pre>
