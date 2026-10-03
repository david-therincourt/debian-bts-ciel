# debian-bts-ciel

Site Jekyll (thème [Just the Docs](https://just-the-docs.com/)) rassemblant les
procédures de post-installation de Debian 13 pour le BTS CIEL
(options Électronique et Physique).

Site publié : <https://david-therincourt.github.io/debian-bts-ciel/>

## Prévisualiser en local

```bash
sudo apt install ruby-full build-essential zlib1g-dev
gem install --user-install bundler
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve --livereload
```

Puis ouvrir <http://127.0.0.1:4000/debian-bts-ciel/>.

## Publication

Le site est construit et déployé par GitHub Actions
(`.github/workflows/pages.yml`) à chaque push sur `main`.
Dans les paramètres du dépôt GitHub : *Settings → Pages → Source : GitHub Actions*.
