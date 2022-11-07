# cdelledonne.eu

Generated with [Hugo](https://gohugo.io/) using the
[Anatole](https://github.com/lxndrblz/anatole) theme.

## Cloning

```sh
git clone --recurse-submodules git@github.com:cdelledonne/cdelledonne.eu.git
```

## Initial set-up

Add theme as submodule:

```sh
git submodule add git@github.com:lxndrblz/anatole.git themes/anatole
```

## Theme configuration

Replace list-based home page with simple page
(https://github.com/lxndrblz/anatole/issues/2):

```sh
cp themes/anatole/layouts/_default/single.html layouts/index.html
```

Copy `sidebar.html` layout from theme default for customization:

```sh
cp themes/anatole/layouts/partials/sidebar.html layouts/partials/sidebar.html
```

Change fonts and dimensions:
* https://github.com/lxndrblz/anatole/issues/77
* https://github.com/lxndrblz/anatole/issues/87
