<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
Projeto UML
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#Autores)
- [Descrição do projeto](#Descrição-do-Projeto)
- [Análise de requisitos funcionais e não-fucionais](#Análise-de-requisitos-funcionais-e-não-funcionais)
- [Diagrama de casos de uso](#Diagrama-de-casos-de-uso)
- [Diagrama de senquencia](#Diagrama-de-sequencia)
- [Diagrama de classes](#Diagrama-de-classes)
- [Diagrama de componentes](#Diagrama-de-Componentes)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#Diagrama-de-implantação)
- [Referências](#referências)


# Autores

* Daniel Chen 
* Daniel Zou
* Danilo Ye

# Descrição do projeto

<p>O Pizza-Express é uma plataforma de de 40 lojas de fast-food e entrega em casa,com a problema de  negócio,perdeu 30% da renda.</p>

<p>Detalhe da problema:</p>

<p>O Pizza-Express anuncia a entrega em uma hora,no entanto,há outra plataforma que garante a entre de 30 minutos.</p>

<p>Solução da problema:</p>

<p>uma aplicação do software para identificar a localização de lojas de pizza Pizza-Express mais próxima do cliente e para criar o sistema de software necessário para operá-las,a fim de garantir a entrega em menos de 30 minutos,para isso,há duas projetos-primeiro é um sistema de software para o atendimento do pedido e para encontrar localização da fábrica da pizza mais próxima do cliente para fazer a entrega e segundo é um sistema de software para suportar operações da fábrica de pizzas.</p>


# Análise de requisitos funcionais e não-funcionais
# Requisitos Funcionais - Sistema de Atendimento de Pedidos e Localização de Fábricas de Pizza:

## Sistema de Pedido Online:

- Contas de usuário.
- Seleção e personalização de pizzas.
- Opção de entrega ou retirada.
- Carrinho de compras.
- Confirmações de pedidos.

## Localização do Cliente:

- Geolocalização automática.
- Exibição da fábrica de pizza mais próxima.

## Processamento de Pedidos:

- Roteamento automático.
- Rastreamento de pedidos.
- Cancelamento antes da confirmação.

## Estimativa de Tempo de Entrega:

- Cálculo e exibição do tempo estimado.
- Atualizações sobre atrasos.

## Integração de Pagamento:

- Suporte a diferentes métodos.
- Segurança nas transações.

## Requisitos Não Funcionais - Sistema de Atendimento de Pedidos e Localização de Fábricas de Pizza:

### Desempenho:

- Lidar com picos de tráfego.

### Segurança:

- Proteção de dados do cliente.

### Usabilidade:

- Interface intuitiva.

### Disponibilidade:

- 24/7 com mínimo de inatividade.

## Requisitos Funcionais - Sistema de Suporte para Operações da Fábrica de Pizzas:

### Gerenciamento de Pedidos na Fábrica:

- Visualização e aceitação/rejeição de pedidos.
- Priorização baseada na proximidade e hora.

### Produção Eficiente:

- Monitoramento de estoque.
- Programação de equipamentos.

### Roteirização de Entregas:

- Cálculo de rotas eficientes.
- Atualizações em tempo real para motoristas.

## Requisitos Não Funcionais - Sistema de Suporte para Operações da Fábrica de Pizzas:

### Desempenho:

- Eficiência na preparação e entrega.

### Segurança:

- Proteção de dados e transações.

### Confiabilidade:

- Minimizar erros na preparação.

### Integração:

- Integração perfeita com o sistema de atendimento de pedidos.

### Escalabilidade:

- Lidar com aumento de pedidos.

### Manutenção:

- Fácil manutenção e atualização.



# Diagrama de casos de uso

## Diagrama de casos de uso da Sistema de Atendimento de Pedidos e Localização de Fábricas de Pizza: 

![diagrama de caso de uso 1](https://github.com/yangcunwozuisao/engenharia-de-software-/blob/master/images/uml_engenharia%20de%20software.drawio%20(2).png)

## Diagrama de casos de uso da Sistema de Suporte para Operações da Fábrica de Pizzas:

![diagrama de caso de uso 2](https://github.com/yangcunwozuisao/engenharia-de-software-/blob/master/images/Untitled%20Diagram.drawio.png)

# Descrição dos casos de uso 

## descrição de casos de uso da Sistema de Atendimento de Pedidos e Localização de Fábricas de Pizza: 

- O cliente opta por navegar no diretório do cardápio ou inserir as informações de pesquisa de alimentos a serem visualizadas.

- O sistema processa a solicitação com sucesso e retorna à página correspondente do catálogo de refeições visualizada pelo cliente.

- Os clientes verificam o nome, preço, foto, número de pedidos e outras informações do prato.

- O cliente define a quantidade de compra do prato alvo, caso contrário a quantidade de compra padrão é

- O cliente define o prazo de entrega do prato e o tempo padrão é de 1 hora.

- O cliente coloca os pratos alvo definidos no carrinho de compras para garantir que quando o usuário confirmar o pedido, este

- As refeições podem aparecer na lista de compras do usuário. 7. O cliente repete os passos 3 a 6 até que todos os pratos sejam adicionados ao carrinho de compras.

- O cliente seleciona os pratos a serem apresentados no carrinho de compras. Clique no botão Enviar para gerar um pedido de envio.

- O cliente verifica o destinatário, endereço de entrega, prazo de entrega, número de contato, valor do pagamento e outras informações exibidas no pedido enviado.

- O cliente clica no botão de pagamento.

- O cliente escolhe a forma de pagamento, pagamento online ou contra-reembolso.

- O pagamento do cliente foi bem-sucedido.

- O sistema finaliza a operação do pedido.

## Descrição de casos de uso da Sistema de Suporte para Operações da Fábrica de Pizzas: 

- O cliente faz o pedido pelo site ou aplicativo mobile, seleciona o tipo de pizza, quantidade, recheio, etc., e informa o endereço de entrega e forma de pagamento.
- 
- Após o sistema receber o pedido, ele verifica a validade do pedido e envia uma mensagem de confirmação ao cliente.
- 
- O sistema atribui o pedido à pizzaria mais próxima e avisa o atendente da loja e o entregador.
- 
- O atendente confecciona a pizza de acordo com o pedido e atualiza o status da produção no sistema.
- 
- O entregador retira a pizza na loja e atualiza o status da entrega no sistema.
- 
- O entregador entrega a pizza ao cliente e recebe o pagamento (se pagar em dinheiro) ou confirma o pagamento (se pagar online).
- 
- O entregador atualiza o status da entrega no sistema e retorna à loja.

# Diagrama de sequencia

__Diagrama de sequência da Sistema de Atendimento de Pedidos e Localização de Fábricas de Pizza:__

![diagrama de sequencia1](https://github.com/yangcunwozuisao/engenharia-de-software-/blob/master/images/Diagrama%20de%20Sequ%C3%AAncia%20de%20atendimento.drawio.png)

__Diagrama de sequência da Sistema de Suporte para Operações da Fábrica de Pizzas:__

![diagrama de sequencia2](https://github.com/yangcunwozuisao/engenharia-de-software-/blob/master/images/Diagrama%20de%20sequencia%20de%20operacao.drawio.png)

# Diagrama de classes

__Diagrama de Classe de Domínio da Sistema de Atendimento de Pedidos e Localização de Fábricas de Pizza:__

![diagrama de classe 1](https://github.com/yangcunwozuisao/engenharia-de-software-/blob/master/images/calsse%20de%20dominio(engenharia%20de%20software).drawio.png)

__Diagrama de Classe de Domínio da Sistema de Suporte para Operações da Fábrica de Pizzas:__

![diagrama de classe 2](https://github.com/yangcunwozuisao/engenharia-de-software-/blob/master/images/Diagrama%20sem%20nome.drawio.png)

# Diagrama de Componentes

![diagrama de componente](https://github.com/yangcunwozuisao/engenharia-de-software-/blob/master/images/diagrama%20de%20componente.drawio.png)

# Decisões de arquitetura

Para a segurança da sistema,é necessário implementar uma abordagem abrangente de segurança para proteger sistemas e dados e garantir a confidencialidade dos dados durante a transferência,optando-se por utilizar protocolos de comunicação segura, como o HTTPS. 
A autenticação robusta foi implementada para clientes, funcionários e entregadores, incluindo autenticação de dois fatores, a fim de controlar o acesso às funcionalidades do sistema e prevenir acessos não autorizados. Práticas de segurança foram aplicadas na aplicação web para proteger contra ataques comuns, como injeção SQL e cross-site scripting. Adicionalmente, a proteção de dados sensíveis do cliente foi priorizada, utilizando criptografia para informações de pagamento e dados pessoais. Ferramentas de monitoramento de segurança e sistemas de detecção de intrusões foram implementados para identificar e responder rapidamente a atividades suspeitas. Estratégias robustas de backup e recuperação de dados foram estabelecidas para garantir a disponibilidade dos dados em situações adversas. Um processo eficiente de aplicação regular de atualizações de segurança foi adotado para mitigar vulnerabilidades conhecidas, assegurando que o sistema esteja protegido contra ameaças emergentes. Testes regulares, incluindo testes de penetração, são realizados para identificar e corrigir potenciais vulnerabilidades, garantindo a contínua robustez da segurança do sistema ao longo do tempo. Essas decisões visam a criar uma arquitetura segura e resiliente para o Pizza-Express, salvaguardando a integridade e confiabilidade das operações e dados do sistema.

# Diagrama de implantação

![diagrama de implementacao](https://github.com/yangcunwozuisao/engenharia-de-software-/blob/master/images/diagrama%20implementacao.drawio.png)

# Referências

*&lt;Lista de referências&gt;*
