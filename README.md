# jober-app

## Autores

Gabriel Alves de Paulo

Luis Fernando Pereira da Costa

Mateus Pereira de Souza

Raniery Pereira Azevedo

Ruan Lucas Soares do Nascimento

## Sumário

1. Introdução
2. Posicionamento
    1. Declaração do problema
    2. Declaração da posição do produto
3. Declaração das partes interessadas
    1. Resumo das partes interessadas
    2. Ambiente do usuário
4. Visão geral do produto
    1. Necessidades e recursos
5. Outros requisitos do produto
6. Requisitos funcionais
    1. Diagrama de casos de uso
    2. Especificação de casos de uso
        1. Caso de uso Manter Usuario – Mateus Pereira

        | Nome do caso de uso:      | CADASTRAR USUÁRIO |  CDU-01 |
        | ----------- | ----------- |  |
        | Ator Principal:    | Usuário |
        | Atores Secudários:    |  |
        | Atores Secudários:    |  |



        2. Caso de uso Manter Serviço Ofertado – Ruan Lucas
        3. Caso de uso Manter proposta – Gabriel Alves
        4. Caso de uso Interagir via chat – Luiz Fernando
        5. Caso de uso Efetuar pagamento on line – Raniery Azevedo
7. Lista de regras de negócio
8. Lista de requisitos não funcionais
9. Wireframe

## Introdução

O Jober é um aplicativo mobile para Android (6.0.1 ou mais) e IOS (10 ou
mais) que tem como objetivo promover oportunidades de trabalho para
Freelancers, tanto de serviços gerais ou de alguma habilidade específica,
com o objetivo de suprir um deficit de empregabilidade no Distrito Federal.

## Posicionamento

1. Declaração do problema

| Syntax      | Description |
| ----------- | ----------- |
| O problema da      | Crise na empregabilidade       |
| Afeta   | Os habitantes do Distrito Federal        |
| No qual o impacto é | Índice alto de desemprego        |
| Uma solução de sucesso seria      | Promover um aplicativo que facilita a comunicação entre um profissional (freelancer) e um cliente (o que necessita de um serviço), e, através desse vínculo, oferecer oportunidades de emprego e sanar a demanda de um trabalho, tornando-se uma medida eficaz para ambos os lados    |

2. Declaração da posição do produto

| Syntax      | Description |
| ----------- | ----------- |
| Para  | Freelancers e clientes do Distrito Federal.       |
| Quem  | Busca complementar ou adquirir uma renda (freelancer), ou tem uma demanda de serviço a ser sanada (cliente)        |
| O (Jober) | É um aplicativo.        |
| Que | Busca integrar um cliente com uma necessidade de serviço, e um freelancer disposto a prestar o serviço de forma rápida e eficiente.   |
| Diferente de |  Linkedin.  |
| Nosso produto |  Organiza os tipos de serviço ofertados em categorias, disponibiliza diversos freelancers capacitados a prestar o serviço, possibilita a comunicação entre as duas partes (cliente e freelancer) através de um sistema de chat, facilitando a negociação do serviço, oferece a possibilidade de pagamento por meio de carteira digital e outras formas de pagamento.  |

## Declaração das partes interessadas

1. Resumo das partes interessadas

| Nome      | Descrição |
| ----------- | ----------- |
| Freelancer      | Pessoa que deseje oferecer algum tipo de serviço, desde um “faz-tudo” até algo que demende uma habilidade specifica.       |
| Cliente   | Pessoa que necessite de um serviço não voltado para area empresarial.        |
| Administrador      | Pessoa responsável de cuidar da integridade do sistema.       |
| Desenvolvedores   | Pessoa responsável por cuidar da codificação e desenvolvimento do software em si.: Mateus, Gabriel e Luiz Fernando.        |
| Patrocinadores      | Pessoa responsável por oferecer uma ajuda monetária para o desenvolvimento do software. Raniery e Ruan.       |

2. Ambiente do usuário

