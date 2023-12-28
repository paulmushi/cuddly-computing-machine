## cuddly-computing-machine
Building AI Website using Javascript and PHP
https://paulmushi.github.io/cuddly-computing-machine/

A) Create your API Key on the openAI website - TOP Create an account and generate your API_KEY. Go to https://platform.openai.com/account/api-keys

To store your api key, you have 2 options: Using a key on the frontend You can put your API Key in a json file, without the need to use a server. The advantage is that you don't need a server. The disadvantage is that your API KEY is exposed, and other people can see it. Then access the file.json file (html-files/json/config.json) and put your key in the API_KEY field between the quotes

Using a key on the backend The second option, you can use a php file to store your key, so your key will be protected on the server To use this option, you must set the "use_php_api" field to true in the config.json file. Note: To use this option you will need a host with PHP 7 or higher

B) Configure your environment - TOP The CORS (Cross-Origin Resource Sharing) is a security measure that browsers implement to protect users against malicious attacks that can occur when a website attempts to access resources from another site. In other words, CORS is a security policy that browsers use to prevent a site from accessing information from another site without authorization.

When you try to run the index.html file locally and it makes a request to another file such as config.json, the browser may prevent the request from being completed due to the CORS security policy. This is because the browser is trying to protect you against possible malicious attacks.

To solve this problem, it is recommended to run the application on a local server on your machine such as WAMP, XAMPP or similar. Alternatively, you can upload the application to your website using FTP.

After configuring your environment, you can access index.html in your browser and test Open the index.html file in your browser.

D) Customizing the characters - TOP You can configure the behavior of the characters by opening the config.json file

name: Name of the character that will appear in the chat image: Character image path description: Description of the character that appears in the carousel welcome_message: Initial message that the character will send when opening the chat display_welcome_message: Configures whether the initial message will appear in the chat expert: Label that says what the character is expert at background_thumb_color: Character thumbnail background color training: Says what the character will be like, how he will behave, what tone he will use in his answer, write everything here in first person
