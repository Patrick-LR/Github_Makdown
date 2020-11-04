# Markown-memento
Voici un petit fichier memento pour vous indiquer les principales syntaxes que vous pouvez utiliser en markdown.
Pour voir les détails de la syntaxe, cliquez que l'icone d'édition de ce fichier.

----------------

####Mettre un mot en italique

Voici un mot *en italique* 

Votre mot se trouve entre astérisques `*mon-mot*`

-----------------

####Mettre un mot en gras

Voici un mot __en gras__ ! 

Votre mot se trouve entre deux `__underscores__` 

-----------------

####Les titres

# Titre de niveau 1 
Pour un titre de niveau 1 (h1), il faut placer un `#titre` devant votre titre.

## Titre de niveau 2
Pour un titre de niveau 2 (h2), il faut cette fois deux `##titre` devant votre titre

Et ainsi de suite jusqu'au h6.

-----------------

####Aller à la ligne en fin de phrase

Pour faire un  
changement de ligne

Votre ligne doit se terminer par 2 `espaces` pour faire ce qu'on appelle un __retour-chariot__, c'est à dire aller à la ligne.

-----------------

####Faire une liste à puces

* Une puce
* Une autre puce
* Et encore une autre puce !

Il faut simplement placer un astérisque devant les éléments de votre liste.

`* Une puce`

`* Une autre puce`

`* Et encore une autre puce !`

######Pour faire une liste ordonnée : 

1. Et de un
2. Et de deux
3. Et de trois

`1. Et de un`
`2. Et de deux`
`3. Et de trois`

######Pour imbriquer une liste dans une autre :

* Une puce
* Une autre puce
    * Une sous-puce
    * Une autre sous-puce
* Et encore une autre puce !

`* Une puce`

`* Une autre puce`

    `* Une sous-puce`
    
    `* Une autre sous-puce`
    
`* Et encore une autre puce !`

1. Une puce
2. Une autre puce
    1. Une sous-puce
    2. Une autre sous-puce
3. Et encore une autre puce !

`1. Une puce`

`2. Une autre puce`

    `1. Une sous-puce`
    
    `2. Une autre sous-puce`
    
`3. Et encore une autre puce !`

-----------------

####Faire une citation

> Ceci est un texte cité. Vous pouvez répondre
> à cette citation en écrivant un paragraphe
> normal juste en-dessous !

Il vous suffit d'ajouter un `>` devant votre citation.

`> Ceci est un texte cité. Vous pouvez répondre à cette citation en écrivant un paragraphe normal juste en-dessous !`

-----------------

####Ecrire du code

#####Un code entier

Voici un code en C :

    int main()
    {
        printf("Hello world!\n");
        return 0;
    }
    
Il vous suffit d'écrire votre phrase de présentation comme n'importe quelle phrase et d'écrire votre code à la ligne.
    
`Voici un code en C :`

    int main()
    {
        printf("Hello world!\n");
        return 0;
    }

#####Juste un morceau de code

`<h1>Titre</h1>`

Il vous suffit d'entourer votre morceau de code avec deux accents graves.
Pour faire un accent grave, il vous suffit de faire `AltGr` + `7` sur votre clavier.

-----------------

####Mettre un lien

Rendez-vous sur [Simplonline](http://www.simplonline.com) !

Il vous faut le mot sur lequel vous souhaitez faire votre lien entre crochets [ ], puis votre lien entre parenthèses ( ).

`Rendez-vous sur [Simplonline](http://www.simplonline.com) !`

-----------------

####Intégrer une image

La syntaxe est la même que pour un lien, il suffit juste d'ajouter un point d'exclamation devant les crochets. 

Ce que vous mettez entre crochet est le texte alternatif de l'image, que nous vous conseillons fortement d'intégrer à chaque fois que vous mettez une image.

Important : ça ne marche qu'avec des url d'images prises sur le web.

`![Simplon.co](http://simplon.co/wp-content/uploads/2015/04/if-coder-keep-coding-else-learn-with-simplon-2-600x675.png)`

![Simplon.co](http://simplon.co/wp-content/uploads/2015/04/if-coder-keep-coding-else-learn-with-simplon-2-600x675.png)

-----------------

####Barre de séparation

Pour faire une barre de séparation il vous suffit d'écrire plusieurs `-` d'affilé. Plus vous en mettrez plus le trait sera épais.

`-----------------`

----------------

Markdown Cheatsheet<a name="TOP"></a>
===================

- - - - 
# Heading 1 #

    Markup :  # Heading 1 #

    -OR-

    Markup :  ============= (below H1 text)

## Heading 2 ##

    Markup :  ## Heading 2 ##

    -OR-

    Markup: --------------- (below H2 text)

### Heading 3 ###

    Markup :  ### Heading 3 ###

#### Heading 4 ####

    Markup :  #### Heading 4 ####


Common text

    Markup :  Common text

_Emphasized text_

    Markup :  _Emphasized text_ or *Emphasized text*

~~Strikethrough text~~

    Markup :  ~~Strikethrough text~~

__Strong text__

    Markup :  __Strong text__ or **Strong text**

___Strong emphasized text___

    Markup :  ___Strong emphasized text___ or ***Strong emphasized text***

[Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>

    Markup :  [Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>

[heading-1](#heading-1 "Goto heading-1")
    
    Markup: [heading-1](#heading-1 "Goto heading-1")

Table, like this one :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

Adding a pipe `|` in a cell :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | \|

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \| 
```

Left, right and center aligned table

Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell

```
Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
```

`code()`

    Markup :  `code()`

```javascript
    var specificLanguage_code = 
    {
        "data": {
            "lookedUpPlatform": 1,
            "query": "Kasabian+Test+Transmission",
            "lookedUpItem": {
                "name": "Test Transmission",
                "artist": "Kasabian",
                "album": "Kasabian",
                "picture": null,
                "link": "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp"
            }
        }
    }
```

    Markup : ```javascript
             ```

* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2

~~~
 Markup : * Bullet list
              * Nested bullet
                  * Sub-nested bullet etc
          * Bullet list item 2

-OR-

 Markup : - Bullet list
              - Nested bullet
                  - Sub-nested bullet etc
          - Bullet list item 2 
~~~

1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered

~~~
 Markup : 1. A numbered list
              1. A nested numbered list
              2. Which is numbered
          2. Which is numbered
~~~

- [ ] An uncompleted task
- [x] A completed task

~~~
 Markup : - [ ] An uncompleted task
          - [x] A completed task
~~~

- [ ] An uncompleted task
    - [ ] A subtask

~~~
 Markup : - [ ] An uncompleted task
              - [ ] A subtask
~~~

> Blockquote
>> Nested blockquote

    Markup :  > Blockquote
              >> Nested Blockquote

_Horizontal line :_
- - - -

    Markup :  - - - -

_Image with alt :_

![picture alt](http://via.placeholder.com/200x150 "Title is optional")

    Markup : ![picture alt](http://via.placeholder.com/200x150 "Title is optional")

Foldable text:

<details>
  <summary>Title 1</summary>
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>
<details>
  <summary>Title 2</summary>
  <p>Content 2 Content 2 Content 2 Content 2 Content 2</p>
</details>

    Markup : <details>
               <summary>Title 1</summary>
               <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
             </details>

```html
<h3>HTML</h3>
<p> Some HTML code here </p>
```

Link to a specific part of the page:

[Go To TOP](#TOP)
   
    Markup : [text goes here](#section_name)
              section_title<a name="section_name"></a>    

Hotkey:

<kbd>⌘F</kbd>

<kbd>⇧⌘F</kbd>

    Markup : <kbd>⌘F</kbd>

Hotkey list:

| Key | Symbol |
| --- | --- |
| Option | ⌥ |
| Control | ⌃ |
| Command | ⌘ |
| Shift | ⇧ |
| Caps Lock | ⇪ |
| Tab | ⇥ |
| Esc | ⎋ |
| Power | ⌽ |
| Return | ↩ |
| Delete | ⌫ |
| Up | ↑ |
| Down | ↓ |
| Left | ← |
| Right | → |

Emoji:

:exclamation: Use emoji icons to enhance text. :+1:  Look up emoji codes at [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

    Markup : Code appears between colons :EMOJICODE:
