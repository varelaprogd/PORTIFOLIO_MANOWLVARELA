# PORTIFOLIO_MANOELVARELA
PORTFÓLIO PARA DOCUMENTAR O PROCESSO DE APRENDIZADO DA PROGRAMAÇÃO WEB
Projeto: Página para calcular média

Arquivo (s):

⚫ MANEL

Descrição: Página Web que calcula a média aritmética de duas notas.

Tecnologias utilizadas:

• JavaScript

• Google App Script

Dificuldades/erros encontrados durante o desenvolvimento do projeto:

Erro: TypeError: Cannot read properties of null (reading 'value')

Descrição: Não foi possível ler a propriedade especificada ao tentar utilizar a função getElementById(). Solução: Isso acontece porque o valor passado como parâmetro para a função getElementById() é diferente do Id do elemento que está sendo acessado

Projeto MANEL



# AULA DE WEB 02/06/2023
A gente teve que fazer um código para cadastrar e-mail senha  do usuário
Na aula essa códigos, tem cadastra os e-mail senha
Usamos os códigos para estrutura do programa <!DOCTYPE html>
<html>
  <head>
    <base target="_top">
  </head>
  <body>
    <h1>Login</h1>
    <form onsubmit="event.preventDefault(); verificarLogin();">
      <label for="email">E-mail:</label>
      <input type="email" id="email" required><br>
      <label for="senha">Senha:</label>
      <input type="password" id="senha" required><br>
      <input type="submit" value="Login">
      Esse base do estrutura do comando para funcionar é processar os dados.
