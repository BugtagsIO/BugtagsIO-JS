# Bugtags Bug Reporter for HTML 5

Improve your app quality and reliability through In-App bug reporting and crash reporting.

Report bugs directly from within your app, no longer need to switch to a bug reporting application.

## Installation

1. Load the Bugtags JS SDK on your Web page, there are three options:

    Option 1. Load from Bugtags CDN

    ``` javascript
    <script src="https://static.bugtags.io/sdk/bugtags-1.0.3.js"></script>
    ```

    Option 2. Load from your local, [Download to Local](https://bugtags.io/url/js-sdk)

    ``` javascript
    <script src="YOUR_SITE/bugtags-1.0.3.js"></script>
    ```

    Option 3. Load with `AMD Asyncronous Framework`

    ``` javascript
    require('https://static.bugtags.io/sdk/bugtags-1.0.3.js');
    ```

2. Add the following lines into the 'body' tag on your web page:

    ``` javascript
    <script>
        new Bugtags('APP_KEY','VERSION_NAME','VERSION_CODE');        
    </script>
    ```

for more details about the SDK integration, please visit https://docs.bugtags.io/start/integrate/js/.