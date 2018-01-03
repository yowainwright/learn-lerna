# Learn Lerna

This repository is [Lerna](https://github.com/lerna/lerna#getting-started) demo for ensuring that I understand Lerna. Lerna provides an easier way to manage mulitple packages within a parent repository.

For this repository, I followed a tutorial by [Reggi](https://github.com/reggi), [here](https://github.com/reggi/lerna-tutorial)

**Below is the output of following the tutorial:**

```txt
├── LICENSE
├── README.md
├── lerna.json
├── package.json
└── packages
    ├── alpha
    │   ├── index.js
    │   └── package.json
    ├── beta
    │   ├── index.js
    │   └── package.json
    └── usage
        ├── index.js
        ├── node_modules
        │   ├── alpha -> ../../alpha
        │   └── beta -> ../../beta
        └── package.json
```
