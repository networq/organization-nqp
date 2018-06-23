networq:organization
====

This is the "networq:organization" package for [NetworQ](https://github.com/networq).

## Types

This package defines the following types that you can use in your own Networq:

### networq:organization:membership type

Fields:

  * `group`: *networq:organization:group*
  * `member`: *networq:organization:member*

### networq:organization:member type

Fields:

  * `memberships`: *networq:organization:membership[]*

### networq:organization:organization type

Fields:

  * `parentOrganization`: *networq:organization:organization*

### networq:organization:supplier type

Fields:

  * `notes`: *string*

### networq:organization:group type

Fields:

  * `memberships`: *networq:organization:membership[]*
  * `parentGroup`: *networq:organization:group*


