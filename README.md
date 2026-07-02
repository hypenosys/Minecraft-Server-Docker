# Docker Run del Servidor:

```bash
docker run -d \
-p 25565:25565 \
-v /DATA/AppData/mc-data/:/data \
-e EULA=TRUE \
--name minecraft \
itzg/minecraft-server
```

Adding "Items Adder Documentation":
https://itemsadder.devs.beer/plugin-usage/first-install
