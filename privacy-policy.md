# Política de Privacidade — KnowHer

**Última atualização:** 10 de maio de 2026
**Versão:** 1.0

---

## 1. Quem somos

A presente Política de Privacidade rege o tratamento de dados pessoais realizado pelo aplicativo móvel **KnowHer** (doravante "Aplicativo" ou "KnowHer"), de titularidade de:

- **Razão Social:** NICOLAS SERVIÇOS DE DESENVOLVIMENTO WEB LTDA
- **CNPJ:** 41.249.522/0001-09
- **Contato (Encarregado de Dados):** nicolastroles95@gmail.com

Para fins desta Política, **"Controlador"** significa a empresa acima identificada, que toma decisões sobre o tratamento de seus dados, conforme o art. 5º, VI da Lei nº 13.709/2018 (Lei Geral de Proteção de Dados Pessoais — **LGPD**).

---

## 2. A quem se aplica esta Política

Esta Política se aplica a todas as pessoas que utilizam o KnowHer em território brasileiro. O Aplicativo é destinado **exclusivamente a maiores de 18 anos**. Ao instalar e usar o KnowHer, você declara ter pelo menos 18 anos de idade.

Caso o Controlador identifique que dados de menores de 18 anos foram tratados, tais dados serão excluídos imediatamente.

---

## 3. Bases legais e finalidade

O tratamento de dados pessoais pelo KnowHer se baseia em:

- **Consentimento** (art. 7º, I e art. 11, I da LGPD), no caso de dados pessoais sensíveis;
- **Execução de contrato** (art. 7º, V da LGPD), para entrega das funcionalidades do Aplicativo;
- **Legítimo interesse** (art. 7º, IX da LGPD), para diagnóstico técnico e prevenção de fraude.

As finalidades do tratamento são, exclusivamente:

1. Operar as funcionalidades do Aplicativo (acompanhamento de ciclo, lembretes, datas importantes);
2. Sincronizar dados entre dispositivos do mesmo usuário, quando houver vinculação de conta;
3. Diagnosticar erros e melhorar a estabilidade do Aplicativo;
4. Cumprir obrigações legais.

**Não realizamos** tratamento de dados para fins de publicidade direcionada, venda a terceiros, ou criação de perfil comportamental para fins comerciais.

---

## 4. Dados pessoais que tratamos

### 4.1. Dados fornecidos por você

Ao utilizar o KnowHer, você fornece os seguintes dados:

| Categoria | Dado | Origem |
|---|---|---|
| Identificação | Nome próprio | Você digita |
| Identificação de terceiros | Nome da parceira | Você digita (ver Seção 5) |
| Dados sensíveis (saúde) | Data da última menstruação da parceira, duração média do ciclo | Você digita |
| Datas pessoais | Aniversários, datas comemorativas, eventos importantes | Você digita |
| Preferências | Horário de notificações, tom das mensagens, antecedência de avisos | Você configura |

### 4.2. Dados coletados automaticamente

| Categoria | Dado | Origem |
|---|---|---|
| Identificador de conta | UID anônimo (gerado pelo Firebase Authentication) | Automaticamente ao abrir o Aplicativo |
| Identificador de conta vinculada | Endereço de e-mail, nome e foto do perfil Google ou Apple | Apenas se você optar por vincular uma conta |
| Dados técnicos | Versão do Aplicativo, sistema operacional, idioma do dispositivo, fuso horário | Automaticamente |
| Logs de erro | Mensagens de erro técnicas, *stack traces* | Automaticamente, em caso de falha |

### 4.3. Dados que **não** coletamos

Para sua tranquilidade, esclarecemos que o KnowHer **não coleta**:

- Localização (GPS, IP geolocalizado)
- Lista de contatos
- Fotos, microfone ou câmera
- Histórico de navegação fora do Aplicativo
- Dados biométricos
- Informações financeiras

---

## 5. Dados pessoais sensíveis e dados de terceiros

### 5.1. Natureza sensível

Informações sobre o ciclo menstrual e datas associadas configuram **dado pessoal sensível**, nos termos do art. 5º, II da LGPD ("dado referente à saúde"). Como tal, recebem proteção reforçada.

