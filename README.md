# Training_html_css

liste de certains des attributs HTML couramment utilisés :

    id : Identifie de manière unique un élément sur la page.
    class : Associe un ou plusieurs noms de classe à un élément, permettant le ciblage CSS ou JavaScript.
    src : Spécifie la source (URL) d'un élément, comme une image ou un script.
    href : Spécifie la destination (URL) d'un lien hypertexte.
    alt : Fournit un texte alternatif pour les éléments multimédias, comme les images.
    width : Définit la largeur d'un élément, par exemple pour les images.
    height : Définit la hauteur d'un élément, par exemple pour les images.
    title : Fournit un titre ou une info-bulle pour un élément, généralement affiché au survol.
    target : Spécifie comment ouvrir un lien (nouvelle fenêtre, nouvel onglet, même fenêtre, etc.).
    type : Indique le type de contenu d'un élément, comme le type de média ou de script.
    value : Définit la valeur initiale d'un élément de formulaire, comme un champ de saisie.
    placeholder : Affiche un texte indicatif dans un champ de formulaire tant qu'il est vide.
    disabled : Désactive un élément de formulaire, le rendant non interactif.
    checked : Indique que la case à cocher (input type="checkbox") est cochée par défaut.
    selected : Indique que l'option d'une liste déroulante (select) est sélectionnée par défaut.
    autocomplete : Active ou désactive la fonction d'autocomplétion pour un champ de formulaire.
    autofocus : Donne le focus automatique à un élément de formulaire lors du chargement de la page.
    required : Indique qu'un champ de formulaire doit être rempli avant de soumettre le formulaire.
    min : Définit une valeur minimale pour les éléments de formulaire numériques.
    max : Définit une valeur maximale pour les éléments de formulaire numériques.
    step : Spécifie l'incrément entre les valeurs possibles pour les éléments de formulaire numériques.
    name : Donne un nom à un élément de formulaire, utilisé lors de la soumission du formulaire.
    form : Associe un élément de formulaire à un formulaire particulier en utilisant son id.
    multiple : Autorise la sélection de plusieurs options dans une liste déroulante (select).
    colspan : Définit le nombre de colonnes qu'une cellule de tableau doit occuper.
    rowspan : Définit le nombre de lignes qu'une cellule de tableau doit occuper.
    colgroup : Regroupe des colonnes de tableau pour une mise en forme commune.
    rowgroup : Regroupe des lignes de tableau pour une mise en forme commune.
traduction
    id : Identifiant
    class : Classe
    src : Source
    href : Référence
    alt : Texte alternatif
    width : Largeur
    height : Hauteur
    title : Titre
    target : Cible
    type : Type
    value : Valeur
    placeholder : Placeholder (Texte indicatif)
    disabled : Désactivé
    checked : Coché
    selected : Sélectionné
    autocomplete : Autocomplétion
    autofocus : Autofocus
    required : Requis
    min : Minimum
    max : Maximum
    step : Pas
    name : Nom
    form : Formulaire
    multiple : Multiple
    colspan : Fusion de colonnes
    rowspan : Fusion de lignes
    colgroup : Groupe de colonnes
    rowgroup : Groupe de lignes




    #flex p1
Les flexbox, ou flexbox layouts, sont une technologie CSS (Cascading Style Sheets) permettant de créer des mises en page flexibles et adaptatives pour les éléments d'une page web. Ils sont particulièrement utiles pour créer des mises en page réactives, où les éléments s'ajustent automatiquement en fonction de la taille de l'écran et du contenu.

