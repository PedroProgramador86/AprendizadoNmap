# Previa
## Oque é o Nmap ?

O Nmap (Network Mapper) é uma ferramenta livre e de código aberto, muito usada em redes e segurança.
Ele foi criado para descobrir hosts e serviços ativos em uma rede — em outras palavras, para “mapear” o que está rodando em computadores e dispositivos.

### Oque ele pode fazer:
- Descobrir hosts ativos
- Fazer varreduras de portas
- Identificar os servirços e versões do software alvo
- Detectar qual o sistema operacional utilizado
- Permite rodar scripts prontos ou personalizados para coletar informações mais avançadas

### Sintaxe
```Shell
$ nmap <tipoDeScan> <opções> <Especificaçãodoalvo/range>
```
- Opções do tipo de Scan
1. Host Discovery
2. Scan Techniques
3. Port Specification and Scan Order
4. Service/Version Detection
5. Script Scan
6. OS Detection
7. Timing and Performace
8. Firewall/IDS Evasion and Spoofing
9. Output
10. Misc
11. Target Specification

### Opções de entradas mais utilizadas (Não obrigatorias para todos os scans):

1. Determina qual porta será executada a varredura:

```shell
nmap -p <Porta(s) Escolhida(s)> <IpAlvo/range>
```

obs: Aqui é onde o nmap fará um scan apenas nas portas especificadas (Isso fará com que o scan seja executado mais rapidamente)

2. Determina qual porta de origem do nmap:

```shell
nmap -g <Porta Escolhida> <IpAlvo/range>
```

obs: Aqui é onde o nmap fará o scan se passando pela porta especificada