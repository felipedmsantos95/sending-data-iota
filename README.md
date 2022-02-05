# Send Data to IOTA Tangle Devnet


**Requirements:**

*	Node 12.x or later
*	NPM 6.x or later

**Before you run app first time:**

Install app dependencies:

Using NPM:

```$ npm i```
    
Using yarn:

```$ yarn install```

**Using app:**

To run type:

```$ node index.js```

Example of output:

    ```
    {
        message: {
            networkId: '6514788332515804015',
            parentMessageIds: [
                '352e3b749e0343137207a7759514591101685325512c9624fd92ed3591e09f8a',
                '530496f17a7d8213ce2f57f15e3addd5da6e721bdeebdbb44c8c9563583a3609',
                '81a378c1299598154bd52bfd7e2d0fd4f9406b1fd4cc0ac5eae1ce783b2a69a3',
                'c5762d87299bb04a9713ab5228a3d52342595d75cecb7cc8f963b6ed59e09cd0'
            ],
            payload: {
            type: 2,
            index: '4066656c697065646d73616e746f733935',
            data: '7b2274657374223a2274657374227d'
            },
            nonce: '6917529027641104443'
        },
        messageId: '72a54294e7adfbdd2b8618d3b6d896742d3869d9edb4657c906f6ec7f3b2ffb7'
    }
    ```
Now you can get the `messageId` and check the given message via [Tangle Explorer](https://explorer.iota.org/devnet)




