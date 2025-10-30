# about this project
This repository is a Fork of the SPQR.TextAudioTool v0.4. In addition to its original functionality, it allows:
1) To get the emotion (sentiment) of the message and send it to the client.
Edit the TextAudioToolPref.json (it will be created after the first run of the script) file to select a sentiment classification model and enable/disable sentiment classification and audio playback.
The audio can be sent to its desination using a virtal audio cable software.
<br/>
2) This tool can also work as a proxy for the AI Horde for use with KoboldLink. For this purpose endpoint 127.0.0.1:7069/horde_generate is added. Please use KoboldLink version 11 or higher. Enter "http://127.0.0.1:7069/horde_generate" in the text box "KoboldAI URL" to use this proxy. Edit TextAudioToolPref.json to enter your apikey and the model name to use when connecting to the Horde.
To get a list of models currently active in the horde, use the aihorde.net/api/v2/status/models endpoint with the "text" parameter and check the response body. If you are using a browser, you can check it using the following link: https://aihorde.net/api/v2/status/models?type=text&model_state=all. If you have no API key you can get it here https://aihorde.net/

# installation
It is recommended to install SPQR.TextAudioTool v0.4 first. Then replace the original SPQR.TextAudioTool.bat and SPQR.TextAudioTool.script.py files from the .../SPQR.TextAudioTool directory with the updated ones from this repository.
Alternatively, if you don't have SPQR.TextAudioTool v0.4 installed, unzip the contents to the target directory and run "SPQR.TextAudioTool - (standalone).bat" or "SPQR.TextAudioTool/SPQR.TextAudioTool.bat" (the first time you run it, the installation of the necessary packages will begin; Python must be installed on PC).
