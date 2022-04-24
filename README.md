# buildspace X Terra project: <br> Problems you may have run into.

[toc]

## Section 2
### :computer: Get the local Terra env running.
- **node version issues.**

    Make sure to always check your node version. This is usually the case if you get an error with the following:
    ```bash=
    Code: ERR_OSSL_EVP_UNSUPPORTED
    ```
- **Problems with generating the contracts with rust.**

    ![](https://i.imgur.com/CZJqmrQ.png)

    The error might look like this :arrow_down:

    ![](https://i.imgur.com/Il03kpT.png)
    
    Solution: <br>
    Your rust is out of date. run `rustup update` in your             terminal.


    
