# Drupal project template

Get a working Drupal website locally in minutes with this fine-tuned template.

Based on the great [Drupal project template](https://github.com/MatthieuScarset/drupal-template).

## Requirement

Install [Lando](https://docs.lando.dev/drupal/) on your machine.

## Usage

```bash
git clone https://github.com/MatthieuScarset/drupal-test.git drupal-test
cd drupal-test
cp .env.example .env
lando start
lando composer install -o
lando drush site:install --existing-config -y
lando drush user:password admin admin
lando drush user:login # -> Ctrl+Click the URL to open your site :)
```
