# Detecção de discuros de ódio em redes sociais - Trabalho de conclusão do curso de Data Science & Machine Learning (TERA)
<div align="center">
  <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="Gastos Saúde" width="200" />
</div>

# Visão Geral
Projeto de conclusão do curso de pós-graduação em ciência de dados & machine learning da escola Tera (ensino superior) com objetivo de coletar dados da rede social Twitter 
(atual X) para elaboração de modelo de machine learning para detecção de discursos ofensivos e de ódio, assim como analisar os dados coletados para extrair insights.

# Problema e Solução
Discuros de ódio nas redes sociais tem demostrado preocupante aumento, afetando não somente as interações entre usuários de redes sociais mas também produzindo desdobramentos 
na vida real, como aumento de crimes relacionados a esses discursos nocivos. Essa realidade segundo dados afeta em maior número pessoas de grupos historicamente desfavorecidos 
e marginalizados.

As bigtechs responsáveis por essas redes, e consequentemente seus conteúdos, são alvo de críticas nesse campo pois apesar dos esforços para detectar e evitar esses conteúdos, 
assim como tomar as medidas legais necessárias em relação aos usuários que contribuem para esse cenário, ainda demonstram certo nível de falha e/ou negligencia para mitigar o 
problema.  

Nesse contexto a PL 2.630 de 2020 (PL das Fake News) foi elaborada para criar mecanismos que auxiliem nesse enfrentamento, responsabilizando as redes e dando maior conhecimento aos usuários de 
como o conteúdo das redes são processados e avaliados.

Assim para ajudar a solucionar esse problema foi proposto um mecanismo de detecção e análise de conteúdo da rede social Twitter (atual X) para dar ao usuário maior controle de 
suas redes e possibilidade de ter maior autonomia e compreender o contexto geral em que ele está inserido.

Através desse processo foi proposto investigação de redes sociais de personalidades da política para tentar responder as seguintes perguntas:<br>
<br>
1.É possível elaborar um modelo de machine learning para detectar de maneira confiável discursos de ódio?<br>
2.O discurso de ódio ocorre em taxas diferentes dependendo de genero, etnia, orientação sexual, orientação política?<br>

# Processo
O projeto seguiu as seguintes etapas:<br>
__1.Extração dos dados:__<br>
  - Extração dos dados do Twiter e Portal de Dados abertos TSE (não incluida devido mudança de política da plataforma twitter)<br>
  <br>
  
[__2.Modelos Transformers (HuggingFace):__<br>](https://github.com/Bruno-Donato/projeto_tera/blob/main/teste_huggingface.ipynb)
  - Selecionando modelos<br>
  - Métricas do modelo<br>
  - Classificaçaõ manual<br>
  - Ajuste fino<br>
  - Métricas pós ajuste<br>
  <br>
  
[__3.Análise de contexto:__<br>](https://github.com/Bruno-Donato/projeto_tera/blob/main/analise_contexto.ipynb)
  - Pré-processamento dos dados<br>
  - Análise descritiva<br>
  - Extraindo e visualizando contexto com Word2Vec<br>
  - Bag of words e N-grams<br>
  <br>

[__BONUS__<br>](https://github.com/Bruno-Donato/projeto_tera/blob/main/curso_hugging_face.ipynb)
  - Curso huggingface sobre transformers

# Resultados
- Há uma dificuldade em definir e identificação objetiva de discursos de ódio pelos avaliadores
- Foi possível entregar um modelo com métricas aceitáveis para detecção de discurso de ódio
- No corpus dos dados coletados e analisados foi identificado altas taxas de discurso de ódio
- Não foram encontradas diferenças de incidência de discursos entre candidatos com diferentes características
- Formas mais veladas de discursos, como sarcasmos, ironias e piadas são especialmente difíceis de serem detectados (lacuna semântica)

# Conclusão
Com as ferramentas propostas e utilizadas foi possível elaborar uma maneira de detectar discursos de ódio e analisar o contexto dos discursos analisados. Porém mais esforços precisam ser desprendidos para aprimorar todo o processo.

A apresentação do trabalho pode ser encontrada [aqui](https://github.com/Bruno-Donato/projeto_tera/blob/main/data/TERA%20-%20Apresenta%C3%A7%C3%A3o.pdf).
