# Video Streaming with RTSP and RTP

## Files
- `Client.py` : where the client is implemented.
- `ClientLauncher.py` : launcher to take in arguments and spawn the client.
- `ServerWorker.py`: where the server is implemented.
- `Server.py`: launcher to spawn the server.
- `RtpPacket.py`: where RTP packets are encoded/decoded.
- `VideoStream.py`: helper class to parse mjpeg files.

## Usage
To launch the server:
```
python3 Server.py <server_port>
```
To launch the client:
```
python3 ClientLauncher.py <server_host> <server_port> <RTP_port> <video_file>
```
