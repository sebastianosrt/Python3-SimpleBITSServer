# Python3 SimpleBITSServer (Background Intelligent Transfer Service)

A simple python implementation of a BITS server. BITS protocol is used to transfer files asynchronously between a client and a server.
[SEE](https://github.com/SafeBreach-Labs/SimpleBITSServer/) for the initial work

## Usage

```
python3 SimpleBITSServer.py [port]
```

### Client
Prerequisites:
* Windows and powershell

```
> Bitsadmin /Transfer JOB /PRIORITY HIGH /UPLOAD http://<SERVER>/<FILENAME> <PATH_FILE_TO_UPLOAD>
```
