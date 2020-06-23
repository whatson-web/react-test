This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Pour réaliser ce test, utiliser les données contenues dans
countries.json et effectuer les tâches numérotéees. Vous êtes libres
d'utiliser les modules de votre choix (ou même de ne pas en utiliser).
Vous êtes libres pour le design mais on ne sera pas très exigeant
dessus tant que c'est lisible et que ça ne pique pas trop les yeux 😉
Vous êtes encouragé à utiliser les meilleures pratiques possibles et à
créer autant de composants que bon vous semble, n'hésitez pas à
commenter votre code.

<b>Contrainte:</b> utiliser uniquement des Function Component React
avec des{" "}
<a
  href="https://reactjs.org/docs/hooks-intro.html"
  target="_blank"
  rel="noopener noreferrer"
>
  Hooks
</a>

<ol>
<li>
  Dresser un tableau listant les pays. Ce tableau contiendra les
  colonnes suivantes: Nom, Code, Capitale, Lontitude, Lagitude{" "}
</li>
<li>
  Mettre en place un système de pagination permettant de n'afficher
  que 10 pays à la fois. Prevoir simplement un bouton "Suivant" et un
  bouton "Précédent" pour pouvoir naviguer entre les pages.
</li>
<li>
  Mettre en place un select qui permettra à l'utilisateur de trier les
  pays dans le tableau:
  <br />
  - par ordre alphabétique de nom de pays <br />
  - par ordre alphabétique inverse de nom de pays <br />
  - par ordre alphabétique de nom de capitale <br />
  - par ordre alphabétique inverse de nom de capitale <br />
</li>

<li>
  Mettre en place plusieurs champs input pour pouvoir filtrer les
  résultats:
  <br />
  - par nom de pays
  <br />
  - par nom de capitale
  <br />
  <i>
    Exemple: si je tape "Bel" dans le champs de recherche de pays,
    seul les pays commençant par "bel" s'afficheront (soit Belgium,
    Belize et Belarus){" "}
  </i>
</li>

<li>
  Permettre à l'utilisateur de télécharger tous les résultats (en
  fonction du tri et des filtres) dans un fichier CSV
</li>
</ol>
