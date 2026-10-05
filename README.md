# proxy residencial preço: quanto custa por GB, o que encarece a conta e como pagar menos

Quem digita "proxy residencial preço" normalmente quer um número. Dá para começar por ele: hoje é possível comprar tráfego residencial a partir de **US$ 1 por GB**, e provedores com pegada mais corporativa cobram algo entre US$ 4 e US$ 8 por GB, dependendo do volume e do tipo de pool.

O problema é que esse número, isolado, mente um pouco. Duas ofertas com o mesmo US$ 1/GB podem terminar custando valores bem diferentes no fim do mês, porque o que define o preço final não é só a etiqueta do gigabyte: é o volume mínimo de recarga, a cobrança de segmentação geográfica, a validade do tráfego e o tipo de sessão que você precisa.

## Por que o mesmo GB custa US$ 1 em um provedor e US$ 8 em outro

A diferença não é arbitrária. Provedores com pool próprio e usuários que consentem em compartilhar a conexão conseguem repassar preços mais baixos, porque não estão revendendo tráfego de terceiros com margem em cima. Redes montadas por revenda intermediária carregam o custo de duas ou três empresas até chegar ao seu cartão.

Depois entram os itens que aparecem na fatura e não no anúncio:

- **Modelo de cobrança.** Assinatura mensal com franquia de GB é o formato mais comum, e ele obriga você a comprar um pacote fechado todo mês — mesmo nos meses em que o projeto roda devagar.
- **Validade do tráfego.** Em boa parte do mercado, o GB não usado no ciclo simplesmente desaparece.
- **Alvo e segmentação.** Cidade, CEP, operadora e ASN costumam ser cobrados à parte, ou como multiplicador sobre o preço por GB.
- **Taxa de sucesso real.** Um provedor barato que acerta 70% das requisições pode sair mais caro do que um que acerta 99%, porque você paga pelo tráfego gasto nas tentativas que falharam.

É nesse ponto que a DataImpulse ficou conhecida. Ela trabalha com pagamento conforme o uso e tráfego que não expira, com preço de entrada de **US$ 1/GB em residencial**. A avaliação do TechRadar sobre o serviço aponta exatamente esse ponto como o principal argumento da empresa: US$ 1 por GB de baseline em proxy residencial, com dados que não vencem, e uma rede declarada de mais de 90 milhões de IPs residenciais de origem ética em 195 países.

## Os planos disponíveis e o preço de cada um

A estrutura de preços aqui não é dividida em "Basic / Pro / Enterprise" com recursos travados. São quatro tipos de proxy, cobrados por tráfego, com desconto por volume nos blocos maiores.

| Tipo de proxy | Tráfego | Preço | Por GB | Observações | Comprar |
| --- | --- | --- | --- | --- | --- |
| Residencial — entrada | 5 GB | US$ 5 | US$ 1 | Plano introdutório, garantia de reembolso de 7 dias em cartão | Ver o bloco de 5 GB |
| Residencial | 50 GB | US$ 50 | US$ 1 | Tráfego não expira, segmentação por país incluída | Ver o bloco de 50 GB |
| Residencial | 100 GB | US$ 100 | US$ 1 | Mesmo preço unitário da entrada | Ver o bloco de 100 GB |
| Residencial — nível Advanced | 1 TB | US$ 800 | US$ 0,80 | Desconto de 20% por volume | Ver o bloco de 1 TB |
| Datacenter — entrada | 10 GB | US$ 5 | US$ 0,50 | IPs de servidor, resposta abaixo de 100 ms | Ver o plano de datacenter |
| Datacenter — volume | a partir de US$ 450 | conforme pacote | US$ 0,45 | Faixa de desconto por volume | Ver o pool de datacenter |
| Móvel — entrada | 2,5 GB | US$ 5 | US$ 2 | IPs 3G/4G/5G/LTE, pool declarado de 16 milhões de IPs | Ver o plano móvel de entrada |
| Móvel — volume | 1 TB ou mais | conforme pacote | US$ 1,60 | 20% de desconto na faixa de volume | Ver tráfego móvel em volume |
| Residencial premium — entrada | 1 GB | US$ 5 | US$ 5 | Segmentação completa sem sobretaxa, gerente de conta dedicado | Ver o premium de 1 GB |
| Residencial premium | 10 GB | US$ 50 | US$ 5 | Mesmo pool de alta velocidade | Ver o premium de 10 GB |
| Residencial premium — enterprise | 5 TB ou mais | preço personalizado | negociado | Valores personalizados a partir de US$ 20.000 | Consultar o preço personalizado |

Vale reparar numa coisa: o residencial padrão é **plano de preço único** de 5 GB até cerca de 800 GB. Só no bloco de 1 TB o valor por GB cai para US$ 0,80. Se o seu consumo mensal é de 30 GB ou 60 GB, comprar um "plano maior" não reduz o preço unitário — o que faz sentido é recarregar conforme a necessidade, já que o saldo não vence.

