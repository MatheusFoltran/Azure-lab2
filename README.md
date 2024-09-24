# Máquinas Virtuais

Características Principais das VMs no Azure:

Escalabilidade:

As VMs no Azure podem ser escaladas para atender às necessidades de computação, desde pequenas instâncias para testes e desenvolvimento até máquinas robustas para cargas de trabalho intensivas em CPU ou memória.

Escolha do Sistema Operacional:

Você pode escolher entre várias distribuições de Linux (como Ubuntu, CentOS, Red Hat) ou Windows Server. Também é possível fazer o upload de sua própria imagem personalizada do sistema operacional.

Armazenamento:

As VMs podem usar discos gerenciados do Azure, que oferecem opções como SSDs e HDDs.
O disco do sistema operacional e discos adicionais de dados podem ser adicionados conforme a necessidade.

Redes:

Cada VM pode ser conectada a uma Rede Virtual (VNet) no Azure, permitindo uma comunicação segura entre diferentes recursos, como outras VMs, bancos de dados ou serviços de aplicativos.
Também é possível configurar endereços IP públicos e privados, regras de firewall e balanceamento de carga.

Segurança:

Você pode usar Network Security Groups (NSGs) para gerenciar o tráfego de rede de entrada e saída das VMs.
Além disso, o Azure Bastion permite o acesso seguro às suas VMs sem a necessidade de um IP público, minimizando o risco de ataques externos.
O serviço também oferece Backups automáticos, criptografia de discos e integração com o Azure Security Center para monitorar vulnerabilidades e aplicar patches de segurança.

Disponibilidade:

Para garantir alta disponibilidade, você pode usar Conjuntos de Disponibilidade e Zonas de Disponibilidade. Isso ajuda a proteger suas VMs contra falhas de hardware, de data center ou de toda uma região do Azure.
