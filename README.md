# Nexus-Beta

![ZenRock Banner](https://pbs.twimg.com/profile_banners/1741850179068678144/1723531251/1500x500)

## Links
- [Discord](https://discord.gg/dria)
- [Web](https://dria.co/)
- [Twitter](https://x.com/driaforall/)


## System Requirements

- **RAM**: 8 GB
- **CPU**: 4 cores
- **Disk Space**: 100 GB

## Installation ⚙️

# Auto Install
Only role node keeper

Before Install
prepare PK
and API
- [OPEN AI](https://platform.openai.com/api-keys)
- [SERPER](https://serper.dev/api-key)
- [JINA](https://jina.ai/embeddings/)

```bash
bash <(curl -s https://file.winsnip.xyz/file/uploads/Dria.sh)
```

# Cek log
```bash
sudo journalctl -u dria-node.service -f
```

# Cek Status
```bash
sudo systemctl status dria-node.service
```

Delete
```bash
sudo systemctl stop dria-node.service && \
sudo systemctl disable dria-node.service && \
sudo rm /etc/systemd/system/dria-node.service && \
sudo systemctl daemon-reload && \
rm -rf /root/dkn-compute-node
```
