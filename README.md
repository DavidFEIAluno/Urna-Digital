# Urna Digital

Feito por: David Ivaldi Elhain
RA: 24.124.009-2


Esse programa em C implementa um sistema de votação eletrônica simples. O objetivo é permitir que usuários se cadastrem, façam login, e votem em um dos candidatos cadastrados. O programa também inclui um sistema de encerramento de votação que exibe o vencedor ou, caso ocorra, informa sobre um empate.

Objetivo:

1. Cadastro de Usuários: Cada usuário pode se cadastrar fornecendo nome, CPF e RG formatados corretamente, e senha.


2. Votação: Após login, cada usuário pode votar em um dos candidatos disponíveis.


3. Encerramento e Apuração: Após o encerramento, o programa exibe os votos de cada candidato e informa o vencedor ou declara empate.



Compilação e Execução:

1. Compilação: O programa pode ser compilado em um terminal com o comando gcc nome_do_arquivo.c -o votacao.


2. Execução: Após compilado, o programa pode ser executado com ./votacao em ambientes Unix ou votacao.exe no Windows.



Funcionamento do Código:

Cadastro: A função cadastrar_usuario() permite ao usuário se registrar, validando CPF e RG e salvando uma senha, que o mesmo tenha colocado.

Login: A função login_usuario() permite ao usuário entrar na sessão.

Votação: Ao votar, o sistema valida o número do candidato e, se for válido, registra o voto e salva o log em um arquivo.

Encerramento: A função encerrar_votacao() exibe os resultados e verifica empates.

Esse sistema em C, é um sistema simples, que visou fazer uma Urna eletrônica, a inspiração dessa ideia, foi por conta do periodo atual de eleições, mas nem todos tem acesso ou tempo, seja pela dificuldade de transporte publicos, ou pela rotina de trabalho, essa urna poderia ajudar esse tipo de gente, visando facilitar o acesso, desse período de eleições em nosso país.
