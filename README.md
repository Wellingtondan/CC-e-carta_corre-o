# Reposta à consulta
Resposta à consulta



### 1. Carta de Correção Eletrônica (CC-e)

> RESPOSTA À CONSULTA TRIBUTÁRIA 29992/2024, de 12 de julho de 2024. 

Ementa

**ICMS – Obrigações Acessórias - Documento fiscal emitido com incorreção em dado cadastral – Carta de Correção Eletrônica (CC-e).**

I. Não é admitido o uso de Carta de Correção Eletrônica (CC-e) para corrigir dados cadastrais que impliquem alteração na identidade ou no endereço do remetente ou do destinatário.


> Ajuste SINIEF 07/2005 (com alterações posteriores)

Este é o ato normativo que regulamenta a NF-e e sua correção. Os principais dispositivos sobre a CC-e estão nos seguintes trechos:

Cláusula décima sexta-A (inserida pelo Ajuste SINIEF 01/2007 e atualizada)
"A correção de erros na NF-e que não impliquem em alteração de valores fiscais da operação ou da prestação, bem como de dados cadastrais que impliquem mudança do remetente ou do destinatário, poderá ser feita por meio de Carta de Correção Eletrônica – CC-e."

Cláusula décima quarta-A Após a concessão da Autorização de Uso da NF-e, de que trata a cláusula sétima, o emitente poderá sanar erros em campos específicos da NF-e, por meio de Carta de Correção Eletrônica - CC-e, transmitida à administração tributária da unidade federada do emitente, desde que o erro não esteja relacionado com:

I - as variáveis que determinam o valor do imposto tais como: base de cálculo, alíquota, diferença de preço, quantidade, valor da operação ou da prestação;

II - a correção de dados cadastrais que implique mudança do remetente ou do destinatário;

III - a data de emissão ou de saída.

Acrescido os incisos IV e V à cláusula décima quarta-A pelo Ajuste SINIEF 44/20, efeitos a partir de 11.12.20.

IV -   campos da NF-e de exportação informados na Declaração Única de Exportação – DU-E;

V -   a inclusão ou alteração de parcelas de vendas a prazo.

-----------------------------------------------



### Carta de Correção Eletrônica (CC-e)

📘A **Carta de Correção Eletrônica (CC-e)** é um evento da Nota Fiscal Eletrônica (NF-e) que permite corrigir erros formais em documentos fiscais, desde que **não alterem valores, tributos ou dados essenciais da operação**.

✅ Quando pode ser utilizada
A CC-e pode ser usada para corrigir erros que **não impliquem**:

- Mudança de **valores fiscais** da nota (base de cálculo, alíquota, valor total, etc.)

Alteração de **impostos** (ICMS, IPI, etc.)

Modificação do **emitente** ou do **destinatário** (ex: mudança de CNPJ)

📌 Exemplos de campos que podem ser corrigidos


|Tipo de Informação	| Pode Corrigir?|
| -------------------- | -------------------- |
| *CFOP ou CST (sem mudança de tributação)* |  ✅  |
| *Descrição do produto (sem mudar valor)* |  ✅  |
| *Peso, volume, embalagem*	|   ✅  |
| *Data de saída ou emissão (mesmo período ICMS)*	| ✅ |
| *Transportadora*	| ✅ |
| *Dados adicionais no rodapé*	| ✅ |
| *Quantidade, preço unitário, valor total*	| ❌ |
| *CNPJ do destinatário*	| ❌ |
| *Alíquota de ICMS/IPI/PIS/COFINS*	| ❌ |

📅 Prazos e limites
Prazo: até 720 horas (30 dias corridos) após a autorização da NF-e

Limite de eventos: até 20 CC-e por NF-e

Consolidação: a última CC-e deve conter todas as correções anteriores

🛠️ Procedimento técnico
A CC-e é registrada como um evento da NF-e, com o código 110110

Deve ser transmitida para a SEFAZ autorizadora

O XML da CC-e deve conter:

Chave da NF-e

Descrição da correção

Sequência do evento

Assinatura digital do emitente




