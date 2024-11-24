# resumo-do-lab-Tipos-de-Serviço-de-Nuvem-na-Azure
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento de aula e laboratório na DIO

# Tipos de Servico de Nuvem na Azure

Este repositório contém informações sobre os diferentes tipos de serviço de nuvem na Azure, incluindo IaaS, PaaS e SaaS, bem como o Modelo de Responsabilidade Compartilhada.

## Tipos de Serviço de Nuvem.


## 1. **IaaS - Infrastructure as a Service** (Infraestrutura como Serviço)

### Definição
O modelo **IaaS** oferece uma infraestrutura de TI sob demanda. Ele inclui recursos como servidores, armazenamento, redes e máquinas virtuais. Em vez de adquirir hardware físico, as empresas podem alugar esses recursos conforme necessário, com a flexibilidade de escalabilidade. Ou seja com om o IaaS, os usuários podem provisionar e gerenciar servidores virtuais, armazenamento e redes. A Azure cuida da parte física dos datacenters, enquanto os usuários são responsáveis pelo gerenciamento dos sistemas operacionais, aplicativos e dados.

### Exemplos
- Microsoft Azure
- Amazon Web Services (AWS)
- Google Cloud
- IBM Cloud

### Responsabilidades
- **Responsabilidade do provedor de nuvem**:
  - Gerenciamento da infraestrutura física (data centers, servidores, redes).
  - Garantia da segurança física e disponibilidade dos recursos.

- **Responsabilidade do cliente**:
  - Gerenciamento do sistema operacional, aplicativos, middleware e dados.
  - Configuração e manutenção da segurança de redes e sistemas.

---

## 2. **PaaS - Platform as a Service** (Plataforma como Serviço)

### Definição
O modelo **PaaS** fornece uma plataforma de desenvolvimento completa, permitindo que as empresas criem, desenvolvam e implantem aplicativos sem se preocupar com a infraestrutura subjacente ou seja, concentrar se no desenvolvimento e na lógica do aplicativo, enquanto a Azure gerencia a infraestrutura, middleware e outros serviços necessários. O PaaS oferece ferramentas de desenvolvimento, bancos de dados e sistemas de gerenciamento de aplicações.

### Exemplos
- Microsoft Azure App Services
- Google App Engine
- Heroku
- Red Hat OpenShift

### Responsabilidades
- **Responsabilidade do provedor de nuvem**:
  - Gerenciamento de toda a infraestrutura, como servidores, redes, armazenamento e sistema operacional subjacente.
  - Oferecimento de ferramentas de desenvolvimento e integração.

- **Responsabilidade do cliente**:
  - Gerenciamento dos aplicativos desenvolvidos e seus dados.
  - Configuração e manutenção da segurança do aplicativo.

---

## 3. **SaaS - Software as a Service** (Software como Serviço)

### Definição
O modelo **SaaS** oferece software e aplicativos prontos para uso, hospedados na nuvem. Os usuários finais acessam o software/aplicativos através de um navegador, sem se preocupar com a infraestrutura ou a manutenção do aplicativo, normalmente por meio de uma assinatura. A Azure gerencia toda a infraestrutura, middleware e software, permitindo que os usuários se concentrem na utilização dos serviços.


### Exemplos
- Microsoft 365
- Google Workspace (Gmail, Docs)
- Salesforce
- Dropbox

### Responsabilidades
- **Responsabilidade do provedor de nuvem**:
  - Gerenciamento completo da infraestrutura, software e atualizações.
  - Garantia da disponibilidade, segurança e manutenção do software.

- **Responsabilidade do cliente**:
  - Gerenciamento do uso do software, incluindo configuração de usuários e permissões.
  - Gerenciamento de dados dentro do aplicativo, como proteção de dados sensíveis.

---

## Modelo de **Responsabilidade Compartilhada** na Nuvem

O conceito de **responsabilidade compartilhada** descreve a divisão de responsabilidades entre o provedor de nuvem e o cliente. O provedor gerencia a infraestrutura e a segurança da rede, enquanto o cliente é responsável por dados, configurações e uso adequado dos serviços.

- **IaaS**: A Azure é responsável pela infraestrutura física e virtualização, enquanto o cliente gerencia os sistemas operacionais, aplicativos e dados.
  - **Provedor**: Infraestrutura física e virtual.
  - **Cliente**: Sistema operacional, aplicativos, dados e segurança de rede.

- **PaaS**: A Azure gerencia a infraestrutura física, virtualização, sistemas operacionais e middleware. O cliente é responsável pelo aplicativo e seus dados.
  - **Provedor**: Infraestrutura e plataforma de desenvolvimento.
  - **Cliente**: Aplicativos, dados e segurança dentro da plataforma.

- **SaaS**: A Azure gerencia toda a infraestrutura, sistemas operacionais, middleware e software. O cliente utiliza o aplicativo e gerencia seus dados.
  - **Provedor**: Infraestrutura e software.
  - **Cliente**: Uso do software, configuração de usuários e dados.

### Conclusão
- **IaaS**, **PaaS** e **SaaS** são três modelos de serviços de nuvem oferecidos pela **Azure**, cada um oferecendo diferentes níveis de controle e responsabilidades ao cliente.
  - **IaaS** oferece mais controle ao cliente sobre a infraestrutura, mas também mais responsabilidades.
  - **PaaS** abstrai mais a infraestrutura, focando no desenvolvimento de aplicativos.
  - **SaaS** oferece uma solução pronta para uso, com o mínimo de responsabilidade para o cliente.
  - **On-Premises**: O cliente é responsável por tudo, desde a infraestrutura física até os aplicativos e dados.

Quanto maior a abstração do serviço (de IaaS para SaaS), menor o controle do cliente sobre a infraestrutura, mas também menores são as suas responsabilidades. A escolha entre **IaaS**, **PaaS** ou **SaaS** dependerá das necessidades do cliente em termos de controle, flexibilidade e facilidade de uso.

## Recursos Adicionais

- [Documentação Oficial do Microsoft Azure](https://azure.microsoft.com/pt-br/documentation/)
- [Visão geral dos Serviços de Nuvem na Azure](https://azure.microsoft.com/pt-br/overview/)

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork deste repositório e enviar pull requests.

## Licença

Este repositório está licenciado sob a [MIT License](LICENSE).

## Contato

Se você tiver dúvidas ou sugestões, entre em contato através do meu e-mail: [anderson.coelho.2477@gmail.com]
