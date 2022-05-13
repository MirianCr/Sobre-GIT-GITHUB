# Sobre-GIT-GITHUB
:point_right:Aqui vou colocar informações/comandos mais utilizados do Git

:magic_wand:

*********Git & GitHub*********<br>
:point_right:Nessa parte eu ensino a fazer a alteração da master para main<br>

:magic_wand:

:thumbsup:Verifique se o Git está instalado<br>

:magic_wand:

:star:No terminal digite git --version (preferível a versão 1.8 ou superior)<br>
Se não, baixe o Git [aqui] (http://git-scm.com/downloads). Então, configure seu perfil Git localmente - <br>

:star:no terminal:<br>
Digite git config --global user.name "seu-nome"<br>
Digite git config --global user.email "seu-email"<br>

:star:Para checar se o Git já está configurado, você pode digitar git config --list<br>

:star:Na linha de comando –tenha certeza de que você entrou na sua pasta railsgirls utilizando cd–e insira:<br>
==Aqui eu clico com botão direito em git bash here dentro da pasta que eu quero subir pro github<br>

:star:git init<br>
==Isso inicializa um repositório git no seu projeto<br>

:star:Então digite:
==git status
==Isso irá listar todos os arquivos no seu diretório de trabalho.

:star:Digite: <br>
==git remote add origin https//..seu endereço voce encontra na parte code https no github<br>
==Aqui ele cria uma copia do github para associar os dois projetos<br>

:star:Digite:
==git pull origin main<br>
==para salvar/puxar o primeiro commit<br>

:star:Digite:
==git checkout -b main
==para adaptar ao padrão main e nao mais o master<br>
==checkout ele muda de brainch<br>
== -b para criar branch caso nao exista ainda<br>

:star:Digite:
==git status (aqui a branch ja mudou pra main)<br>

:star:Digite:
==git add . ou git add "nome do seu arquivo se vc quer separado"<br>

:star:Digite:
==git commit -m "seu commit"   -  adicione o seu comentario <br>

:star:Digite:
==git log --oneline
==aqui pra vc ver o historico de commits<br>

:star:digite:
--git push origin main
--para enviar pro seu github

:magic_wand:

:point_right:Indico esse video para melhor entendimento:
https://www.youtube.com/watch?v=MdthEusEoy8
=====================================================================================

:magic_wand:

:point_right:PRA PODER DEIXAR OUTRAS PESSOAS VIZUALIZAREM O CODIGO SEM O CODIGO SO A PAGINA FINAL:===
SETTINGS;
GITHUB PAGES - SELECT BRANCHES marca brainch main; -root - CLICA SAVE
Ele vai ficar com final do link como io
======================================================================================
:magic_wand:

## Para criar um clone do repositorio
:point_right:Crie um novo repositorio no github

(Botao code no github- copiar o https)

:point_right:Crie uma nova pasta do seu projeto em seu pc

:point_right: Botao direito- git bash here [se necessario faca o download do gitbash] https://gitforwindows.org/

:point_right: git clone https://o-que- voce-copiou-do-botao-code-aqui.git
(aqui ele cria o arquivo .git e o readme)

:point_right:cd nome do seu repositorio (ex. dio-desafio-github)
(-voce pode criar suas pastas e arquivos com anotações e textos também)

:point_right:git status (pra ver o que vai subir)

:point_right:git add .

:point_right:git commit -m "suas anotações e comentarios aqui"

:point_right:git push origin main


