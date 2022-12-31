# Comparação de ambientes virtuais venv e conda para pacotes de redes complexas

## Descrição das atividades

Primeiramente foi criada uma máquina virtual Linux com a distribuição Ubuntu
e instalado a versão mais recente do Python. Essa máquina foi usada para analisar 
o processo de instalação de cada um dos três pacotes sem influência de pacotes 
previamente instalados no sistema.

Foram então instalados os softwares pip e minconda na máquina, assim criei os ambientes 
virtuais usando cada um deles. Dentro dos ambientes venv e conda instalei os pacotes de 
redes complexas usando pip e minconda, durante os processos de instalação anotei as 
dificuldades para o fazer e ao fim de cada uma delas verifiquei a quantidade de disco 
utilizado.



|-------------------|-------------------|--------|
| Pacote / Ambiente | venv (Usando pip) | conda  |
|-------------------|-------------------|--------|
| Networkx          | 32 MB             | 208 MB |
| igraph            | 29 MB             | 279 MB |
| graph-tools       | 87 MB             | 1.4 GB |
|-------------------|-------------------|--------|



Abaixo estão as informações mais detalhadas sobre o processo de instalação e comparação de cada pacote.