### 5.2. Dados de terceiros (sua parceira)

O KnowHer foi desenhado para registrar dados sobre **uma terceira pessoa** (sua parceira), e não sobre você. **Esse fato gera responsabilidades específicas para o usuário do Aplicativo:**

- **Você declara, ao usar o Aplicativo, que possui consentimento da pessoa cujos dados são registrados.**
- A responsabilidade pela legitimidade do consentimento da parceira é **inteiramente sua**, na forma do art. 11, §4º da LGPD.
- O KnowHer atua exclusivamente como **operador técnico** do registro, sem coletar diretamente dados da parceira (nenhum cadastro em nome dela é exigido).
- A parceira pode, a qualquer momento, exigir do usuário que cesse o tratamento, hipótese em que o usuário deve excluir os dados conforme a Seção 9 desta Política.

Se você não possui consentimento, **não utilize o Aplicativo**.

---

## 6. Como armazenamos seus dados

### 6.1. Provedor de infraestrutura

Os dados são armazenados em infraestrutura **Google Firebase** (Google LLC), nos seguintes serviços:

- **Firebase Authentication** — para identificação de conta (anônima, Google ou Apple);
- **Cloud Firestore** — para armazenamento dos dados do Aplicativo.

A região de armazenamento configurada é **southamerica-east1 (São Paulo, Brasil)**.

### 6.2. Transferência internacional

Embora o armazenamento seja primário no Brasil, o Google opera em infraestrutura global e **eventualmente** dados podem trafegar por servidores nos Estados Unidos, conforme cláusulas-padrão do Google Cloud, em conformidade com o art. 33 da LGPD e com decisão da ANPD sobre transferências internacionais.

### 6.3. Cópia local

Os dados também são armazenados **localmente no seu dispositivo** (no `AsyncStorage` do sistema operacional), permitindo uso offline. Ao desinstalar o Aplicativo, essa cópia local é apagada pelo sistema operacional.

---

## 7. Compartilhamento com terceiros

O KnowHer **não vende**, **não aluga** e **não compartilha** dados pessoais para fins comerciais.

Os únicos terceiros com acesso técnico aos dados são:

| Terceiro | Função | Localização | Política |
|---|---|---|---|
| Google LLC (Firebase) | Armazenamento e autenticação | Brasil + EUA (eventual) | https://firebase.google.com/support/privacy |
| Google LLC (OAuth) | Autenticação opcional via Google Sign-In | EUA | https://policies.google.com/privacy |
| Apple Inc. (Sign in with Apple) | Autenticação opcional via Apple | EUA | https://www.apple.com/legal/privacy/ |

**Compartilhamento por exigência legal:** dados poderão ser compartilhados com autoridades públicas mediante ordem judicial, ofício ou determinação legal expressa, na forma do art. 23 da LGPD.

---

## 8. Tempo de retenção

| Dado | Retenção |
|---|---|
| Conta anônima sem uso | Excluída automaticamente após **180 dias** sem acesso |
| Conta vinculada (Google/Apple) | Mantida enquanto a conta existir |
| Dados após exclusão pelo usuário | Removidos do Firestore em até **30 dias**; backups de segurança rotativos do Google podem reter cópias por mais **30 dias**, após o que são apagados definitivamente |
| Logs de erro | **90 dias** |

---

## 9. Seus direitos

Como titular de dados pessoais, você tem os direitos garantidos pelo art. 18 da LGPD:

1. **Confirmação** da existência de tratamento;
2. **Acesso** aos dados;
3. **Correção** de dados incompletos, inexatos ou desatualizados;
4. **Anonimização, bloqueio ou eliminação** de dados desnecessários ou tratados em desconformidade;
5. **Portabilidade** dos dados a outro fornecedor;
6. **Eliminação** dos dados tratados com base no consentimento;
7. **Informação** sobre as entidades públicas e privadas com as quais o Controlador realizou uso compartilhado de dados;
8. **Informação** sobre a possibilidade de não fornecer consentimento e suas consequências;
9. **Revogação do consentimento**, nos termos do art. 8º, §5º da LGPD;
10. **Oposição** ao tratamento realizado com fundamento em uma das hipóteses de dispensa de consentimento, em caso de descumprimento da LGPD.

