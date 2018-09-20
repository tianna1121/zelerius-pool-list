# Zelerius Pool List


A JSON list of Zelerius Pools

The goal of this repository is to have a **central list** of pools for Zelerius Network mining.

You can use this list in your app via: https://raw.githubusercontent.com/zelerius/zelerius-pool-list/master/pool-list/zelerius-pools.json

## Adding a Mining Pool

If you run a pool, please **submit a Pull Request** against *pool-list/zelerius-pools.json* to get added. 

* Please add your pool to the list in **alphabetical order**, named using **CamelCase** style, and **including trailing slashes** for the `url` and `api` values.

* Example
  ```
    {
        "name" : "YourPool.com",
        "url" : "https://yourpool.com/",
        "api" : "https://yourpool.com/api/",
        "type" : "node.js"
    },
    ```

*  Possible values for **type**
  - node.js
  - other
