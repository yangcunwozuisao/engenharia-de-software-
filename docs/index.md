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
- [Análise de requisitos funcionais e não-fucionais](#Análise-de-requisitos-funcionais-e-não-fucionais)
- [Diagrama de casos de uso](#Diagrama de casos de uso)
- [Descrição dos casos de uso](#escrição dos casos de uso)
- [Diagrama de senquencia](#diagrama-de-ordem-interações)
- [Diagrama de classes](#diagrama-orientado-objetos)
- [Diagrama de componentes](#diagrama-estrutura-componente)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-hardware-software)
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
<!DOCTYPE html>
<html>
<head>
</head>
<body>

<h1>Requisitos Funcionais - Sistema de Atendimento de Pedidos e Localização de Fábricas de Pizza:</h1>

<h2>Sistema de Pedido Online:</h2>
<ul>
    <li>Contas de usuário.</li>
    <li>Seleção e personalização de pizzas.</li>
    <li>Opção de entrega ou retirada.</li>
    <li>Carrinho de compras.</li>
    <li>Confirmações de pedidos.</li>
</ul>

<h2>Localização do Cliente:</h2>
<ul>
    <li>Geolocalização automática.</li>
    <li>Exibição da fábrica de pizza mais próxima.</li>
</ul>

<h2>Processamento de Pedidos:</h2>
<ul>
    <li>Roteamento automático.</li>
    <li>Rastreamento de pedidos.</li>
    <li>Cancelamento antes da confirmação.</li>
</ul>

<h2>Estimativa de Tempo de Entrega:</h2>
<ul>
    <li>Cálculo e exibição do tempo estimado.</li>
    <li>Atualizações sobre atrasos.</li>
</ul>

<h2>Integração de Pagamento:</h2>
<ul>
    <li>Suporte a diferentes métodos.</li>
    <li>Segurança nas transações.</li>
</ul>

<h1>Requisitos Não Funcionais - Sistema de Atendimento de Pedidos e Localização de Fábricas de Pizza:</h1>

<h2>Desempenho:</h2>
<ul>
    <li>Lidar com picos de tráfego.</li>
</ul>

<h2>Segurança:</h2>
<ul>
    <li>Proteção de dados do cliente.</li>
</ul>

<h2>Usabilidade:</h2>
<ul>
    <li>Interface intuitiva.</li>
</ul>

<h2>Disponibilidade:</h2>
<ul>
    <li>24/7 com mínimo de inatividade.</li>
</ul>

<h1>Requisitos Funcionais - Sistema de Suporte para Operações da Fábrica de Pizzas:</h1>

<h2>Gerenciamento de Pedidos na Fábrica:</h2>
<ul>
    <li>Visualização e aceitação/rejeição de pedidos.</li>
    <li>Priorização baseada na proximidade e hora.</li>
</ul>

<h2>Produção Eficiente:</h2>
<ul>
    <li>Monitoramento de estoque.</li>
    <li>Programação de equipamentos.</li>
</ul>

<h2>Roteirização de Entregas:</h2>
<ul>
    <li>Cálculo de rotas eficientes.</li>
    <li>Atualizações em tempo real para motoristas.</li>
</ul>

<h1>Requisitos Não Funcionais - Sistema de Suporte para Operações da Fábrica de Pizzas:</h1>

<h2>Desempenho:</h2>
<ul>
    <li>Eficiência na preparação e entrega.</li>
</ul>

<h2>Segurança:</h2>
<ul>
    <li>Proteção de dados e transações.</li>
</ul>

<h2>Confiabilidade:</h2>
<ul>
    <li>Minimizar erros na preparação.</li>
</ul>

<h2>Integração:</h2>
<ul>
    <li>Integração perfeita com o sistema de atendimento de pedidos.</li>
</ul>

<h2>Escalabilidade:</h2>
<ul>
    <li>Lidar com aumento de pedidos.</li>
</ul>

<h2>Manutenção:</h2>
<ul>
    <li>Fácil manutenção e atualização.</li>
</ul>

</body>
</html>


# Diagrama de casos de uso

![diagrama de caso de uso 1](https://github.com/yangcunwozuisao/engenharia-de-software-/blob/master/uml_engenharia%20de%20software.drawio.png)

# Descrição dos casos de uso

*&lt;Descrição do comportamento entre os atores/resquisitos&gt;*

# Diagrama de sequencia

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Componentes

*&lt;Diagrama para exibir a relação estrutural dos componentes de um sistema de software

# Decisões de arquitetura

*&lt;Descrever a infraestrutura escolhida para arquitetura do projeto&gt;*

# Diagrama de implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
