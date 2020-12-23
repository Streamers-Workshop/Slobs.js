<div align="center">
  <br />
  <p>
    <img src="https://avatars1.githubusercontent.com/u/33038602?s=200&v=4" width="200" alt="Slobs.js" />
  </p>
  <br />
  <p>
    <a href="https://discord.gg/Kc7fyx2"><img src="https://discord.com/api/guilds/728527921504845884/embed.png" alt="Discord server" /></a>
  </p>
</div>

# Notice
## Created by Krammy
## Maintained by Streamer's Workshop
### Reason: System is required for Blazebot, and currently the Package is receiving no love from its creator. As it was created during the development of Trovobot, we will take maintance of it.

# SlobsJS
An easy solution to access Streamlabs OBS (SLOBS) websocket connections.

## How to use
### Get Token
In Streamlabs OBS, go to ``Settings``->``Remote Control`` and click on the ``QR-Code`` and then on ``show details``

### Basic slobs.js example
```
const SlobsJS = require('slobs.js');
const slobs = new SlobsJS('http://127.0.0.1:59650/api' , 'token');

console.log( slobs.getStreamingStatus() ); //Will return 'live' or 'offline' if slobs is streaming or not.
```
