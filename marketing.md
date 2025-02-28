# Funcionalidades relacionadas à Marketing

## Introdução

Como uma empresa comprometida com a excelência e o crescimento contínuo, reconhecemos a importância de manter uma abordagem sólida e atualizada em relação às **boas práticas de SEO** e à inovação no cenário do comércio eletrônico. Acreditamos que a visibilidade nos mecanismos de busca é **essencial para o sucesso online**, e nossas ferramentas são desenvolvidas com isso em mente. Neste documento, você encontrará **informações precisas e práticas** sobre como aproveitar
ao máximo as funcionalidades de SEO da nossa plataforma, garantindo que sua loja online esteja sempre otimizada para ser encontrada por seu público-alvo. Além disso, estamos comprometidos em permanecer à frente das tendências em Marketing Digital. Sabemos que o Digital está em constante evolução, e nossa equipe trabalha para incorporar as inovações mais recentes em nossa plataforma. Isso significa que você terá acesso às ferramentas e estratégias mais atualizadas para promover e expandir seus negócios online.

## Meta-Tags

Em todos os registros que criam novas páginas dentro da Loja – como em categorias,subcategorias, produtos e páginas de conteúdo, por exemplo - é possível, de maneira gerenciável, definir dados importantes relacionados ao SEO que são as meta-tags de: **Metakeyword, metadescription e Nome alternativo de imagem** (atributo ‘alt’).Esses dados são atribuídos em campos presentes no formulário de cadastro de todosesses registros.

Assim que confirmados estes dados no registro, eles serão refletidos no HTML da página, permitindo com que os mecanismos de busca façam sua leitura.

## Gerenciador de Scripts Personalizados

Em **Database > Configurações Gerais**, no painel administrativo, há uma funcionalidade denominada **“Google Analytics”**. Apesar de ter este nome, essa funcionalidade não está restrita somente a esta ferramenta do google essencial para captura de dados. Nesta área, é possível, de maneira autônoma, incluir scripts na sua loja que vão desde chatbots como Jivochat, Tawk.to e Zendesk até a inclusão de Scripts que exibem popups em sua loja por meio de jquery. Qualquer ferramenta online que requer a incorporação de um script pode usar essa funcionalidade como um método de implementação. 

Portanto, esta ferramenta é uma grande aliada na adequação dos requisitos para o Marketing Digital da Loja. Além dos exemplos já citados, essa funcionalidade também permite com que os scripts de tag manager e de qualquer outro código que precise ser inserido no HTML de qualquer página seja implementado. Vale dizer também que com essa funcionalidade, atributos e metatags que, por algum motivo não estejam presentes em determinadas páginas, sejam incluídos via script customizado. 

O formulário consiste na definição do tipo de Script (se é personalizado, de Selo do EBIT, de Pixel do Facebook ou de Comércio Eletrônico do Google Analytics), em quais páginas o código vai vigorar e em qual área do HTML o código vai ser inserido.

## XML de Produtos

A plataforma também conta com documentos dinâmicos de XML de produtos, que são atualizados automaticamente com todos os produtos ativos na sua loja. Esses documentos estão alinhados e adequados para importação no Google e Facebook, para impulsionamento em feed de produtos destas mesmas ferramentas.

Esses XMLs estão disponíveis nas seguintes URLs:

- `http://dominiodaloja.com.br/nomedaloja/rss/facebook.asp`
- `http://dominiodaloja.com.br/nomedaloja/rss/google.asp`

## Sitemap

Um **sitemap**, também conhecido como mapa do site, é uma estrutura organizada e hierárquica de links que lista todas as páginas e recursos de um site da web. Ele é criado especificamente para **facilitar a navegação pelos motores de busca**, como o **Google**, e também pelos visitantes humanos. O Sitemap da Loja também é um documento desenvolvido com a lógica de ser dinâmico, ou seja, é atualizado com cada alteração feita na loja, de modo à manter os registros sempre em dia.

O link para o sitemap em XML fica disponível em:
- `http://dominiodaloja.com.br/nomedaloja/rss/sitemap`

## Robots.TXT

