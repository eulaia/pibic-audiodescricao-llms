# Geração Automática de Audiodescrição com Inteligência Artificial

Este repositório reúne os códigos e experimentos desenvolvidos durante um projeto de Iniciação Científica voltado à geração automática de audiodescrição para imagens utilizando modelos multimodais de Inteligência Artificial.

A pesquisa analisou como diferentes modelos interpretam conteúdos visuais e investigou suas possibilidades e limitações na geração de descrições voltadas à acessibilidade de pessoas com deficiência visual.

## Sobre o projeto

A audiodescrição é um recurso de acessibilidade que transforma informações visuais relevantes em informações verbais.

Com o avanço dos modelos multimodais, tornou-se possível utilizar sistemas de Inteligência Artificial capazes de receber imagens e gerar descrições em linguagem natural.

Durante o projeto, foram realizados experimentos com diferentes modelos multimodais. As descrições geradas foram analisadas considerando aspectos como fidelidade ao conteúdo visual, clareza, nível de detalhamento, presença de informações inexistentes e adequação ao contexto da audiodescrição.

## Objetivo

Investigar o uso de modelos multimodais de Inteligência Artificial para geração automática de audiodescrição de imagens, comparando os resultados obtidos por diferentes modelos e identificando suas principais características e limitações.

## Modelos avaliados

Durante a pesquisa, foram realizados experimentos com os seguintes modelos:

* GPT-4o
* LLaVA 1.5 7B
* Qwen2-VL 2B
* Qwen2.5-VL 3B
* Qwen2.5-VL 7B

## Tecnologias utilizadas

* Python
* Google Colab
* Google Drive
* Git e GitHub
* APIs de modelos de Inteligência Artificial
* Hugging Face

As bibliotecas utilizadas variaram de acordo com o modelo testado.

## Processamento de imagens

Nos experimentos, as imagens foram enviadas aos modelos juntamente com prompts desenvolvidos para orientar a geração da audiodescrição.

Entre os elementos considerados nas descrições estavam:

* foco principal;
* personagens e objetos;
* ações;
* perspectiva e plano;
* enquadramento;
* plano de fundo;
* iluminação;
* contexto visual.

Os prompts foram ajustados ao longo da pesquisa a partir dos resultados observados nos testes.

## Execução

Os experimentos foram desenvolvidos em Python e executados principalmente no Google Colab.

### Pré-requisitos

Para reproduzir os experimentos, podem ser necessários:

* Python 3;
* pip;
* acesso ao Google Colab;
* acesso à API ou ao provedor correspondente ao modelo utilizado.

As dependências específicas estão indicadas nos próprios notebooks de cada experimento.

Exemplo:

```bash
pip install openai pillow
```

## Chaves de API

Alguns dos modelos utilizados dependem de serviços externos e exigem credenciais de acesso.

As chaves de API não estão incluídas neste repositório por questões de segurança. Para reproduzir esses experimentos, é necessário utilizar credenciais próprias.

Exemplo:

```python
OPENAI_API_KEY = ""
```

Chaves e tokens privados não devem ser enviados ao GitHub.

## Resultados

Os resultados obtidos permitiram comparar o comportamento dos diferentes modelos na geração das descrições.

Entre os aspectos considerados na análise estavam:

* fidelidade ao conteúdo original;
* clareza da descrição;
* nível de detalhamento;
* identificação de elementos relevantes;
* informações omitidas;
* informações incorretas;
* ocorrência de alucinações.

Os códigos e notebooks disponibilizados neste repositório correspondem aos experimentos realizados durante a pesquisa.

## Considerações finais

A pesquisa permitiu analisar o comportamento de diferentes modelos multimodais na geração automática de audiodescrição de imagens, observando diferenças na forma como cada modelo identifica, organiza e descreve as informações visuais.

Os experimentos contribuíram para compreender o potencial dessas tecnologias no contexto da acessibilidade e para identificar aspectos importantes para o desenvolvimento de soluções de apoio à produção de audiodescrição.

Os códigos e notebooks disponibilizados neste repositório registram os experimentos realizados e podem servir como base para estudos e trabalhos futuros relacionados à aplicação de Inteligência Artificial multimodal à acessibilidade digital.

## Autoria

**Maria Euláia dos Santos Araujo**
Graduanda em Ciência da Computação
Projeto de Iniciação Científica

**Orientador:** Adonias Caetano de Oliveira
**Instituição:** IFCE - Instituto Federal de Educação, Ciência e Tecnologia do Ceará
