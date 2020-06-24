# blackip
Bash de Black List

Tool Readaptada do https://github.com/adionditsak/blacklist-check-unix-linux-utility

### Instalação

    git clone https://github.com/Cyb3rEvil007/blackip.git
    CD blackip
    chmod + x ./blackip
    mv ./blackip / usr / bin

### Uso

    # Use com domínios ou endereços IP
    $ blackip dominio.com.br
    $ blackip 8.8.8.8 # IP
    
    # Canalize com outros utilitários UNIX, por exemplo. grep. Apenas na lista negra:
    $ bl domínio.tld | grep "lista negra"

### Lembrete
Cuidado nos seus testes, use sempre um proxy, VPN.