## Quanto rende, na prática, cada bloco de tráfego

Aqui vale fazer a conta que quase nenhuma comparação de preço mostra.

Um gigabyte é 1.024 MB de tráfego de rede, contando request e response. Uma página de e-commerce ou um resultado de busca sem renderização de JavaScript costuma ficar entre 0,5 MB e 2 MB. Ou seja, **US$ 1 compra aproximadamente 500 a 2.000 requisições**, dependendo do peso da página, de imagens e de scripts.

Traduzindo os blocos:

- US$ 5 (5 GB): algo entre 2.500 e 10.000 páginas, na faixa estimada acima.
- US$ 50 (50 GB): algo entre 25.000 e 100.000 páginas.
- US$ 800 (1 TB, US$ 0,80/GB): o custo por mil requisições fica ainda mais baixo, e o desconto real é de 20% em relação ao preço padrão.

Esses números são estimativas baseadas no preço publicado e no tamanho típico de página — tráfego de vídeo, downloads e páginas muito pesadas mudam tudo. O ponto importante é outro: em um modelo por assinatura, você paga o pacote mesmo se usar 10% dele. Em um modelo pré-pago sem expiração, o GB comprado hoje continua disponível no mês em que o projeto voltar a rodar.

Se o seu consumo é baixo e irregular, essa diferença pesa mais do que o preço unitário. Para testar, 👉 criar uma conta e começar pelo bloco de 5 GB custa o preço de um café, e o saldo não se perde.

## O que encarece a conta além do US$ por GB

Três itens merecem atenção antes de fechar a compra, porque são eles que transformam "US$ 1/GB" em algo diferente na fatura.

**Mínimo de recarga de US$ 50.** O plano introdutório sai por US$ 5, mas a documentação oficial do provedor informa que **a recarga mínima para os planos é de US$ 50**. Ou seja, o US$ 5 é a porta de entrada para teste; depois dele, as recargas seguem esse piso. Revisões independentes do serviço também destacam esse ponto como a principal ressalva para quem quer gastar pouco por vez.

**Segmentação avançada cobrada em dobro.** No proxy residencial padrão, o país está incluído no preço. Filtros mais finos — estado, cidade, CEP e seleção específica de ASN — são cobrados a **2× a tarifa normal por GB** segundo as comparações publicadas sobre o serviço. Excluir um ASN continua gratuito. Na linha residencial premium, essa segmentação inteira vem sem sobretaxa, e no datacenter ela aparece como incluída. Se o seu projeto exige CEP ou cidade específica em volume, o cálculo do preço precisa usar US$ 2/GB efetivos no residencial padrão — e aí pode fazer mais sentido olhar o premium a US$ 5/GB ou o datacenter a US$ 0,50/GB. Na dúvida, confirme o tratamento atual da cobrança com o suporte, porque é o tipo de detalhe que muda.

**Taxas de pagamento.** A política do provedor é de que as taxas do meio de pagamento ficam com o cliente, incluindo comissões bancárias e taxas de rede de blockchain. Não é uma sobretaxa escondida, mas entra na conta de quem paga com cripto.

## Pagar em reais: PIX, cartão e o que mais funciona no Brasil

Quem compra do Brasil não precisa de cartão internacional obrigatoriamente. A lista de métodos de pagamento inclui **PIX com cobrança em reais**, além de cartão de crédito e débito, Apple Pay, Google Pay, Alipay, UPI e criptomoedas. O limite por transação via PIX é o equivalente a **US$ 2.500**, segundo a documentação oficial.

O PayPal existe, mas não está disponível por padrão: precisa de solicitação manual ao suporte e passa por verificação, com o provedor se reservando o direito de negar o acesso. Quem depende exclusivamente de PayPal deve resolver isso antes de contar com o método.

Existe também recarga automática, que recompra tráfego quando o saldo cai abaixo de um limite definido por você — útil para quem roda rotinas diárias e não quer ver o script parar no meio.

## Teste grátis, reembolso e os limites reais do serviço

Vale ser direto sobre o que não existe: **não há teste gratuito sem pagamento**. Todo acesso começa com uma compra mínima de US$ 5. O que existe é uma garantia de reembolso de **7 dias** nos planos introdutórios pagos com cartão, válida desde que menos de 80% do tráfego tenha sido consumido. Compras em criptomoeda no plano introdutório não são reembolsáveis.

Depois vêm os limites que não aparecem em nenhuma tabela de preço, mas decidem se o serviço serve para você:

- Não há **proxy ISP estático**. Isso descarta o uso para gerenciar várias contas com IP fixo — nesse caso, o próprio provedor recomenda procurar outro tipo de fornecedor.
- Não há **API de scraping gerenciada** nem navegador integrado. Você recebe a conexão proxy e escreve o seu código. O TechRadar lista exatamente esses dois pontos como as desvantagens do serviço, junto com a ausência de templates prontos por alvo.
- Não é indicado para **sites bancários e governamentais**.

