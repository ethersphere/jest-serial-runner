# jest-serial-runner

Simple extension of the default Jest runner that makes it run serially (as of running with --runInBand flag)
The non-cli functionality is slightly hidden in the Jest docs.

Useful for integration tests.

# Usage

``` npm install @ethersphere/jest-serial-runner --save-dev```

Add ``` "runner": "@ethersphere/jest-serial-runner" ``` in your jest config

# Credit

Credit to @codejedi365 and @gabrieli that developed the original solution.
