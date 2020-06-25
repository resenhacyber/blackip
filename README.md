# BLACK IP - Resenha|Cyber
    Black List para o CLI

    Tool Reformulada do Adionditsak | blacklist-check-unix-linux-utility - Criada em 2014

### Instalação

    git clone https://github.com/Cyb3rEvil007/blackip.git
    CD blackip
    chmod + x ./blackip
    mv ./blackip /usr/bin

### Uso

    # Use com domínios ou endereços IP
    $ blackip dominio.com.br
    $ blackip 158.69.35.227 
    $ blackip 158.69.35.227
    
    Resenha|Cyber Analisando o IP: 158.69.35.227
    158.69.35.227 Nome: tor-exit.ubermen.net.
    227.35.69.158.z.mailspike.net.         [Lista Negra] (127.0.0.2)
    227.35.69.158.rbl.interserver.net.     [Lista Negra] (127.0.0.2)
    227.35.69.158.invaluement.             [OK]
    227.35.69.158.SIP.                     [OK]
    227.35.69.158.hostkarma.junkemailfilter.com.[Lista Negra] (127.0.0.2)
    227.35.69.158.exploit.mail.abusix.zone.[OK]
    227.35.69.158.cbl.abuseat.org.         [Lista Negra] (127.0.0.2)
    227.35.69.158.black.junkemailfilter.com.[Lista Negra] (127.0.0.2)
    227.35.69.158.all.s5h.net.             [Lista Negra] (127.0.0.2)
    227.35.69.158.0spam.fusionzero.com.    [OK]
    227.35.69.158.aspews.ext.sorbs.net.    [OK]
    227.35.69.158.backscatter.spameatingmonkey.net.[OK]
    227.35.69.158.bl.blocklist.de.         [OK]
    227.35.69.158.bl.konstant.no.          [OK]
    227.35.69.158.bl.nosolicitado.org.     [OK]
    227.35.69.158.bl.scientificspam.net.   [OK]
    227.35.69.158.bl.spamcop.net.          [OK]
    227.35.69.158.bl.suomispam.net.        [OK]
    227.35.69.158.block.dnsbl.sorbs.net.   [OK]

    
    # Canalize com outros utilitários UNIX, por exemplo. grep. Apenas na lista negra:
    $ blackip 158.69.35.227 | grep "Lista Negra"
     
    227.35.69.158.z.mailspike.net.         [Lista Negra] (127.0.0.2)
    227.35.69.158.rbl.interserver.net.     [Lista Negra] (127.0.0.2)
    227.35.69.158.hostkarma.junkemailfilter.com.[Lista Negra] (127.0.0.2)
    227.35.69.158.cbl.abuseat.org.         [Lista Negra] (127.0.0.2)
    227.35.69.158.black.junkemailfilter.com.[Lista Negra] (127.0.0.2)
    227.35.69.158.all.s5h.net.             [Lista Negra] (127.0.0.2)
    227.35.69.158.torexit.dan.me.uk.       [Lista Negra] (127.0.0.100)
    227.35.69.158.dnsbl.justspam.org.      [Lista Negra] (127.0.0.2)
    227.35.69.158.bl.mailspike.net.        [Lista Negra] (127.0.0.2)


### Lembrete
    Cuidado nos seus testes, use sempre um proxy, VPN.
