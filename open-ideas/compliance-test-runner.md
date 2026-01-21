# Compliance test runners for CL clients

## Introduction

There is a fork-choice compliance test generator, which can generate fork choice compliance test suites.
The tests are based on the fork choice reference test format, with a minor update (new property added).

The goal is to ensure that major CL clients are able to execute the tests.

## Analoguos tool for reference tests

There is a Justin Traglia's tool [https://jtraglia.github.io/nyx/](https://jtraglia.github.io/nyx/) for running reference tests.
It contains scripts to run tests with several CL clients.
Since fork-choice compliance tests are based on the same format, the scripts should be a good starting point.

## Current state

Currently, only Teku is able to consume the fork-choice compliance tests, using its standard reference test runner.
So, the goal is to implement necessary changes so that one can run the tests with other CL clients.

## CL clients

- Grandine
- Lighthouse
- Prysm
- Nimbus
- Lodestar
- Teku
- more??

## How to generate tests

## How to check tests against the CL spec

## Running compliance tests with Teku

