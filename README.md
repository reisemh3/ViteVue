# ViteVue

# Les éléments HTML

<p>
<b>h1,2,3...</b> correspond à un titre avec h et une taille avec le chiffre.
<b>p</b> correspond à un paragraphe
<b>br</b> correspond à un saut de ligne.
<b>a</b> correspond à un tag (lien) vers une autre page defini avec le <b>href</b>.
<b>section</b> permet de créer divers section et avec un id pour connaitre la section dont l'on parle (faciliter le renvoi à une section existante) / Le target renvoie la section sur une nouvelle page.
<b>img</b> permet d'afficher une image à partir d'une source / <b>alt</b> donne un nom à l'image.
<b>ol</b> correspond à order liste, qui contiendra ensuite la liste des éléments de de la liste avec <b>li</b> alant de 1 et ainsi de suite.
<b>ul</b> correspond à unorder liste, qui contiendra ensuite la liste des éléments de de la liste avec <b>li</b> mais sans ordre donc remplacer par un point.
<b>span</b> va permettre de définir un style à l'élément qu'il contient malgré qu'il soit déjà stylisé.
<b>div</b> est l'élément le plus important qui va vous permettre de créer divers blocs.
<b>input</b> va vous permettre d'ajouter un bouton de type radio/checkbox/submit etc.
<b>form</b> vous servira à la création d'un formulaire.
<b>style</b> vous permet de créer directement des style et divers fomules pour mettre en forme vos élémements.
<br>
</p>

# Les éléments CSS

<p>
Pour commencer vous aurez besoin de créer un nouveau fichier avec un "nom" et l'extentision CSS. Ce qui vous donnera nom.css
Dans notre cas, nous l'appellerons "style.css"

Une fois nouveau fichier créé, vous aurez besoin de le relier à votre page HTML afin d'appliquer les styles que vous aurez créer.
Nous utiliserons pour cela un <b>link</b> qui sera placer directement dans le <p>head</p> de votre fichier ".HTML" où vous souhaiter injecter vos styles.
Après cela, vous devez indiquer qu'il sagit d'un fichier de style et le lien du fichier CSS que vous voulez utiliser avec le <b>href</b>.

Ce qui vous donnera :
    >link rel="stylesheet" href="style.css"<
<br>
</p>
