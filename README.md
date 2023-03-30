# Sobre LGPD com chatGPT

Experiência de geração de slides com gpt-4 e [reveal.js](https://github.com/hakimel/reveal.js).

## Motivação

Durante uma conversa entre amigos, surgiu a ideia de uma IA que pudesse gerar apresentações a partir de um roteiro. Eu sugeri, então que o chatGPT seria capaz de fazer isso utilizando instruções de qual framework usar para montar os slides. 

Supus que tal iniciativa pudesse ajudar na concepção inicial de uma apresentação corporativa formal, ou uma aula sobre determinado tema com teor mais textual. Se o teste for útil, tal fluxo pode ser automatizado por meio da API da openAI especificamente para essa finalidade.

## Processo

Minha hipótese era de que o GPT seria capaz de calcular corretamente tanto o domínio linguístico do tema a ser discutido na apresentação quanto o código a ser utilizado para os slides. Para que isso pudesse ser feito, usei o GPT-4 pela interface [Chatbotui](https://www.chatbotui.com) com o seguinte prompt: 

> faça 10 slides em reveal.js explicando a LGPD

O resultado foram várias **<section>** com o conteúdo de cada slide pronto para ser inserido no index.html padrão do reveal.js

Para encerrar a apresentação em bom tom, dei mais um comando:

> inclua um slide de agradecimento com um gif engraçado do tenor.com

Ainda que tenha gerado todo o código corretamente, a ID do gif sugerido foi uma string aleatória não existente. A única ação que eu precisei fazer foi acessar o Tenor e buscar a URL correta do gif.

## Conclusão

A geração dos slides me custou apenas R$0.72 centavos. Julguei barato demais para uma ferramenta que foi capaz de gerar em segundos um código útil, bem-estruturado e com informações relevantes sobre um tema jurídico. 

Alternativas de código-aberto ao chatGPT serão importantes para democratização dessa tecnologia e garantir autonomia às instituições e profissionais que desejem incorporar tais ferramentas aos seus processos produtivos e criativos.

--- 
<div align="center">
  Reveal.js is MIT licensed | Copyright © 2011-2023 Hakim El Hattab, https://hakim.se
</div>
