# Python3 SimpleBITSServer (Background Intelligent Transfer Service)

A simple python implementation of a BITS server. BITS protocol is used to transfer files asynchronously between a client and a server.
[SEE](https://github.com/SafeBreach-Labs/SimpleBITSServer/) for the initial work

## Background

[Official protocol specification](https://winprotocoldoc.blob.core.windows.net/productionwindowsarchives/MC-BUP/[MC-BUP].pdf) - Background Intelligent Transfer Service (BITS)

[Example use at SafeBreach Labs](https://safebreach.com/Post/Building-a-Python-BITS-Server)

## Usage

```
python SimpleBITSServer.py [port]
```

### Client
Prerequisites:
* Windows and powershell

```
> Bitsadmin /Transfer JOB /PRIORITY HIGH /UPLOAD http://<SERVER>/<FILENAME> <FILEPATH>
```
