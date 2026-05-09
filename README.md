# Mother-s-Day-Surprise

📸 Adding images manually (Balloons 1, 2, 3)
Find this section near the top of the <script>:
const photoDataURLs = [
  null,   // Balloon 1 photo
  null,   // Balloon 2 photo
  null,   // Balloon 3 photo
];


🎙️ Adding a pre-recorded voice note (Balloon 6)
Find this line:
const VOICE_NOTE_BASE64 = null;

Replace null with your audio as base64:
const VOICE_NOTE_BASE64 = 'data:audio/mpeg;base64,//uQxAAAA...(your audio base64)...';
To get it: go to base64.guru/converter/encode/audio, upload your MP3/WAV, and paste the result.


Record your voice using Voice Recorder (Windows) or QuickTime (Mac) → save as MP3 or M4A
Go to base64.guru/converter/encode/audio
Upload the file → copy the output
Paste into the code as:

const VOICE_NOTE_BASE64 = 'data:audio/mpeg;base64,PASTE_HERE';
Replace PASTE_HERE with the copied text
