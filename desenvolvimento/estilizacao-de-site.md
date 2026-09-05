# Estilização de site

## Objetivo

Criar ou aprimorar a identidade visual e a experiência de um site existente sem prejudicar seu conteúdo, suas funcionalidades ou sua acessibilidade.

## Quando usar

Use este prompt para modernizar um site, aplicar uma identidade visual, melhorar a hierarquia da interface, corrigir inconsistências de estilo ou tornar páginas existentes mais responsivas e agradáveis.

## Variáveis

- `[TIPO DE SITE]`: site institucional, landing page, loja, portfólio, sistema ou outro
- `[OBJETIVO DO SITE]`: principal resultado esperado da página
- `[PÚBLICO-ALVO]`: perfil das pessoas que usarão o site
- `[CÓDIGO OU ARQUIVOS]`: código atual ou indicação dos arquivos que podem ser alterados
- `[IDENTIDADE VISUAL]`: cores, fontes, logotipo, estilo e referências
- `[DIREÇÃO ESTÉTICA]`: sensações e características visuais desejadas
- `[TECNOLOGIA]`: HTML/CSS, React, Vue, Tailwind ou outra tecnologia
- `[RESTRIÇÕES]`: elementos, bibliotecas, conteúdo ou comportamentos que devem ser preservados
- `[REFERÊNCIAS]`: sites, imagens ou produtos usados apenas como inspiração

## Prompt

```text
Atue como designer de interfaces sênior e desenvolvedor front-end especialista em design systems, responsividade e acessibilidade.

Sua tarefa é estilizar ou aprimorar o visual de um [TIPO DE SITE].

Contexto:
- Objetivo do site: [OBJETIVO DO SITE]
- Público-alvo: [PÚBLICO-ALVO]
- Código ou arquivos disponíveis: [CÓDIGO OU ARQUIVOS]
- Identidade visual: [IDENTIDADE VISUAL]
- Direção estética desejada: [DIREÇÃO ESTÉTICA]
- Tecnologia utilizada: [TECNOLOGIA]
- Restrições e elementos que devem ser preservados: [RESTRIÇÕES]
- Referências visuais: [REFERÊNCIAS]

Antes de editar:
1. analise a estrutura, o conteúdo, os componentes e os estilos atuais;
2. identifique problemas de hierarquia visual, consistência, legibilidade, responsividade e acessibilidade;
3. preserve funcionalidades, rotas, integrações, dados e textos, salvo quando eu autorizar alterações;
4. se faltar uma informação indispensável, faça no máximo cinco perguntas objetivas;
5. se puder avançar, registre brevemente as suposições adotadas.

Defina uma direção visual coerente e específica. Evite uma aparência genérica de template. Use as referências como inspiração, sem copiá-las. A estilização deve reforçar o objetivo do site e facilitar a ação principal do usuário.

Crie ou refine um sistema visual contendo:
- paleta com cores de fundo, superfície, texto, borda, destaque, sucesso, aviso e erro;
- tipografia com famílias, pesos, tamanhos e alturas de linha;
- escala consistente de espaçamento;
- grid, larguras máximas, alinhamentos e pontos de quebra;
- raios de borda, sombras, ícones e tratamento de imagens;
- estilos para títulos, parágrafos, links, listas e conteúdos longos;
- componentes como cabeçalho, navegação, botões, campos, cartões, tabelas, modais e rodapé, quando existirem;
- estados padrão, hover, foco, ativo, selecionado, desabilitado, carregamento, vazio, sucesso e erro;
- animações discretas que respeitem a preferência por movimento reduzido.

Requisitos obrigatórios:
- abordagem mobile-first e bom funcionamento em telas pequenas, médias e grandes;
- contraste adequado e foco de teclado claramente visível;
- HTML semântico e ordem de navegação lógica;
- alvos de toque confortáveis e formulários com rótulos e mensagens claras;
- ausência de rolagem horizontal acidental, textos cortados e sobreposição de elementos;
- preferência por tokens ou variáveis reutilizáveis em vez de valores espalhados;
- reutilização dos padrões e componentes já existentes no projeto;
- dependências novas somente quando houver benefício claro;
- desempenho preservado, evitando imagens, fontes ou efeitos excessivamente pesados;
- nenhuma alteração desnecessária na lógica do site.

Entregue:
1. diagnóstico curto dos principais problemas visuais encontrados;
2. direção visual adotada e justificativa;
3. resumo dos tokens e padrões do sistema visual;
4. código completo das alterações, indicando claramente cada arquivo;
5. explicação breve das decisões importantes;
6. checklist de validação em celular, tablet e desktop;
7. lista do que foi preservado e de qualquer limitação restante.

Critérios de qualidade:
- o resultado deve parecer intencional, coeso e adequado ao público;
- a ação principal deve estar visualmente evidente;
- componentes semelhantes devem ter comportamento e aparência consistentes;
- o conteúdo deve continuar legível em diferentes tamanhos de tela;
- a interface deve funcionar por teclado e comunicar seus estados sem depender apenas de cor;
- o projeto deve continuar executável após as alterações.

Não entregue apenas sugestões conceituais: implemente as mudanças. Não invente logotipos, depoimentos, selos, prêmios ou resultados comerciais. Quando um recurso real estiver ausente, use um substituto claramente identificado.
```

## Exemplo de uso

Estilize a landing page de uma consultoria financeira voltada a pequenas empresas. O objetivo é incentivar o agendamento de uma conversa. Preserve todos os textos, links e o formulário atual. Use HTML e CSS existentes, sem adicionar frameworks. A direção estética deve ser sóbria, contemporânea e acolhedora, com azul-marinho, verde discreto e bastante espaço em branco. Melhore especialmente o cabeçalho, a hierarquia das seções, os cartões de serviços, o formulário e a experiência em celulares.

## Resultado esperado

A resposta deve incluir um diagnóstico objetivo e alterações de código prontas para aplicação. O site final precisa apresentar uma identidade visual consistente, boa leitura, ação principal evidente, comportamento responsivo e estados acessíveis, mantendo intactas as funcionalidades que não foram autorizadas para mudança.
