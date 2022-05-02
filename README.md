# IndMiner

IndMiner is propably the fastest walletminer out there, built using C# (.net 4.7.1) and NBitcoin.

Precompiled version should be there, if you don't want to use it then compile yourself (recommended due to antivirus false positives).

## Quick Start

### Precompiled version

Download the latest release, unzip it and run IndMiner.exe.

### Compile yourself

Download source code and open up IndMiner.sln. Add NBitcoin via nuget and make sure build actions are cleared (Edit -> IndMiner Preferences -> Build Actions). Then select a build config and press F5.

## Webhook & Hit Behaviour

When a hit is experienced, a webhook with the private key is sent to you. Also, the private key is written to file (Name structure: "hit-[unix].txt").

![image](https://user-images.githubusercontent.com/64090338/166115824-ae177ed0-1ed7-435f-a008-0b0a8b5271c9.png)


## Files in this repo
**[wallets.ind](https://github.com/OlMi1/indminer/blob/main/wallets.ind)** The database used to check for a balance

**[genAddressDB.py](https://github.com/OlMi1/indminer/blob/main/genAddressDB.py)** Small python script to generate your own wallets.ind

The rest should be self explanatory.

## Virustotal

For some reason, a [Virustotal Scan](https://www.virustotal.com/gui/file/4ec6b3ac8fd3e5574f29299c9b5b6cd655b34304c23c85396b72d311d315e3cc) of the build detects it as malicious. Pull requests helping remove the detections would be much appreciated. Until then, build from source if you're unsure.

## License

Read the full license for yourself. In short terms it basically adds up to: Change and redistribute for **PRIVATE** usage, unpermitted commercial usage will be taken down.

## Donate

Donate if you're cool

| ![Donate BTC](https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=162z6QWSR3Mwp5h9ezExZSUyRiPXckcxUL) | ![Donate XMR](https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=89M6YHy914v7CZwyJRwgL6YdoSK45XzuF5kL3iyjiMWqFU6e8KaX57RVf8M9cAxJ69SuT7gme16UnF62rdxovNzJQa2M3NU) | ![Donate ETH](https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=0x8e6ac85fe87b9f31ed2fdeccee210af1d4d409ae) |
|:--:|:--:|:--:|
| BTC | XMR | ETH |
