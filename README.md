# Meu Kit de IA

Desafio de Projeto da [DIO](https://dio.me): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

O kit foi criado pelo Expert Bruno Lima com os prompts, templates, checklists e skills usados nas Aulas. Ele não é uma apostila: abra a pasta que resolve o seu problema, copie o modelo, adapte e use.

Este repositório foi personalizado para minha rotina de estudos em Engenharia de Software, programação e cibersegurança.

**Copie → adapte → teste → confira → melhore**

## Como Fazer o Desafio

1. Clique em **Use this template**, depois em **Create a new repository**. Dê um nome simples, deixe **Public** e confirme.
2. Siga os passos abaixo com uma tarefa real.
3. Preencha a seção [Minha Entrega](#minha-entrega) e entregue o link da sua cópia na DIO.

## Os Passos

1. **Escolha uma tarefa real.** Comece por uma atividade que se repete ou que seja útil à sua rotina.
2. **Pegue um modelo.** Abra a pasta do kit que combina com a tarefa.
3. **Adapte.** Troque o que está entre colchetes pelo seu contexto, objetivo, dados, limites e formato.
4. **Teste.** A primeira resposta é um ponto de partida. Ajuste até funcionar para sua realidade.
5. **Delegue.** Entregue a tarefa à IA. Peça o plano antes de ela começar, acompanhe e valide o resultado.
6. **Confira.** Provável não é o mesmo que verdadeiro. Valide fatos, números, datas, fontes e contexto com o checklist.

## O Que Tem no Kit

| Pasta | Para que serve |
|---|---|
| [01-prompts](01-prompts) | Pedidos prontos para adaptar: escrita, comunicação, pesquisa, comparação e preparação de reuniões |
| [02-templates](02-templates) | Estruturas para preencher: bom pedido, pesquisa e decisão, e delegação |
| [03-checklists](03-checklists) | Revisão de respostas, de textos e de tarefas delegadas |
| [04-skills](04-skills) | Como criar uma skill e a Skill Preparador de Reuniões usada nas Aulas |
| [05-delegacao-e-automacao](05-delegacao-e-automacao) | Gatilhos de automação, supervisão e checkpoints |

## Os Frameworks das Aulas

- **Bom pedido:** contexto + instrução + objetivo + formato.
- **Pesquisa e decisão:** pergunta → pesquisa → critérios → comparação → você. Peça fontes quando precisar de informação externa.
- **Segurança:** pare → confira → use. Valide fatos, números, datas, fontes e contexto.
- **Atalhos reutilizáveis:** criar → testar → ajustar → salvar. Separe instruções fixas das informações que mudam a cada uso.
- **Delegação:** objetivo + contexto + recursos + limites + sucesso.
- **Supervisão:** definir → delegar → acompanhar → validar. Em tarefas maiores, confira o plano, acompanhe os checkpoints e valide o resultado.

> A IA pode ajudar você a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo sua.

---

## Minha Entrega

### Minha Tarefa Real

Escolhi realizar uma análise estática preliminar de segurança do CineMostra, meu primeiro site, desenvolvido como atividade prática. O projeto utiliza HTML e CSS, além de JavaScript inserido diretamente no final do arquivo `index.html`.

A tarefa está relacionada à minha formação em Engenharia de Software e ao meu interesse em cibersegurança. O objetivo foi revisar o código-fonte, identificar riscos e oportunidades de melhoria, explicar os achados e sugerir recomendações, mantendo a decisão final sob minha responsabilidade.

**Escopo autorizado:** somente análise documental/estática dos arquivos fornecidos. O projeto original não foi modificado. Não foram realizados testes ativos, ataques, acessos externos ou alterações no site.

### Meus Atalhos

Adaptei dois atalhos para minha rotina:

1. **Professor de Programação:** ajuda a aprender conceitos, entender códigos, resolver exercícios e identificar erros. As instruções fixas orientam a IA a ensinar passo a passo; o assunto, a linguagem e o nível do exercício variam conforme a necessidade.
2. **Pesquisador de Tecnologia:** orienta pesquisas sobre tecnologias, ferramentas, frameworks e cibersegurança. As instruções fixas exigem fontes confiáveis, distinção entre fatos e sugestões e transparência sobre informações não confirmadas; o tema pesquisado muda a cada uso.

#### Atalho 1 — Professor de Programação

```text
Me ajude como se fosse meu professor de programação.

Quero estudar: [ASSUNTO OU LINGUAGEM].

Sou estudante do primeiro ano de Engenharia de Software, atualmente no segundo semestre. Ainda estou aprendendo a base, então explique de um jeito simples, como em uma aula da faculdade, sem usar termos difíceis sem explicar.

Quando eu pedir um assunto, siga esta ordem:
1. Explique o que é e para que serve.
2. Mostre como funciona, por partes.
3. Dê um exemplo simples e explique o código linha por linha.
4. Mostre um exemplo um pouco mais próximo de uma atividade prática.
5. Comente os erros que um iniciante costuma cometer.
6. Passe três exercícios, começando pelo mais fácil.

Não mostre a solução dos exercícios logo de início. Espere eu tentar responder. Depois, corrija o que eu fiz, mostre onde errei e explique como posso melhorar.

Se eu não entender, tente explicar de outro jeito e use outro exemplo. Não faça tudo por mim: quero aprender a pensar e conseguir resolver sozinho.
```

#### Atalho 2 — Pesquisador de Tecnologia

```text
Me ajude a pesquisar sobre tecnologia para meus estudos de Engenharia de Software.

Assunto que quero pesquisar: [TECNOLOGIA OU ASSUNTO].

Sou estudante do primeiro ano de Engenharia de Software, no segundo semestre. Quero entender o assunto e saber onde ele é usado, sem receber uma explicação avançada demais.

Organize a pesquisa assim:
1. O que é esse assunto e para que serve?
2. Como funciona, explicado de forma simples?
3. Onde ele é usado na prática?
4. Quais são as vantagens e desvantagens?
5. Como se relaciona com Engenharia de Software e, quando fizer sentido, com cibersegurança?
6. Dê exemplos de uso.
7. Indique materiais ou documentação para eu continuar estudando.

Se precisar de informações atuais, pesquise na internet e dê preferência a documentação oficial, páginas dos projetos e fontes conhecidas. Coloque os links das fontes e a data da consulta. Explique quais informações vieram das fontes e quais partes são sua análise ou recomendação.

Não invente dados. Se não encontrar uma informação ou não conseguir confirmar se ela está atualizada, avise. Explique siglas e termos técnicos na primeira vez que aparecerem.

No final, faça um pequeno resumo do que eu preciso lembrar e sugira por onde posso continuar estudando.
```

### Atalho de Delegação — Análise de Segurança

```text
# Delegação — Análise preliminar de segurança de um projeto

## Objetivo
Realizar uma análise preliminar de segurança de um projeto de software próprio ou de estudo, identificando possíveis vulnerabilidades, falhas de configuração e oportunidades de melhoria.

## Contexto
Sou estudante de Engenharia de Software e estou desenvolvendo conhecimentos em programação e cibersegurança. Quero usar a IA como apoio para aprender a reconhecer problemas de segurança em um projeto de estudo.

## Recursos
- Código-fonte de um projeto próprio ou desenvolvido para estudos.
- Documentação técnica disponível.
- IA para apoiar a revisão.
- OWASP Top 10 como referência de boas práticas, quando aplicável.

## Instruções
1. Solicite os arquivos necessários antes de começar.
2. Identifique a estrutura e as tecnologias utilizadas.
3. Analise o material fornecido e aponte possíveis falhas.
4. Classifique os achados por nível de risco, justificando a classificação.
5. Explique o impacto potencial e recomende formas de correção.
6. Diferencie vulnerabilidades confirmadas por evidência, hipóteses que exigem validação e recomendações preventivas.
7. Apresente um relatório organizado, indicando limitações da análise.

## Limites
- Não testar sistemas de terceiros.
- Não acessar ambientes externos.
- Não coletar informações pessoais, credenciais ou segredos.
- Não modificar arquivos do projeto.
- Não instalar ferramentas nem executar comandos sem autorização.
- Não realizar ações destrutivas.
- Não apresentar suspeitas como vulnerabilidades confirmadas.

## Critérios de sucesso
A tarefa será considerada concluída quando houver uma análise documentada, achados explicados e classificados, recomendações justificadas e limitações registradas. O relatório deverá ser revisado por mim antes de qualquer uso.

## Aprovações
Peça minha autorização antes de qualquer teste ativo, alteração de arquivos, instalação de ferramentas ou ação fora da análise documental. A decisão final sobre as correções será minha.
```

### O Plano da IA

A IA propôs e executou o seguinte plano, respeitando o escopo autorizado:

1. Listar os arquivos recebidos e identificar as tecnologias utilizadas.
2. Ler o HTML, os estilos CSS e o JavaScript existente.
3. Revisar o formulário, as validações, os dados pessoais e as dependências externas.
4. Separar problemas observados, riscos condicionais e boas práticas.
5. Registrar recomendações e limitações, sem alterar o projeto.

**Execução:** foram inspecionados `index.html`, `css/base.css`, `css/layout.css`, `css/componentes.css` e `README.md`. O JavaScript está embutido no HTML; não há arquivos JavaScript separados no ZIP.

### O Resultado — Relatório da Análise Estática

A análise encontrou os seguintes pontos:

| ID | Achado | Classificação | Evidência e interpretação |
|---|---|---|---|
| A01 | Mensagem de reserva pode induzir ao erro | Problema funcional / confiabilidade | O evento `submit` chama `event.preventDefault()` e mostra `alert('Reserva enviada')`. O código analisado não implementa envio a um servidor nem confirmação real da reserva. |
| A02 | Validação somente no navegador | Recomendação preventiva | O formulário usa `required`, `minlength`, `pattern`, `min` e `max`. Essas verificações ajudam a experiência do usuário, mas não substituem validação no servidor caso um backend seja criado futuramente. |
| A03 | Nome completo presente na página | Privacidade / exposição de informação | O nome do autor aparece no título HTML, no rodapé e no README do projeto. É informação visível a quem recebe ou acessa os arquivos. Avaliar se a publicação do nome completo é necessária. |
| A04 | Dependência de recursos externos | Dependência de terceiros / privacidade | As imagens usam `picsum.photos` e o mapa é incorporado do Google Maps por um `iframe`. Isso cria dependência de disponibilidade e pode envolver requisições a esses serviços quando a página é aberta. |
| A05 | Proteção adequada no link que abre nova aba | Boa prática observada | O link externo utiliza `target="_blank"` junto com `rel="noopener noreferrer"`, reduzindo riscos associados à página aberta em nova aba. |

#### Recomendações

- **A01:** em uma versão futura, exibir uma mensagem que deixe claro que se trata de uma demonstração, ou implementar um backend que processe e confirme a reserva. Nenhuma alteração foi feita nesta atividade.
- **A02:** se o projeto ganhar backend, validar os dados novamente no servidor e tratar entradas de forma segura.
- **A03:** revisar quais informações pessoais precisam constar na versão publicada.
- **A04:** avaliar a necessidade dos serviços externos, sua política de privacidade e alternativas locais quando apropriado.
- **A05:** manter a proteção `noopener noreferrer` nos links externos que abrem novas abas.

#### Limitações da análise

- Foi feita somente leitura do código-fonte fornecido.
- Não houve execução do site em navegador, varredura automatizada, teste de rede ou teste de penetração.
- Não há backend no material analisado; portanto, não foi possível avaliar autenticação, autorização, banco de dados, processamento de reservas ou validação no servidor.
- Não foi confirmada exploração de vulnerabilidade. Os achados são problemas observados no código ou recomendações preventivas, conforme indicado na tabela.
- Não foi possível avaliar cabeçalhos HTTP, configuração de hospedagem, HTTPS ou políticas de segurança do servidor a partir dos arquivos estáticos.

**Conclusão:** o material permitiu identificar pontos de melhoria de confiabilidade, privacidade e preparação para uma futura integração com backend. Não há evidência suficiente nesta análise para afirmar que o site possui uma vulnerabilidade explorável.

### Como Foi para Você

Os atalhos foram pensados para apoiar meus estudos de programação e minhas pesquisas sobre tecnologia. Na tarefa delegada, a IA ajudou a organizar a revisão do código e a separar problemas observados de recomendações preventivas. A análise foi limitada ao conteúdo do ZIP, e o projeto original foi preservado.

Durante essa atividade, percebi que a IA pode ajudar bastante nos meus estudos, principalmente quando uso as respostas como apoio para aprender e não apenas para copiar. No teste do Professor de Programação, pratiquei listas em Python, o uso de `append()`, laços `for`, `range()`, `len()` e a condição para identificar números pares. Os exercícios e as correções me ajudaram a entender melhor como cada parte do código funciona.

Com o Pesquisador de Tecnologia, pesquisei o OWASP Top 10:2025 e conheci melhor alguns riscos relacionados à segurança de aplicações. Também entendi a importância de consultar as fontes indicadas e conferir se as informações estão atualizadas.

Na análise do CineMostra, que foi meu primeiro site feito em uma atividade prática, consegui observar o formulário, o JavaScript e o uso de recursos externos. Aprendi que nem todo ponto de melhoria é uma vulnerabilidade confirmada: é importante explicar o que foi observado no código e deixar claras as limitações da análise.

Como estou no segundo semestre do primeiro ano de Engenharia de Software, ainda estou aprendendo os fundamentos. Essa atividade me ajudou a praticar conteúdos que estou estudando e a perceber que posso usar a IA para tirar dúvidas, pesquisar e revisar meus trabalhos, mas preciso conferir as respostas e entender o resultado antes de utilizá-lo. Em próximos projetos, pretendo prestar mais atenção à segurança desde o começo do desenvolvimento.

---

## Evidências da Execução

As capturas de tela das cinco etapas do desafio foram reunidas em um arquivo compactado para facilitar a consulta.

**[Baixar evidências — prints_kit_ia_etapas_1_a_5.zip](evidencias_kit_ia_etapas_1_a_5.zip)**

O arquivo contém:
1. **Professor de Programação:** exercícios de Python com listas, `append()`, `for`, `range()` e números pares.
2. **Pesquisador de Tecnologia:** pesquisa sobre OWASP Top 10:2025.
3. **Envio e autorização do CineMostra:** apresentação do projeto e definição dos limites da análise.
4. **Plano da IA:** planejamento da análise estática.
5. **Resultado da análise:** achados, recomendações, limitações e conclusão.

Para visualizar as imagens individualmente, baixe o ZIP e extraia seu conteúdo.

---

## Cuidados com a publicação

Não publique e-mails, nomes de clientes, dados de empresas, senhas, tokens, chaves de API, credenciais ou informações pessoais. Utilize apenas projetos próprios ou autorizados e remova segredos do código antes de compartilhá-los.
