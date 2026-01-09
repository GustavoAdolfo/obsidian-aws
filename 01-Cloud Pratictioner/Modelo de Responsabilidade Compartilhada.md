Nome original: *AWS Shared Reponsibility Model*

Define o que é de resposabilidade do cliente e o que é de responsabilidade da AWS.
Dados armazenados e de tráfego, políticas de acesso às aplicações e recursos, gerenciamento de identidade, tráfego de rede, encriptação, firewall, informações armazenadas, configurações de conta, autenticação em aplicações, sistemas operacionais em instâncias... tudo isso é de reponsabilidade do cliente.

Softwares e sistemas operacionais que gerenciam os recursos, hardware, disponibilidade de recursos envolvendo energia e redes, estrutura de armazenamento de dados física, computação, estrutura de armazenamento de arquivos, estrutura de regiões e a comunicação da rede global, zonas de disponibilidade e  localização de borda ([[Edge Location]])... são responsabilidades da AWS.

O gerenciamento compartilhado envolve a aplicação de patches e correção de falhas na infraestrutura pela AWS, mas a aplicação de patches e correção de falhas em SO é responsabilidade atribuída ao cliente. A AWS mantém a configuração dos dispositivos de infraestrutura, mas o cliente é responsável pela configuração dos seus próprios bancos de dados, aplicativos e sistemas operacionais convidados. A AWS treina funcionários da AWS, mas o cliente deve treinar seus próprios funcionários.

Ref. [[Domínio 1 - Definição da Nuvem AWS]]