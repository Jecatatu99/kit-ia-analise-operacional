# Kit de IA para Análise Operacional

Projeto desenvolvido como parte de um desafio da DIO para criação de um kit de inteligência artificial aplicado a uma tarefa real do dia a dia.

O objetivo deste projeto é demonstrar como a IA pode auxiliar na organização de registros, análise de indicadores e preparação de um resumo executivo, mantendo a validação e a decisão final sob responsabilidade humana.

Todos os dados utilizados são fictícios e foram criados exclusivamente para esta atividade acadêmica.

## Minha Entrega

### Minha Tarefa Real

Escolhi preparar um resumo semanal de ocorrências no serviço de TV a partir de dados fictícios de monitoramento.

Essa atividade representa uma tarefa que pode se repetir durante a semana e exige organização dos registros, conferência dos indicadores, identificação de padrões e preparação de uma comunicação objetiva.

A tarefa vale a pena porque a IA pode reduzir o tempo gasto na organização inicial dos dados, nos cálculos e na elaboração do resumo. Mesmo com o apoio da IA, a conferência final permanece sob minha responsabilidade.

Antes de utilizar o resultado, devo verificar os totais, as durações, as classificações e a separação entre fatos encontrados nos dados, interpretações que precisam de validação e sugestões produzidas pela IA.

Para proteger dados corporativos, todos os registros utilizados neste projeto são fictícios. A base não inclui nomes de clientes, e-mails, endereços IP, credenciais, identificadores internos ou informações operacionais reais.

## Meus Atalhos

Criei dois atalhos reutilizáveis.

O primeiro atalho analisa os registros de monitoramento e apresenta os indicadores. O segundo transforma uma análise já validada em um resumo executivo.

As regras, os limites de segurança e o formato das respostas ficam fixos. O período, o foco da análise, o público e os registros mudam a cada utilização.

### Atalho 1: análise de ocorrências

Você atuará como assistente de análise de dados de monitoramento de um serviço fictício de TV.

#### Objetivo

Analisar os registros fornecidos, consolidar os indicadores e identificar padrões que possam ajudar na preparação de um resumo semanal.

#### Contexto

Os dados utilizados nesta atividade são fictícios e foram criados exclusivamente para um projeto acadêmico. Os registros não representam clientes, sistemas, incidentes ou informações reais de nenhuma empresa.

#### Dados variáveis de cada análise

- Período analisado: informar o período;
- Prioridade da análise: informar o foco da semana;
- Registros: inserir os dados fictícios ou anonimizados.

#### Instruções

1. Verifique se os registros possuem data, horário, categoria, severidade, duração e situação final.
2. Informe quais campos estão ausentes antes de iniciar a análise.
3. Calcule:
   - quantidade total de ocorrências;
   - quantidade por categoria;
   - quantidade por severidade;
   - quantidade por situação final;
   - duração total;
   - duração média;
   - maior duração registrada.
4. Identifique as três ocorrências de maior duração.
5. Aponte concentrações por categoria, severidade ou período.
6. Não invente informações para completar campos ausentes.
7. Não apresente uma hipótese como fato confirmado.
8. Quando um cálculo não puder ser realizado, informe que não foi possível calcular com os dados fornecidos.
9. Separe claramente fatos encontrados, interpretações e sugestões.
10. Não envie, publique ou altere nenhum registro.

#### Formato da resposta

1. Qualidade dos dados;
2. Indicadores;
3. Principais ocorrências;
4. Fatos encontrados;
5. Interpretações que precisam de validação;
6. Sugestões da IA;
7. Pontos para conferência humana.

#### Critério de sucesso

A análise será considerada satisfatória se:

- todos os registros forem considerados;
- os cálculos puderem ser conferidos manualmente;
- nenhum dado for inventado;
- fatos, interpretações e sugestões estiverem separados;
- os pontos que exigem validação humana estiverem destacados.

Antes de realizar a análise, a IA deverá apresentar somente um plano curto com as etapas que pretende executar e aguardar minha aprovação.

#### Partes fixas e variáveis

As regras de cálculo, o formato da resposta, os limites de segurança e a necessidade de aprovação humana são partes fixas do atalho.

O período, a prioridade da semana e os registros fornecidos são informações variáveis.

### Atalho 2: resumo executivo semanal

Você atuará como assistente de comunicação operacional e preparará um resumo executivo a partir de uma análise de ocorrências fictícias de monitoramento de um serviço de TV.

