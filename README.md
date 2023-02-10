# Aula de rede
## *O que é cisco packet tracer*
O Packet Tracer é um programa educacional gratuito que permite simular uma rede de computadores, através de equipamentos e configurações presente em situações reais. O programa apresenta uma interface gráfica simples, com suportes multimídia que auxiliam na confecção das simulações. 

---

## *Comandos*

<code>
en/enable = Super usario ou modo previlegiado 

conf t = Modo de configuração terminal

hostname = Mudar o nome do roteador

line console "0" = Lihha de console

password =Colocar senha 

login = Longar

exit = Sair ou voltar 

enable secret "ccna" = Para adicionar senha criptografada 

banner motd # = Para criar uma messagem no inicio do roteador

wr = Para salvar as configurações

interface s0/0/0 - Acessou a porta serial

ip address "192.168.10.1 255.255.255.0" - Acrecentou um ip 

no shutdown = Comado para abilitar a porta serial 

description "conexao com roteador R-AR" = Adicionar uma descrição

end = Voltar para o cd inicial

ping = Para ver se está pingado a maquina 

interface g0/1 = Acessou a porta gigabit

router rip = para apontar os ip do protocolo

network "192.168.1.0" = apontar o ip

### DHCP

router (config) # ip dhcp pool ip-local

router(dhcp-config) # network 192.168.5.0 255.255.255.0

router(dhcp-config) # dns-server 8.8.8.8

router(dhcp-config) # default-router 192.168.5.1
router(config) # ip dhcp excluded-address 192.168.5.1 192.168.5.10

### Comando Show 

Router#show ? (O comando show ? fornece uma lista dos comandos show disponíveis)

Router#show arp (Exibe a tabela ARP do roteador)

Router#sh interfaces (Verifica detalhadamente as configurações das interfaces)

Router#sh ip interface brief (Verifica resumidamente as configurações das interfaces)

Router#sh ip route (Verifica a tabela de roteamento)

Router#sh running-config (Verifica as configirações ativas na RAM)

Router#sh startup-config (Verifica as configurações da NVRAM)

Router#sh flash: (Verifica os arquivos de sistema operacional da Flash)

Router#copy running-config startup-config (Salva as configurações ativas na RAM para a NVRAM) 
</code>
