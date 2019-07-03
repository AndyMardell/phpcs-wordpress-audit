# PHPCS/WPCS WordPress Audit

A phpcs ruleset to quickly audit a WordPress theme or plugin for a selection of best practices.

I found that WPCS was OTT for auditing themes or plugins which haven't been strictly written to
WPCS standards, as it flags up all sorts of formatting issues. This ruleset gives you the power
to easily scan for the more critical errors flagged by WPCS such as security issues and general
best practices.

This ruleset is a modified version of WPCS/WordPress-Extra

## Prerequisites

You should have `composer`, `phpcs` and `wpcs` installed. In a nutshell:

`brew install composer`

`composer global require "squizlabs/php_codesniffer=*"`

`composer global require "wp-coding-standards/wpcs"`

## Installation

To use this ruleset you must clone it, and then reference the path.

`git clone git@github.com:AndyMardell/phpcs-wordpress-audit.git`

## Usage

`phpcs --standard=phpcs-wordpress-audit/ruleset.xml /my_project/wp-content/themes/my_theme`
