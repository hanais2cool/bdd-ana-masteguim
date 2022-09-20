# BDD---TCC---BARKANET
#encoding: UTF-8
#language: pt

cadastro
Funcionalidade: Cadastro de um novo usuário 
E não logado 
Para que esse usuário crie um login 
E consiga acessar o Barkanet

Contexto: Dado que "A" não possui uma cadastro no Barkanet

Cenário 1: Informações válidas 
E ele acessa a página de cadastro 
E ele preenche as informações corretamente Quando ele envia o formulário para cadastro 
Ele será redirecionado para a página de login

Cenário 2: Informações inválidas ou formulário vazio 
E ele acessa a página de cadastro 
E ele preenche as informações de modo errado ou não preenche o formulário 
Quando ele envia o formulário para cadastro Aparecerá uma mensagem avisando que os campos estão preenchidos de modo errado.
