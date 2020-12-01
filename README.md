# 🦅 Hawkeye Targets

This is the repository contains the correct configuration structure to run hawkeye test

## Dependency

`npm i -g @jinzheli/hawkeye`

This will expose a `hawkeye` command line to use.

## Usage

At the moment, there is only one single `basic` check which expects **2xx** or **3xx** response status code. This is also the default task. So running

`hawkeye basic` = `hawkeye`

You can either run

`hawkeye --group foo`

This will run the urls in the file `basic/foo`

`hawkeye --group all`

This will run the urls in all groups in the folder `basic`