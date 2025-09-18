# Site personnel de Jean-Marie Gilliot

Site web personnel créé avec Jekyll et le thème Minimal Mistakes.

## Description

Ce site personnel contient :
- Une page d'accueil de présentation
- Une section blog avec articles organisés par catégories et tags
- Une page "À propos" pour présenter l'auteur
- Une navigation intuitive et un design responsive

## Technologies

- [Jekyll](https://jekyllrb.com/) - Générateur de site statique
- [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) - Thème Jekyll
- [GitHub Pages](https://pages.github.com/) - Hébergement

## Structure

```
├── _config.yml          # Configuration Jekyll
├── _data/
│   └── navigation.yml   # Configuration du menu
├── _pages/              # Pages statiques
├── _posts/              # Articles de blog
├── _sass/               # Fichiers de style personnalisés
├── assets/              # Images et autres ressources
├── Gemfile              # Dépendances Ruby
└── index.md             # Page d'accueil
```

## Installation locale

Pour tester le site en local :

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Le site sera accessible à l'adresse `http://localhost:4000`.
