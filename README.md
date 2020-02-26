## Améliorer la lisibilité du projet de loi relatif à la communication audiovisuelle et à la souveraineté culturelle à l'ère numérique

Les projets de loi étant écrits sous la forme d'instructions modifiant différents codes, il pourrait être plus simple de travailler avec ces modifications sous la forme de différences sur le contenu directement.

Le but de ce projet est donc d'appliquer les "instructions" de chaque article du projet de loi pour ensuite produire un texte comparatif pour chaque article.

## Résultats

*en cours*

## Comment contribuer ?

### Organisation

- La branche `loi-en-vigeur` contient les codes et lois avant modification
- Les branches `articles-<numéro de l'article>` se basent sur la `loi-en-vigeur` et appliquent l'article.

### Ajouter un article

Tout les 64 articles du projet du loi ne sont pas encore fait, la façon la plus simple de participer est d'en faire un qui n'est pas encore fait.

 1. Ouvrez [le projet de loi](http://www.assemblee-nationale.fr/dyn/15/textes/l15b2488_projet-loi)
 2. Prendre un article
 3. Modifier la loi en vigeur
    * Si l'article modifie un code, il faut éditer ce code
    * Si l'article s'applique directement, alors il faut créer un nouveau fichier `loi`, et mettre dans ce fichier l'article et son texte, comme dans [cet exemple](https://github.com/regardscitoyens/pjl-retraites/compare/loi-en-vigeur...article-018).

**Si besoin d'aide, n'hesitez pas me contacter via un courriel à `damien@dam.io`**

### Inspirations

- [Duralex/Sedlex](https://github.com/Legilibre/SedLex) qui automatise ce qui est fait ici à la main
- [Archeo Lex](http://archeo-lex.fr/) qui est utilisé comme source pour les codes
- [La Fabrique de la loi](http://lafabriquedelaloi.fr/) qui produit un equivalent des textes comparatifs en permettant de comparer les version des projets de loi
- [Le même projet pour le PJL retraites](https://github.com/regardscitoyens/pjl-retraites)
