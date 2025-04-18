# 🚦 Projeto Fundamentos de Ciência de Dados  
## Análise dos Acidentes de Trânsito de Belo Horizonte (2016–2022)

### 👤 Autor
**Marco Aurélio Gonçalves de Souza**

---

### 📑 Descrição

Este projeto tem como objetivo realizar uma análise exploratória e estatística dos acidentes de trânsito ocorridos em Belo Horizonte entre os anos de 2016 e 2022. Utilizando ferramentas da ciência de dados, foram aplicadas técnicas de visualização, agrupamento, regressão e inferência estatística para entender padrões temporais, espaciais e de severidade nos acidentes.

---

### 🛠️ Tecnologias e Bibliotecas

- Python
- [BabyPandas](https://pypi.org/project/babypandas/)
- pandas
- NumPy
- Matplotlib

---

### 📂 Estrutura dos Dados

Os dados utilizados estão organizados em arquivos `.csv`, contendo informações como:

- Data e hora do boletim
- Tipo e descrição do acidente
- Região e bairro
- Pavimento e condições do tempo
- Coordenadas geográficas (latitude e longitude)
- Indicador de fatalidade

---

### 🔍 Etapas do Projeto

#### 1. **Carregamento e Limpeza de Dados**
- Importação e concatenação de arquivos CSV.
- Conversão da data e criação de um índice temporal.
- Remoção de colunas irrelevantes para análise.

#### 2. **Análise Temporal**
- Gráficos de linha do número de acidentes por mês e por ano.
- Comparações por período (ex: pandemia de 2020–2021).

#### 3. **Análise por Tipo de Acidente**
- Gráficos de barras horizontais com os tipos mais comuns por ano.
- Separação de acidentes fatais e não fatais.

#### 4. **Análise Regional**
- Distribuição de acidentes por região e fatalidade.
- Visualização em gráficos de barras.

#### 5. **Visualização Espacial**
- Geração de mapas de calor com `hexbin`, simulando o mapa de BH por tipo de acidente usando latitude e longitude.

#### 6. **Inferência Estatística - Bootstrap**
- Cálculo de intervalos de confiança para o número médio de acidentes por mês.
- Uso da técnica de reamostragem com 10.000 iterações.

#### 7. **Regressão Linear**
- Comparação entre anos (2019, 2020, 2021 vs. 2022).
- Modelagem de regressão linear simples por bairro.
- Cálculo de resíduos e análise da acurácia das previsões.

---

### 📊 Exemplos de Visualizações

- 📈 Gráfico de acidentes por mês e ano
- 🗺️ Mapa de calor de acidentes em BH
- 📉 Regressões lineares para previsão de acidentes
- 📌 Análise de resíduos (diferença entre previsto e real)

---

### 📌 Conclusões

- O número de acidentes varia significativamente entre os anos, com queda acentuada em 2020, refletindo o impacto da pandemia.
- Algumas regiões são consistentemente mais perigosas.
- A modelagem preditiva simples mostra tendências, mas com limitações notáveis.

---

### ✅ Como Executar

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

2. Instale as dependências:
```bash
pip install babypandas pandas numpy matplotlib
```

3. Coloque os arquivos `.csv` de acidentes na pasta do projeto.

4. Execute o notebook ou script `.py` principal.

---

### 📎 Licença

Este projeto é apenas para fins educacionais e acadêmicos. Sem fins comerciais.
