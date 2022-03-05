# Sobre-GIT-GITHUB
Aqui vou colocar informações/comandos mais utilizados do Git

*********Git & GitHub*********<br>
Nessa parte ja fiz a alteração da master para main<br>

--Verifique se o Git está instalado<br>

--No terminal digite git --version (preferível a versão 1.8 ou superior)<br>
Se não, baixe o Git [aqui] (http://git-scm.com/downloads). Então, configure seu perfil Git localmente - <br>

--No terminal:<br>
Digite git config --global user.name "seu-nome"<br>
Digite git config --global user.email "seu-email"<br>

--Para checar se o Git já está configurado, você pode digitar git config --list<br>

--Na linha de comando –tenha certeza de que você entrou na sua pasta railsgirls utilizando cd–e insira:<br>
--Aqui eu clico com botão direito em git bash here dentro da pasta que eu quero subir pro github<br>

--git init<br>
--Isso inicializa um repositório git no seu projeto<br>

--Então digite:
--git status
--Isso irá listar todos os arquivos no seu diretório de trabalho.

--Digite: <br>
--git remote add origin https//..seu endereço voce encontra na parte codes<br>
--Aqui ele cria uma copia do github para associar os dois projetos<br>

--git pull origin main<br>
--para salvar/puxar o primeiro commit

--git checkout -b main
--para adaptar ao padrão main e nao mais o master<br>
--checkout ele muda de brainch<br>
-- -b para criar branch caso nao exista ainda<br>

--git status (aqui a branch ja mudou pra main)<br>

--git add . ou git add "nome do seu arquivo se vc quer separado"<br>

--git commit -m "seu commit"   -  seu comentario <br>

--git log --oneline
--aqui vc ve o historico de comits<br>

--git push origin main
--para enviar pro seu github