Em troca, o que a mesma avaliação destaca como pontos fortes: preço competitivo, pool de origem ética, suporte a HTTP(S) e SOCKS5, suporte humano 24/7, sessões rotativas e sticky, e tráfego que não expira. A empresa divulga taxa de sucesso de 99,51% e nota 4,8/5 no G2; é número do fornecedor, então trate como referência de marketing, não como laudo independente.

Na prática técnica, o gateway fica em `gw.dataimpulse.com`, porta 823 para HTTP/HTTPS e 824 para SOCKS5, com sessões sticky presas a portas da faixa 10000 a 20000 e intervalos de rotação configuráveis entre 1 e 120 minutos. O padrão de sessão é de 30 minutos quando você não define intervalo.

## Quando o GB mais barato não é a decisão certa

Preço por GB é o critério principal em três situações: projetos de scraping em volume grande, monitoramento de preços em escala e coleta de dados que tolera alguma variação de IP. Nesses casos, o residencial padrão a US$ 1/GB resolve, e o bloco de 1 TB a US$ 0,80/GB derruba o custo unitário mais ainda.

Fora dessas situações, mude a linha de produto em vez do volume:

- Alvos com anti-bot agressivo, redes sociais e fluxos dentro de aplicativos costumam se beneficiar de **IP móvel**, a US$ 2/GB. É mais caro por gigabyte, mas o número de tentativas desperdiçadas tende a cair.
- Operações críticas que precisam de estabilidade, latência menor e risco reduzido de bloqueio fazem mais sentido no **residencial premium**, a US$ 5/GB, com segmentação completa inclusa e gerente de conta dedicado.
- Coleta de diretórios públicos e páginas simples não precisa de IP residencial. **Datacenter a US$ 0,50/GB** custa metade do preço e responde mais rápido; o IP residencial só é necessário quando o alvo realmente bloqueia tráfego de servidor.

Em qualquer um dos casos, o cálculo honesto é custo por requisição bem-sucedida, não preço de tabela. 👉 conferir os preços atuais de cada tipo de proxy na página oficial é o jeito mais rápido de comparar as quatro linhas lado a lado.

## Perguntas frequentes sobre preço de proxy residencial

**O preço é mensal ou por uso?**
Por uso. Você compra um bloco de tráfego e paga apenas pelos bytes que passarem pela rede, a partir de US$ 1/GB no residencial. Não há mensalidade no residencial padrão.

**O tráfego não usado expira?**
Não. O saldo comprado permanece disponível até ser consumido, sem prazo de validade. É o argumento central do modelo pré-pago do provedor, e aparece tanto no material oficial quanto nas avaliações de terceiros.

**Tem teste grátis?**
Não há versão gratuita sem pagamento. O teste é pago, com o plano introdutório de US$ 5, e inclui garantia de reembolso de 7 dias para pagamentos em cartão, respeitado o limite de 80% de consumo.

**Posso comprar só US$ 10 ou US$ 20 depois do primeiro teste?**
A recarga mínima informada na documentação oficial é de US$ 50.

**Segmentação por cidade ou CEP aumenta o preço?**
No residencial padrão, sim: filtros de estado, cidade, CEP e seleção específica de ASN são cobrados a 2× a tarifa por GB. Na linha premium e no datacenter, a segmentação aparece como incluída, sem sobretaxa.

**Existe desconto por volume?**
Sim. No residencial, o bloco de 1 TB sai a US$ 0,80/GB, 20% abaixo do preço padrão. Móvel segue a mesma lógica, caindo para US$ 1,60/GB, e o datacenter tem faixa própria a partir de US$ 0,45/GB.

## O resumo que interessa na hora de decidir

Proxy residencial a US$ 1/GB com tráfego que não expira coloca a DataImpulse abaixo de praticamente todo o mercado de pool próprio — a faixa de US$ 3,50 a US$ 8/GB é onde vive a maior parte da concorrência. O que define se essa etiqueta se traduz em economia real no seu caso é simples: se você usa pouco e de forma irregular, o modelo pré-pago sem expiração ganha fácil. Se você precisa de cidade e CEP em volume no pool padrão, a conta dobra e vale reavaliar entre residencial padrão, datacenter e premium. E se você depende de IP ISP fixo ou de uma API de scraping pronta, nenhum preço por GB resolve — o serviço não é esse.

Para quem quer começar pelo degrau mais baixo e medir o custo por requisição antes de escalar, 👉 abrir a conta e usar o bloco de teste de 5 GB é o caminho com menor risco financeiro. Se o volume já é previsível, 👉 vale olhar direto o bloco de 1 TB a US$ 0,80/GB e comparar com o que você paga hoje por gigabyte.
