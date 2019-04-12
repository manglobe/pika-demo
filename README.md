# pika demo
A simple demo for get start with pika & preact;

`why not "react"?   "react" has no ES "module" entrypoint :(`

## steps:

1. install pika
    ```Bash
        npm install --save-dev @pika/web
        <!-- or -->
        yarn add --dev @pika/web
    ```

2. install your packages
    ```Bash
        npm install --save preat html
    ```
3. add webDependencies into your `package.json`
    ```json
        "@pika/web": {
            "webDependencies": [
                "preact"
            ]
        },
    ```

4. install web_modules
    ```Bash
        npx @pika/web
    ```

5. start your project
    ```Bash
        node server.js
    ```
#### That's all.  Now you can change your files see what will happen.
