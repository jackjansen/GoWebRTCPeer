# GoWebRTCPeer
 
## Usage

### Specifiy Proxy Port

Use -p followed by the port ex: ./peer.exe -p :8000

The ":" is important, it wont work otherwise.


### Specify Remote Input

Use -i in addition to -p to receive remote frames from the plugin and use these as a frame source. When not using this option the application will fallback to using preloaded files. Ex: ./peer.exe -p 8008 -i

### Specift Remote Output

Use -o in addition to -p to forward the received packets to the plugin, allowing you to process the frames in the application using the plugin. Ex: ./peer.exe -p 8000 -o

## Plugin

### Location (use other branch for now)
https://github.ugent.be/madfr/l4s-proxy-unity-plugin
### Receive Example
https://github.ugent.be/madfr/PluginReceiveExample
### Send Example
https://github.ugent.be/madfr/PluginSendExample

## Building

Notes by Jack, as he's trying to build this.
Open this directory in VSCode and open the workspace.
Install go.