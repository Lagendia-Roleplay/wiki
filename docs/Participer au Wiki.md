---
hide:
 - navigation
---

## Préambule

- Vous devez d'abord créer votre compte Github (possibilité d'utiliser votre compte microsoft)
- Vous n'avez pas besoin d'installer quoique ce soit sur votre ordinateur
- Les fichiers sont éditables sur n'importe quel navigateur (et possiblement mobile, mais ça peut être vite le foutoir dans ce cas là)

## Étape 1 : Fork le dossier

Une fois que vous avez créer votre compte GitHub, revenez sur cette page.
Vous devez maintenant cliquer sur **FORK** (tout en haut de la page)
![TUTO - Mettre une page sur le wiki-02-10-2022](https://user-images.githubusercontent.com/30244939/193438880-828f1cf2-322d-40fd-b0b5-e082ddd362ea.png)
![TUTO - Mettre une page sur le wiki-02-10-2022-1](https://user-images.githubusercontent.com/30244939/193438890-bcd87f31-08fd-4878-8352-cbfaf009e74f.png)

Cela créera une copie du wiki sur votre compte GitHub !

Note : Vous pouvez aussi cliquer [ici](https://github.com/Lagendia-Roleplay/wiki/fork).

## Étape 2 : Ouvrir github.dev pour modifier les fichiers

Ensuite, vous devez vous rendre dans la copie du wiki. Normalement, cela s'ouvrira automatiquement après la copie.
Vous aurez quelque chose dans le style :
![TUTO - Mettre une page sur le wiki-02-10-2022-2](https://user-images.githubusercontent.com/30244939/193438909-d76a1cf3-887c-432b-813b-64429cb4eaf6.png)

Ensuite, vous pouvez donc ouvrir le "GitHub.dev", c'est à dire, tout simplement **changer le .com** du lien en **.dev**, comme ceci : `https://github.com/votre_username/wiki` → `https://github.dev/votre_username/wiki`

Cela créera donc un éditeur web de VSCode, qui peut être très pratique !
![TUTO - Mettre une page sur le wiki-02-10-2022-3](https://user-images.githubusercontent.com/30244939/193438916-31d4e467-614f-4c24-a002-eb29dd3dab55.png)

## Étape 3 : Éditer les fichiers

> [!warning] Attention
> - Seulement les fichiers dans `docs`, sauf `docs/_assets`
> - Les images doivent être ajouté dans `docs/_img`

Vous devez maintenant éditer les fichiers. Quelques truc à savoir :
- Le fichier "de base" d'un dossier doit se nommer `index.md`. Dans ce cas vous devez rajouter, en haut du fichier :



	```md
	---
	title: Nom du dossier
	---
	contenu
	```



- Les fichiers sont en **Markdown**, une syntaxe similaire à discord avec quelque différence et rajout. Je vous conseille d'aller jeter un œil à la [syntaxe Markdown](https://cours-web.ch/divers/markdown.html) pour appréhender l'ensemble.
- Le Wiki, spécifiquement, est un poil relou avec les chemins vers les fichiers. Au besoin, les administrateurs s'occuperont de réparer les liens, donc pas besoin de spécifiquement vous en souciez.
- Les images doivent être mises dans **`docs/_img`** avec un nom **lisible**.

Vous pouvez aussi créer votre fichier dans un fichier texte sur votre ordinateur, et le glisser dans le github sans passer par le `.dev`. Attention à bien le placer dans le bon dossier !

## Étape 4 : Validez les modification

Pour que les modifications soient prises en compte, vous devez aller dans le symbole bizarre en forme de points/branches :
![TUTO - Mettre une page sur le wiki-02-10-2022-4](https://user-images.githubusercontent.com/30244939/193438927-e9d8ad13-0c81-4b44-873b-7333873d45b0.png)

Vous cliquez sur le `+` pour mettre en attente les informations. Vous devez aussi marquer un petit message qui décrit ce que vous avez changer sur le wiki :
![TUTO - Mettre une page sur le wiki-02-10-2022-5](https://user-images.githubusercontent.com/30244939/193438933-c0a628ab-ec60-48d8-bc15-1d5cfb157760.png)

Vous cliquez ensuite sur le petit check :
![TUTO - Mettre une page sur le wiki-02-10-2022-6](https://user-images.githubusercontent.com/30244939/193438939-8cde56a8-418e-47a6-871c-bead93628b90.png)

Félicitation ! Vos changements ont été pris en compte.

À chaque fois que vous modifier un fichier, vous devez refaire ce petit truc, pour que les modifications soient bien prises en compte !

## Étape 5 : Proposez ses modifications

Et c'est là que la magie de l'open-source entre en scène !

Retournons dans **github.com** "normal" :
![TUTO - Mettre une page sur le wiki-02-10-2022-7](https://user-images.githubusercontent.com/30244939/193438959-82eca093-20c2-4b1c-94af-de31a5902d14.png)

Vous verrez le message `This branch is x commit ahead of Lagendia-Roleplay:main.`
(le nombre de "commit" correspond au nombre d'édition que vous avez fait.)

Cliquons sur **CONTRIBUTE**.
![TUTO - Mettre une page sur le wiki-02-10-2022-8](https://user-images.githubusercontent.com/30244939/193438969-72dc36da-1491-4ec0-a724-cca1e9853234.png)

Une nouvelle fenêtre apparaît :
![TUTO - Mettre une page sur le wiki-02-10-2022-9](https://user-images.githubusercontent.com/30244939/193438976-3e3f9dc6-0dc0-4136-9e31-d90f90d6e03a.png)

On clique donc sur **Open Pull request**.
![TUTO - Mettre une page sur le wiki-02-10-2022-10](https://user-images.githubusercontent.com/30244939/193438978-e65413c1-f5a7-4df4-affc-8967f7b7ce91.png)

Cette drôle de fenêtre apparaît. Ne vous inquietez pas !

Il vous suffit donc maintenant de laisser un commentaire expliquant vos éditions et de créer la pull request.
![TUTO - Mettre une page sur le wiki-02-10-2022-11](https://user-images.githubusercontent.com/30244939/193438981-88ec910d-8d91-4fb7-88b3-e4b7b5615381.png)

Maintenant, c'est au tour des ADMINISTRATEURS !

Vous n'avez plus besoin de rien faire pour le moment !
Les administrateurs s'occuperont de vous avertir et, au besoin, éditer les fichiers. Ensuite, la pull-request sera fusionnée sur le wiki.

>[!warning] Il est possible qu'il y ait des "conflits", c'est à dire que sur le wiki, les fichiers sont trop différents pour être fusionné. Pas de panique, on vous expliquera pas à pas ce qu'il faudra faire dans ce cas là.

## Bonus : Mettre à jour sa copie

Une fois que votre pull-request est fusionnée avec le wiki, vous pouvez :
- Supprimez le fork
- Ou le conserver

Si vous le conservez pour le mettre à jour dans le futur, il vous suffira de cliquez sur le bouton : "sync fork" :
![TUTO - Mettre une page sur le wiki-02-10-2022-12](https://user-images.githubusercontent.com/30244939/193438992-44b3b4f7-2c9d-492a-8a11-c46233da89c1.png)

Dans le cas où il y a des conflits lors de la mise à jour, il suffit de MP un admins et on vous expliquera pas à pas la procédure à suivre !

## Note

Vous pouvez directement "glisser" vos fichiers `.md` dans Github, dans le dossier voulu de `docs`
Un bon éditeur de fichier markdown est [Typora](https://typora.io/), ou [zettlr](https://www.zettlr.com/) mais vous pouvez aussi faire à partir d'[Obsidian](https://obsidian.md/) !

### Obsidian

- Si vous utilisez [Obsidian](https://obsidian.md/), vous pouvez ouvrir le dossier `_template/docs` directement dedans en tant que Vault.
- Dans ce cas là, vous devrez installer [git](https://git-scm.com/) et `git clone <fork>`. Ensuite, vous devrez valider vos modification à l'aide de la commande `git add . && git commit -am "Votre mis à jour" && git push
