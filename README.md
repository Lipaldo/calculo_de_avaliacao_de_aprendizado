# calculo_de_avaliacao_de_aprendizado
# 🧠 Cálculo Interativo e Visual de Métricas de Avaliação

![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Ready-orange)
![License](https://img.shields.io/badge/license-MIT-green)

## 🎯 Descrição do Projeto

Este projeto tem como objetivo **calcular e interpretar as principais métricas de avaliação de modelos de classificação supervisionada**, de forma **interativa e visual**.
A partir de valores inseridos pelo usuário na **matriz de confusão**, o notebook calcula automaticamente:

* **Acurácia (Accuracy)**
* **Precisão (Precision)**
* **Sensibilidade / Recall**
* **Especificidade (Specificity)**
* **F-Score (F1-Score)**

Em seguida, o programa apresenta:

* Uma **tabela detalhada** com os resultados e descrições das métricas.
* Uma **interpretação textual automática** do desempenho do modelo.
* Um **gráfico de barras colorido** comparando visualmente as métricas.

---

## 🧩 Estrutura do Projeto

O notebook foi estruturado em **cinco etapas**:

1. **Entrada de dados**: o usuário informa VP, VN, FP e FN.
2. **Cálculo das métricas**: fórmulas aplicadas automaticamente.
3. **Apresentação dos resultados**: tabela formatada com `tabulate`.
4. **Interpretação dos resultados**: análise textual automática.
5. **Visualização gráfica**: gráfico comparativo com `matplotlib`.

---

## 📘 Fórmulas Utilizadas

| Métrica                    | Fórmula                                       | Descrição                                      |
| -------------------------- | --------------------------------------------- | ---------------------------------------------- |
| **Acurácia**               | (VP + VN) / (VP + VN + FP + FN)               | Proporção total de acertos.                    |
| **Precisão**               | VP / (VP + FP)                                | Percentual de predições positivas corretas.    |
| **Recall (Sensibilidade)** | VP / (VP + FN)                                | Capacidade de detectar positivos corretamente. |
| **Especificidade**         | VN / (VN + FP)                                | Capacidade de detectar negativos corretamente. |
| **F-Score**                | 2 × (Precisão × Recall) / (Precisão + Recall) | Média harmônica entre Precisão e Recall.       |

---

## 🧮 Exemplo de Uso

```bash
📊 Digite os valores da Matriz de Confusão

Verdadeiros Positivos (VP): 50
Verdadeiros Negativos (VN): 40
Falsos Positivos (FP): 10
Falsos Negativos (FN): 5
```

📈 **Saída esperada (tabela resumida):**

| Métrica                | Valor  | Descrição                           |
| ---------------------- | ------ | ----------------------------------- |
| Acurácia               | 0.9000 | Proporção total de acertos          |
| Precisão               | 0.8333 | Predições positivas corretas        |
| Recall (Sensibilidade) | 0.9091 | Capacidade de identificar positivos |
| Especificidade         | 0.8000 | Capacidade de identificar negativos |
| F-Score                | 0.8696 | Equilíbrio entre precisão e recall  |

---

## 📊 Visualização Gráfica

O gráfico de barras exibe o desempenho relativo de cada métrica:

```
📊 Comparativo das Métricas de Avaliação
```

*(Gerado automaticamente com Matplotlib.)*

---

## 🧠 Objetivo Educacional

O projeto foi desenvolvido com fins didáticos, permitindo:

* **Compreender o significado de cada métrica** na avaliação de modelos.
* **Explorar diferentes combinações de erros** (FP, FN) e seus impactos.
* **Visualizar o desempenho geral do classificador** de forma intuitiva.

Ideal para disciplinas de:

* Inteligência Artificial
* Aprendizado de Máquina
* Avaliação de Modelos
* Mineração de Dados

---

## ⚙️ Tecnologias Utilizadas

* [Python 3.10+](https://www.python.org/)
* [Google Colab](https://colab.research.google.com/)
* [Matplotlib](https://matplotlib.org/)
* [Tabulate](https://pypi.org/project/tabulate/)

---

## 🚀 Como Executar no Google Colab

1. Acesse o Colab: [https://colab.research.google.com](https://colab.research.google.com)
2. Crie um novo notebook.
3. Copie e cole o código do projeto (todas as células).
4. Execute as células em sequência.
5. Insira os valores de **VP, VN, FP e FN** quando solicitado.

---

## 🧾 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
Sinta-se à vontade para usar, modificar e compartilhar para fins educacionais.

---

## ✍️ Autor

**Felipe Maciel**
Professor de Sistemas de Informação • Doutor em Educação • Especialista em IA aplicada à Educação
📧 [Entre em contato](mailto:seuemail@exemplo.com)

