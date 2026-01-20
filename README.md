<h1>
    Section 1 : Entrez les détails de votre carte
</h1>

<br />
<h3>
    Étape 1 : Entrez le nom du point
</h3>

<br />
Dans cette étape, vous devez entrer le nom de chaque point de votre carte. Le nom du point doit être unique.

<br />
<b>Conditions</b>
<br />

<ul>
    <li>Veuillez créer plus d'un seul sommet !</li>
</ul>

<br />
Vous devez créer au moins deux sommets pour créer une carte valide.
<br /><br />

<h3>
    Étape 2 : Entrez le point de départ, le point d'arrivée et la distance
</h3>

<br />
Dans cette étape, vous devez entrer le point de départ, le point d'arrivée et la distance entre les deux points. Le point de départ doit être différent du point d'arrivée.

<br />
<b>Conditions</b>
<br />

<ul>
    <li>Veuillez ne pas répéter la même association !</li>
</ul>

Vous ne pouvez pas créer deux associations identiques.  
Par exemple, A → B est différent de B → A.

<br />

<ul>
    <li>Veuillez ne pas connecter un point avec lui-même !</li>
</ul>

<br />

<ul>
    <li>Veuillez ne pas laisser un sommet isolé !</li>
</ul>

Chaque sommet doit être connecté à au moins un autre sommet.

<br />
<b>Exemple :</b>
<br />

<table class="table table-bordered table-sm">
    <tr>
        <th>Point de départ</th>
        <th>Point d'arrivée</th>
        <th>Distance</th>
    </tr>
    <tr>
        <td>A</td>
        <td>B</td>
        <td>12</td>
    </tr>
    <tr>
        <td>B</td>
        <td>C</td>
        <td>8</td>
    </tr>
</table>

<br />

Dans cet exemple, la carte comporte trois sommets : A, B et C.  
La distance entre A et B est 12, et entre B et C est 8.

<br /><br />

<b>Remarques :</b>
<ul>
    <li>Vous pouvez entrer les informations dans n'importe quel ordre.</li>
    <li>Les distances doivent être des nombres entiers positifs.</li>
</ul>

<br /><br /><br />

<h1>
    Section 2 : Utilisation de la carte
</h1>

Pour utiliser la carte, double-cliquez sur un cercle pour le sélectionner.  
Le cercle sélectionné sera entouré d'une bordure jaune.

Une fois que vous avez sélectionné **un point de départ** et **un point d'arrivée**,  
l'algorithme de recherche de chemin de **Dijkstra** est exécuté.

Le **chemin le plus court** entre les deux points sera mis en évidence.

Vous pouvez répéter ce processus autant de fois que vous le souhaitez.  
Vous pouvez annuler la sélection en cliquant sur un autre élément de la carte.

Les associations affichent des flèches pour indiquer le sens du trajet,  
car **A → B est différent de B → A**.

<br /><br /><br />

<h1>
    Section 3 : Algorithme utilisé
</h1>

<p>
    L'algorithme de Dijkstra est un algorithme de recherche du plus court chemin
    dans un graphe pondéré à poids positifs.
    Il permet de déterminer la distance minimale entre un sommet de départ
    et tous les autres sommets du graphe.
</p>

<br />

<b>Algorithme détaillé</b>
<ol>
    <li>Initialiser la distance du sommet de départ à 0 et celle des autres sommets à l'infini.</li>
    <li>Marquer tous les sommets comme non visités.</li>
    <li>Sélectionner le sommet non visité ayant la plus petite distance connue.</li>
    <li>Mettre à jour les distances de ses voisins si un chemin plus court est trouvé.</li>
    <li>Marquer le sommet comme visité.</li>
    <li>Répéter jusqu'à ce que le sommet d'arrivée soit atteint ou que tous les sommets soient visités.</li>
</ol>

<br />

<b>Temps d'exécution</b>
<p>
    Le temps d'exécution de l'algorithme de Dijkstra est de
    <b>O((V + E) log V)</b> avec une file de priorité,
    où V est le nombre de sommets et E le nombre d'arêtes.
</p>

<br />

<b>Applications</b>
<ul>
    <li>Navigation GPS et calcul d'itinéraires</li>
    <li>Routage réseau</li>
    <li>Jeux vidéo (pathfinding)</li>
    <li>Analyse de graphes pondérés</li>
</ul>

<br />

<b>Conclusion</b>
<p>
    L'algorithme de Dijkstra est un algorithme fondamental pour la recherche
    du plus court chemin. Il est fiable, efficace et largement utilisé dans
    les systèmes de navigation et les applications graphiques interactives.
</p>

<br /><br />

<b>
    Codé par : <i>Yasser Chenik</i><br />
    Algorithme par : <i>Youness</i>
</b>

<br />

Lien d'exécution :
<a href="https://yasser-chen.github.io/Dijkstra/">
    https://yasser-chen.github.io/Dijkstra/
</a>
