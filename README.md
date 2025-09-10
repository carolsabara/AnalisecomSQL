
# 📊 Análise de Dados de Chicago com SQL no Google Collab

## 🎯 Objetivo
Integrar três conjuntos de dados públicos da cidade de Chicago — **registros de crimes**, **informações de escolas** e **dados do censo** — em um banco de dados e executar consultas SQL para responder perguntas analíticas sobre segurança pública, desempenho escolar e indicadores socioeconômicos.

---

## 📂 Conjuntos de Dados Utilizados (Esses conjuntos de dados foram modificados e fornecidos pelo curso para a realização dessa análise e não foi permitido fazer alterações, apenas permitido manipulação):
1. **ChicagoCrimeData.csv**  
   - Registros de crimes reportados na cidade de Chicago.

2. **ChicagoPublicSchools.csv**  
   - Informações sobre escolas públicas de Chicago.

3. **ChicagoCensusData.csv**  
   - Indicadores socioeconômicos por área comunitária.

---

## 🛠️ Tecnologias e Ferramentas:
- **Python** (Pandas, SQLite3)
- **Google Colab**
- **ipython-sql** para executar SQL diretamente no notebook
- **PrettyTable** para formatação de resultados
- **SQLite** como banco de dados local

---

## 🔍 As consultas são capazes de responder as seguintes informações:
 - Consultar total de crimes registrados
 - Listar áreas com baixa renda per capita 
 - Identificar crimes envolvendo crianças 
 - Identificar sequestros de crianças 
 - Listar tipos de crimes em escolas
 - Calcular média de segurança por tipo de escola
 - Identificar áreas com maior pobreza 
 - Identificar área com maior criminalidade 
 - Determinar área com maior índice de dificuldades 
 - Determinar área com maior número de crimes 

---

## 📊 Insights: Análise de Crimes, Escolas e Censo de Chicago

**Maior incidência criminal:** Área comunitária 25 (Austin) lidera em número de ocorrências.  
**Vulnerabilidade socioeconômica:** Regiões como Englewood e Fuller Park apresentam renda per capita abaixo de US$ 11 mil e altos índices de pobreza.  
**Crimes envolvendo crianças:** Casos de crime envolvendo crianças e sequestro infantil identificados, concentrados em áreas específicas.  
**Ambiente escolar:** Crimes mais comuns em escolas são agressão física, furto e dano criminal. Escolas de ensino médio têm menor pontuação média de segurança que as de ensino fundamental.  
**Índice de dificuldades:** Englewood apresenta o maior índice, reforçando a correlação entre vulnerabilidade social e criminalidade.  

Concluise-que há relação clara entre fatores socioeconômicos, segurança escolar e incidência criminal. Áreas mais vulneráveis concentram maior número de crimes e demandam ações integradas de segurança e desenvolvimento social.

