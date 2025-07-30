<h1 align="center">Alura Store</h1>

<p align="center">
  <a href="https://github.com/viniciuseduardofarias/desafio-vendas-alura-store">
    <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/0*TMvhLMMOy0NHzNIy.gif" alt="Visão Geral do Projeto" />
  </a>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"></a>
  <a href="#"><img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"></a>
  <a href="#"><img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"></a>
  <a href="#"><img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib"></a>
  <a href="https://www.linkedin.com/in/vinicius-eduardo-farmacia/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<h4 align="center">Projeto de Análise de Dados 📊🛒</h4>

<h4 align="center">
  :white_check_mark: Concluído
</h4>

---

## 📝 Descrição do Projeto

Este projeto faz parte de um desafio de **análise de dados** proposto no contexto do programa **Oracle Next Education**, em parceria com a **Alura**. A atividade consiste na **exploração e visualização de dados** consolidados de vendas de quatro lojas online (Loja 1 a Loja 4), abrangendo informações como produtos, categorias, valores de frete, localização dos pedidos, avaliações de clientes e dados de transações.

A análise foi desenvolvida em um ambiente interativo (**Google Colab**), utilizando bibliotecas como **Pandas**, **Seaborn** e **Folium** para gerar visualizações e identificar padrões relevantes, afim de transformar dados brutos em **insights estratégicos** que possam auxiliar na **tomada de decisões** do negócio.

## 🎯 Objetivo

O objetivo deste projeto é realizar uma análise comparativa entre as quatro unidades da Alura Store, a fim de identificar padrões de desempenho e subsidiar decisões estratégicas baseadas em dados. Para isso, foram avaliados aspectos como faturamento, perfil dos produtos mais vendidos, nível de satisfação dos clientes, custos com frete e a distribuição geográfica dos pedidos.

Com base nesses indicadores, busca-se responder à seguinte pergunta central: **“Qual loja apresenta melhor desempenho para ser priorizada nas vendas?”** A proposta é transformar os dados em informações claras, que revelem os pontos fortes e os desafios de cada loja.

## 2. Análise dos Dados

### 2.1 Faturamento Total das Lojas

<img width="784" height="584" alt="image" src="https://github.com/user-attachments/assets/a47d8d31-a0de-456e-943c-98439a25f612" />

A análise do faturamento revela diferenças significativas no desempenho financeiro entre as quatro unidades da Alura Store. A **Loja 1** se destacou como a loja com maior receita total, atingindo aproximadamente **R$ 1.534.509,12**, o que pode indicar um alto volume de vendas ou um maior valor médio por transação.

Na sequência, aparecem a **Loja 2** e a **Loja 3**, com valores próximos entre si, sugerindo um desempenho relativamente equilibrado.

Por outro lado, a **Loja 4** apresentou o menor faturamento, totalizando **R$ 1.384.497,58**. Esse resultado pode refletir um fluxo menor de clientes, ticket médio reduzido ou até mesmo menor competitividade na sua região de atuação.

## 2.2 Categorias de Produtos Mais Vendidas

<img width="1177" height="584" alt="image" src="https://github.com/user-attachments/assets/7ee3031b-b089-42c1-b9d4-fa8424d9f23f" />

A categoria de móveis lidera as vendas em todas as lojas, com a Loja 3 registrando o maior volume (499 vendas). Eletrônicos também se destacam especialmente nas Lojas 1 e 4. A Loja 4 apresenta um mix de produtos mais equilibrado, enquanto as Lojas 1 e 3 concentram suas vendas em poucas categorias, tornando-se menos diversificadas. A Loja 2 mantém desempenho estável, mas sem grandes destaques. Essas diferenças indicam que um mix diversificado pode proteger melhor contra variações de mercado.

## 2.3 Avaliação Média dos Clientes

<img width="687" height="479" alt="image" src="https://github.com/user-attachments/assets/e3f44873-ddde-4607-8952-7fac93d203ae" />

A Loja 3 apresenta a maior média de avaliação (4,05), indicando melhor experiência de compra. As Lojas 2 (4,04) e 4 (4,00) também tiveram avaliações satisfatórias. A Loja 1 ficou abaixo de 4,0, com média de 3,98, apontando possíveis problemas no atendimento ou entrega. Essas avaliações são essenciais para entender a qualidade percebida e seu impacto na fidelização e crescimento das lojas.

