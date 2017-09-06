# Simple ripple effect

Ce repository contient deux fichiers qui vous serviront à créer très facilement des effets dits de *vague* ou *ripple effect* en anglais, inspirés de [Google Material Design](https://material.io/guidelines/motion/material-motion.html#material-motion-implications-of-motion).


## Demo
![ScreenShot](https://github.com/audeo23/simple-ripple-effect/blob/master/media/Ripple%20effect%20demo.gif)


## Utilisation


### Etape 1 : Inclure jQuery :

La partie script est écrite en jQuery, il faut donc l'inclure dans votre code HTML. Si vous n'avez jamais vu ou utilisé jQuery auparavant, aucune inquiétude, vous n'aurez rien à coder. Pour ce faire, copier / coller la ligne de code suivante dans le *Head* de votre code HTML :
```html
<script src="https://code.jquery.com/jquery-2.1.4.js"></script>
```

### Etape 2 : Inclure la feuille de style CSS et le code JavaScript

De même qu'avant, dans le *Head* de votre code HTML, copier / coller les deux lignes de code suivantes : 
```html
<link href="ripple_style.css" rel="stylesheet" type="text/css" />
<script src="ripple_script.js"></script>
```
**Attention** : Veillez à ce jQuery (étape 1) soit inclut **avant** le code Javasscript (étape 2) sinon votre navigateur vous renverra une erreur.


### Etape 3 : Appliquer l'effet à votre élément

L'effet peut être appliqué sur tout type d'élement HTML : div, table, li, ul, button, ...
Il suffit d'insérer l'attribut *data-ripple* dans l'élément HTML de votre choix, par exemple : 
```html
<div data-ripple class="foo baar"> </div>
```

Par défaut, l'effet de vague aura une couleur blanche. Pour y appliquer une couleur différente, il suffit de donner à l'attribut *data-ripple*, la valeur du code RGB ou RGBa (avec prise en charge de l'opcacité) de la couleur désirée. Par exemple, pour une vague rouge légèrement transparente :
```html
<div ata-ripple="rgba(155,0,0, 0.5)" class="foo baar"> </div>
```
