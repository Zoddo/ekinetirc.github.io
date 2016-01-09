---
layout: page
title: Enregistrer un pseudo/canal
---

L'enregistrement permet de "réserver" et protégrer un nom d'utilisateur ou un canal.

* Dans le cas des noms d'utilisateurs, cela permet d'empêcher quelqu'un d'autre d'utiliser votre pseudo et vous permet aussi d'enregistrer un canal.
* Dans le cas des canaux, cela permet de conserver vos droits sur le canal (par défaut, un canal non-enregistré est détruit lorsqu'il n'y a plus personne; la première personne qui s'y reconnecte est alors considérer comme fondatrice et obtient alors les droits d'administration).

**Note :** Si vous n'êtes pas habituer à IRC, sachez qu'une commande comemnce toujours par un slash. Sinon, ce que vous entrez est considérer comme un message. Attention à ne pas mettre d'espace avant le slash lorsque vous tapez une commande.

## Eneregistrer un pseudo (nom d'utilisateur)
L'enregistrement d'un pseudo est simple. Pour enregistrer le pseudo sous lequel vous êtes actuellement connecté, il suffit de tapez cette commande :
<pre><code>/nickserver register <u>mot de passe</u> <u>e-mail</u>
</code></pre>

**Note :** Vous devez remplacer la/les partie(s) <u>souilgnée(s)</u> ci-dessus par leur correspondance.  
**Note :** <u>mot de passe</u> est sensible à la casse.

Un e-mail vous est ensuite envoyé pour vérifier votre adresse. Ce dernier contient une autre commande qui permet de confirmer l'enregistrement.

**Astuce :** Vous pouvez abréger `/nickserv` en `/ns` lorsque vous tapez votre commande.  
**Astuce :** Vous pouvez aussi enregistrer votre pseudo par [l'interface web](http://services.ekinetirc.fr.nf/register).

### Connexion
Une fois votre pseudo enregistrer, vous devez vous connecter avec votre mot de passe, sinon vous ne pourrez pas l'utiliser (il sera modifié automatiquement après 60 secondes).

Pour cela, il suffit généralement de cochez une case (`J'ai un mot de passe`) si vous utilisez un webclient. Sinon, vous pouvez utiliser cette commande :
<pre><code>/identify <u>pseudo</u> <u>mot de passe</u>
</code></pre>

**Note :** Le pseudo est facultatif.

### Paramètrage
Si vous souhaitez paramètrer votre pseudo, n'hésitez pas à consulter ce que retourne cette commande :
<pre><code>/nickserv help <u>commande</u>
</code></pre>

Cela donnera le détail d'une commande. Si vous ne spécifiez pas de commande, cela va lister toutes les commandes disponible et leur rôle.  
**ATTENTION :** Toutes les commandes qui sont donné via l'aide doivent être préfixés par `/nickserv`

## Enregistrer un canal
Avant d'enregistrer un canal, vous devez être connecter dessus et y être opérateur (avec un `@` devant votre pseudo).
Ensuite, exécutez cette commande :
<pre><code>/chanserv register <u>#canal</u> <u>description</u>
</code></pre>

**Note :** Vous devez remplacer la/les partie(s) <u>souilgnée(s)</u> ci-dessus par leur correspondance.  
**Note :** La description est facultative.

Le canal est désormais enregistrer sous votre pseudo.

**Astuce :** Vous pouvez abréger `/chanserv` en `/cs` lorsque vous tapez vos commandes.

### Paramètrage
Afin de paramètrer votre canal, n'hésitez pas à consulter ce que retourne cette commande :
<pre><code>/chanserv help <u>commande</u>
</code></pre>

Cela donnera le détail d'une commande. Si vous ne spécifiez pas de commande, cela va lister toutes les commandes disponible et leur rôle.  
**ATTENTION :** Toutes les commandes qui sont donné via l'aide doivent être préfixés par `/chanserv`

## Obtenir de l'aide
Si vous avez un problème, n'hésitez pas à demande de l'aide sur #EkiNetIrc (`/join #EkiNetIrc`). Nous nous ferons une joie de vous aider.
