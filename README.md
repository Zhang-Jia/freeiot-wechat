# freeiot-wechat
Wechat app server and demo to build IOT application on Wechat.
# 1号插座控制URL:
curl -X GET -H "App-Key: a1967a51960ea3f4d0aa104aa66512a7a114e0462c0452453cb0d78f382699a1" http://120.24.46.148:8888/application/v1/device/info?device_key=cbe89c82a9af4366e6b72da534600f087e346d902a7d517608eb4d9f0458e10f
curl -X PUT -H "App-Key: a1967a51960ea3f4d0aa104aa66512a7a114e0462c0452453cb0d78f382699a1 " -d "{\"plug\":[1]}" http://120.24.46.148:8888/application/v1/devices/1-1-18fe34d8964d/status
curl -X PUT -H "App-Key: a1967a51960ea3f4d0aa104aa66512a7a114e0462c0452453cb0d78f382699a1 " -d "{\"plug\":[0]}" http://120.24.46.148:8888/application/v1/devices/1-1-18fe34d8964d/status