## 2.4 Desempenho de Vendas por Produto

Cada loja tem um perfil distinto nos produtos mais vendidos:

- Loja 1 foca em eletrodomésticos e móveis, como micro-ondas, TV LED UHD 4K, guarda-roupas e cômodas, contribuindo para seu alto faturamento.
- Loja 2 tem um mix diversificado, com destaque para livros técnicos e instrumentos musicais, atendendo a um público mais nichado.
- Loja 3 concentra vendas em móveis e itens domésticos, como kit banquetas, mesa de jantar e jogo de panelas, mas com portfólio pouco diversificado.
- Loja 4 apresenta variedade com camas box, faqueiros e produtos tecnológicos, porém com volume e ticket médio menores.

Esses perfis são importantes para orientar decisões estratégicas sobre investimento e posicionamento das lojas.

## 2.5 Custo Médio de Frete

A Loja 4 tem o menor custo médio de frete, representando uma vantagem competitiva. Em seguida vêm as Lojas 3, 2 e 1, sendo esta última a com maior custo médio. Embora a variação seja pequena (R$ 3,41 entre maior e menor), pode influenciar consumidores sensíveis ao preço final.

## 2.6 Resumo do Desempenho Geral

<img width="757" height="642" alt="image" src="https://github.com/user-attachments/assets/135bf14d-3f0f-412d-bb02-046af76762b7" />

O gráfico radar avalia as quatro lojas em quatro critérios: Faturamento, Avaliação Média, Vendas Totais e Frete (inverso).

- Loja 1 tem o maior faturamento e vendas, mas avaliações baixas e frete caro.
- Loja 2 apresenta desempenho equilibrado em todos os critérios.
- Loja 3 é a mais bem avaliada, com faturamento e vendas moderados, e frete razoável.
- Loja 4 tem o frete mais barato, mas baixo desempenho nos demais aspectos.

O gráfico mostra que é importante considerar múltiplos critérios para decisões estratégicas, pois cada loja tem pontos fortes e fracos.

## 2.7 Mapa de Calor dos Pedidos

<img width="628" height="493" alt="image" src="https://github.com/user-attachments/assets/27f476a8-7234-4cf6-8e28-82a598b32de6" />

A análise das coordenadas geográficas revelou grandes concentrações de vendas em São Paulo (Sudeste) e Fortaleza (Nordeste). Capitais como Brasília, Rio e Belo Horizonte apresentam calor moderado. Esses dados indicam que campanhas de marketing e logística devem focar no Sudeste e Nordeste, enquanto ações de expansão podem mirar regiões com menor demanda, como Centro-Oeste e Norte.

## 🚀 Tecnologias & Ferramentas que impulsionam este projeto

- 🐍 **Python** – Linguagem principal para análise de dados
- 🧮 **Pandas** – Manipulação e análise de dados
- 📊 **Matplotlib** & **Seaborn** – Visualização de dados
- 🧑‍💻 **Jupyter Notebook / Google Colab** – Ambiente de desenvolvimento e execução
- 🔢 **NumPy** – Operações matemáticas e vetoriais
- 🗃 **Git & GitHub** – Versionamento de código e colaboração
- 📝 **Markdown** – Documentação e estrutura do README  

## 💻 Instruções de Execução  
1. Clone este repositório e acesse a pasta do projeto no terminal:

    ```bash
    git clone https://github.com/viniciuseduardofarias/desafio-vendas-alura-store.git
    cd desafio-vendas-alura-store
    ```

2. Abra o notebook `Alura_StoreBr.ipynb` no **Jupyter Notebook** ou faça upload para o **Google Colab**.

3. Instale as dependências necessárias (por exemplo, usando o arquivo `requirements.txt`):

    ```bash
    pip install -r requirements.txt
    ```

    Ou instale manualmente:

    ```bash
    pip install pandas matplotlib folium seaborn
    ```

4. Execute as células sequencialmente. O notebook contém comentários explicativos e visualizações para cada etapa da análise.

5. Os gráficos serão gerados inline, e o mapa de calor aparecerá interativo (no Colab, pode ser necessário habilitar a visualização do Folium).
