# 🎨 Sistema de Processamento de Ativos Multimídia (ADS)

## 📝 Descrição do Projeto

Este projeto foi desenvolvido para a disciplina de **Lógica de Programação e Estrutura de Dados**, com foco no desenvolvimento de algoritmos para manipulação de matrizes e processamento digital de ativos. O sistema realiza a transformação de dados brutos em representações visuais e sonoras, simulando o backend de um editor multimídia.

O diferencial deste sistema é a utilização de **matrizes multidimensionais** para representar pixels e frequências sonoras. Através de loops aninhados e estruturas de dicionários complexas, o software é capaz de realizar o tratamento de cores (filtro de brilho) e a transposição de matrizes de áudio para harmonização de toques.

## 🚀 Tecnologias Utilizadas

* **Linguagem:** Python 3.10
* **Bibliotecas:**
* `Pillow (PIL)`: Para renderização e manipulação de imagens.
* `Matplotlib`: Para exibição gráfica e visualização de dados.

* **Paradigma:** Programação Estruturada e Manipulação de Coleções (Dicionários/Listas).

## 📊 Funcionalidades e Aprendizados

O projeto foca na eficiência algorítmica para processar dados estruturados:

* **Processamento de Imagem (Bitmask):** Implementação de um algoritmo que percorre uma matriz $5 \times 5$, identifica cores específicas (amarelo) e aplica uma redução de luminância de **50%**, demonstrando conceitos de manipulação de canais RGB.
* **Transposição de Áudio:** Reestruturação de matrizes de frequências musicais (Toques "Alegre" e "Triste"), convertendo listas de frequências em tuplas organizadas para processamento de som digital.
* **Redimensionamento por Interpolação:** Uso do método `NEAREST` para ampliar ativos de baixa resolução sem perda de definição estrutural (Pixel Art).

## 🔧 Estrutura do Código

O sistema está dividido em dois módulos principais:

### 1. Renderizador de Emojis (Matriz RGB)

Transforma uma grade de cores em uma imagem real.

![emoji](emoji.png)


```python
# Exemplo do processamento de cor
nova_cor = (cor_original[0] // 2, cor_original[1] // 2, 0) # Filtro de Escurecimento

```

### 2. Gestor de Biblioteca Musical

Organiza e processa matrizes de áudio em dicionários aninhados.

```python
# Transposição de matrizes de frequência
nova_matriz = ((linha1[0], linha2[0]), (linha1[1], linha2[1]))

```

## ⚙️ Como Executar

1. Certifique-se de ter o Python instalado.
2. Instale as bibliotecas necessárias:
```bash
pip install Pillow matplotlib

```


3. Clone o repositório:

```bash
   git clone https://github.com/seu-usuario/sistema-multimidia-ads.git

```

4. Execute o script principal:
```bash
python main.py

```





```

```
