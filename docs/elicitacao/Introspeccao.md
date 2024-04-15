# Introspecção

## Introdução
Introspecção é uma técnica muito rica e profunda. Consiste em entender quais propriedades o sistema deve possuir para que seja um sucesso. Demanda o Engenheiro de Requisitos imaginar o que ele gostaria, se ele tivesse que desempenhar uma dada tarefa, com os equipamentos disponíveis e demais recursos.<a id="TEC1" href="#RP1">[1]</a>

## Metodologia

Para aplicar esta técnica, os alunos [Johnny Lopes](https://github.com/JohnnyLopess) e [José Filipi](https://github.com/JoseFilipi) primeiro assumiram papéis distintos, cada um se colocando em um cenário hipotético onde o uso do aplicativo se fazia necessário. Essa abordagem permitiu que cada um explorasse de forma criativa e detalhada como o aplicativo poderia ser utilizado em contextos diferentes, considerando variadas necessidades e desafios.

Durante a introspecção, eles se concentraram em identificar as funcionalidades que o aplicativo deveria possuir para atender efetivamente às situações propostas. A análise desses cenários possibilitou uma compreensão profunda das exigências práticas e das preferências dos usuários em potencial.

Com base nesta análise, foram elicitados requisitos específicos, que foram cuidadosamente documentados e estão detalhados nas tabelas 1 e 2. Estas tabelas apresentam uma organização clara dos requisitos funcionais e não funcionais.

## Situação hipotética

### [Johnny Lopes](https://github.com/JohnnyLopess)

Para aprimorar a experiência do usuário no aplicativo "Meu INSS", decidi adotar uma abordagem introspectiva e imaginativa, colocando-me na posição de um usuário que deseja acessar serviços e informações oferecidas pelo Instituto Nacional do Seguro Social (INSS) através do aplicativo, sem ter visibilidade direta de suas funcionalidades atuais.

### [José Filipi](https://github.com/JoseFilipi)

Visando melhorar a acessibilidade e a experiência do usuário no aplicativo "Meu INSS", optei por uma abordagem introspectiva na posição de um usuário com deficiência que busca acessar os serviços e informações fornecidos pelo Instituto Nacional do Seguro Social (INSS) por meio do aplicativo.


## Lista de Requisitos Elicitados

### Legenda da Tabela de Requisitos

- **Identificador**: Código único para cada requisito, usado para identificação e referência rápida, onde o IT significa Introspecção.
- **Requisito**: Descrição do que o sistema deve realizar (RF) ou das características que deve possuir (RNF).
- **Implementação**: Estado atual da implementação do requisito, indicando se já foi implementado.



### Requisitos Funcionais
<p align="center" > <strong> Tabela 1 - </Strong> Elicitação dos requisitos Funcionais</font> <gitbr></p>

|Identificador|Requisito|Implementação|
|:--:|:--:|:--:|
|IT01|O aplicativo deve permitir que o usuário se autentique usando CPF e senha para acessar informações pessoais e serviços.|Sim|
|IT02|O usuário deve poder visualizar detalhes de todos os benefícios aos quais tem direito, incluindo valores, datas de pagamento e status.|Sim|
|IT03|O aplicativo deve oferecer a funcionalidade de agendar, reagendar e cancelar perícias médicas.|Sim|
|IT04|O usuário deve ser capaz de enviar documentos necessários para o processo de requerimento ou manutenção de benefícios.|Sim|
|IT05|O aplicativo deve permitir que o usuário consulte o status de seus requerimentos, incluindo etapas completadas e pendências.|Sim|
|IT06|Deve haver uma funcionalidade para simular o tempo de contribuição e estimar a aposentadoria com base nos dados do usuário.|Sim|
|IT07|O usuário deve poder atualizar seus dados pessoais, como endereço, telefone e email.|Sim|

<p align="center">Fonte: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a> & <a href="https://github.com/JoseFilipi">José Filipi</a>, 2024.</p>


### Requisitos não Funcionais
<p align="center" > <strong> Tabela 2 - </Strong> Elicitação dos requisitos não Funcionais</font> <gitbr></p>

|Identificador|Requisito|Implementação|
|:--:|:--:|:--:|
|IT08|O aplicativo deve ser fácil de usar, com uma interface intuitiva que minimize o número de cliques para realizar uma tarefa.|Não|
|IT09|Todos os recursos do aplicativo devem ser acessíveis para pessoas com deficiência visual, incluindo leitores de tela compatíveis e suporte para gestos de acessibilidade.|Não|
|IT10|O aplicativo deve permitir ajustes de contraste e tamanho de fonte para facilitar a leitura por pessoas com deficiências visuais.|Não|
|IT11|O aplicativo deve ser compatível com tecnologias assistivas, como teclados virtuais, controle por voz e dispositivos de entrada alternativos.|Não|
|IT12|O aplicativo deve garantir a segurança das informações pessoais dos usuários através de criptografia de dados e autenticação robusta.|Sim|
|IT13|O aplicativo deve responder a comandos do usuário em menos de 3 segundos.|Sim|
|IT14|O aplicativo deve estar disponível 24 horas por dia, 7 dias por semana, com uma taxa de uptime de 99.9%.|Sim|
|IT13|O aplicativo deve ser compatível com as versões mais recentes e anteriores dos sistemas operacionais iOS e Android.|Sim|
|IT15|O aplicativo deve oferecer suporte em português e, opcionalmente, em inglês e espanhol.|Não|

<p align="center">Fonte: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a> & <a href="https://github.com/JoseFilipi">José Filipi</a>, 2024.</p>

## Referências Bibliográficas

> <a id="RP1" href="#TEC1">1.</a> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. Disponível em: [https://aprender3.unb.br/pluginfile.php/2844984/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdfg](https://aprender3.unb.br/pluginfile.php/2844984/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf). Acesso em: 14 abr. 2024.

## Bibliografia

> </a> Requisitos de Software. Bilheteria Digital (2023.1). Disponível em: [https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital). Acesso em: 14 abr. 2024.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 11/04/2024  | Versão inicial da pagina de Introspecção. | [Johnny Lopes](https://github.com/JohnnyLopess) & [José Filipi](https://github.com/JoseFilipi) | | |
| `1.1` | 14/04/2024  | Adição da introdução, metodologia e requisitos elicitados. | [Johnny Lopes](https://github.com/JohnnyLopess) | 15/04/2024 |[José Filipi](https://github.com/JohnnyLopess) |
| `1.2` | 15/04/2024  | Adição de requisitos de acessibilidade elicitados. | [José Filipi](https://github.com/JohnnyLopess) |15/04/2024 | [Johnny Lopes](https://github.com/JohnnyLopess)|