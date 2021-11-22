# analise-dados-python

Apresentação do MODCLIM5 sobre tratamento de dados com Python com aplicação ao setor elétrico.

## :scroll: Conteúdo

1. Coleta de arquivos do modelo de previsão GEFS, direto da fonte;
2. Como trabalhar com a extensão grib;
3. Visualização espacial da previsão;
4. Manipulação da informação na grade;
5. Granularização! - Breve estudo sobre a previsão na bacia de Itaipu.

## :rocket: Como executar

Para rodar o notebook, você precisará do gerenciador `conda` instalado, e um ambiente conda dedicado para o projeto. Caso não possua, você pode baixar o conda [aqui](https://docs.conda.io/en/latest/)! 

Para ajudar a configurar o ambiente, disponibilizamos um script `bash` que irá ler as dependências necessárias no arquivo `.yaml` do repositório e criar o ambiente `modclim5` para você. :)

Certifique-se de que você possui o conda, e rode o seguinte comando em seu terminal `linux`:

```bash
# para instalar o ambiente
bash conda-install.bash

# para ativar o ambiente
conda activate modclim5
```

O notebook pode ser executado através do `vscode` (certifique-se de que a sua versão possui suporte à notebooks) OU executando o comando `jupyter lab` no terminal com seu ambiente conda ativo.

## Dúvidas, sugestões, contato

Sinta-se livre para subir uma issue no repositório ou enviar um e-mail para `andradelis@id.uff.br`, caso prefira. :)


Bons códigos! :sparkles:  