O cenário atual do negócio é simples e se baseia na relação de uma pessoa que necessita de um serviço e uma outra que oferece seu serviço
por um preço, como um dono de imóvel que contrata um pedreiro para uma
reforma, por exemplo. Entretanto, no ambiente atual, encontrar alguém para um determinado tipo de serviço não é uma tarefa fácil, ainda mais quando é algo muito específico, e a escolha dos profissionais que são responsáveis por prestar algum serviço é normalmente feita através da recomendação de um terceiro, delimitando o escopo de profissionais com a mesma especialidade que poderiam prestar o tal serviço.

## Visão geral do produto

1. Necessidades e recursos

| Necessidades      | Funcionalidades correspondentes | Responsável |
| ----------- | ----------- | ----------- |
| Cadastrar usuários no sistema e definir a categoria do perfil do usuário para que possam ter acesso aos recursos oferecidos pela plataforma.      |<ul><li>Cadastrar Usuário </li><li>Consultar Usuário </li><li>Editar Usuário  </li><li>Excluir usuário </li></ul> | Mateus Pereira De Souza Moreira |
| Cadastrar o tipo de serviço oferecido pelo freelancer, afim de disponibilizar para que os clientes possam visualizar e escolher.|<ul><li>Cadastrar Serviço </li><li>Consultar Serviço</li><li>Editar Serviço  </li><li>Excluir Serviço. </li></ul> | Ruan Lucas Soares do Nascimento |
| Ofertar uma proposta para um freelancer, após a escolha do serviço.|<ul><li>Criar Proposta </li><li>Listar Proposta</li><li>Cancelar Proposta</li><li>Escolher Proposta</li><li>Aceitar Proposta</li><li>Recusar Proposta</li></ul> | Gabriel Alves de Paulo |
| Facilitar a comunicação entre os usuários, para que possam negociar de forma mais fácil e prática.|<ul><li>Enviar Mensagem</li><li>Visualizar Mensagem</li><li>Bloquear Usuário</li><li>Desbloquear Usuário</li></ul> | Luiz Fernando Pereira da Costa |
| Possibilitar o pagamento por meio da própria plataforma ou por meio de outras formas de pagamento.|<ul><li>Cadastrar Formas de Pagamento</li><li>Consultar Saldo</li><li>Editar Formas de Pagamento</li><li>Cancelar Formas de Pagamento</li><li>Emitir recibo</li></ul> | Raniery Pereira Azevedo |

## Outros requisitos do produto

| Requisitos não-funcionais      |
| ----------- |
| RNF 1: O sistema necessitará de conexão com internet.      |
| RNF 2: O sistema funcionará apenas em dispositivos com Android (6.0.1 ou mais) e IOS (10 ou mais).   |
| RNF 3: O sistema necessitará de conexão com o GPS do smartphone.  |

## Requisitos funcionais

1. Diagrama de casos de uso

![Use Case!](/usecase/use-case-full.png "Diagrama de Casos de Uso do Sistema")

