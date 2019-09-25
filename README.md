# Solhint: Workshop

1. Install Solhint via npm:

    `npm i -g solhint`

2. Initialize a configuration file:

    `solhint init-config`

3. Update `.solhint.json` to extend `solhint:recommended` instead of `solhint:default`

4. Add the [`reason-string`](https://protofire.github.io/solhint/rules/best-practises/reason-string.html) rule to the configuration.

5. Run solhint on the [`ERC20.sol`](ERC20.sol) contract:

    `solhint ERC20.sol`

6. Fix the warnings and errors
