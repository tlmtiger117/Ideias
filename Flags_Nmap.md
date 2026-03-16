# 03/02/26
# Delay nmap:

- Entender ou olhar um pouco sobre essas opções(flags)
   - --scan-delay: Tem potencial de automação(script que scaneai a cada "x" tempo)
   - --max-parallelism: Limita o npumeros de scans acontecendo ao mesmo tempo.
      - Isso evita aparecer respostas de scans muito coladas uma nas outras no tráfego.
   - [!] Como utilizar o Modelo OSI pra entender onde o scan começa,onde atua e onde termina
   - -sI (scan-zombie): IDLE-SCAN. Essa técnica é absurda, mas como nada é 100% confiável em redes, sempre tem contexto pra usar.
   - --reason: mostra o motivo do nmap ter classificado uma porta como "x"(esse é útul pra estudos).
   - - --packet-trace: mostra todos os pacotes enviados e recebidos do nmap(útil, mas... qual a diference entre ele e o -vv?)
   - --scanflags: permite criar pacotes tcp personalizados(nunca ouvi falar).
   - --ttl: modifica o seu ttl(tempo de vida do pacote), para parecer que os dados vieram de outra rede.
   - --data-length: modifica o tamanho de um pacote. evita fire e IDS que analisam tamanhos de pacotes(tamanhos padrões deles)
  

-[ATUALIZAÇÃO]: link para o arquivo explicando o paralelismo:
   - https://github.com/tlmtiger117/Nmap-Network-Mapper-/edit/main/Nmap_Paralelismo.md
