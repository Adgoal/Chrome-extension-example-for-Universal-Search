# Universal Search extension example

Instruction:
- In background.json file you have to fill object with your US credentials. It looks like:
    ```javascript
    const universalSearchCredentials = {
        API_PUBLIC_KEY: 'your_api_key',
        MEMBER_HASH: 'your_member_hash',
        PANEL_HASH: 'your_panel_hash'
    };
    ```
- Open in Chrome chrome://extensions/
- Switch to developer mode in right upper corner
- Press "Load unpacked button"
- Select this folder (where manifest.json located)
- Go to https://google.com and try :)