# DeepLearning-DisciplinaUFPB
Repositório com o material de apoio para a disciplina Tópicos Avançados em PDI (Deep Learning), ministrada pelos professores Leonardo Vidal, Tiago Maritan e Thaís Gaudencio no Centro de Informática (UFPB).

# Instalação

A disciplina utilizará Python como linguagem de programação principal, sendo recomendada a versão 3.6. Recomenda-se a instalação utilizando Miniconda.

## Miniconda

Anaconda é uma distribuição em Python e R que permite a utilização de ambientes virtuais e facilita a instalação de bibliotecas e pacotes. Ao criar um ambiente Conda, cada projeto poderá ter seu proprio ambiente apenas com os pacotes necessários, permitindo uma melhor organização da máquina.

### Instalação

1. Baixe e instale o [Miniconda](https://conda.io/miniconda.html)
2. Abra um terminal para criação de um ambiente e instalação de pacotes necessarios
```
$ conda create -n dl-ufpb python=3.6 numpy pandas matplotlib=2.0.2 scikit-learn jupyter keras tensorflow
```

# Utilização

## Miniconda
1. Abra o terminal e digite:
* Windows:
```
$ activate dl-ufpb
```
* Linux/Mac:
```
$ source activate dl-ufpb
```

## Jupyter Notebook

Notebooks são documentos que contém partes que podem ser executadas como código, e outras com elementos de texto (e.g. parágrafos, imagens, equações Latex, links), facilitando a interpretação e documentação de forma mais didática. O Jupyter é uma aplicação que edita e executa os Notebooks pelo navegador.

# Utilização

1. Abra o terminal e clone o repositório:

```
$ git clone https://github.com/cflavs/DeepLearning-DisciplinaUFPB.git
```

2. Acesse o diretório e digite:

```
$ jupyter notebook
```

Ao fazer isso, o seu navegador deverá abrir uma janela correspondente ao conteúdo do repositório. Caso isso não ocorra, o link do repositório estará disponível no terminal 


# Materiais de Apoio

* The Deep Learning Book (Ian Goodfellow and Yoshua Bengio and Aaron Courville, 2016)
* Deep Learning: A Practitioner's Approach (Josh Patterson, 2016)

# Equipe

* Prof. Leonardo Vidal
* Profa. Thais Gaudencio
* Prof. Tiago Maritan
* Cecília Flávia 
* Lira Neto

# Onde estamos
* Universidade Federal da Paraíba
* Centro de Informática
* Laboratórios de pesquisa LAViD/Visio







