# hatherstone

Static Hugo version of hatherstone.com, migrated from WordPress (Storefront theme + MetaSlider). The WooCommerce shop was dropped in the migration.

## Run locally

    hugo server          # http://localhost:1313
    hugo --gc --minify   # build to ./public

## Layout

- `hugo.toml`: site title, Google Analytics ID, logo, social links, menus
- `content/_index.md`: homepage; slider images are listed in front matter
- `content/*.md`: Contact us and Maintenance pages
- `layouts/`: templates that reproduce the WordPress/Storefront markup
- `static/wp-content/…`: theme/plugin CSS, JS, fonts and uploads copied from the
  live site at their original paths, so existing image URLs keep working
