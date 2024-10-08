# resumo-do-lab-3

**Microsoft Azure - Modelos de Serviço e Responsabilidade Compartilhada**

### IaaS, PaaS e SaaS na Azure
- **IaaS (Infrastructure as a Service)**: Modelo onde a Azure oferece infraestrutura básica, como servidores, armazenamento e redes, que os clientes podem gerenciar e configurar de acordo com suas necessidades. Esse modelo dá maior controle ao cliente sobre o sistema operacional e aplicativos, sendo ideal para empresas que precisam personalizar sua infraestrutura. Exemplo no Azure: Máquinas Virtuais (VMs).
  
- **PaaS (Platform as a Service)**: Nesse modelo, o Azure fornece uma plataforma gerenciada para desenvolvimento, onde os clientes podem focar na criação e implementação de aplicativos sem se preocupar com a gestão da infraestrutura subjacente. O Azure lida com a manutenção de servidores, armazenamento, banco de dados e escalabilidade. Exemplo no Azure: Azure App Service.
  
- **SaaS (Software as a Service)**: Aqui, o Azure oferece soluções completas de software que os clientes podem usar diretamente pela internet, sem precisar gerenciar a infraestrutura ou desenvolver aplicativos. O usuário final utiliza o software pronto, sem precisar de manutenção ou gerenciamento. Exemplo no Azure: Office 365.

### Modelo de Responsabilidade Compartilhada
- **Modelo de Responsabilidade Compartilhada**: Esse modelo descreve como a responsabilidade pela segurança e gerenciamento dos dados e sistemas é dividida entre o provedor de serviços de nuvem (Azure) e o cliente. Dependendo do modelo de serviço escolhido (IaaS, PaaS ou SaaS), o nível de responsabilidade varia:
  - **IaaS**: O cliente tem maior responsabilidade, incluindo a gestão de máquinas virtuais, sistemas operacionais, redes e dados. A Azure se responsabiliza pela segurança física e da infraestrutura.
  - **PaaS**: A responsabilidade do cliente é reduzida para a gestão de dados e aplicativos, enquanto a Azure gerencia o sistema operacional, a plataforma e a infraestrutura subjacente.
  - **SaaS**: A maior parte da responsabilidade recai sobre a Azure, que gerencia o software, a infraestrutura e a segurança, enquanto o cliente é responsável pelos dados inseridos no sistema e pela forma como utilizam o software.