### Como exercer seus direitos

Envie e-mail para **nicolastroles95@gmail.com** com:
- Assunto: "LGPD — [tipo de pedido]"
- Identificação (nome ou e-mail vinculado à conta, ou UID se for conta anônima)
- Descrição do pedido

Responderemos em até **15 dias úteis**, conforme prazo recomendado pela ANPD.

### Exclusão dentro do Aplicativo

Você também pode excluir todos os seus dados sem precisar nos contatar:

1. Acesse **Ajustes → Dev → Resetar tudo** (em versões de desenvolvimento), ou
2. **Desinstale o Aplicativo** (apaga dados locais; se sua conta era anônima e você não a vinculou, os dados na nuvem serão excluídos no ciclo de retenção).

Para conta vinculada (Google/Apple), o processo de exclusão completo deve ser feito por e-mail.

---

## 10. Segurança

Adotamos medidas técnicas e administrativas razoáveis para proteger seus dados:

- **Criptografia em trânsito** (HTTPS/TLS) em todas as comunicações;
- **Criptografia em repouso** nos servidores do Google Firebase;
- **Regras de segurança no Firestore** (Security Rules) que garantem que cada usuário só acessa os próprios dados;
- **Autenticação obrigatória** para qualquer acesso a dados não-públicos;
- **Princípio do menor privilégio** — coletamos apenas o mínimo necessário para o funcionamento do Aplicativo.

Apesar dos cuidados, **nenhum sistema é totalmente imune a falhas**. Em caso de incidente de segurança que possa acarretar risco ou dano relevante a você, comunicaremos a ANPD e os titulares afetados em prazo razoável, conforme art. 48 da LGPD.

---

## 11. Cookies e tecnologias similares

O KnowHer é um aplicativo móvel e **não utiliza cookies**. Utilizamos:

- **Identificadores anônimos** gerados pelo Firebase Authentication (UID), necessários ao funcionamento;
- **Tokens de autenticação** armazenados localmente no dispositivo, expurgados ao desinstalar.

---

## 12. Notificações push

O KnowHer envia notificações **locais** (geradas no próprio dispositivo, não pela rede) com base nos dados que você configurou. Você pode desativar a qualquer momento em **Ajustes → Receber avisos** ou nas configurações do sistema operacional.

Atualmente **não enviamos notificações push remotas**, ou seja, nenhum servidor nosso dispara mensagens para o seu celular.

---

## 13. Crianças e adolescentes

O KnowHer **não é destinado a menores de 18 anos**. Não coletamos dados de menores conscientemente. Se identificarmos que dados de menor foram coletados, eliminaremos imediatamente.

Se você é responsável por menor que esteja usando o Aplicativo, contate-nos para a exclusão.

---

## 14. Alterações nesta Política

Podemos atualizar esta Política a qualquer momento. Mudanças relevantes serão comunicadas por:

1. Aviso destacado na tela de Ajustes do Aplicativo na próxima abertura, e
2. Atualização da data no topo deste documento.

Continuar usando o Aplicativo após a comunicação implica aceite da nova versão.

---

## 15. Encarregado pelo Tratamento de Dados Pessoais (DPO)

Conforme art. 41 da LGPD, o Encarregado pelo tratamento de dados pessoais do KnowHer é:

- **Nome:** Nicolas Troles
- **E-mail:** nicolastroles95@gmail.com

---

## 16. Foro

Para resolução de qualquer controvérsia decorrente desta Política, fica eleito o foro da Comarca onde o titular dos dados estiver domiciliado, conforme art. 101, I do Código de Defesa do Consumidor.

Você também pode apresentar reclamação à **Autoridade Nacional de Proteção de Dados (ANPD)** pelo site https://www.gov.br/anpd.

---

## 17. Contato

Em caso de dúvida sobre esta Política ou sobre o tratamento dos seus dados, contate-nos:

- **E-mail:** nicolastroles95@gmail.com
- **Razão Social:** NICOLAS SERVIÇOS DE DESENVOLVIMENTO WEB LTDA
- **CNPJ:** 41.249.522/0001-09