2. Especificação de casos de uso
    1. Caso de uso Manter Usuario – Mateus Pereira

    | CDU-01 |
    | ----------- |

    | Nome do caso de uso: | CADASTRAR USUÁRIO |
    | ----------- | ----------- |
    | Ator Principal: | Usuário |
    | Atores Secundários:| |
    | Descrição: | Este caso de uso permite ao ator, se cadastrar no sistema. |
    | Pré-condições: | O usuário deve ter acesso ao sistema. |
    | Pós-condições: | Usuário cadastrado no sistema. |

    | Fluxo Basíco |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| O caso de uso tem inicio quando o ator clica em cadastre-se, na pagina inicial. | O sistema apresenta um formulário. |
    |2| O ator preenche as informações cadastrais. | O sistema valida os dados. <RN[1.1.1]><RN[1.1.2]><RN[1.1.3]> |
    |3| | O sistema armazena os dados, e redireciona o usuário para definir uma senha. |
    |4| O ator digita uma senha. | O sistema valida senha.<RN[1.1.4]> e guarda |
    |5| | O sistema apresenta a mensagem “Usuário cadastrado”. O caso de uso e encerrado. |


    | CDU-02 |
    | ----------- |

    | Nome do caso de uso: | VISUALIZAR USUÁRIO |
    | ----------- | ----------- |
    | Ator Principal: | Usuário |
    | Atores Secundários:| |
    | Descrição: | Este caso de uso permite ao ator, consultar, editar e excluir todas as informações do seu perfil de usuário. |
    | Pré-condições: | O usuário deve estar autenticado no sistema. |
    | Pós-condições: | Informações do usuário visualizadas. |

    | Fluxo Basíco |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| O caso de uso tem inicio na pagina inicial do app, quando o ator clica em visualizar dados de usuário. | O sistema recupera os dados do usuário. |
    |2| | O sistema apresenta os dados para o usuário e as opção de voltar editar e excluir.<RN[1.3] > |
    |3| O ator em voltar para pagina inicial.| O caso de uso é encerrado. |

    | FLUXO ALTERNATIVO 1 – EDITAR USUÁRIO |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| 2 – Editar dados. | O sistema recupera os dados. |
    |2| | O sistema apresenta um formulário para edição dos dados. |
    |3| | O sistema apresenta um formulário preenchido com os dados editáveis.<RN[1.1.3]> |
    |4| O ator modifica o campo que deseja alterar. | O sistema validada os dados. |
    |5| | O sistema guarda os dados. |
    |6| | O sistema apresenta a mensagem “Usuário alterado”. O caso de uso e encerrado. |


    | FLUXO ALTERNATIVO 2 – EXCLUIR USUÁRIO |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| 2 – O caso de uso tem inicio na pagina inicial do APP, quando o ator clica em excluir usuário. | O sistema recupera os dados. |
    |2| | O sistema apresenta um popup, perguntando se deseja mesmo excluir o perfil. |
    |3| O ator clica em sim, desejo excluir o meu perfil. | O sistema apresenta um checkbox com os possíveis motivos, e caixa de texto, caso queira relatar. |
    |4| | O sistema guarda os motivos da exclusão e solicita novamente autenticação para exclusão.|
    |5| O ator se autentica. | O sistema valida a autenticação. |
    |6| | O sistema verifica pendências relacionadas ao usuário.<RN[1.4.1]> |
    |7| |O sistema exclui o usuário. O caso de uso é encerrado.|


    | FLUXO EXCEÇÃO – VALIDAÇÃO DE DADOS |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| O fluxo de exceção tem inicio quando o ator tenta excluir o usuário. | O sistema apresenta um formulário para o usuário. |
    |2| O ator preenche os dados com valores incorretos. | O sistema apresenta a mensagem “Dados incorretos”. E não permite continuar, até que sejam preenchidos corretamente.<RN[1.1.2]><RN[1.1.3]><RN[1.1.4]> |
    |3| O ator deixa de preencher alguns dados. | O sistema apresenta a mensagem “Dados em branco”. E não permite continuar, até que sejam preenchidos os dados.<RN[1.1.2]><RN[1.1.3]><RN[1.1.4]> |
    |4| O ator deixa o formulário totalmente em branco.| O sistema apresenta a mensagem “Formulário em branco”. E não permite continuar, até que sejam preenchidos os dados.<RN[1.1.2]><RN[1.1.3]><RN[1.1.4]>|

    2. Caso de uso Manter Serviço Ofertado – Ruan Lucas


    | CDU-01 |
    | ----------- |

    | Nome do caso de uso: | MANTER SERVIÇOS |
    | ----------- | ----------- |
    | Ator Principal: | Freelancer |
    | Atores Secundários:| Cliente |
    | Descrição: | Descreve os passos para que o Freelancer possa cadastrar, ler, atualizar e excluir um tipo de serviço ofertado. Descreve os passos para que o Cliente possa visualizar os serviços ofertados. |
    | Pré-condições: | Ambos os atores devem estar cadastrados no sistema. O Cliente só terá acesso ao “Listar serviços ofertados”. |
    | Pós-condições: | Apresentar mensagens de conclusão de acordo com a função desejada. |

    | Fluxo Basíco – CADASTRAR SERVIÇO|
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| Efetuar login no sistema. | Validar dados de login. |
    |2| Clicar em “Perfil do usuário”. | Apresentar tela de “Perfil do usuário”. |
    |3| Clicar em “Listar serviços ofertados”. | Apresentar lista de serviços ofertados referentes a esse usuário. |
    |4| Clicar em “Adicionar serviço”. | Apresentar formulário para preenchimento dos dados. |
    |5| Digitar os dados e clicar em “Salvar”. | Salvar os dados no banco de dados. |
    |6|  | Retornar para a lista de serviços ofertados. |
    |7|  | Apresentar mensagem de “Serviço adicionado com sucesso.”. |

    | FLUXO ALTERNATIVO – CANCELAR CADASTRO DE SERVIÇO |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| Efetuar login no sistema. | Validar dados de login. |
    |2| Clicar em “Perfil do usuário”. | Apresentar tela de “Perfil do usuário”. |
    |3| Clicar em “Listar serviços ofertados”. | Apresentar lista de serviços ofertados referentes a esse usuário. |
    |4| Clicar em “Adicionar serviço”. | Apresentar formulário para preenchimento dos dados. |
    |5| Digitar os dados e clicar em “Cancelar”. | Retornar para a lista de serviços ofertados. |


    | Fluxo Basíco 2 – LISTAR SERVIÇOS |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| Efetuar login no sistema. | Validar dados de login. |
    |2| Clicar em “Perfil do usuário”. | Apresentar tela de “Perfil do usuário”. |
    |3| Clicar em “Listar serviços ofertados”. | Apresentar lista de serviços ofertados referentes a esse usuário. |


    | Fluxo básico 3 – ATUALIZAR SERVIÇOS|
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| Efetuar login no sistema. | Validar dados de login. |
    |2| Clicar em “Perfil do usuário”. | Apresentar tela de “Perfil do usuário”. |
    |3| Clicar em “Listar serviços ofertados”. | Apresentar lista de serviços ofertados referentes a esse usuário. |
    |4| Selecionar o serviço que deseja atualizar e clicar em “Atualizar”. | Apresentar formulário para preenchimento dos dados. |
    |5| Digitar os dados e clicar em “Atualizar”. | Salvar os dados no banco de dados. |
    |6|  | Retornar para a lista de serviços ofertados. |
    |7|  | Apresentar mensagem de “Serviço atualizado com sucesso.”. |


    | Fluxo básico 4 – EXCLUIR SERVIÇO |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| Efetuar login no sistema. | Validar dados de login. |
    |2| Clicar em “Perfil do usuário”. | Apresentar tela de “Perfil do usuário”. |
    |3| Clicar em “Listar serviços ofertados”. | Apresentar lista de serviços ofertados referentes a esse usuário. |
    |4| Selecionar o serviço que deseja atualizar e clicar em “Excluir”. | Apresentar mensagem de confirmação. |
    |5| Clicar em “Excluir”. | Excluir os dados do banco de dados. |
    |6|  | Retornar para a lista de serviços ofertados. |
    |7|  | Apresentar mensagem de “Serviço excluído com sucesso.”. |


    | FLUXO ALTERNATIVO 4 – CANCELAR EXCLUSÃO |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| Efetuar login no sistema. | Validar dados de login. |
    |2| Clicar em “Perfil do usuário”. | Apresentar tela de “Perfil do usuário”. |
    |3| Clicar em “Listar serviços ofertados”. | Apresentar lista de serviços ofertados referentes a esse usuário. |
    |4| Selecionar o serviço que deseja atualizar e clicar em “Excluir”. | Apresentar mensagem de confirmação. |
    |5| Clicar em “Cancelar”. | Retornar para a lista de serviços ofertados. |

    3. Caso de uso Manter proposta – Gabriel Alves


    | CDU-01 |
    | ----------- |

    | Nome do caso de uso: | Criar Proposta |
    | ----------- | ----------- |
    | Ator Principal: | Cliente |
    | Atores Secundários:|  |
    | Descrição: | O cliente cria uma proposta de serviço para o Freelancer contendo informações do serviço a ser prestado |
    | Pré-condições: | O cliente deverá está cadastrado e se encontrar na página de serviço que deseja ofertar. |
    | Pós-condições: | O êxito na criação da proposta. |

    | Fluxo Basíco |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| O cliente aciona a barra lateral do aplicativo “Listar serviços ofertados” | Validar dados de login. |
    |2|  | O sistema Lista os serviços ofertados. |
    |3| O cliente seleciona o serviço desejável e aciona o botão “Criar Proposta”. | Apresentar lista de serviços ofertados referentes a esse usuário. |
    |4|  | O sistema exibe o formulário para o cliente. |
    |5| O cliente preenche todos os campos do formulário. | Salvar os dados no banco de dados. |
    |6| O cliente aciona o botão “Enviar Proposta”. |  |
    |7|  | O sistema envia uma mensagem de confirmação “Você deseja enviar essa proposta” |
    |8| O cliente aciona a opção “Sim”. |  |
    |9|  | O sistema valida os dados preenchidos anteriormente pelo cliente. |
    |10|  | O sistema encaminha o formulário preenchido ao banco de dados do sistema com o status “Proposta em analise”<RN 3.1.1> |
    |11|  | O sistema exibe a mensagem para o cliente “Proposta Criada com sucesso” |
    |12|  | O sistema encaminha o cliente para página principal do aplicativo. |

    | Fluxo alternativo 1 – Reenviar proposta |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| O cliente aciona a barra lateral do aplicativo “Listar serviços ofertados” |  |
    |2|  | O sistema Lista os serviços ofertados. |
    |3| O cliente seleciona o serviço desejável e aciona o botão “Criar Proposta”. |  |
    |4|  | O sistema exibe o formulário para o cliente. |
    |5| O cliente preenche todos os campos do formulário. |  |
    |6| O cliente aciona o botão “Enviar Proposta”. |  |
    |7| O cliente preenche todos os campos do formulário. | O sistema envia uma mensagem de confirmação “Você deseja enviar essa proposta” |
    |8| O cliente aciona a opção “Sim”. |  |
    |9|  | O sistema valida os dados preenchidos anteriormente pelo cliente. |
    |10|  | Caso exista algum campo em branco o sistema exibe uma mensagem “Campos obrigatórios não preenchidos” |
    |11|  | O sistema exibe novamente o formulário junto com a mensagem |
    |12| O cliente preenche os dados que estão faltando e envia novamente o formulário |  |
    |13|  | O sistema valida os dados preenchidos anteriormente pelo cliente. |
    |14|  | O sistema encaminha o formulário preenchido ao banco de dados do sistema com o status “Proposta em analise”<RN 3.1.1> |
    |15|  | O sistema exibe a mensagem para o cliente “Proposta Criada com sucesso” |
    |16|  | O sistema encaminha o cliente para página principal do aplicativo. |

    | CDU-02 |
    | ----------- |

    | Nome do caso de uso: | Cancelar Proposta |
    | ----------- | ----------- |
    | Ator Principal: | Cliente |
    | Atores Secundários:| |
    | Descrição: | Cancelar Proposta criada anteriormente pelo cliente |
    | Pré-condições: | O Freelancer não deve ter aceitado a proposta ainda. |
    | Pós-condições: | O cancelamento da proposta de serviço |

    | Fluxo Basíco |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| O cliente aciona a barra lateral do aplicativo “Listar Propostas” |  |
    |2|  | O sistema exibe todas as propostas criadas por esse cliente. |
    |3| O cliente escolhe a proposta que deseja cancelar |  |
    |4|  | O sistema exibe somente a proposta selecionada |
    |5|  | O sistema exibe a mensagem “Deseja realmente cancelar a proposta” |
    |6| O cliente aciona o botão “Sim”. |  |
    |7|  | O sistema exibe „Proposta cancelada com sucesso” |
    |8|  | O sistema troca o status da proposta como “Proposta cancelada”.<RN 3.1.1> |
    |9|  | O sistema retorna a página inicial do aplicativo |

    | Fluxo alternativo 1 – Negar cancelamento de proposta |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| O cliente aciona a barra lateral do aplicativo “Listar Propostas” |  |
    |2|  | O sistema exibe todas as propostas criadas por esse cliente |
    |3| O cliente escolhe a proposta que deseja cancelar |  |
    |4|  | O sistema exibe somente a proposta selecionada |
    |5|  | O sistema exibe a mensagem “Deseja realmente cancelar essa proposta” |
    |6| O cliente aciona o botão “Não” |  |
    |7|  | O sistema retorna a página inicial do aplicativo |

    | CDU-03 |
    | ----------- |

    | Nome do caso de uso: | Listar Propostas |
    | ----------- | ----------- |
    | Ator Principal: | Cliente,Freelancer |
    | Atores Secundários:| |
    | Descrição: | Listagem das propostas |
    | Pré-condições: | O Ator deve estar logado no sistema |
    | Pós-condições: | Apresentação das propostas de serviço |

    | Fluxo Basíco |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| O ator aciona na barra lateral do aplicativo. |  |
    |2|  | O sistema exibe todas as opções da barra lateral |
    |3| O ator aciona “Listagem de todas as propostas” |  |
    |4|  | O sistema exibe todas as opções disponíveis |

    | CDU-04 |
    | ----------- |

    | Nome do caso de uso: | Escolher Proposta |
    | ----------- | ----------- |
    | Ator Principal: | Freelancer |
    | Atores Secundários:| |
    | Descrição: | Será a decisão do freelancer se ele aceita ou rejeita a proposta do cliente. |
    | Pré-condições: | O freelancer deve estar logado no sistema e possuir pelo menos 1 proposta de serviço |
    | Pós-condições: | O freelancer deve receber todas as informações necessárias para a prestação do serviço junto com o status de “Proposta Aceita” |

    | FLUXO BÁSICO-ACEITAR PROPOSTA |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| O freelancer aciona na barra lateral a listagem de propostas |  |
    |2|  | O sistema exibe todas as propostas disponíveis para aquele freelancer |
    |3| O freelancer seleciona uma proposta |  |
    |4|  | O sistema exibe detalhes dessa proposta de serviço. |
    |5|  | O sistema exibe uma mensagem “Deseja realmente escolher essa proposta de serviço”. |
    |6| O freelancer aciona “Sim” |  |
    |7|  | O sistema exibe todas as informações necessárias para que se possa realizar o serviço |
    |8|  | O sistema muda o status do serviço para “Proposta aceita” |

    | FLUXO ALTERNATIVO – RECUSAR PROPOSTA |
    | ----------- |

    | | Ações do Ator | Principal: Usuário Ações do Sistema: |
    | ----------- | ----------- | ----------- |
    |1| O freelancer aciona na barra lateral a listagem de propostas |  |
    |2|  | O sistema exibe todas as propostas disponíveis para aquele freelancer |
    |3| O freelancer seleciona uma proposta |  |
    |4|  | O sistema exibe detalhes dessa proposta de serviço. |
    |5|  | O sistema exibe uma mensagem “Deseja realmente escolher essa proposta de serviço” |
    |6| O freelancer aciona “Não” |  |
    |7|  | O sistema retorna o freelancer para aba de listagem de propostas |


    4. Caso de uso Interagir via chat – Luiz Fernando
    5. Caso de uso Efetuar pagamento on line – Raniery Azevedo

