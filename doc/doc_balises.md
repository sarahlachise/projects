
Les balises dans Xia
=====
Xia permet la réalisation de mini-jeux en html5. Pour cela, il existe un certain nombre de balises à utiliser pour définir les comportements des éléments du jeu.

Toutes ces balises sont à écrire dans le champ **Propriétés de l'objet -> Description**
Généralités
----
(valables sur Drag and Drop et One click)

### Sur l'image de fond

Définir le **score** : <pre>`<score>nombre de réussites attendues</score>`</pre>
Exemple `<score>7</score>`

Définir un **second score** (utile pour arrêter le jeu après un minimum d'erreurs par exemple): <pre>`<score2>nombre de réussites attendues</score2>`</pre>

Définir le **message de réussite** : <pre>`<message>Message de réussite</message>`</pre>

Définir le message de réussite du score2 : <pre>`<message2>Message de réussite</message2>`</pre>

### Sur un détail

Afficher une autre **image au survol du détail** : <pre>`<tooltip>ID_de_l_image_a_afficher</tooltip>`</pre>
(l'ID doit être sans espace, sans accent)

Jeu Drag and Drop
----
### Sur l'objet à déplacer :

Définir sa **cible** : <pre>`<target>nom_target</target>`</pre>

Définir **si l'objet revient à sa place**, s'il est mal placé : <pre>`<onfail>return</onfail>`</pre>

### Sur la cible

**Magnétiser** la cible : <pre>`<magnet>on</magnet>`</pre>

### Sur l'image de fond

Activer ou désactiver les **collisions** dans le jeu : <pre>`<collisions>on/off</collisions>`</pre>
