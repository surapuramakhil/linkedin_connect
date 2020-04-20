# LinkedIn Connect

LinkedIn Connect is a configurable and easy to use JavaScript script to automate connections with personalized messages.

![LinkedIn Connect Demo](demo/demo.gif)

## Usage
1. Go to https://www.linkedin.com/company/{COMPANY_NAME}/people/
2. Make sure your LinkedIn is in English
3. Modify the constants at the top of the script to your liking

| Constant| Description |
| --- | --- |
| `WAIT_TO_CONNECT` | Time in ms to wait before requesting to connect |
| `WAIT_AFTER_SCROLL` | Time in ms to wait before new employees load after scroll |
| `MAX_SCROLLS` | Max depth of pages to scroll down to |
| `MESSAGE` | Message to connect (`%EMPLOYEE%` and `%COMPANY%*` will be replaced with real values) |
| `POSITION_KEYWORDS` | Keywords to filter employees in specific positions |

4. Open chrome dev tools and paste the raw content of `linkedin_connect.js` or add it as a [snippet](https://developers.google.com/web/tools/chrome-devtools/javascript/snippets#runsources)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)