#### Objetivo

Transformar os resultados de uma análise validada em um resumo semanal curto, claro e adequado para acompanhamento operacional.

#### Contexto

Este é um projeto acadêmico produzido exclusivamente com dados fictícios. O texto não deve mencionar clientes, empresas, plataformas, endereços IP, credenciais, identificadores internos ou outras informações confidenciais.

#### Informações variáveis

- Período do resumo: informar o período;
- Público do resumo: informar o público;
- Limite de tamanho: informar o número máximo de palavras;
- Resultado da análise: inserir a análise validada.

#### Instruções

1. Utilize somente as informações presentes na análise fornecida.
2. Não crie números, causas, impactos ou conclusões que não estejam registrados.
3. Destaque os principais indicadores do período.
4. Resuma as ocorrências mais relevantes com linguagem objetiva.
5. Diferencie fatos confirmados de interpretações que ainda precisam de validação.
6. Apresente as sugestões em uma seção separada.
7. Informe quando uma conclusão não puder ser comprovada.
8. Evite linguagem alarmista, acusações e afirmações absolutas.
9. Não inclua dados pessoais, confidenciais ou informações de empresas.
10. Não envie, publique ou compartilhe o resumo.

#### Formato da resposta

1. Resumo executivo;
2. Principais indicadores;
3. Ocorrências de destaque;
4. Fatos confirmados;
5. Pontos que precisam de validação;
6. Sugestões da IA;
7. Conferência antes do uso.

#### Critério de sucesso

O resumo será considerado satisfatório se:

- utilizar somente os dados fornecidos;
- respeitar o limite de tamanho;
- apresentar os indicadores de forma compreensível;
- separar fatos, interpretações e sugestões;
- não incluir informações confidenciais;
- permanecer como rascunho até receber aprovação humana.

Antes de escrever o resumo, a IA deverá apresentar somente um plano curto e aguardar minha aprovação.

#### Partes fixas e variáveis

A estrutura do resumo, a linguagem objetiva, os limites de segurança e a exigência de revisão humana são partes fixas.

O período analisado, o público, o limite de palavras e o resultado validado são informações variáveis.

## Base Fictícia Utilizada

A tarefa foi testada com a seguinte base fictícia:

| ID | Data | Hora | Categoria | Severidade | Duração | Situação final |
|---|---|---|---|---|---:|---|
| OC-001 | 03/11/2026 | 08:15 | Indisponibilidade | Alta | 42 min | Resolvida |
| OC-002 | 03/11/2026 | 10:30 | Lentidão | Média | 18 min | Resolvida |
| OC-003 | 03/11/2026 | 19:45 | Travamento | Média | 27 min | Resolvida |
| OC-004 | 04/11/2026 | 07:20 | Falha de autenticação | Alta | 35 min | Resolvida |
| OC-005 | 04/11/2026 | 14:10 | Lentidão | Baixa | 12 min | Resolvida |
| OC-006 | 05/11/2026 | 09:05 | Indisponibilidade | Crítica | 75 min | Resolvida |
| OC-007 | 05/11/2026 | 20:40 | Travamento | Alta | 33 min | Em acompanhamento |
| OC-008 | 06/11/2026 | 11:25 | Falha de autenticação | Média | 22 min | Resolvida |
| OC-009 | 06/11/2026 | 18:55 | Indisponibilidade | Alta | 48 min | Resolvida |
| OC-010 | 07/11/2026 | 08:50 | Lentidão | Baixa | 9 min | Resolvida |
| OC-011 | 07/11/2026 | 16:35 | Travamento | Média | 25 min | Resolvida |
| OC-012 | 07/11/2026 | 21:15 | Indisponibilidade | Crítica | 68 min | Em acompanhamento |

## Minha Delegação

### Objetivo

Analisar uma base com 12 ocorrências fictícias de monitoramento de um serviço de TV e produzir um resumo estruturado do período de 03/11/2026 a 07/11/2026.

A análise deve destacar os principais indicadores, as ocorrências mais longas, as categorias mais frequentes e os registros que ainda estão em acompanhamento.

### Contexto

Esta delegação faz parte de uma atividade acadêmica sobre o uso responsável da inteligência artificial.

A tarefa representa uma atividade recorrente de organização e análise de registros operacionais, mas utiliza apenas dados fictícios. Nenhum registro representa cliente, sistema, incidente ou informação real de uma empresa.

### Recursos disponíveis

