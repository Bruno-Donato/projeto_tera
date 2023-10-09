# Detecção de discuros de ódio em redes sociais - Trabalho de conclusão do curso de Data Science & Machine Learning (TERA)

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
<br>

# Processo
A seguiu as seguintes etapas:<br>
1.Extração dos dados do Twiter e Portal de Dados abertos TSE<br>
2.Análise descritiva<br>
3.Pré-processamento dos dados<br>
4.Seleção do modelo pré-treinado Transformers (HuggingFace)<br>
5.Métricas do modelo<br>
6.Classificação manual e ajuste fino do modelo<br>

# Resultados
- Há uma dificuldade em definir e identificação objetiva de discursos de ódio pelos avaliadores
- Foi possível entregar um modelo com métricas aceitáveis para detecção de discurso de ódio
- No corpus dos dados coletados e analisados foi identificado altas taxas de discurso de ódio
- Não foram encontradas diferenças de incidência de discursos entre candidatos com diferentes características
- Formas mais veladas de discursos, como sarcasmos, ironias e piadas são especialmente difíceis de serem detectados (lacuna semântica)

# Conclusão
Com as ferramentas propostas e utilizadas foi possível elaborar uma maneira de detectar discursos de ódio e analisar o contexto dos discursos analisados. Porém mais esforços 
precisam ser desprendidos para aprimorar todo o processo.
