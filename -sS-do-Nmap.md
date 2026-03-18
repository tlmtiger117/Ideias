# 18/03/26
# half-open(-sS/conexão entre-abretar).

- Não é de hoje que eu percebi que o Nmap cria pacotes com o mesmo tamanho qaundo é tramportado via protocolo IP(camada 3).
   - Uma ideia que tive é tentar criar alguma regra de firewall que bloqueasse pacotes com esse tamanho expecífico quando
     enviado.

   - Talvez para isso seria interessante expecificar que para bloquar, 1° teria que haver outros pacotes com o mesmo tamanho
      enviados do mesmo IP em um preriodo de tempo expecífico(assim não bloquando tráfego legítimo).

- Repositório Nmap:
  
  - [https://github.com/tlmtiger117/Nmap-Network-Mapper-]
