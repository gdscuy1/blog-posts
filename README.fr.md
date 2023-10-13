# **GDSC Université de Yaoundé 1 Social**

+-------------------------------+<br>
&ThinSpace;| &ThickSpace; Version: <kbd>[<img title="English" alt="Française" src="https://github.com/madebybowtie/FlagKit/raw/master/Assets/PNG/US@2x.png?raw=true" width="22">](./README.fr.md)</kbd> [*English (En)*](./README.fr.md) &ThickSpace; |<br>
+-------------------------------+

Il s'agit d'un référentiel contenant les liens sociaux des membres de la communauté des Clubs Étudiants Développeurs Google de l'Université de Yaoundé 1.

# 🎃 HacktoberFest 2023 🎃

Si vous êtes venu ici pour le Hacktoberfest, vous êtes au bon endroit 🦇️ :

Célébrez le [Hacktoberfest](https://hacktoberfest.com/) en vous impliquant dans la communauté open source en accomplissant certaines tâches de ce projet.
## Qu'est-ce que la Hacktoberfest ?

[HacktoberFest](https://hacktoberfest.com/) est l'événement annuel de digitalocean qui encourage les gens à contribuer à l'open source tout au long du mois d'octobre. Une grande partie de l’infrastructure technologique moderne, y compris certains produits propres à DigitalOcean, repose sur des projets open source construits et maintenus par des personnes passionnées qui, souvent, n’ont pas le personnel ou les budgets nécessaires pour faire autre chose que de maintenir le projet en vie. HacktoberFest a pour objectif de redonner à ces projets, d'affiner les compétences et de célébrer tout ce qui concerne l'open source, en particulier les personnes qui rendent l'open source si spécial.

Ce référentiel est ouvert à tous les membres de la communauté GitHub. Tout membre peut contribuer à ce projet sans être collaborateur.

## Comment puis-je contribuer ?

Contributions
Il y a 1 tâche disponible et chaque tâche sera considérée comme valide par l'équipe du Hacktoberfest si elle est correctement exécutée. Ci-dessous la tâche :

Prérequis **Fork et Rendre le projet disponible localement**. Exécutez la commande ci-dessous pour cela :

    git clone https://github.com/<votre-github-username>/blog-posts.git

- Créer une branche

```
git checkout -b myBlog main
```

- Effectuez vos modifications. Créez un fichier dans le répertoire [**archives/2023**](./archives/2023/). (nom de fichier = \<**votre-nom d'utilisateur-github**\>.json>)
- Répertoriez tous les articles de blog technique (vous pouvez en rechercher sur Google), autant que vous le souhaitez. Il devra respecter les formats suivants :
  
### Pour un seul article de blog.
Utilisez ce format si vous souhaitez soumettre un seul article de blog. [Exemple](./archives/2023/example-single.json)

```json
 {
    "title": "Titre du billet de blog",
    "description": "Une brève description",
    "url": "Lien vers l'article de blog",
    "author": "Auteur du contenu du blog"
  }
```
### Pour plusieurs articles de blog.
Utilisez ce format si vous souhaitez soumettre plusieurs articles de blog. [Exemple](./archives/2023/example-multiple.json)
```json
{
  "posts": [
    {
    "title": "Titre du billet de blog",
    "description": "Une brève description",
    "url": "Lien vers l'article de blog",
    "author": "Auteur du contenu du blog"
  },
    {
    "title": "Configurer un serveur Apache sur Ubuntu",
    "description": "Un processus résumé d'installation d'un serveur Apache",
    "url": "https://onecode.hashnode.dev/setting-up-an-apache-server-on-ubuntu",
    "author" : "Ndi Lionel"
  }
   ]
}
```

## S'engager
Veuillez noter ce qui suit avant de vous engager
1. Les liens vers les articles de blog doivent être actifs et publics.
2. Tous les auteurs doivent être le(s) véritable(s) auteur(s) du billet de blog.
3. Tous les domaines publics sont acceptés.
4. Votre demande d'extraction sera fermée si vous fournissez un auteur d'article de blog non valide.
5. Aucune modification volontaire des fichiers existants. Si vous remarquez un problème avec un fichier, veuillez créer une [Issue](https://github.com/gdscuy1/blog-posts/issues/new)

Si tout va bien, procédez avec les commandes suivantes :
```
git add .
git commit -m 'feat : ajout de mon article de blog : <github-username>'
git push origin myBlog
```

- Créez une nouvelle pull request à partir de votre référentiel forké (cliquez sur l'onglet « Nouvelle Pull Request » situé en haut de votre dépôt). Assurez-vous de comparer entre les forks, puis sélectionnez ce référentiel comme cible
- Ajouter des réviseurs (facultatif)
- Attendez l'examen de votre demande de tirage et l'approbation de la fusion !

- **Veuillez STAR ce référentiel** si vous vous êtes amusé !

### Merci à tous nos contributeurs

![contributeurs](./CONTRIBUTEURS.svg)

Réalisé avec :purple_heart: