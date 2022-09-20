# BDD---TCC---BARKANET
#encoding: UTF-8
#language: pt

login
Funcionalidade: Login como um usuário cadastrado no Barkanet 
"A" quer completar o login 
Para que ele possa acessar sua conta
E as timelines do Barkanet

Contexto: Dado que "A" possua uma conta no Barkanet

Cenário: Login válido 
E ele acessa a página de login 
E ele preenche o formulário de login corretamente 
Quando ele clica em "Entrar" 
Ele será redirecionado para a página do seu perfil

Cenário: 
Login inválido 
E ele acessa a página de login 
E ele preenche o formulário de login incorretamente 
Quando ele clica em "Entrar" 
Aparecerá uma mensagem de usuário inválido
