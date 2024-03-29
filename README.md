# CRIANDO GRUPO DE RECURSOS NO AZURE
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Bongiorno14/Criando_RecourseGroup_Azure/blob/main/LICENSE) 

# OVERVIEW

Antes de mergulhar nos detalhes técnicos, é essencial entender o papel crucial que os Resource Groups desempenham na estrutura do Azure. Um Resource Group é um contêiner lógico que agrupa recursos relacionados para facilitar o gerenciamento, implantação e monitoramento dentro de um ambiente de nuvem. Ao organizar recursos em Resource Groups,tem se alguns beneficios, tais como:

- Organização Lógica: Agrupamento de recursos por projeto, equipe ou função para uma melhor organização e navegação.
- Gerenciamento Simplificado: Realizaçao de operações em lote, como implantação, atualização e exclusão, em todos os recursos de um grupo de uma vez.
- Governança e Segurança: Aplicação de políticas e permissões específicas a um Resource Group para garantir conformidade e segurança.

A lista certamente é maior que esta, porém atentei para estes 3 tópicos.

# DETALHAMENTO DA CRIAÇAO E CONFIGURAÇÃO

## Introdução ao Azure Resource Group
O que é um Resource Group?
- Benefícios e finalidade do Resource Group no Azure.
- Passos para Criar um Resource Group

## Criando um Resource Group via Portal do Azure.
Utilizando a CLI do Azure para criar um Resource Group.
- Exemplos de templates ARM para automação de criação de Resource Groups.
- Configurações Avançadas e Nuances

## Gerenciamento de permissões e acessos no Resource Group.
Tags e marcações para organização e gerenciamento eficiente.
- Definição de políticas de governança para o Resource Group.
- Recursos Agregados na Criação do Resource Group

## Implementação de Virtual Networks (VNets) dentro do Resource Group.
Criação de Máquinas Virtuais (VMs) e Armazenamento associado.
- Uso de Grupos de Segurança de Rede (NSGs) para controle de tráfego.
- Ferramentas e Referências Úteis

# UPDATE NO APRENDIZADO  DE CRIAÇAO DE MÁQUINAS VIRTUAIS.

Após o parofundamento do aprendizado, seguem um update no conteudo de criação de máquinas virtuais, com o detalhamento de algumas configurações importantes.
## Definiçao
Máquinas virtuais (VMs) são ambientes de computação virtual que funcionam como se fossem computadores físicos completos, incluindo hardware e software. No entanto, em vez de dependerem de hardware físico, as VMs são criadas em software e podem ser executadas em um único servidor físico ou em uma infraestrutura em nuvem, no caso de estudo o Azure.
As VMs são criadas usando um software chamado hipervisor, que permite a criação e execução de múltiplas máquinas virtuais em um único servidor físico. Cada VM tem seu próprio sistema operacional, aplicativos e recursos dedicados, mas compartilha os recursos físicos do servidor subjacente de forma virtualizada.

## Tamanho e Configuração:
- Escolha do tipo de VM: Determina a capacidade de processamento, memória e armazenamento da máquina virtual, com opções como geral, otimizada para computação, memória otimizada, etc.
- Tamanho da VM: Define a quantidade de vCPUs, RAM e armazenamento disponíveis para a máquina virtual, com opções que variam de pequenas a grandes instâncias.

## Modelos de Trabalho:
- VMs dedicadas a funções específicas: São configurações pré-definidas otimizadas para cargas de trabalho específicas, como desenvolvimento, produção, teste, entre outras.
- VMs otimizadas para diferentes cargas de trabalho: Podem ser configuradas para processamento em lote, análise de dados, aplicações web, etc.

## Escalabilidade e Condições:
- Escalabilidade automática: Permite que a quantidade de recursos (como vCPUs e RAM) seja ajustada automaticamente com base em métricas predefinidas, como utilização da CPU.
- Condições de escalabilidade: Define critérios para escalar verticalmente (aumentando os recursos da VM) ou horizontalmente (adicionando mais instâncias da VM).

## Regras para Portas de Entrada:
- Firewall e regras de rede: Permite configurar regras de firewall para controlar o tráfego de entrada e definir quais portas e protocolos são permitidos ou bloqueados.

## Sistemas Operacionais e Gerenciamento de Chaves:
- Seleção de sistemas operacionais: Permite escolher entre Windows Server, várias distribuições Linux, etc.
- Gerenciamento de chaves: Configura chaves SSH para acesso seguro a VMs Linux e chaves RDP para VMs Windows, garantindo a segurança dos acessos.

## Interfaces de Rede e Balanceamento de Carga:
- Interfaces de rede: Define as configurações de rede, como IP, sub-rede, gateway, etc., para comunicação interna e externa da VM.
- Balanceamento de carga: Distribui o tráfego entre várias instâncias de VMs para otimizar o desempenho e garantir alta disponibilidade.

## Gerenciamento de Identidades:
- Integração com Azure Active Directory: Permite gerenciar identidades de usuários e aplicar políticas de acesso baseadas em funções.
- Políticas de acesso: Define permissões e restrições de acesso com base em papéis e responsabilidades dos usuários.

## Monitoramento:
- Azure Monitor: Oferece ferramentas para monitorar o desempenho das VMs, coletando métricas como CPU, memória, disco, etc., e gerando alertas em caso de problemas.

## Adicionar Extensões:
- Extensões: São módulos que adicionam funcionalidades extras às VMs, como monitoramento de agentes, ferramentas de segurança, etc.

## Tags e Categorização:
- Tags: Permitem categorizar e organizar as VMs em grupos lógicos, facilitando a gestão, identificação e rastreamento das instâncias dentro do ambiente Azure.

# Aprendizado

- Tive a oportunidade de explorar a criaçao destas ferramentas, e um ponto importante.. A atençao aos detalhes é primordial para a escolha das opçoes em cada ferramenta.
- Tambem quero ressaltar a facilidade da criaçao, e a didática que o Azure te conduz em cada processo.

## Update

- Com o aprofundamento do aprendizado nas VMs, pude verificar a quantidade de personalizaçao que existe apenas neste serviço.
- AS configuraçoes atendem a necessidades muito especificas conforme cada projeto.