## Lista de regras de negócio

| Regras de negócio |
| ----------- |
| RN 1.1.1 (Cadastrar Usuário): Todo usuário do JOBER deverá obrigatoriamente vinculado a somente um CPF. |
| RN 1.1.2 (Cadastrar Usuário): Todo usuário do JOBER deverá obrigatoriamente estar cadastrado com um dos tipos de usuário, sendo: cliente, freelancer e administrador. |
| RN 1.1.3 (Preenchimento Obrigatório): Todos os campos do cadastro são obrigatórios, sendo eles: nome, sexo, cpf, cep, estado e tipo de usuário. |
| RN 1.1.4 (Cadastro de Senha): O usuário deverá cadastrar uma senha de no mínimo 8 e no máximo 12 caracteres. A senha não poderá conter dados que estejam presentes no cadastro do usuário. |
|RN 1.2 (Consultar Usuário): O sistema não poderá apresentar dados sensíveis para outros usuários, tais como cartão de crédito, CPF e endereço do usuário consultado.|
|RN 1.3 (Alteração do Cadastro): O cadastro poderá ser atualizado quando houver alteração dos dados do usuário. Todos os campos estarão habilitados para atualização, exceto o campo CPF (somente editável caso o usuário tenha como provar judicialmente, ter mudado o CPF).|
|RN 1.4.1 (Exclusão de Cadastro): O usuário sendo cliente ou freelancer, não poderá ser excluído caso tenham alguma pendência financeira no APP.|
|RN 1.4.2 (Exclusão de Cadastro): Se houver a necessidade de desativação por motivos de: mudança de cidade, falecimento, ou por quaisquer outros motivos expressos pelo usuário, o mesmo deverá receber o status “Usuário Inativo”.|
|RN 2.1 (Criar Serviço): O usuário pode cadastrar no máximo cinco tipos de serviço diferentes.|
|RN 3.1 (Escolher Proposta): O serviço só pode ser aceito por apenas 1 freelancer.|
|RN 3.1.1 (Criar Proposta,Escolher Proposta): Os status do serviço são divididos em -Proposta em analise -Proposta cancelada -Proposta aceita
|RN 3.2 (Cancelar Proposta): Caso o FreeLancer não tenha aceitado o contrato, o cliente poderá fazer o cancelamento em até 24h.|
|RN 3.2.1 (Cancelar Proposta): O cancelamento do contrato só pode ser feito caso o FreeLancer não tenha aceitado ainda.|
|RN 4.1 (Enviar Mensagem): Uma identificação do usuário deve ser informada (Nome).|
|RN 4.2 (Bloquear Usuário): É permitido apenas assuntos vinculados ao aspecto professional, sendo permitido um usuário reportar e bloquear, caso submetido a assuntos pessoais.|
|RN 4.2.1 (Bloquear Usuário): Caso haja qualquer tipo de discordia e descumprimento de regras, o usuário poderá ser reportado e bloqueado.|
|RN 5.1 (Cadastrar Forma de Pagamento): É permitido pagamentos com cartão de crédito.|
|RN 5.1.1 (Cadastrar Forma de Pagamento): O usuário dispõem de uma carteira digital.|
|RN 5.1.2 (Cadastrar Forma de Pagamento): É permitido pagamentos através diretamente da plataforma.|

## Lista de requisitos não funcionais

|Requisitos não-funcionais|
| ----------- |
|RNF 1: O sistema deverá oferecer uma carteira digital para o pagamento dos serviços.|
|RNF 2: O sistema poderá utilizar do GPS para possibilitar a visualização de Freelancers próximos ao local.|
|RNF 3: O sistema deverá utilizar do módulo de Informações Cadastrais em modo off-line.|
|RNF 4: O sistema possibilitará a verificação de duas etapas para maior segurança.|

## Wireframe