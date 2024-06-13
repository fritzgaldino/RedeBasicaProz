# Rede Básica - Exercício Proz

Para o show da banda de Miguel, será necessário configurar uma rede de computadores. A comunicação entre os membros da equipe de produção, que estarão espalhados pelo teatro, é fundamental para manter todos informados e verificar se nada está fugindo do controle. O agente da banda decidiu modernizar a infraestrutura do show para melhorar essa comunicação. Para ajudá-los, você deve usar o Cisco Packet Tracer para criar uma topologia de rede estrela que permita a toda a equipe se comunicar facilmente.

Passos:
1. Definir o cenário
- Imagine que cada membro da equipe possui um computador que precisa de uma conexão de rede para se comunicar com os outros membros da produção.

2. Montar a topologia
- Crie uma nova topologia no Cisco Packet Tracer; 
- Arraste um switch para o centro da área de trabalho; 
- Arraste quatro PCs e posicione-os ao redor do switch, representando cada membro da equipe de produção.
  
3. Conectar os dispositivos
- Conecte cada PC a uma porta diferente no switch usando cabos ethernet;
- Visualize os computadores da equipe de produção formando uma estrela ao redor do switch central.

![image](https://github.com/fritzgaldino/RedeBasicaProz/assets/87190206/c25b3ea4-2085-4576-8fa9-52016fe0b80c)

4. Configurar os endereços IP
- Crie um senso de identidade para cada computador, atribuindo nomes e números de endereços IP;
- Configure os endereços IP para as interfaces dos PCs e do switch de acordo com a mesma sub-rede.

Faixa de IP - 192.168.1.0/24. Distribuição dos IPs apartir do 192.168.1.2
Nome Pcs - PC01 até PC04

![image](https://github.com/fritzgaldino/RedeBasicaProz/assets/87190206/f0b470c0-2102-4f91-9266-9918092fdbe0)
  
5. Testar a comunicação
- Para verificar se todos os computadores estão devidamente configurados, acesse um dos PCs da equipe, abra o prompt de comando e tente fazer um ping para o endereço IP do computador de outro membro da equipe.

![image](https://github.com/fritzgaldino/RedeBasicaProz/assets/87190206/bb57c690-e5b1-4286-a381-4c4f75c96750)


Arquivo packet tracer: 