Voici une explication des principaux concepts et propriétés liés aux flexbox :

    Flex Container (Conteneur Flex) : Le conteneur flex est l'élément parent qui encapsule les éléments enfants (appelés items flex). Pour créer un conteneur flex, vous devez appliquer la propriété CSS display: flex; à cet élément. Les éléments à l'intérieur du conteneur deviennent automatiquement des items flex.

    Flex Items (Items Flex) : Ce sont les éléments enfants du conteneur flex. Les items flex sont les éléments qui seront arrangés dans la mise en page flexible. Ils peuvent être de n'importe quel type, comme des div, des paragraphes, des images, etc.

    Axe Principal (Main Axis) : Dans un conteneur flex, il existe deux axes : l'axe principal (main axis) et l'axe transversal (cross axis). L'axe principal est généralement horizontal par défaut (de gauche à droite), mais il peut être modifié en utilisant la propriété flex-direction. Les items flex sont disposés le long de cet axe.

    Axe Transversal (Cross Axis) : L'axe transversal est perpendiculaire à l'axe principal. Par défaut, il est vertical (de haut en bas), mais il peut également être modifié avec flex-direction. L'axe transversal est utilisé pour contrôler l'alignement vertical des items flex.

    Propriété flex : La propriété flex est utilisée pour définir la flexibilité des items flex. Elle prend trois valeurs : flex-grow, flex-shrink, et flex-basis. Par exemple, flex: 1 1 auto; signifie que l'item peut grandir et rétrécir, et sa taille de base est automatiquement calculée.

    flex-direction : Cette propriété définit la direction de l'axe principal. Les valeurs courantes sont row (de gauche à droite), row-reverse (de droite à gauche), column (de haut en bas), et column-reverse (de bas en haut).

    justify-content : Cette propriété contrôle l'alignement des items flex le long de l'axe principal. Vous pouvez l'utiliser pour les aligner à gauche, à droite, au centre, ou les répartir uniformément.

    align-items : Elle contrôle l'alignement des items flex le long de l'axe transversal. Vous pouvez l'utiliser pour les aligner en haut, en bas, au centre, etc.

    align-self : Cette propriété permet de personnaliser l'alignement d'un item flex individuellement, en remplacement de l'alignement défini pour tous les items par align-items.

    flex-wrap : Contrôle si les items flex doivent être enveloppés ou non lorsque l'espace est insuffisant. Vous pouvez l'utiliser pour créer des mises en page flexibles qui passent à la ligne si nécessaire.

    flex-flow : Il s'agit d'une propriété abrégée pour définir à la fois flex-direction et flex-wrap en une seule déclaration.

Les flexbox offrent un moyen puissant et efficace de gérer la disposition des éléments dans une page web. Ils sont largement utilisés pour créer des mises en page modernes et réactives.
  #flex p2 

Les modèles de mise en page flexbox, ou simplement "flex", sont un système de mise en page flexible et puissant en CSS (Cascading Style Sheets) qui permet de créer des mises en page complexes et réactives. Flexbox simplifie le positionnement et l'alignement des éléments dans un conteneur, en particulier lorsque les dimensions des éléments sont inconnues ou dynamiques.

Voici une explication des concepts clés de flexbox :

    Conteneur Flex (Flex Container) : Un conteneur flex est un élément qui est configuré pour utiliser le modèle de mise en page flexbox. Vous définissez un conteneur flex en appliquant la propriété display: flex; ou display: inline-flex; à l'élément parent.

    Éléments Enfants (Flex Items) : Les éléments à l'intérieur du conteneur flex sont appelés des "éléments enfants" ou "éléments flex". Ils sont automatiquement disposés dans le conteneur en fonction des règles de flexbox.

    Axe Principal (Main Axis) : L'axe principal est l'axe principal le long duquel les éléments flex sont alignés. Par défaut, l'axe principal est horizontal (de gauche à droite), mais il peut être inversé en utilisant la propriété flex-direction.

    Axe Transversal (Cross Axis) : L'axe transversal est perpendiculaire à l'axe principal. Par défaut, il est vertical (de haut en bas).

    Direction de la Lecture (Writing Mode) : Elle détermine la direction de la lecture du texte (de gauche à droite ou de droite à gauche). Elle peut être influencée par la langue et peut être modifiée en utilisant la propriété direction et d'autres.

    Propriétés Principales : Voici quelques-unes des propriétés principales de flexbox :
        display: flex; : Définit un conteneur flex.
        flex-direction : Définit la direction de l'axe principal.
        flex-wrap : Contrôle le comportement des éléments flex lorsqu'ils ne tiennent pas dans une ligne.
        justify-content : Aligne les éléments le long de l'axe principal.
        align-items : Aligne les éléments le long de l'axe transversal.
        align-self : Contrôle l'alignement individuel des éléments flex.

    Propriétés Flex : Les éléments flex ont des propriétés spécifiques qui contrôlent leur comportement :
        flex-grow : Détermine la capacité d'un élément à grandir par rapport aux autres.
        flex-shrink : Détermine la capacité d'un élément à rétrécir par rapport aux autres.
        flex-basis : Définit la taille de base d'un élément avant la distribution de l'espace disponible.

    Alignement Flex : Flexbox offre un contrôle précis de l'alignement des éléments, tant le long de l'axe principal que de l'axe transversal. Vous pouvez aligner les éléments au centre, à gauche, à droite, en haut, en bas, etc.

    Flexbox vs Grid : Flexbox est idéal pour les mises en page unidimensionnelles (comme les barres de navigation ou les listes) tandis que CSS Grid est plus adapté aux mises en page bidimensionnelles (comme les grilles régulières).

En utilisant ces concepts, vous pouvez créer des mises en page flexibles et réactives qui s'adaptent aux différentes tailles d'écran et de contenu, ce qui en fait un outil précieux pour la conception web moderne.
  
