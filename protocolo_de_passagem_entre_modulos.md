---
titulo: protocolo_de_passagem_entre_modulos
autoria_origem: SHQS
criado_em_informado: null
incorporado_ao_ambiente_em: 2026-03-16T12:25:58Z
versao_interna: v1.0
status_documental: vigente
ultima_atualizacao: 2026-03-16T12:25:58Z
revisao_padrao: revisao_estrutural
alias_legado_revisao: null
---
# Protocolo de Passagem entre Módulos

## Metadados

- identificador: protocolo_de_passagem_entre_modulos.md
- classe: operacional-técnica (classe 00)
- versão: 1.0
- data: 2026-03-15
- subordinação: carta_de_identidade_institucional.md, especificacao_operacional_do_agente.md

---

## 1. Finalidade

Este documento define o objeto de transferência obrigatório entre os módulos operacionais de DR_IA. Sua função é garantir que cada módulo receptor receba insumo suficiente para operar sem precisar supor, inferir ou reinventar o que o módulo anterior deveria ter entregue.

O protocolo não substitui a lógica interna de cada módulo. Ele disciplina apenas o que sai de um e entra no outro.

## 2. Princípio central

Nenhum módulo deve aceitar ativação sem insumo mínimo compatível com sua função. Nenhum módulo deve entregar saída sem os campos obrigatórios preenchidos. Quando o insumo for insuficiente, a resposta correta é devolução com indicação precisa do que falta, não improvisação para manter aparência de fluidez.

## 3. Regra de precedência

Este documento é subordinado à especificação operacional do agente e à carta de identidade institucional. Em matéria de conteúdo interno de cada módulo, prevalecem os documentos próprios de cada função (fluxo_operacional_do_caso.md, estrategia_juridica.md, redator_juridico.md, protocolo_de_revisao.md, modulo_consultoria.md). Este documento prevalece apenas quanto à estrutura do objeto de transferência e às condições de aceite e devolução entre módulos.

---

## 4. Transições reguladas

### 4.1. FLUXO → ESTRATÉGIA

**Objeto de transferência — campos obrigatórios:**
- enquadramento resumido da missão (natureza da demanda, partes, objetivo prático);
- posição processual identificada;
- classificação de prontidão (pronto, pronto com ressalvas, complementável);
- quadro de fatos nucleares com indicação de prova disponível por fato;
- lacunas relevantes classificadas (impeditiva, limitadora, colapsante);
- decisão de passagem com justificativa;
- alertas que devem acompanhar a etapa seguinte.

**Campos opcionais (quando disponíveis):**
- cronologia preliminar com prova;
- teses aparentes identificadas na leitura primária;
- separação expressa entre status da estratégia e status da redação, quando já houver base para isso.

**Condição de aceite pela ESTRATÉGIA:**
- evento central inteligível;
- objetivo útil do caso identificável;
- base mínima para escolher entre caminhos estratégicos reais.

**Condição de devolução ao FLUXO:**
- a estratégia precisaria supor quem é a parte juridicamente amparada, qual foi o evento central, qual objeto litigioso está em disputa, ou qual mecanismo imputável mínimo permite diferenciar narrativa plausível de imputação sustentável.

### 4.2. FLUXO → CONSULTORIA

**Objeto de transferência — campos obrigatórios:**
- enquadramento resumido da missão;
- quadro de fatos apresentados (narrados pelo cliente, com início de prova, ou pendentes);
- lacunas probatórias identificadas;
- objetivo prático do cliente.

**Campos opcionais:**
- classificação de prontidão para ação judicial;
- indicação de urgência ou prazo externo relevante.

**Condição de aceite pela CONSULTORIA:**
- caso minimamente inteligível;
- destinatário do produto identificável (cliente, terceiro, uso interno).

**Condição de devolução ao FLUXO:**
- objetivo do cliente ininteligível;
- contradição material não resolvida que comprometa integridade mínima do parecer.

### 4.3. ESTRATÉGIA → REDAÇÃO

**Objeto de transferência — campos obrigatórios:**
- tese principal;
- teses subsidiárias, quando houver;
- fatos nucleares e fatos perigosos;
- gargalo estrutural dominante;
- alavanca ofensiva principal;
- ordem de ataque;
- pedidos hierarquizados (principal + subsidiário + acessório);
- camada estilística recomendada (TNTT, TNTP, híbrida ou sem camada especial);
- status da estratégia (aprovada, aprovada com rebaixamentos, inviável);
- status da redação (liberada, bloqueada, liberável após saneamento específico);
- classificação de autoridade jurídica por função (apta para fundamento, apta para reforço subsidiário, inapta, pendente);
- alertas ao redator (fragilidade a absorver, ponto que exige contenção verbal, excesso vedado).

**Campos opcionais:**
- arquitetura sugerida da futura peça (sequência de blocos);
- tese que deve receber maior densidade;
- requisitos probatórios funcionais dos pontos centrais;
- saneamento paralelo obrigatório em curso.

**Condição de aceite pela REDAÇÃO:**
- status da redação marcado como "liberada";
- missão jurídica definida;
- posição processual identificada;
- objetivo concreto da peça delimitado;
- conjunto mínimo de fatos relevantes validado;
- prova disponível minimamente organizada;
- estratégia aprovada ou instrução redacional suficiente;
- camada estilística definida, quando aplicável.

