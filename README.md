My Project Skeleton (@kzykhys)
==============================

[![Latest Stable Version](https://poser.pugx.org/kzykhys/composer-project-skeleton/v/stable.png)](https://packagist.org/packages/kzykhys/composer-project-skeleton)

* PHPUnit ([See phpunit.xml.dist](phpunit.xml.dist))
* Travis CI ([See .travis.yml](.travis.yml))
    * Coveralls
    * SensioLabs Security Checker

Usage
-----

### 1) Create a project

```
composer create-project -s stable kzykhys/composer-project-skeleton PROJECT_DIR
cd PROJECT_DIR
```

### 2) Update composer.json

Please update `name`, `description`, `require`...

``` json
{
    "name": "",
    "description": "",
    "minimum-stability": "stable",
    "require": {
        "php": ">=5.3.2"
    },
    "autoload": {
        "psr-0": {
            "": "src"
        }
    }
}
```

### 3) Update README.md (This file)

Write your project's readme.

### 4) Remove `.gitkeep` (optional)

```
rm src/.gitkeep test/.gitkeep
```

### 5) Init a git repository

```
git init .
git commit -a -m 'Initial commit'
```

### 6) Push your commits to Github

```
git remote add origin git@github.com:username/repository.git
git push -u origin master
```

### 7) Travis CI and Coveralls

Activate your repo on [Travis CI](https://travis-ci.org/) and [Coveralls](https://coveralls.io/).

### 8) Packagist

Register your repo on [Packagist](https://packagist.org/). You can generate a badge on [Badge Poser](https://poser.pugx.org/).

### 9) Service Hooks

Don't forget to activate service hooks.