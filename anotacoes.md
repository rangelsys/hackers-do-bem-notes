## Modelo OSI
Aplicação, Apresentação, Sessão & | Transporte -> Firewall -> Porta |
Dados, Dados, Dados & Segmentos

Rede -> Roteador -> IP
Pacotes 

Enlace -> Switch -> Mac Address
Quadros

Física -> Hub
Bits

# Mac Address 
Endereço exclusivo de um dispositivo de Rede.
 
B4 45 06 64 ED 9F
|-------||-------|
ID Unico Fab. | N/S Dispositivo

## Estrutura Endereçamento IPv4
-> IPv4 | 4 octetos separados por pontos
-> Cada octeto composto por 8 bits -> 

254 Hots possíveis em uma sub-rede com máscara /24
Classe IP: 192.168.5.78 / Classe C
Classe A -> 127.0.0.1 -> 0 a 127 faixa do primeiro octeto | 127 | 0.0.1 -> Permite ~ 16 milhões de Hosts
Classe B -> 128 a 191 -> Redes de médio porte -> ~ 65 mil hosts
Classe C -> 192 a 223 -> Redes pequenas -> Até 254 
Classe D -> 224 a 239 -> Endereço multicast ( envio de pacotes para múltiplos destinos ) -> ~ Não possui divisão
Classe C -> 240 a 255 -> Experimental e Governamental -> Não aplicável tamanho da Rede.

IP Público <> Privado
IP Público -> Fornecido pelo provedor de serviços de Internet
IP Privado -> usado apenas dentro de uma rede privada

## Estrutura Endereçamento IPv6

O endereço IP permite que o computador se conecte à Internet, permitindo a troca de informações com outros dispositivos na rede global.
Tamanho espaço endereçamento IPv6 -> 128 bits
Tipos de comunicação -> unicast; anycast; broadcast & multicast.
Unicast -> Comunicação feita de um para um. Endereçamento para um pacote feito a um único destino.
Anycast -> Feita de uma interface para muitas outras. Contato que elas estejam na mesma região. Cada dis. anuncia o mesmo endereço de rede.
Broadcast -> Método de transferêcia simultânea para diversos receptores. Utilizado especificamente no IPv4.
Multicast -> Quando um dispositivo se comunica com alguns receptores. Método de transmissão de pacote de dados para múltiplos utilizado pelo IPv6

IPv6 ≈ "Endereço Público do IPv4" -> Global Unicast Address

Para configurar o enndereço IPv6 de link-local `fe80::1` em uma interface de um roteador Cisco, utiliza-se:
Router(config-if)# ipv6 address fe80::1 `link-local`

Objetivos abreviações IPv6
-> Reduzir o tamanho dos endereços IPv6
-> Abreviação :: pode ser utilizada em qualquer parte do IPv6

Exemplo:
"2001:0db8:0000:0000:0000:ff00:0042:8329" -> Abreviação -> "2001:db8::ff00:42:8329 "

-> Protocolo POP3 
Receber e-mails no servidor
-> IMAP
permite o acesso e a manipulação das mensagens
-> SMTP
Enviar mensagens
 
SMB -> Server Message Block
Compartilhamento Arquivos e Pastas em Redes Windows -> SMB/CIFS

# Controle de Usuário

LDAP (Lightweight Directory Access Protocol) 
|-> Autenticação e Autorização;

AD (Active Directory)
|-> Controle de Usuários e Recursos de Rede

RADIUS (Remote Authentication Dial-In User Service)
|-> Método de Autenticação Remota

# SNMP, NTP e SYSLOG

SNMP (Simple Network Management Protocol) |-> Coletar e gerenciar informações sobre dispositivos de rede.
NTP -> Network Time Protocol.
Syslog -> Coletar informações de gerenciamento de rede. 

## Sistemas Operacionais
## Windows
# Versões
81 |-> MS-DOS
85 |-> Windows 1.0
90 |-> Windows 3.0
95 |-> Windows 95
2001 |-> Windows XP
2015 |-> Windows Vista, 7, 8 e 10
2021 |-> Windows 11

# File System
FAT16 – File Allocation Table 16 Bit
FAT32 – File Allocation Table 32 Bit 
exFAT – extensible File Allocation Table
NTFS – New Technology File System
ReFS – Resilient File System

Cluster -> Um bloco de alocação mínima em um sistema de arquivos, usados para armazenar dados. 

## Linux
# Comandos
( Criar pasta ) |-> mkdir meus_dados
( Listar arquivos & diretórios ) |- ls
( Elevar privilégio ) |-> sudo
( Criar grupo de usuário) addgroup "nome"

## Lógica de Programação
Linguagem de Programação |-> Conjunto de comandos para realizar tarefas
