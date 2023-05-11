# DHCP-DNS

#### Connettere due sottoreti con DNS e DHCP richiede alcune configurazioni specifiche e passaggi.

* Per prima cosa, è necessario configurare il server DHCP. Il server deve essere configurato per assegnare gli indirizzi IP ai dispositivi presenti nelle due sottoreti. È possibile configurare anche la durata di assegnazione degli indirizzi, la specifica del gateway predefinito, la sottorete e altre informazioni necessarie per la connessione alla rete. Una volta configurato il server, sarà in grado di fornire indirizzi IP univoci ai dispositivi delle sottoreti.
* Successivamente occorre configurare i router per consentire il traffico di rete tra le due sottoreti. In particolare, i router devono essere configurati con l'indirizzo IP statico assegnato alle interfacce di rete che connettono le due sottoreti.
Inoltre, è necessario configurare il server DNS. Il server DNS consente ai dispositivi delle sottoreti di risolvere i nomi di dominio in indirizzi IP. Il server DNS deve essere configurato con le informazioni relative ai nomi di dominio dei dispositivi delle due sottoreti.
* Infine, bisogna configurare i client delle sottoreti. I client devono essere configurati per ottenere i parametri di rete dal server DHCP. Questi parametri includono l'indirizzo IP, il gateway predefinito, la sottorete e il server DNS. I client delle sottoreti dovranno utilizzare questi parametri per connettersi alla rete e comunicare tra loro.

##### In sintesi, la connessione tra due sottoreti con DNS e DHCP richiede la configurazione del server DHCP, dei router, del server DNS e dei client delle sottoreti. Una volta completata la configurazione, i dispositivi delle sottoreti saranno in grado di comunicare tra di loro con l'aiuto del server DHCP e del server DNS.
