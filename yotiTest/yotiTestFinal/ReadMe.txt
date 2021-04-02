Updated readme:

Create an env file with the following template:

YOTI_SCENARIO_ID=
YOTI_CLIENT_SDK_ID=
YOTI_KEY_FILE_PATH=".\keys\%YourApp%-access-security.pem"

Collecting a scenario / client_sdk ID from https://hub.yoti.com/ 
and downloading an access-security key, putting the keys file in the yotiTestFinal directory.

Run npm install assuming node is installed.

Run the website with node index.js whilst in the yotiTestFinal directory

Finally you should be able to access the website from https://localhost:9443/ after bypassing any warnings.

Then you can verify your age via the app using the widget on the website.

Should you be above 18 it should respond 18+ otherwise it will respond "You have to be 18 to access this site".