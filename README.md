Desenvolva o aplicativo de blog em anexo e envie tudo em um arquivo ac07.zip (não .rar, nem .7z)
A pasta deve conter todo o projeto flask (arquivos .py, .html e .css) e no nome da pasta deve ser nome1_sobrenome1-nome2_sobrenome2

no arquivo flaskr.py coloque o cabeçalho conforme o padrão:

# Tecnologia WEB
# AC04 SI/ADS 2A- Tutorial Flask
# alunos: aluno1.sobrenome@aluno.faculdadeimpacta.com.br
# aluno2.sobrenome@aluno.faculdadeimpacta.com.br

* Correções no Tutorial:

Passo 0:
- Crie também uma pasta chamada "tmp" dentro da pasta flaskr

Passo 1:
- Altere o valor de da variável: DATABASE = './tmp/flaskr.db'

Passo 3:
- Não precisa utilizar o sqlite para gerar o banco, ou seja ignore o comando : "sqlite3 /tmp/flaskr.db < esquema.sql"
- Não é necessário importar o módulo: "from __future__ import with_statement"
- altere a linha "bd.cursor().executescript(sql.read())" para "bd.cursor().executescript(sql.read().decode('utf-8'))"

Passo 5: Este passos tem alguns erros de digitação
- Precisa trocar o comando sql '''select titulo, texto from entriadas order by id desc''' por '''select titulo, texto from entradas order by id desc''', pois o nome da tabela ta errada no original
- Precisa trocar todas as ocorrências de "db" por "bd", ele não inverteu na hora de copiar o código
- Precisa trocar todas as ocorrências da variável "error", por "erro", ele também não corrigiu a tradução

# Comentários finais


A intenção desta AC é que vocês exercitem a criação de um app Flask, leia os passos e entenda as linhas de código utilizadas.
Usarei a reposição de aula no dia 21/04 para dúvidas sobre a AC, mas tentem fazer o máximo que conseguirem antes disso.

Bom Trabalho!
