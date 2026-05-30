# automatismes-eam
Atomes pour générer des beamer sur les automatismes en 1ère

<img width="1198" height="904" alt="image" src="https://github.com/user-attachments/assets/355b3a9f-1b62-4cf1-b10f-41f3f2e50069" />

# utilisation automatisée
La fichier `beamerthemeautom.sty` contient le thème `beamer` servant de base à la présentation des automatismes.

Le fichier `autom_beamer.tex` contient un exemple d'utilisation, en mode autonome et en mode automatisé.

# script en ligne
Les fichiers de ce dépôt servent de base au générateur en ligne https://bactex.cpierquet.fr/index.php?page=constructeur_automeam

# présentation des fichiers .tex
Chaque fichier `tex` se présente sous la forme :

```latex
%=== <chemin/nom>.tex || <Thème> || Sous-Thème

% ÉNONCÉ

\smallskip

\eamreponsesautom[<nbcols>]{Rép A}{Rép B}{Rép C}{Rép D}
```
