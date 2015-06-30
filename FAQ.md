---
title: "Foire Aux Questions"
permalink: FAQ/
layout: default
comments: false
markdown: kramdown
kramdown: 
  parse_block_html: true
---
{::options parse_block_html="true" /}

### *Le serveur est-il gratuit ?* 

Oui, l'accès au serveur est gratuit. La boutique présente sur le site permet d'avancer plus vite dans le jeu, mais tous les articles qu'elle contient peuvent être obtenus sans débourser un centime, uniquement avec la monnaie du jeu.
<hr>

### *La TNT est-elle activée sur le serveur ? Et le feu ?*

La TNT et le feu sont activés sur le serveur, sauf dans certaines zones sécurisés comme le spawn par exemple..
<hr>

### *Peut-on utiliser des packs de ressource ?*

Vous avez tout à fait le droit d’utiliser les textures packs qui vous conviennent. Il est par contre interdit d'utiliser un pack de texture spécial dans le but de tricher, comme les packs de ressources "X-Ray" !
<hr>

### *Est-ce que le pvp (player versus player ou joueur contre joueur) est activé sur le serveur ?*

Oui, il est activé sauf dans le spawn et dans certaines zones protégées.
<hr>

### *Pourquoi quand je creuse le bloc réapparaît ?*

Ce phénomène s’explique de trois façons :

 * Le lag, qui fait que le serveur n’a pas pris en compte le cassage de ce bloc ou que l’information n’est pas encore transmise au client.
 * La zone est sous l’effet d’un claim, c’est à dire que la zone à été protégée à l’aide d’un plugin côté serveur pour empêcher toute personne non autorisée à accéder à cette zone. Aucune action n’est alors possible => impossible de poser un cube ou d’en casser un notamment.
 * L'antichest fait des siennes et croit que vous utilisez un programme pour casser les blocs plus vite. Si ce n'est pas le cas, contactez un membre du Staff.
<hr>

### *Quels sont les mods autorisés ?*

Les mods de cheat sont, bien évidemment, tous interdits. Tout contrevenant s’expose à des sanctions lourdes, allant jusqu'au ban définitif.<br>
Les seuls mods autorisés actuellement sont Optifine et ShaderMod. Les mods ajoutant des cartes avec radar sont interdits.

## Enchères avec Auctions

### *Peut-on vendre des items différents dans une même enchère ?*
Non, il est impossible de vendre des items différent en tant que lot dans une même enchère. Il est néanmoins possible de vendre plusieurs items identiques si ceux-ci se *stackent*, *s'empilent*.

### *Comment lancer une enchère ?* 

Lancer une enchère est très simple. Vous devez d'abord sélectionnez l'item que vous voulez vendre en le mettant dans votre barre d'item puis en le mettant dans votre main. Il faut ensuite entrer une commande afin de définir les paramètres de la vente, `/auction start <nombre d'item à vendre> <mise à prix> [pas d'enchère] [prix pour vente instantanée]`

- Le premier paramètre définit le nombre d'item à vendre. Vous ne pouvez vendre que ce qui est dans votre main, cela limite donc ce nombre à 64. Pour vendre tout ce qui est dans votre main, vous pouvez utiliser `all`.
- Le second paramètre définit la mise à prix en $. Il ne peut être inférieur à 50.
- Le troisième paramètre est optionnel. Il définit le pas d'enchère par défaut, si les enchérisseurs ne la définise pas.
- Le quatrième paramètre est lui aussi optionnel. Il permet de définit un montant qui vendra l'item au premier enchérisseur à enchérir ce montant ou plus.

### *Est-ce que lancer une enchère est payant ?*
Lancer une enchère coute 10$. Une fois l'enchère terminée et l'item vendue, le serveur récupère 10% de commision.

### *Les messages d'Auctions m'ennuyent, je peux les désactiver ?*
Vous pouvez désactiver les messages d'Auctions avec la commande `/auction spam`.<br>
Vous ne verrez plus aucun message d'Auctions et vous ne pourrez plus utiliser Auction (ni pour commencer une enchère, ni pour enchérir)<br>. 
Pour réactiver les messages d'Auctions, réexcutez la commande `/auction spam`.<br>

<div class="alert alert-danger" role="alert">Un bug provoque l'impossibilité de réactiver les messages d'Auctions chez certains joueurs. La commande est donc à utiliser avec précautions et en connaissance de cause.
</div>