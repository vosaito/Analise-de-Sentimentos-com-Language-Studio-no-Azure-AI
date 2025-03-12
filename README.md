
# Análise de Sentimentos com Language Studio no Azure AI

## Objetivo:
Criar um resumo das aulas e desafio de projeto destacando os insights e possibilidade, com o intuito de compilar e fixar as informações aprendidas.
## Conteúdo das aulas (arquivos .txt em anexo):
- Fundamento da IA;
- Princípios IA Responsável;
- IA Generativa - Modelo de liguagem grandes;
- Copiloto - engenharia de prompts;
- Fundamentos de aprendizado de máquina (machine learning);
- Processamento de linguagem natural.

## Desafio de projeto
### Análise de texto
Ao analisar o texto, detectamos diversos pontos que possibilita extrair diversas informações sobre o que está escrito e/ou quem escrevou, por exemplo:
- o sentimento/humor da pessoa;
- de qual região ela é (idioma);
- onde ela está ou esteve (entidade-localidade). 
*Parece trivial, mas ao trabalharmos milhares de dados isso pode ser muito efetivo.*

### Serviço de bot do Azure
Plataforma baseada em nuvem para desenvolvimento e gerenciamento de bots
Integração com AI Language e outros serviços
Conectividade atravès de vários canais

### Estudio de fala
Programa que transforma textos em fala e vice e versa.
Com esse serviço, é possível:
- promover inclusão social ao transformar textos em áudios e áudios em textos de forma rápida.
- gerar legendas em tempo real de videos, filmes, transmissões ao vivo
- transcrever reunião para gerar atas

### Language Studio
Programa que faz as associações das palavras analisando os textos e falas para extrair informações de forma rápida.\
Para verificamos o funcionando desse programa, foi feito um teste para análise de texto para detectar o humor/sentimento e mineração de opiniões.\
Primeiro, é preciso criar um recurso de idioma no Microsoft Azure, para podermos associar ao Language Studio.\
Após criação do recurso, podemos associar o recurso criado para utilizar o serviço de analise e texto/fala no Language Studio. Para isso, devemos ir na seção de classificação de texto, e selecionar o análise de sentimento e mineração de opiniões.\
Na interface, podemos colocar o texto que ser analisado e selecionar o idioma que está esse texto.
Após a análise, o programa já te mostra o sentimento do texto avaliando em positivo, neutro e negativo em porcentagens. Podemos ver também como ele fez a avaliação mostrando as palavras-chaves e frases-chaves que compuseram as notas pesando-os para positivo ou negativo.\
*Com isso, podemos utilizar para avaliar as avaliações de serviços e produtos que estamos oferecendo para podemos atuar nas melhorias e/ou investir no que está funcionando, no caso de produtos/serviços novos.*
