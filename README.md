# Dman013/Eloquence

[![Build Status](https://travis-ci.org/jarektkaczyk/eloquence.svg)](https://travis-ci.org/jarektkaczyk/eloquence) [![Downloads](https://poser.pugx.org/dman013/eloquence/downloads)](https://packagist.org/packages/dman013/eloquence) [![stable](https://poser.pugx.org/dman013/eloquence/v/stable.svg)](https://packagist.org/packages/dman013/eloquence)

Easy and flexible extensions for the [Eloquent ORM](https://laravel.com/docs/eloquent).

Currently available extensions:

1. [Searchable](https://github.com/jarektkaczyk/eloquence-base) query - crazy-simple fulltext search through any related model 
1. [Validable](https://github.com/jarektkaczyk/eloquence-validable) - self-validating models
2. [Mappable](https://github.com/jarektkaczyk/eloquence-mappable) -map attributes to table fields and/or related models
3. [Metable](https://github.com/jarektkaczyk/eloquence-metable) - meta attributes made easy
4. [Mutable](https://github.com/jarektkaczyk/eloquence-mutable) - flexible attribute get/set mutators with quick setup 
5. [Mutator](https://github.com/jarektkaczyk/eloquence-mutable) - pipe-based mutating

By installing this package you get aforementioned extensions. Alternatively you can pull just single extension:

```bash
# get all extensions
composer require dman013/eloquence 

# get single extension, eg. Metable
composer require dman013/eloquence-metable
```

**Check the [documentation](https://github.com/jarektkaczyk/eloquence/wiki) for installation and usage info, [website](http://softondman013.com/tag/eloquence/) for examples and [API reference](http://jarektkaczyk.github.io/eloquence-api)**

## Contribution

Shout out to all the Contributors!

All contributions are welcome, PRs must be **tested** and **PSR-2 compliant** - refer to particular extension repository.
