# Especificações do Projeto

Para a especificação do projeto, foram determinadas as personas e suas histórias de usuários. Além disso, foram especificados os requisitos funcionais, não funcionais e restrições do projeto.

## Personas

<table style="border-collapse: collapse;">
  <tr>
    <td style="border: 1px solid black; padding: 10px;">
      <img src="https://i.imgur.com/Y9JHVPs.png" alt="Joana Santos" style="max-width: 100%; height: auto;">
    </td>
    <td style="border: 1px solid black; padding: 10px;">
      <img src="https://i.imgur.com/oUCGXZY.png" alt="José da Silva" style="max-width: 100%; height: auto;">
    </td>
  </tr>
</table>

<!-- Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja. -->

## Histórias de Usuários

A partir do conhecimento acerca das necessidades das personas Joana Santos e José da Silva, se tornou possível descrever as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Cliente  | Quero encontrar mão de obra qualificada na minha região          | Para tornar mais fácil a reforma ou construção de casas para locação e na própria casa.               |
|Cliente       | Quero encontrar preços acessíveis, ou seja, quero fazer vários orçamentos com profissionais distintos                 | Para comparar preços e conseguir o melhor custo-benefício. |
|Cliente  | Quero ter comodidade, praticidade e segurança na contratação de serviços           | Para ter praticidade e realizar uma melhor gestão na hora de escolher o serviço e os profissionais.               |
|Profissional       | Quero receber o pagamento conforme o previsto e no prazo proposto                 | Para receber conforme o acordado. |
|Profissional  | Quero ser avaliado pelos clientes           | Para poder ser referência no meu trabalho, me destacando e gerando novos serviços no futuro.               |
|Profissional       | Quero ter um contrato válido e bem definido                 | Para evitar imprevistos em projetos, como falta de materiais. |


<!-- > **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/) -->

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O site deve permitir que o usuário visualize na página inicial, a logo e o menu principal. O menu deve conter categorias como: cadastro/login, como funciona, quem somos, suporte, solicite um orçamento e blog. O usuário também deve conseguir visualizar ao longo da página principal, a apresentação do propósito da empresa, provas sociais, chamada para ação (cadastro na plataforma), assinatura de newsletter e rodapé. | ALTA | 
|RF-002| O site deve oferecer a funcionalidade de cadastro para usuários. Para o cliente, esse cadastro deve conter informações essenciais como nome completo, CPF, e-mail, senha, celular (WhatsApp), gênero, data de nascimento, endereço residencial. Para o cadastro de profissionais, será exibido um caminho alternativo, dando opções de registro de área de atuação, portfólio e imagens de trabalhos anteriores.| ALTA |
|RF-003| O site deve permitir que o usuário realize o login com nome de usuário e senha. | ALTA | 
|RF-004| O site deve permitir ao cliente visualizar e realizar feedbacks dos profissionais a qual está contratando o serviço. Com isso, os profissionais também poderão ver o histórico dos serviços prestados e para quais clientes foram.   | ALTA |
|RF-005| O site deve ter uma funcionalidade que permita o cliente entrar em contato com o profissional dentro do próprio site, para solicitar orçamentos e tirar dúvidas, sem a necessidade de uma ferramenta externa. | ALTA | 
|RF-006| O site deve fornecer aos usuários, quando sinalizado que o serviço vai ser realizado, um modelo de contrato amparando ambos os lados. Para o profissional, deve-se assegurar o recebimento do pagamento conforme o acordado e fornecimento dos materiais. Para o cliente, deve-se assegurar a entrega dentro do prazo previsto, com qualidade e segurança.   | ALTA |
|RF-007| O site deve permitir a visualização das informações de contato do mantenedor da plataforma (“suporte”), além de deixar um formulário à disposição. O suporte servirá de apoio para os usuários que necessitarem de um intermediador para resolver conflitos ou bugs na plataforma. | MÉDIA | 
|RF-008| O site deve fornecer uma página de blog ao usuário, onde ele terá acesso a dicas e informações acerca do ramo de construção civil e imóveis.   | BAIXA |
|RF-009| O site deve exibir para o usuário os comentários registrados juntamente com os posts publicados no blog. | BAIXA | 
|RF-010| O site deve apresentar uma funcionalidade de pesquisa com predefinições que ajudam o cliente a se orientar através do mesmo.   | BAIXA |
|RF-011| O site deve oferecer cards adicionais que permitam ao cliente visualizar os orçamentos de profissionais que mostraram interesse no serviço, contendo os dados do profissional, descrição do serviço e valor.   | BAIXA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deve ser publicado em um ambiente acessível publicamente na Internet (Repl.it, GitHub Pages, Heroku). | ALTA | 
|RNF-002| O site deve ser compatível e capaz de rodar nos principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) com alterações mínimas. |  ALTA | 
|RNF-003| O site deve cumprir com a Lei Geral de Proteção de Dados (LGPD). | ALTA | 
|RNF-004| O site deve proteger as informações do usuário, incluindo dados pessoais e informações financeiras contra ataques maliciosos. |  ALTA | 
|RNF-005| O site deve ser fácil de usar e atender aos requisitos de UX, sendo eles: todo o site deve ser responsivo, deve haver a otimização de imagens e o uso de técnicas de compressão de dados, a fim de minimizar o carregamento da página (que deve ser inferior a 3 segundos) e todas as páginas devem possuir feedback de usuários a partir de ações realizadas pelo mesmo. | ALTA | 
|RNF-006| O site deve atender aos principais critérios de acessibilidade visual, ou seja: todas as fontes devem ter tamanhos apropriados, todas as imagens/gráficos devem ter descrições apropriadas, e todos os esquemas de cores devem ser acessíveis. |  MÉDIA | 
|RNF-007| O site deve seguir em toda sua estrutura, as leis de pregnância e segregação de gestalt, a fim de gerar um visual agradável, intuitivo e fácil de navegar. Com isso, a escolha de imagens, cores e fontes devem ser apropriadas para o público-alvo. | MÉDIA | 
|RNF-008| O  perfil dos usuários, bem como suas avaliações recebidas, serão públicos a partir do momento que uma das partes se conectarem (seja por solicitação de orçamento ou até mesmo por pesquisa). |  BAIXA | 

<!-- Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos. -->

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir:

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue no final do semestre letivo.|
|02| Neste primeiro semestre, o site deve utilizar apenas tecnologias web fundamentais do Front-end.|
|03| Não é permitido à equipe terceirizar o desenvolvimento do trabalho.|
|04| Deve-se utilizar uma navegação clara, com as tags html apropriadas, para que os usuários que usam leitores de tela possam navegar com mais precisão, a fim de cumprir o que foi definido na RNF-06. |
|05| O design do site deve seguir as diretrizes e requisitos estabelecidos, como o uso de cores específicas, logotipos e estilo de fonte. |


<!-- Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/) -->
