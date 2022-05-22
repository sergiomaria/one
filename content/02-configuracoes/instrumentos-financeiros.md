---
title: "Instrumentos Financeiros"
date: 2022-05-14T12:23:04+01:00
draft: false
url: "/configuracoes/instrumentos-financeiros"
---

Um instrumento financeiro está geralmente associado a uma empresa, tal como a EDP, Microsoft, etc., mas pode também representar um fundo ou um ETF cotado nas diferentes bolsas mundiais.

Todos os títulos têm um ISIN (International Securities Identification Number) que funciona analogamente como o n.º de contribuinte, permitindo identificar de forma única uma empresa/fundo/ETF. 

Apesar do ISIN parecer uma ótima forma de identificar um título, este não permite diferenciar a negociação em diferentes mercados bolsistas. Por exemplo: a EDP tem o ISIN PTEDP0AM0009, podendo ser negociada na bolsa portuguesa e americana, em EUR e USD. O ISIN identifica a empresa mas é limitado se quisermos rastrear a evolução e cálculo do lucro com base na cotação. Que preço usar? 

É por esse motivo que o OneFinance recomenda a utilização de **tickers**, que permitem não só identificar de forma única o título, mas também o mercado bolsista em que é transacionado.

Assim, os títulos da EDP podem estar associados a 2 tickers:
- [**EDP.LS** - Transacionada no mercado português.](https://finance.yahoo.com/quote/EDP.LS)
- [**EDPFY** - Transacionada no mercado americano.](https://finance.yahoo.com/quote/EDPFY) 


### Que tickers usar?
Apesar de não haver uma uniformização dos tickers para os diferentes títulos pelas grandes instituições financeiras (Reuters, Morningstar, Bloomberg, etc.), o OneFinance rege-se pelos tickers da [Yahoo Finance!](https://finance.yahoo.com/)

A enorme diversidade e facilidade de pesquisa fazem com que a Yahoo seja uma referência na matéria.

Quando pesquisar um título na [Yahoo Finance!](https://finance.yahoo.com), confirme o mercado em que o título é transacionado. O prefixo do ticker identifica claramente o mercado. Por exemplo, se terminar com .LS, pertence ao mercado português, se terminar com .MD ao mercado espanhol e quando não tem sufixo .XX é porque é transacionado no mercado americano.

Se ainda não sabe os tickers dos seus títulos, [Procure aqui](https://finance.yahoo.com)

### Qual a necessidade de registar o instrumento financeiro?
Esta etapa é muito importante porque os dados que inserir determinarão que anexos do IRS serão preenchidos atendendo à natureza do movimento. Por exemplo, se tiver mais valias de um título com o país da sede em Portugal, será registado no anexo G, caso contrário será no anexo J.   

Futuramente, esperamos poder pré-preencher corretamente a grande maioria de informação sobre os vários títulos. Até que isso aconteça, é necessário que o investidor saiba a implicação de cada ação e que esteja comprometido em ter os dados corretos.


### Adicionar instrumentos financeiros
Para aceder à página de instrumentos financeiros, aceda ao *menu lateral esquerdo → Definições → Info s/ Instrumentos Financeiros* ou clique [aqui](https://onefinance.pt/my/instrument-info)

À semelhança da vista de corretoras, existe um botão **Adicionar** no topo da página que lhe permite adicionar um determinado instrumento financeiro.

Após clicar no botão adicionar será direcionado para este ecrã, onde poderá inserir o ticker. Se não souber qual é, siga o link para o Yahoo Finance. O uso do ticker da Yahoo não é obrigatório, mas se não o usar, não terá aacesso a informações relevantes, nem poderá acompanhar a evolução do mercado no portal OneFinance.pt.

{{<figure src="/02-configuracoes/images/pesquisar-instrumento.png" title="Pesquisar instrumento Financeiro" class="center">}}

Se inserir um título reconhecido e previamente carregado no portal, o nome já estará preenchido e o país da sede terá uma grande probabilidade de estar correto. **Deverá sempre confirmar pois é usado um algoritmo que tem em conta o país em que o título está a ser negociado, o que, como vimos não indica com absoluta certeza qual a sede do instrumento financeiro.**

Se colocar, por exemplo, o ticker EDP.LS, a informação seguinte já estará mais completa, não necessitando de preencher o nome e o país da fonte.
{{<figure src="/02-configuracoes/images/adicionar-instrumento.png" title="Adicionar Instrumento Financeiro" class="center">}}

O NIF é também relevante, especialmente em instrumentos financeiros nacionais. Se o colocar, este será preenchido automaticamente no anexo G no quadro referente às mais-valias.

Ao voltar à página anterior, poderá visualizar todos os instrumentos adicionados e que se encontram validados, processo que lhe permitirá registar transações e dividendos posteriormente.

{{<figure src="/02-configuracoes/images/instrumentos-validados.png" title="Instrumentos Validados" class="center">}}

Para cada instrumento, tem agora a opção de editar/eliminar, clicando em cada um dos ícones da primeira coluna da tabela.

{{% notice warning %}}
Só poderá eliminar um instrumento se não houver quaisquer operações registadas com esse mesmo instrumento.
{{% /notice %}}

### Links Úteis
- [Página de instrumentos financeiros](https://onefinance.pt/my/instrument-info)
- [Yahoo Finance!](https://finance.yahoo.com)

