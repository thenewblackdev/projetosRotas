#Projeto 1

Eu consegui criar todo o projeto, porém, tenho algumas dúvidas sobre isso...

Eu fiz via $_GET as páginas como foi mostrado nas aulas, tratei a falta do arquivo com a função 'file_exists' do php
e funcionou perfeitamente.

O meu grande problema agora é o formulário de contato, eu já tratei os dados que são enviados via $_POST, se tentar acessar
o arquivo pela URL (/acaoContato.php) ele diz que o formulário não foi preenchido corretamente.... Mas se você clicar 
no botão ENVIAR sem preencher NADA ele está caindo na condição errada, ou seja, está dizendo que os dados foram enviados
mas não aparece nada, pois eu coloquei condições para não mostrar as tags, NOME, EMAIL, etc...

Com a condição '<?php if (!empty($_POST))  : ?>' não está funcionando, ele continua entrando na condição errada...

Como eu faço para saber que meu $_POST veio VAZIO? Se eu fizer 1 por 1 eu sei que vai funcionar, mas é a maneira BEM ERRADA...
Eu tentei passar 1 array também: '$_POST[array("nome", email", "assunto", "mensagem")]' mas não funcionou, e creio que esta também
é a maneira errada, pois se eu tivesse 1 formulário dinâmico ou 200 campos eu tava ferrado para fazer isso na mão.

Eu não assisti as outras aulas, apenas estou aplicando o que eu já sei de PHP para ver se consigo.

Outro detalhe, eu tive que setar no footer.php o 'date_default_timezone_set()'... Sem ele o PHP gera 1 WARNING pra mim, mesmo eu
setando no 'PHP.ini' o meu 'timezone'.

> Por favor, me avise se aqui no README.md é o local certo para colocar as minhas dúvidas, caso contrário eu abro 1 chamado direto
no sistema.

*Abraços*