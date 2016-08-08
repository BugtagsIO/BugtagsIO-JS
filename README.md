# Bugtags Bug Reporter for HTML 5

Bugtags is The Simplest and Most Efficient Tool for Mobile App Testing.

In-App Bug reporting, crash reporting and all context data will be automatically uploaded to the Bugtags Cloud. With all this data, Bug can be fixed efficiently.

## Installation

1. Load the Bugtags JS SDK on your Web page, there are three options:

    Option 1. Load from the Bugtags CDN

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