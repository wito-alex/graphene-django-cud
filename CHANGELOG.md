# Changelog

## Version 0.1.0
* Improve test environment
* Add `check_permissions` and `get_permissions` methods. The methods can be overridden to provide custom permissions handling.
* Fix issue with `required`-handling for fields with choices.
* Add queryset handling to delete mutations.
* Add field validation.
* Add `before_mutate`, `before_save` and `after_mutate` hooks.

## Version 0.0.16
* Fix bug related to conversion of filter fields.

## Version 0.0.15
* Fix bug with many to many extras type extraction

## Version 0.0.14
* Loosen graphene-django required version

## Version 0.0.13
* Change package mangement to poetry
* Add missing install dependencies in setup.py
* Move repo to github

## Version 0.0.12
* Fix issue with fields havng name "input": Change items call to use super.

## Version 0.0.11
* Make sure enum fields are fetched from registry

## Version 0.0.10
* Add better handling of filter fields in DjangoBatchDeleteMutation

## Version 0.0.9
* Add DjangoBatchCreateMutation

## Version 0.0.8
* Fix bug with bad auto context field

## Version 0.0.7
* Improve conversion of Boolean field

## Version 0.0.6
* Add customizible names for many to many and many to one rels.

## Version 0.0.5
* Fix some issues with adding/removing many to one rels

## Version 0.0.4
* Fix bug where argument was not sent into update_obj

## Version 0.0.3
* Improve nested auto field name generation

## Version 0.0.2

* Add foreign key, many to many and many to one extras generation.

## Version 0.0.1

Initial release, add core and classes:
 * DjangoCreateMutation
 * DjangoPatchMutation
 * DjangoUpdateMutation
 * DjangoDeleteMutation
 * DjangoBatchDeleteMutation
 