O arquivo **"robots.txt"** é um arquivo de texto utilizado para comunicar instruções aos motores de busca e outros robôs da web sobre quais partes de um site eles têm permissão para rastrear e indexar. Em outras palavras, o "robots.txt" atua como um conjunto de diretrizes que informam aos robôs da web quais páginas ou diretórios de um site podem ser acessados e quais devem ser excluídos.

Não há arquivo robots.txt na raiz da plataforma, salvo exceção da pasta /admin, cujo qual restringe e bloqueia a indexação dos arquivos contidos no painel administrativo. 

Além disso, por padrão, os buscadores já possuem permissão para indexação de forma nativa, o que independe da existência do arquivo robots. 

Também há a questão de que a plataforma permite multilojas atuando em um mesmo ambiente, o que pode apresentar problemas de regras contidas no arquivo robots.txt, caso este esteja presente e informando um sitemap. Por exemplo, caso haja um endereçamento de um sitemap para um projeto que haja mais de uma loja. Além disso, também pode variar o endereço da URL.

Porém, é possível que o gestor de marketing envie o arquivo robots.txt com os parâmetros desejados para que a Universo Ink realize a hospedagem do arquivo na raiz da loja. As instruções para criação tal como deve ser de ciências das agências que o solicita, pode ser acessada em: `https://rockcontent.com/br/blog/robots-txt/`ou em `https://developers.google.com/search/docs/crawling-indexing/robots/create-robots-txt?hl=pt-br`

## URLs Amigáveis

A plataforma da Universo Ink possui uma estrutura de registros bem definida que naturalmente depende das URLs para mapear seus acessos. As URLs já foram otimizadas de modo que fiquem amigáveis e adequadas para os mecanismos de busca. Todas as URLs de Produtos, categorias e subcategorias possuem um slug compreensivo que apresenta o nome do registro com validações que respeitam as demandas do Google como a isenção de caracteres especiais, a separação de palavras por hífen e a conversão de caracteres maiúsculos para minúsculos.

## Google Analytics 4

Na área de Google Analytics, no campo de Tipo de Script, há a opção de ‘Google Analytics 4’. Ao criar um script com esta tratativa, a loja trabalhará com todos os eventos e conversões referentes ao GA4, conforme a documentação do Google. Os eventos considerados serão

`(https://developers.google.com/analytics/devguides/collection/ga4/reference/events?hl=pt-br&client_type=gtag)`:

- view_item_list: Registre esse evento quando uma lista de itens de uma determinada categoria for exibida para o usuário.
- search: Registre este evento para indicar quando o usuário realizou a pesquisa. Você pode usar esse evento para identificar o conteúdo que os usuários estão pesquisando no seu site ou app. Por exemplo, você pode enviar esse evento quando um usuário acessar uma página de resultados de pesquisa depois de realizar uma pesquisa.
- `view_item`: Esse evento indica que parte do conteúdo foi exibido ao usuário. Use o evento para descobrir os itens mais procurados que foram visualizados.
- `add_to_cart`: Esse evento indica que um item foi adicionado a um carrinho de compras.
- `view_cart`: Esse evento indica que um usuário viu o carrinho.
- `remove_from_cart`: Esse evento indica que um item foi removido do carrinho.
- `begin_checkout`: Esse evento indica que um usuário iniciou o processo de finalização da compra.
- `add_shipping_info`: Esse evento significa que um usuário enviou as informações de frete em um processo de finalização de compra de e-commerce.
- `add_payment_info`: Esse evento significa que um usuário enviou as informações de pagamento em um processo de finalização de compra de e-commerce.
- `purchase`: Esse evento indica quando um ou mais itens são comprados por um usuário.

## Sua Opinião é Fundamental!

Se você tiver alguma dúvida, feedback ou solicitação relacionada a SEO ou qualquer outro aspecto de nossa plataforma, não hesite em entrar em contato com nossa equipe de suporte dedicada. Esperamos ansiosamente ouvir suas sugestões e continuar aprimorando nossos serviços para atender às suas expectativas. Juntos, podemos alcançar grandes realizações no mundo online.