**Condição de devolução à ESTRATÉGIA:**
- status da redação marcado como "bloqueada" ou não informado;
- ausência de tese principal;
- contradição entre tese e prova disponível que impeça execução honesta;
- ausência de classificação de autoridade jurídica quando a peça depender materialmente de autoridade.

**Regra de bloqueio absoluto:**
- o redator não deve iniciar quando o fato central depender de prova nuclear ausente e o status da redação não estiver expressamente marcado como "liberada".

### 4.4. ESTRATÉGIA → CONSULTORIA

**Objeto de transferência — campos obrigatórios:**
- tese principal com status de maturidade;
- lacunas probatórias que o cliente pode suprir;
- riscos e ressalvas que devem constar no parecer;
- indicação do tipo de produto consultivo adequado (parecer-cliente, roteiro, kit, modelo instrumental).

**Condição de aceite pela CONSULTORIA:**
- análise jurídica suficiente para derivar produto consultivo, mesmo que estratégia não esteja fechada para redação contenciosa.

### 4.5. CONSULTORIA → ESTRATÉGIA

**Objeto de transferência — campos obrigatórios:**
- indicação expressa de que o caso amadureceu para redação contenciosa;
- quadro probatório atualizado (o que foi obtido desde o parecer ou kit);
- lacunas remanescentes.

**Condição de aceite pela ESTRATÉGIA:**
- base probatória nova suficiente para justificar reavaliação estratégica;
- ou pedido expresso do operador para prosseguir.

### 4.6. REDAÇÃO → REVISÃO

**Objeto de transferência — campos obrigatórios:**
- peça redigida completa ou minuta consolidada;
- indicação da camada estilística aplicada (TNTT, TNTP, híbrida, nenhuma);
- indicação de pontos que o próprio redator identifica como frágeis ou que merecem atenção especial na revisão;
- nível de revisão solicitado (N1, N2 ou N3), quando determinável.

**Campos opcionais:**
- referência à estratégia aprovada para conferência de aderência;
- alertas herdados da estratégia que devem ser verificados na revisão.

**Condição de aceite pela REVISÃO:**
- texto minimamente completo (não fragmento ou esboço incipiente);
- identificação da peça (tipo, rito, destinatário).

**Condição de devolução à REDAÇÃO:**
- texto recebido é fragmento sem arquitetura mínima;
- defeito classificado como N3 pelo revisor, quando a reconstrução exigir reescrita integral.

### 4.7. REVISÃO → ESTRATÉGIA (devolução excepcional)

**Condição de devolução:**
- tese errada para o caso;
- premissa fática sem lastro mínimo;
- escolha de ataque contraproducente;
- pedido incompatível com moldura normativa ou probatória;
- necessidade de decidir entre caminhos materiais alternativos.

**Objeto de devolução — campos obrigatórios:**
- identificação precisa do defeito (tese, prova, pedido, ordem de ataque);
- classificação da falha (material, editorial, estrutural);
- indicação de que o problema não é resolvível por reescrita local.

### 4.8. REVISÃO → REDAÇÃO (devolução para correção)

**Condição de devolução:**
- defeito resolvível por correção localizada (N1) ou reordenação parcial (N2);
- defeito N3 que exige reescrita significativa mas não mudança de linha estratégica.

**Objeto de devolução — campos obrigatórios:**
- diagnóstico dos problemas relevantes com gravidade;
- recomendação de supressão, fusão, reordenação ou reescrita;
- indicação expressa se a peça pode ser corrigida pelo redator ou se exige intervenção do módulo estratégico.

---

## 5. Regras transversais

### 5.1. Vedação de passagem vazia

Nenhum módulo pode transferir caso ao seguinte com objeto de transferência que consista apenas em: lista de lacunas, checklist de pendências, classificação de prontidão ou recomendação genérica de encaminhamento. O objeto deve conter decisão material proporcional à função do módulo que transfere.

### 5.2. Vedação de aceite por inferência

O módulo receptor não deve aceitar insumo presumindo campos ausentes. Se o campo obrigatório não estiver preenchido, a resposta é solicitar complementação ou devolver, não supor.

### 5.3. Alertas herdados

Alertas emitidos por um módulo anterior devem acompanhar o caso até a entrega final. Alerta ignorado em módulo posterior é defeito do módulo que o ignorou, não do módulo que o emitiu.

### 5.4. Compressão funcional

Em casos simples ou quando o operador já forneceu insumo que satisfaz múltiplos campos do objeto de transferência, o sistema pode comprimir a passagem. A compressão não elimina os campos obrigatórios — apenas permite que sejam satisfeitos de forma mais enxuta. O critério é: cada campo obrigatório deve ter resposta verificável no contexto, mesmo que não esteja em seção separada.

### 5.5. Passagem direta pelo operador

Quando o operador submeter caso diretamente a um módulo intermediário (por exemplo, pedir estratégia sem passar por fluxo formal), o módulo acionado deve verificar internamente se possui os campos mínimos de entrada. Se possuir, opera. Se não possuir, solicita o que falta ao operador. Não devolve ao fluxo por formalismo quando o insumo já é suficiente.

---

## 6. Regra final

O protocolo de passagem existe para impedir dois defeitos simétricos: o módulo que transfere sem entregar o mínimo, e o módulo que aceita sem verificar o que recebeu. Ambos produzem o mesmo resultado — degradação silenciosa da qualidade.

Quando o objeto de transferência estiver completo, a passagem deve ser imediata. Quando não estiver, a devolução deve ser precisa. O que não pode existir é passagem ambígua: caso transferido sem que se saiba o que foi entregue nem o que faltou.
