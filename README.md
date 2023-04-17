# Instalando Python

Baixar o instalador para o seu sistema operacional em https://www.python.org/downloads/.
Recomenda-se a versão mais recente (3.11).
O seguinte guias (em português) ensinam a instalar.
https://python.org.br/instalacao-windows/
https://python.org.br/instalacao-mac/
https://python.org.br/instalacao-linux/

IMPORTANTE: durante a instalação no Windows, não se esqueça de marcar 'Add Python to PATH'.

# Instalando pacotes

Para o curso, recomenda-se instalar os seguintes pacotes:
- numpy
  - Fornece funções para manipular vetores e matrizes como o Matlab.
- scipy
  - Fornece funções para processamento de sinais.
- matplotlib
  - Pacote para plotar gráficos
- jupyter
  - Permite criar cadernos interativos para executar código Python.
- Pillow
  - Pacote para manipular imagens.

No prompt de comando, é possível instalar pacotes usando a ferramenta pip.
Basta digitar `pip install <nome do pacote>` ex: `pip install numpy`.
```
pip install numpy scipy notebook Pillow matplotlib
```
NB: o nome do pacote Jupyter no `pip` é `notebook`.

Se você estiver no diretório do projeto, pode instalar a lista a partir do arquivo `requirements.txt`.
```
pip install -r requirements.txt
```

Uma vez instalados todos os pacotes acima, abrir o jupyter notebook pelo prompt, usando o comando 'python3 -m notebook'.
