# Política de privacidade — CVGen

**Última atualização:** abril de 2026  

A **Orbit Apps** (“**nós**”, “**Operador**”) respeita a sua privacidade. Esta Política descreve como tratamos dados pessoais no aplicativo **CVGen** (“**App**”), em conformidade com a **Lei Geral de Proteção de Dados (Lei nº 13.709/2018 — LGPD)** e legislação aplicável.

**Encarregado / contato:** [contact@orbitapps.dev](mailto:contact@orbitapps.dev)

---

## 1. Quem é o controlador

O **controlador** dos dados pessoais tratados para a prestação do serviço CVGen é a **Orbit Apps**, responsável pelas decisões referentes ao tratamento descrito nesta Política.

---

## 2. Quais dados coletamos

Dependendo de como você usa o App, podemos tratar:

| Categoria | Exemplos |
|-----------|----------|
| **Dados de conta** | E-mail, identificador de usuário (Supabase Auth), senha (armazenada de forma segura pelo provedor de autenticação). |
| **Conteúdo do currículo** | Nome, telefone, e-mail, experiências, formação, texto de carta, fotografia opcional, preferências de modelo e idioma do documento. |
| **Dados técnicos e de uso** | Tipo de dispositivo, sistema operacional, identificadores de app, logs de erro (quando necessários), dados de rede básicos. |
| **Compras e assinaturas** | Identificadores de assinatura e status de plano processados pelas **lojas** (Apple/Google) e **RevenueCat** (ou equivalente), sem que armazenemos o número completo do cartão (tratado apenas pelas lojas). Eventos de compra podem atualizar **saldo de créditos** para melhorias com IA na sua conta. |
| **Métricas de produto** | Eventos de uso (por exemplo, telas visitadas, conclusão do tour inicial), versão do app e identificador pseudônimo no aparelho; quando configurado, enviados ao **PostHog** (ou equivalente) para melhorar o serviço. |
| **Dados de IA (Pro+)** | Trechos de texto que você enviar para recursos de **sugestão**, processados conforme a seção 6. |

**Fotografia:** se você adicionar foto ao currículo, ela pode ser armazenada **localmente** e, com sincronização ativada, em **armazenamento seguro** na nuvem (bucket privado), associada à sua conta.

---

## 3. Finalidades e bases legais (LGPD)

Tratamos dados pessoais para:

- **Execução do contrato / uso do App** — criar e editar currículos, exportar PDF, sincronizar quando habilitado (art. 7º, V e VII, LGPD).
- **Consentimento** — quando exigido para funcionalidades opcionais (por exemplo, permissões do sistema ou recursos de IA), mediante aceite ou configurações do dispositivo.
- **Legítimo interesse** — segurança, prevenção a fraudes, melhoria do serviço e métricas agregadas, observados seus direitos (art. 7º, IX).
- **Cumprimento de obrigação legal** — quando exigido por lei ou ordem judicial.

---

## 4. Compartilhamento com terceiros

Podemos depender de **prestadores** estritamente necessários:

- **Supabase** (autenticação, banco de dados e armazenamento de arquivos do currículo/foto, conforme configuração do projeto).
- **Apple / Google** — para compras in-app, login e distribuição do App.
- **RevenueCat** (ou similar) — gestão de assinaturas e entitlements.
- **PostHog** (ou equivalente) — métricas de produto e diagnóstico, quando ativado nas variáveis de ambiente do App; não vendemos seus dados pessoais para marketing.
- **Provedor de IA** — quando você usa sugestões com IA, o texto enviado é processado por **funções do Operador** (Edge Functions) e pode ser encaminhado a **provedor de modelo** (por exemplo, OpenAI), **sem** treinar modelos com seus dados pessoais para fins comerciais do provedor, salvo política própria do provedor aplicável naquele momento.

**Não vendemos** seus dados pessoais a terceiros para marketing.

---

## 5. Transferência internacional

Alguns provedores podem processar dados **fora do Brasil**. Nesses casos, adotamos medidas compatíveis com a LGPD (por exemplo, cláusulas contratuais ou avaliação de local adequado), conforme aplicável.

---

## 6. IA e cache

Para reduzir custos e repetições, sugestões podem ser **armazenadas em cache** associadas à sua conta e ao documento (hash do trecho analisado). Você pode **aceitar, editar ou descartar** sugestões; o conteúdo final do currículo permanece sob seu controle.

---

## 7. Retenção

- Mantemos os dados **enquanto sua conta estiver ativa** ou conforme necessário para prestação do serviço.
- Após exclusão da conta ou exclusão solicitada, poderemos **anonimizar** ou **apagar** dados em prazos razoáveis, salvo cumprimento legal ou resolução de litígio. A exclusão pela tela **Conta** remove o usuário de autenticação e os dados associados na nuvem conforme a infraestrutura (incluindo cache de IA ligado aos documentos), ressalvados backups temporários.
- **Backups** podem reter cópias por período técnico limitado.
- Registros de métricas no prestador de analytics seguem prazos e políticas desse prestador, em forma agregada ou pseudônima.

---

## 8. Seus direitos (LGPD)

Você pode solicitar:

- **Confirmação** de tratamento e **acesso** aos dados;
- **Correção** de dados incompletos ou desatualizados;
- **Anonimização, bloqueio ou eliminação** de dados desnecessários ou excessivos;
- **Portabilidade**, quando aplicável;
- **Informação** sobre compartilhamentos;
- **Revogação de consentimento**, quando o tratamento depender dele.

Pedidos podem ser feitos pelo e-mail **contact@orbitapps.dev**. Podemos solicitar informações para **confirmar sua identidade**.

**Métricas:** pode solicitar oposição ou esclarecimentos sobre o tratamento para melhoria do produto pelo mesmo e-mail. Com a conta excluída, deixamos de associar seu identificador de usuário aos eventos enviados após a exclusão, nos termos técnicos do prestador. Para desativar a coleta por completo enquanto usa o App, pode ser necessário contato com o suporte ou configuração futura no próprio App.

---

## 9. Segurança

Adotamos medidas técnicas e organizacionais razoáveis (por exemplo, HTTPS, controles de acesso, armazenamento seguro de segredos em ambiente servidor). **Nenhum sistema é 100% seguro**; use senha forte e proteja seu dispositivo.

---

## 10. Crianças e adolescentes

O App não se destina a menores de **16 anos** (ou idade mínima local). Se tomarmos conhecimento de cadastro indevido, tomaremos medidas para remover os dados.

---

## 11. Cookies e tecnologias similares

Em versões **web** (se houver), podem ser usados cookies ou armazenamento local conforme o navegador. No app nativo, utilizamos armazenamento local do sistema para sessão e preferências.

---

## 12. Alterações desta Política

Podemos **atualizar** esta Política. A data no topo será revisada. Alterações relevantes serão comunicadas por meio razoável (por exemplo, no App ou por e-mail). O uso continuado após a vigência pode indicar ciência das mudanças, quando permitido pela lei.

---

## 13. Contato

**Privacidade e dúvidas:** contact@orbitapps.dev  

Você também pode acionar a **Autoridade Nacional de Proteção de Dados (ANPD)** nos termos da legislação.

---

*Recomenda-se revisão jurídica antes da publicação definitiva.*
