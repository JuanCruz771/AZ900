
#  AZ900 ☁️

## ☁️ O que é Computação em Nuvem: 

Computação em nuvem é o modelo de fornecimento de recursos de TI (como servidores, bancos de dados, redes, armazenamento e softwares) pela internet, em vez de depender de infraestrutura física própria. Isso permite que empresas e usuários acessem serviços sob demanda, pagando apenas pelo que utilizam, com escalabilidade quase infinita, alta disponibilidade, segurança gerenciada pelo provedor e flexibilidade para ajustar recursos conforme a necessidade. Em resumo, é como "alugar" infraestrutura ou serviços de TI ao invés de comprar e manter tudo localmente.

## ☁️ Tipos de Nuvem:

| Tipo            | Características                        | Vantagens                         | Exemplo                               |
|-----------------|----------------------------------------|-----------------------------------|--------------------------------------|
| **Pública**     | Infraestrutura compartilhada pelo provedor, acessível via internet | Escalabilidade rápida, menor custo inicial, manutenção pelo provedor | Azure, AWS, Google Cloud            |
| **Privada**     | Infraestrutura dedicada a uma única empresa, on-premises ou hospedada por terceiros | Maior controle, segurança e customização | Data center próprio, Azure Stack     |

## 💰 O que é CAPEX e OPEX

CAPEX (Capital Expenditure) e OPEX (Operational Expenditure) são formas de classificar os gastos de uma empresa com infraestrutura de TI: o CAPEX refere-se a investimentos em ativos físicos próprios, como servidores, data centers e equipamentos, exigindo alto custo inicial e resultando em propriedade do bem; já o OPEX é gasto operacional contínuo, pago conforme o uso de serviços ou recursos, como VMs, storage e bancos de dados na nuvem, oferecendo flexibilidade, escalabilidade e menor investimento inicial.
| Tipo   | Definição                           | Características / Observações             | Exemplo                               |
|--------|-------------------------------------|------------------------------------------|--------------------------------------|
| **CAPEX** | Despesa de Capital                 | Compra de ativos físicos, alto investimento inicial, ativo próprio | Servidores e data centers próprios   |
| **OPEX**  | Despesa Operacional                | Pagamento recorrente, serviços sob demanda, flexível | VMs, storage e bancos de dados na nuvem |



##  O que é SLA: 

SLA (Service Level Agreement) é um acordo de nível de serviço entre o provedor (como Azure, AWS ou Google Cloud) e o cliente, que define a disponibilidade mínima garantida de um serviço (ex.: 99,9%), além de regras de qualidade, suporte e compensação caso o contrato não seja cumprido; em resumo, o SLA indica quanto tempo um serviço pode ficar indisponível sem quebrar o acordo, sendo que quanto maior o percentual, maior a confiabilidade e menor a tolerância a falhas.

| SLA (%)   | Indisponibilidade Máxima / Mês | Indisponibilidade Máxima / Ano |
|-----------|--------------------------------|--------------------------------|
| **99%**   | ~7h 18min                      | ~3 dias 15h 36min              |
| **99,9%** | ~43min                        | ~8h 45min                      |
| **99,95%**| ~21min                        | ~4h 22min                      |
| **99,99%**| ~4min 23s                     | ~52min 34s                     |
| **99,999%**| ~26s                         | ~5min 15s                      |


| Serviço                         | SLA (%)   | Máx. / Mês        | Máx. / Ano       |
|---------------------------------|-----------|-------------------|------------------|
| **VM isolada**                  | 99,9%     | ~43min            | ~8h 45min        |
| **VM em Availability Set**      | 99,95%    | ~21min            | ~4h 22min        |
| **VM em Availability Zones**    | 99,99%    | ~4min 23s         | ~52min 34s       |
| **Azure SQL Database**          | 99,99%    | ~4min 23s         | ~52min 34s       |
| **Armazenamento (Storage)**     | 99,9–99,99%| ~43min a ~4min   | ~8h 45min a ~52m |
| **App Service (Web Apps)**      | 99,95%    | ~21min            | ~4h 22min        |
| **Azure Kubernetes Service**    | 99,95%    | ~21min            | ~4h 22min        |
| **Load Balancer**               | 99,99%    | ~4min 23s         | ~52min 34s       |
| **Azure AD (Autenticação)**     | 99,9%     | ~43min            | ~8h 45min        |


## 🔹 Comparação entre IaaS, PaaS e SaaS

| Modelo | O que é? | O que o cliente gerencia | Exemplos |
|--------|----------|---------------------------|----------|
| **IaaS** (Infrastructure as a Service) | Infraestrutura como serviço: provedor entrega servidores, rede e armazenamento. | SO, aplicações, dados, runtime. | Azure VM, AWS EC2, Google Compute Engine |
| **PaaS** (Platform as a Service) | Plataforma como serviço: provedor entrega ambiente completo para desenvolvimento. | Apenas o código e dados da aplicação. | Azure App Service, Google App Engine, Heroku |
| **SaaS** (Software as a Service) | Software como serviço: usuário consome a aplicação pronta pela internet. | Nada, só usa o software. | Office 365, Google Workspace, Salesforce |
