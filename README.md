# ViteVue

# Les éléments HTML

<ul>
<li><b>h1,2,3...</b> correspond à un titre avec h et une taille avec le chiffre.</li>
<li><b>p</b> correspond à un paragraphe.</li>
<li><b>br</b> correspond à un saut de ligne.</li>
<li><b>a</b> correspond à un tag (lien) vers une autre page defini avec le <b>href</b>.</li>
<li><b>section</b> permet de créer divers section et avec un id pour connaitre la section dont l'on parle (faciliter le renvoi à une section existante) / Le target renvoie la section sur une nouvelle page.</li>
<li><b>img</b> permet d'afficher une image à partir d'une source / <b>alt</b> donne un nom à l'image.</li>
<li><b>ol</b> correspond à order liste, qui contiendra ensuite la liste des éléments de de la liste avec <b>li</b> alant de 1 et ainsi de suite.</li>
<li><b>ul</b> correspond à unorder liste, qui contiendra ensuite la liste des éléments de de la liste avec <b>li</b> mais sans ordre donc remplacer par un point.</li>
<li><b>span</b> va permettre de définir un style à l'élément qu'il contient malgré qu'il soit déjà stylisé.</li>
<li><b>div</b> est l'élément le plus important qui va vous permettre de créer divers blocs.</li>
<li><b>input</b> va vous permettre d'ajouter un bouton de type radio/checkbox/submit etc.</li>
<li><b>form</b> vous servira à la création d'un formulaire.</li>
<li><b>style</b> vous permet de créer directement des style et divers fomules pour mettre en forme vos élémements.</li>
</ul>

# Les éléments CSS

<p>
Pour commencer vous aurez besoin de créer un nouveau fichier avec un "nom" et l'extentision CSS. Ce qui vous donnera "nom.css".<br>
Dans notre cas, nous l'appellerons "style.css".<br>
<br>
Une fois nouveau fichier créé, vous aurez besoin de le relier à votre page HTML afin d'appliquer les styles que vous aurez créer.<br>
Nous utiliserons pour cela un <b>link</b> qui sera placer directement dans le <b>head</b> de votre fichier ".HTML" où vous souhaiter injecter vos styles.<br>
Après cela, vous devez indiquer qu'il sagit d'un fichier de style et le lien du fichier CSS que vous voulez utiliser avec le <b>href</b>.<br>
<br>
Ce qui vous donnera :<br>
    <b>link rel="stylesheet" href="style.css"</b>
<br>
<br>
Pour commencer dans votre fichier CSS, vous aurez des selecteurs qui vont contenir dans des acolades, des propriétées et des valeurs.
<b>Selecteur {<br>
    propriétés: valeurs;<br>
}</b><br>
<br>
Vous trouverez surtout deux style de selecteurs, l'un avec un . avant le nom de l'élements et lautre sans, sous la forme suite :
<br>
<ul>
<li><b>Selecteur {}</b></li>
<li><b>.Selecteur {}</b></li>
</ul>
Lorsque vous indiquer directement le selecteur sans le . vous attriburez directement les propertiées et les valeurs que vous aurez mis à l'intérieurs dans le type du selecteur de votre page html.<br>
Et dans le cas de l'ajouter du . dans .Seclecteur, le style sera appeler grace à l'element class="Selecteur" dans un élément de votre HTML<br>
<br>
Maintenant, nous allons voir quelques propriétés :<br>
<ul>
<li><b>color:</b> permet d'ajouter une couleur.</li>
<li><b>font-size:</b> ce qui permet de changer la taille du texte.</li>
<li><b>font-family:</b> va changer la police de votre texte.</li>
<li><b>:</b></li>
<li><b>:</b></li>
<li><b>:</b></li>
<li><b>:</b></li>
</ul>
<br>
Maintenant, nous allons voir quelques valeurs :<br>
<ul>
<li><b>px</b> correspond à une taille en pixel.</li>
<li><b>em</b> correspond à une taille en % et 1em correspond donc à 100% de la taille initiale.</li>
<li><b>font-family:</b> va changer la police de votre texte.</li>
<li><b>:</b></li>
<li><b>:</b></li>
<li><b>:</b></li>
<li><b>:</b></li>
</ul>
</p>
