## Change Log

### 2.0.4

Support SimpleSchema 1.0.0+

### 2.0.3

Add support for validating an upsert where the query has $and.

### 2.0.2

Fix issue where autoValue function was running twice on the client for client-initiated inserts and updates. This led to issues with autoValues not being added correctly, or inserts or updates not succeeding.

### 2.0.1

Fix error when validating an object with no prototype (thanks @jasonphillips)

### 2.0.0

Requires Meteor 1.3+ and requires you to install and use the [Node SimpleSchema package](https://github.com/aldeed/node-simple-schema).

### 1.2.0

Support for SimpleSchema 2.0

### 1.1.1

- Fix merging of identical selector schemas (thanks @spencern)
- Fix attaching w/ "replace" option when switching between a selector and non-selector schema (thanks @paulbalomiri)
- Fix choosing of correct selector schema for cleaning inserts or updates that originate on the client (thanks @paulbalomiri)

### 1.1.0

Support for multiple schemas on the same collection. See aldeed:collection2 readme.

### 1.0.0

Initial release. Previously included in aldeed:collection2 package.