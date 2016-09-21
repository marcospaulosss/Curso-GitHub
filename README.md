# Curso-GitHub
Curso de GitHub

<h2>Configurando Informações Globais</h2>
<ul>
  <li>git config --global user.name "Marcos Paulo de Sousa Santo"</li>
  <li>git config --global user.email "marcospaulo.s.s@hotmail"</li>
</ul>

<h2>Criando Repositório</h2>
<ul>
  <li>git init</li>
</ul>

<h2>Verificação dos stages</h2>
<ul>
  <li>git status</li>
</ul>

<h2>Adicionando arquivos para versionamento do git</h2>
<ul>
  <li>git add . 'Adiciona todos os arquivos para acompanhamento do git'</li>
  <li>git add nome_arquivo 'Adiciona o arquivo especificado para o acompanhamento do git'</li>
</ul>

<h2>Ignorando arquivos indesejados para o acompanhamento do git</h2>
<ul>
  <li>git ignore 'Gera um arquivo onde sera especificado todos os arquivos ou pastar que o git pode ignorar no acompanhamento'</li>
</ul>

<h2>Efetuando Commits</h2>
<ul>
  <li>git Commit 'apos a adição dos arquivos no acompanhamento do git, possibilitando uma descrição mais detalhada sobre o commit'</li>
  <li>git commit -a -m 'adiciona e commita todos os arquivos existentes no 1 stage'</li>
</ul>

<h2>Regredindo Commits</h2>
<ul>
  <li>git reset --hard HEAD~1 (volta ao último commit)</li>
  <li>git reset --soft HEAD~1 (volta ao último commit e mantém os últimos arquivos no Stage)</li>
  <li>git reset --hard XXXXXXXXXXX (Volta para o commit com a hash XXXXXXXXXXX)</li>
</ul>

<h2>Criação de Branch</h2>
<ul>
  <li>git checkout -b nome_branch 'gera um branch'</li>
  <li>git branch 'Visualisa todos os branchs criados'</li>
  <li>git checkout nome_brench 'altera de um breanch para outro'</li>
</ul>

<h2>Migrando os dados de um branch para outro</h2>
<ul>
  <li>git merge nome_branch 'migra as informações do branch atual para o branch informado'</li>
  <li>git rebase nome_branch 'migra as informações do branch atual para o branch informado reordenando os commits'</li>
</ul>

<h2>Criando push</h2>
<ul>
  <li>git remote add origin nome_hash</li>
  <li>git rebase nome_branch 'migra as informações do branch atual para o branch informado reordenando os commits'</li>
</ul>
