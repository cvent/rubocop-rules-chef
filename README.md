Rubocop Style Rules for Chef
============================

Just a set of baseline rules for Rubocop to run against chef code.

## Default Rules

By default we will be using [Chef/Cookstyle](https://github.com/chef/cookstyle)
as a baseline for chef cookbook rules.  Any overrides will appear in the
rubocop.yml file listed here.

## Usage

Add the following lines to the top of your .rubocop.yml file

```yml
inherit_from:
- 'https://raw.githubusercontent.com/cvent/rubocop-rules-chef/master/rubocop.yml'
```

## Style Rules / Decisions

Any alternatives to the original cookstyle rules will be defined here and
listed with the appropriate reason.
