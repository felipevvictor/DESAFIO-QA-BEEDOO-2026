# DESAFIO-QA-BEEDOO-2026
Desafio avaliatório para a empresa Beedoo

## Objetivo da aplicação
Consiste em ser um formulário web simples para inserção, visualização e deleção de lista de cursos

## Principais fluxos disponíveis
É possível visualizar texto e imagem de um curso já cadastrado.
cadastrar um curso por um formulário contendo: 
- Nome do curso
- Descrição do curso
- Instrutor do curso
- Capa ilustrativa
- Data de inicio e fim
- Número de vagas
- Tipo de curso (presencial ou online)
  
Remover um curso completamente (excluindo em forma de lista)

A aplicação web contém o título no canto superior à esquerda (Beedoo QA Chalenge) dois botões superiores à direta "Listar curso" e "cadastrar curso"
Após a inserção é possível visualizar todas as informações do curso

Na visualização existe o botão "Delete" que deve excluir o curso em questão retornando uma mensagem

## Pontos críticos

- Verificação de botões: se existe um botão obrigatóriamente ele deve funcionar, ou seja, ao ser precionado ele deve executar a função descrita
- Verificação de campos: os campos obrigatórios não devem permitir enviar o formulário ou deve gerar erro/log se o formulário for enviado
- Tipos de dados: cada campo deve obedecer o tipo de dado atribuído, não permitindo que um campo que aceite hora (dateTime) por exemplo, aceite uma string
- Elementos (Labels, Botões, TextArea, etc) não devem ser cortados ao redimencionar a página (O máximo de responsividade possível)
- Retorno de dados devem ser explicitos e verdadeiros (Se uma mensagem como "Item excluído" é apresentada, o item realmente deve ser excluído)
- Integridade: a aplicação deve rodar em todas as máquinas igualmente e não somente na máquina do programador
- Performance: a aplicação deve ser verdadeira e exibir logs caso a performance caia ou não consiga incluir grande quantidade de dados
- Segurança: se o app utilizar conexões com API ou Banco de dados, deve ser garantido a segurança dos dados para modificação interna ou possíveis ataques cibernéticos

## Casos de testes

https://docs.google.com/spreadsheets/d/1qgBsfl9ECuiDmuATrCxZZKODIL6gHhkzPPBiJEkSPTY/edit?usp=sharing 

