# 🛍️ Análise de Dados - AluraStore

Este repositório contém um projeto de análise de dados realizado com Python, Jupyter Notebook e Quarto. O objetivo é explorar e visualizar informações comerciais das lojas do grupo **AluraStore**, com foco em desempenho de vendas e comportamento dos clientes.

A análise foi feita utilizando técnicas de exploração de dados (EDA), agregações estatísticas e visualizações gráficas para responder perguntas-chave sobre o negócio. O projeto oferece uma visão completa dos dados de vendas, avaliando tanto a performance individual de cada loja quanto padrões gerais de consumo.

Foram considerados dados de faturamento, custos com frete, avaliações dos clientes, localização geográfica dos pedidos, categorias de produtos e volumes de vendas. Essa abordagem permite identificar quais lojas estão performando melhor, quais produtos têm mais (ou menos) saída e quais regiões concentram maior volume de vendas.

Além disso, foram aplicadas boas práticas de organização e documentação, com o relatório estruturado em Quarto, gerando uma versão final em PDF. Isso facilita a leitura, compartilhamento e reprodutibilidade do projeto.

Este repositório pode ser útil tanto como estudo de caso para aprendizado em análise de dados, quanto como base para análises empresariais reais em ambientes comerciais.

Sinta-se à vontade para navegar pelo código-fonte, reutilizar os gráficos e adaptar as análises para outras finalidades.


---

## 🚀 Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Jupyter Notebook**: Ambiente interativo para análise de dados.
- **Quarto**: Ferramenta para geração de relatórios científicos.
- **TinyTeX**: Distribuição LaTeX leve, usada para renderizar o PDF final do relatório.

---

## 📄 Visualizar o Relatório

👉 [Clique aqui para abrir o PDF](./relatorio-pdf.pdf)

---

## 📁 Conteúdo da Análise

O relatório aborda as seguintes análises:

- 📦 Faturamento das lojas do grupo AluraStore
- 🚚 Custos de frete
- 🥇 Produtos mais vendidos
- 🧊 Produtos menos vendidos
- 🗺️ Distribuição geográfica dos pedidos
- 🧾 Categorias dos produtos
- 🌟 Avaliações por loja

---

## ⚙️ Código-Fonte

- Código principal do relatório: [`relatorio-1.qmd`](./relatorio-1.qmd)
- (Opcional) Versão em Jupyter Notebook: [`relatorio-1.quarto_ipynb`](./relatorio-1.quarto_ipynb)

---

## ▶️ Como gerar o PDF

### 1. Instale o Quarto
Veja as instruções em: https://quarto.org/docs/get-started/

### 2. Instale o TinyTeX
Com Python:
```python
import tinytex
tinytex.install_tinytex()
```

Ou via terminal:
```bash
tlmgr install
```

### 3. Renderize o arquivo
```bash
quarto render relatorio-1.qmd --to pdf
```

---

## 📬 Contato

Dúvidas ou sugestões? Fique à vontade para abrir uma issue ou enviar um pull request.
c h a l l e n g e r - A l u r a S t o r e  
 