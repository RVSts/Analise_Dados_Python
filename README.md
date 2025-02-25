# Visão Geral
---

Seja bem-vindo! Esta é uma análise sobre o mercado de trabalho de dados, o foco é na função de Analista de Dados (Data Analyst), meu interesse princial. Neste projeto estarão presentes análises sobre os cargos mais comuns e as localizações com maior número de ofertas de emprego. Além disso, avalia as habilidades mais mencionadas nas descrições de vagas. No escopo da análise também se abrange as condições de trabalho (remota, exigência de diploma e benefícios oferecidos). Outro aspecto importante é a análise temporal das postagens de vagas, permitindo identificar padrões sazonais no mercado de trabalho. 


A fonte dos dados pertence a [Luke Barousse](https://huggingface.co/datasets/lukebarousse/data_jobs), ele possui informações sobre cargos, localizações, empresas, tipos de trabalho, requisitos de habilidades, datas de postagem, benefícios oferecidos e disponibilidade de salários. O projeto está direcionado para esse tipo de dados principalmente por apresentar uma estrutura que possibilita diversas aplicações dos conhecimentos sobre Pandas, Matplotlib e Seaborn.

## Perguntas Feitas
---

A seguir estão as perguntas que pretendo responder em meu projeto sobre o cargo de Analista de Dados:

1. Quais as localizações com maior oferta de emprego? Quais apresentam maior oferta por tipo de trabalho (presencial, remoto ou híbrido)?
2. Quais as habilidades técnicas mais requisitadas? E qual o comportamento dessas requisições ao longo do tempo?
3. Quais as condições de trabalho apresentadas?
4. Em quais meses há mais postagens de vagas? Existe algum padrão sazonal?
5. Quais as médias salarias? (Por cargo, habilidades técnicas, etc.)

## Ferramentas Utilizadas
---

As seguintes ferramentas foram necessárias para se obter uma maior compreensão dos dados, fazer suas visualizações e posteriores análises:

* **Python**: 
  * **Biblioteca Abstract Syntax Trees (ast)**:
  * **Biblioteca Pandas**:
  * **Biblioteca Datasets**:
  * **Biblioteca Matplotlib**:
  * **Biblioteca Seaborn**:
  * **Biblioteca adjustText**:
* **Jupyter Notebook**:
* **Git & GitHub**:


## Preparação & Limpeza dos Dados
---


### Importar e limpar os dados
---
```python

```

### Conhecendo os dados
---

### Filtrando vagas da França
---

# Análise dos Dados
---


## 1. Quais as localizações com maior oferta de emprego? Quais apresentam maior oferta por tipo de trabalho (presencial, remoto ou híbrido)?
---


### **Distribuição Geográfica**  
- **Paris** concentra **3.786 vagas** (27% do total nacional).  
- Polos secundários: Lyon (**522**), Nanterre (**319**), Toulouse (**273**).  
- Apenas **2.161 vagas remotas** ("Anywhere"), indicando **cultura predominantemente presencial**.  

### **Empresas Líderes**  
- **Top 3**:  
  1. **OpenClassrooms** (204 vagas)  
  2. **Carrefour** (190)  
  3. **Société Générale** (103)  
- Setor financeiro em destaque: **BNP Paribas** (77), **Michael Page** (88).  

### **Requisitos das Vagas**  
- **Graduação**: 75% não exigem diploma (**10.348 vagas**).  
- **Trabalho Remoto**: 96,1% não oferecem (**apenas 537 remotas**).  
- **Seguro de Vida**: Nenhuma vaga menciona o benefício.  

### **Habilidades Implícitas**  
- **Ferramentas de BI**: Power BI (Air France), Tableau (PRO ADVICE).  
- **Linguagens**: SQL (Kepler Cheuvreux), Python (Engie).  

---

### Conclusões Estratégicas  
1. **Foco em Competências Práticas**: 75% das vagas dispensam diploma, valorizando **SQL, Python e Power BI**.  
2. **Cultura Presencial**: Baixa oferta de remoto (<4%) exige adaptação de candidatos internacionais.  
3. **Oportunidades Emergentes**: Lyon e Toulouse são polos em crescimento para além de Paris.  

**Nota Final**: O mercado francês para **Data Analysts** é robusto, porém exige **adaptação cultural**. Destaque para a necessidade de habilidades técnicas e projetos práticos para compensar a ausência de requisitos formais. 🚀  



### 2. Quais as habilidades técnicas mais requisitadas? E qual o comportamento dessas requisições ao longo do tempo?
---


### 3. Quais as condições de trabalho apresentadas?
---



### 4. Em quais meses há mais postagens de vagas? Existe algum padrão sazonal?
---



### 5. Quais as médias salarias? (Por cargo, habilidades técnicas, etc.)
---