- Base fictícia com 12 ocorrências;
- Campos de identificação, data, hora, categoria, severidade, duração e situação final;
- Atalho de análise criado para este projeto;
- Checklist de conferência;
- Valores calculados manualmente;
- Aprovação humana antes da execução;
- Revisão humana antes do uso do resultado.

### Etapas da tarefa

1. Apresentar somente o plano da análise.
2. Aguardar minha aprovação.
3. Validar a estrutura e a qualidade dos registros.
4. Calcular os indicadores solicitados.
5. Identificar as três ocorrências de maior duração.
6. Separar fatos comprovados, interpretações e sugestões.
7. Indicar os pontos que precisam de conferência humana.
8. Entregar o resultado como rascunho, sem publicação ou envio.

### Limites

- Não inventar campos, valores, causas ou impactos;
- Não transformar hipóteses em fatos;
- Não utilizar informações externas para completar os registros;
- Não incluir dados pessoais ou confidenciais;
- Não enviar, publicar ou compartilhar o resultado;
- Não alterar os registros fornecidos;
- Não executar ações operacionais;
- Aguardar minha aprovação antes de iniciar a análise.

### Ações que exigem minha aprovação

A execução da análise deve aguardar a aprovação do plano.

Qualquer alteração nos dados, uso externo, publicação, envio de mensagem ou transformação de uma sugestão em ação também dependerá de autorização humana.

A IA prepara o conteúdo e apresenta sugestões, mas a aprovação e a decisão final permanecem sob minha responsabilidade.

### Critério de sucesso

A tarefa será considerada concluída quando:

- os 12 registros forem considerados;
- os cálculos coincidirem com a conferência manual;
- as maiores durações forem identificadas corretamente;
- fatos, interpretações e sugestões estiverem separados;
- nenhum dado tiver sido inventado;
- o resultado permanecer como rascunho;
- os pontos que exigem validação humana estiverem destacados.

### Valores esperados para validação

- Total de ocorrências: 12;
- Duração total: 414 minutos;
- Duração média: 34,5 minutos;
- Ocorrências resolvidas: 10;
- Ocorrências em acompanhamento: 2;
- Três maiores durações: 75, 68 e 48 minutos.

## O Plano da IA

Antes de executar a tarefa, a IA apresentou o seguinte plano:

1. Validar a estrutura dos 12 registros.
2. Verificar campos vazios, identificadores duplicados e durações inválidas.
3. Calcular a quantidade total de ocorrências.
4. Calcular a duração total e a duração média.
5. Contar as ocorrências por categoria, severidade e situação final.
6. Identificar as três ocorrências de maior duração.
7. Verificar concentrações por categoria, severidade, data ou horário.
8. Separar fatos, interpretações e sugestões.
9. Indicar os pontos que precisariam de conferência humana.
10. Aguardar minha autorização antes de executar a análise.

Conferi se o plano incluía a validação da base, os cálculos necessários, a separação entre fatos e sugestões e a revisão humana.

O plano estava de acordo com o objetivo e os limites definidos. Por isso, autorizei a execução utilizando somente os dados fictícios fornecidos.

### Evidência do plano

<img width="426" height="526" alt="image" src="https://github.com/user-attachments/assets/a76e2fcd-5709-40f2-9940-eda37248be6c" />

## O Resultado

A IA analisou os 12 registros e apresentou os indicadores, as ocorrências de maior duração, os fatos encontrados, as interpretações que precisavam de validação e as sugestões de acompanhamento.

### Indicadores encontrados

| Indicador | Resultado |
|---|---:|
| Total de ocorrências | 12 |
| Duração total | 414 minutos |
| Duração média | 34,5 minutos |
| Ocorrências resolvidas | 10 |
| Em acompanhamento | 2 |
| Maior duração individual | 75 minutos |

### Distribuição por categoria

| Categoria | Quantidade | Duração total |
|---|---:|---:|
| Indisponibilidade | 4 | 233 minutos |
| Lentidão | 3 | 39 minutos |
| Travamento | 3 | 85 minutos |
| Falha de autenticação | 2 | 57 minutos |

### Distribuição por severidade

| Severidade | Quantidade | Duração total |
|---|---:|---:|
| Crítica | 2 | 143 minutos |
| Alta | 4 | 158 minutos |
| Média | 4 | 92 minutos |
| Baixa | 2 | 21 minutos |

### Maiores durações

