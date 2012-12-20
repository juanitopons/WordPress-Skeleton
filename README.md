# WordPress Skeleton

This is simply a skeleton repo for a WordPress site. Use it to jump-start your WordPress site repos, or fork it and customize it to your own liking!

## Assumptions

* WordPress as a Git submodule in `/wp/`
* Custom content directory in `/content/` (cleaner, and also because it can't be in `/wp/`)
* `wp-config.php` in the root (because it can't be in `/wp/`)
* All writable directories are symlinked to similarly named locations under `/shared/`.

## To start installation in local

* Clone local-config-sample.php to local-config.php and edit the database options to your local database access.
* Go to http://yourdomain/wp to start the installation.
* Remove the trailing /wp from home option in wp_options table.
* Create shared directory with writable subdirectories inside.

