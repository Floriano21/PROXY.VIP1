# Proxy ARM64 GF VIP

```sh
{
    curl -s -L -o WebSocketARM.zip https://github.com/Floriano21/PROXY.VIP1/raw/main/WebSocketARM.zip
    curl -s -L -o wssecARM https://github.com/Floriano21/PROXY.VIP1/raw/main/wssecARM
    apt install unzip -y
    unzip WebSocketARM.zip
    rm WebSocketARM.zip
    chmod +x wssecARM WebSocketARM
    apt install dos2unix screen -y
    dos2unix wssecARM
}
```

para executar apenas digite ./wssecARM


# Proxy X86 GF VIP

```sh
{
    curl -s -L -o WebSocket86.zip https://github.com/Floriano21/PROXY.VIP1/raw/main/WebSocket86.zip
    curl -s -L -o wssecX86 https://github.com/Floriano21/PROXY.VIP1/raw/main/wssecX86
    apt install unzip -y
    unzip WebSocket86.zip
    rm WebSocket86.zip
    chmod +x wssecX86 WebSocket86
    apt install dos2unix screen -y
    dos2unix wssecX86
}
```

para executar apenas digite ./wssecX86


# Proxy DT

```sh
{
    rm -f /usr/bin/proxy
    curl -s -L -o /usr/bin/proxy https://github.com/Floriano21/PROXY.VIP1/raw/main/proxy
    chmod +x /usr/bin/proxy
    clear
    echo "Para usar digite o comando: proxy"
    echo ""
    echo "Exemplo Telks: screen -dmS proxy /usr/bin/proxy --port 80 --http --ssh-only --response FLORIANO.X"
}
```
Para usar digite o comando: proxy

Exemplo: screen -dmS proxy80 proxy --http --port 80

Exemplo Telks: screen -dmS proxy /usr/bin/proxy --port 80 --http --ssh-only --response FLORIANO.X


