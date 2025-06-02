# about this project
This is just a small modification of SPQR.TextAudioTool v0.4 that allows, in addition to the original functionality, to get the emotion (sentiment) of the message and send it to the client.
Edit the TextAudioToolPref.json (it will be created after the first run of the script) file to select a sentiment classification model and enable/disable sentiment classification and audio playback.
The audio can be sent to its desination using a virtal audio cable software.
<br/>This tool can also work as a proxy for the AI Horde for use with KoboldLink. For this purpose endpoint 127.0.0.1:7069/horde_generate is added. Please use KoboldLink version 11 or higher. Enter "http://127.0.0.1:7069/horde_generate" in the text box "KoboldAI URL" to use this proxy. Edit TextAudioToolPref.json to enter your apikey and the model name to use when connecting to the Horde.
To get a list of models currently active in the horde, use the aihorde.net/api/v2/status/models endpoint with the "text" parameter and check the response body.
