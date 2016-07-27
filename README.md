# TDD/BDD Quickstart

This project has a basic PHPUnit and Behat setup that allows you to start writing tests in a TDD and BDD manner straight away.

## Requirements

- PHP 5.6 or 7
- Composer

## Setup

After cloning the repository, run `composer install` to install PHPunit and Behat.

## Writing tests

PHPUnit tests go into the `tests` directory, Behat features and feature contexts go into `features`. Code under test goes into `src`.

The expected root namespace of PHP files put in both the `src` and `tests` directories is `TddBddQuickstart`.

## Running tests

You can find the PHPUnit and Behat executables in the `bin` directory. You can run them as follows:

- `./bin/phpunit`
- `./bin/behat`