1. OC-006: 75 minutos;
2. OC-012: 68 minutos;
3. OC-009: 48 minutos.

As três ocorrências de maior duração pertencem à categoria Indisponibilidade e somam 191 minutos.

### Fatos confirmados

- A base possui 12 ocorrências;
- A duração acumulada é de 414 minutos;
- A duração média é de 34,5 minutos;
- Indisponibilidade é a categoria mais frequente, com quatro registros;
- Indisponibilidade também possui a maior duração acumulada, com 233 minutos;
- As duas ocorrências críticas pertencem à categoria Indisponibilidade;
- Dez ocorrências foram resolvidas;
- OC-007 e OC-012 permaneceram em acompanhamento;
- A maior duração individual é de 75 minutos.

### Interpretações que precisam de validação

A categoria Indisponibilidade merece atenção por apresentar a maior quantidade de ocorrências e a maior duração acumulada.

Essa observação não confirma que os registros possuem a mesma causa. A base não apresenta informações suficientes para determinar causas, impactos, regiões ou componentes afetados.

A ocorrência OC-012 combina severidade crítica, duração de 68 minutos e situação em acompanhamento. Por isso, pode receber prioridade durante a conferência humana.

### Sugestões da IA

- Conferir primeiro as ocorrências OC-012 e OC-007;
- Analisar os registros de Indisponibilidade em conjunto;
- Verificar se as três ocorrências mais longas possuem alguma característica comum;
- Incluir campos adicionais em análises futuras, como causa e componente afetado;
- Comparar os resultados com outros períodos;
- Não atribuir causas com base somente na categoria, no horário ou na duração.

As sugestões não representam ações autorizadas. Qualquer decisão dependeria de análise e aprovação humana.

### Minha conferência

Comparei os resultados da IA com uma conferência manual da base.

Validei:

- o total de 12 ocorrências;
- a soma de 414 minutos;
- a média de 34,5 minutos;
- as 10 ocorrências resolvidas;
- as duas ocorrências em acompanhamento;
- a distribuição por categoria;
- a distribuição por severidade;
- as três maiores durações;
- a separação entre fatos, interpretações e sugestões.

Os valores calculados pela IA coincidiram com os valores obtidos na conferência manual.

Também confirmei que nenhum dado ausente foi inventado e que as sugestões foram apresentadas separadamente dos fatos.

### Evidência do resultado

<img width="505" height="354" alt="image" src="https://github.com/user-attachments/assets/f506ddd9-b9a4-427e-be0a-c98abd6aa997" />


## Como Foi para Mim

A atividade mostrou que a IA pode reduzir o tempo necessário para organizar registros, calcular indicadores e preparar um resumo inicial.

O principal aprendizado foi perceber que a qualidade do resultado depende de um pedido claro, de critérios de sucesso verificáveis, de limites bem definidos e da conferência humana.

Solicitar o plano antes da execução permitiu revisar o processo e confirmar se a IA havia compreendido a tarefa.

A separação entre fatos, interpretações e sugestões também ajudou a evitar que hipóteses fossem apresentadas como conclusões confirmadas.

A IA ajudou a organizar e interpretar os dados, mas a aprovação e a decisão de utilizar o resultado permaneceram sob minha responsabilidade.

Os atalhos poderão ser reutilizados em novas análises, alterando somente o período, o foco, o público e os registros fornecidos.

## Segurança e Privacidade

Para realizar esta atividade, foram adotados os seguintes cuidados:

- utilização exclusiva de dados fictícios;
- ausência de nomes de clientes;
- ausência de e-mails e informações pessoais;
- ausência de endereços IP;
- ausência de senhas, chaves e credenciais;
- ausência de identificadores corporativos reais;
- proibição de envio ou publicação automática;
- revisão dos resultados antes do uso;
- decisão final mantida sob responsabilidade humana.

## Conclusão

O projeto resultou na criação de dois atalhos reutilizáveis e na delegação supervisionada de uma tarefa completa para a IA.

O processo utilizado foi:

1. definir uma tarefa real;
2. adaptar os atalhos;
3. utilizar dados fictícios;
4. solicitar um plano;
5. conferir e aprovar o plano;
6. executar a análise;
7. validar os resultados;
8. registrar as evidências;
9. manter a decisão final sob responsabilidade humana.

O kit demonstra que a IA pode apoiar atividades operacionais com mais organização e rapidez, desde que existam objetivos claros, limites de atuação, critérios de validação e supervisão humana.
