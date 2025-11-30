# Comment installer la config
Dans le terminal, executez les commandes suivantes :
`cd`
`git clone https://github.com/epitavim/config`
`mv config/vimconfig .vimrc`
Puis, allez dans vim, allez en mode normal avec `Esc` puis executer `:PluginInstall`
Voila ;)

# Commandes
- souris fonctionnelle (pour bouger le curseur et selectionner du texte)
- autocomplétion avec `Tab`
- `Ctrl + C` `Ctrl + V` `Ctrl + Z` `Ctrl + X` `Ctrl + A` fonctionnelles (comme dans un éditeur de texte)
- `Ctrl + Q` pour sauvegarder et quitter
- `Ctrl + S` pour sauvegarder (et détection d'erreur  automatique)

- `F5` pour compiler et exécuter le fichier courant dans vim
- `F6` pour lancer GDB (Termdebug) dan vim (pour le quitter, écrivez `quit` dans gdb)
- `F1` pour commenter/decommenter le main
- `F4` pour afficher l'erreur de la ligne actuelle dans une bulle
- `F7` pour une compilation et execution plus "classique"
