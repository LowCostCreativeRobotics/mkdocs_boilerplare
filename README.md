# mkdocs_boilerplate

### Atualizar/Instalar pip

```pip install --upgrade pip```

Se precisar instalar o pip, baixe get-pip.py. E rode o comando:

```python get-pip.py```

### Instalando mkdocs
Instale o mkdocs usando o pip

```pip install mkdocs```

Após instalar o mkdocs, execute ``` mkdocs
--version ``` para verificar se foi instalado corretamente.

    $ mkdocs --version
    mkdocs, version 0.15.3

### Nota

Se você estiver usando windows, pode ser necessário executar os comandos dessa maneira:
```
python -m pip install mkdocs
python -m mkdocs

```

Para uma solução mais permanente é necessário editar a variavel de ambiente ` PATH` para incluir os Scripts que estão no diretório de instalação do Python. Versões mais recentes do Python incluem um script que faz isso para você. Vá até a pasta de instalação do Python (por exemplo C:\Python34\), abra a pasta Tools, e depois Scripts, e rode o script `win_add2path.py` clicando duas vezes nele. 

---

Para rodar o servidor de desenvolvimento da documentação, basta rodar o comando: 

```mkdocs serve```

Para adicionar uma nova página de documentação basta adicionar um arquivo com a extensão `.md` no diretório docs.

Para gerar o site estático, executar o comando: 
````mkdocs build```

[Folha de dicas para o Markdown(.md)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#lines)

Mais comandos de personalização, entrar no site oficial do [mkdocs](https://www.mkdocs.org/).


