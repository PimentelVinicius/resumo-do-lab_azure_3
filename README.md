# resumo-do-lab_azure_3
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO sobre azure 3


Tipos de Serviços de Nuvem

IaaS - Infraestrutura como Serviço
No IaaS, o cliente (nós) tem mais responsabilidade e acesso aos recursos finais, sendo responsável pela gestão e configuração de muitos aspectos da infraestrutura.
Esse modelo permite maior personalização de acordo com as necessidades da empresa.
Apesar de termos controle sobre a infraestrutura, não precisamos nos preocupar com a parte física dos servidores.

PaaS - Plataforma como Serviço
O PaaS oferece ferramentas de análise e gerenciamento, especialmente voltadas para desenvolvedores.
Um exemplo de serviço PaaS é um banco de dados, onde não precisamos nos preocupar com a gestão do servidor, mas apenas com a aplicação em si.

SaaS - Software como Serviço
O SaaS é um serviço de mais alto nível, como o Microsoft Teams, por exemplo. Nesse modelo, os administradores têm acesso a algumas ferramentas de gerenciamento, enquanto os usuários utilizam o software diretamente.
Todo o sistema está na nuvem, sem a necessidade de estar em nossos servidores ou algo similar.
O nível de acesso dos usuários geralmente é determinado pela licença adquirida no contrato.

Modelo de Responsabilidade Compartilhada
Há uma tabela que podemos consultar para verificar de quem é a responsabilidade em cada tipo de serviço.

No ambiente local, tudo é de nossa responsabilidade.
No IaaS, temos um pouco menos de responsabilidade, já que a gestão de redes, datacenter físico e hosts não fica sob nosso controle.
No PaaS, além das responsabilidades do IaaS, a Microsoft também gerencia o sistema operacional, e compartilhamos responsabilidades em relação a aplicativos, controles de rede e infraestrutura de identidade e diretório.
No SaaS, nossa responsabilidade se limita a informações e dados, dispositivos (móveis e PCs), e contas e identidades. Todo o restante é gerenciado pela Microsoft.
