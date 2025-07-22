
## Carta de Correção Eletrônica (CC-e) quando emitir?

### Carta de Correção Eletrônica (CC-e)

📘A **Carta de Correção Eletrônica (CC-e)** é um evento da Nota Fiscal Eletrônica (NF-e) que permite corrigir erros formais em documentos fiscais, desde que **não alterem valores, tributos ou dados essenciais da operação**.

✅ Quando pode ser utilizada

A CC-e pode ser usada para corrigir erros que **não impliquem**:

- Mudança de **valores fiscais** da nota (base de cálculo, alíquota, valor total, etc.)

- Alteração de **impostos** (ICMS, IPI, etc.)

- Modificação do **emitente** ou do **destinatário** (ex: mudança de CNPJ)
--------------------------

📌 **Exemplos de campos que podem ou não podem ser corrigidos**

| **Tipo de Informação**	| **Pode Corrigir?** |
| -------------------- | -------------------- |
| *CFOP ou CST (sem mudança de tributação)* |  ✅  |
| *Descrição do produto (sem mudar valor)* |  ✅  |
| *Peso, volume, embalagem*	|   ✅  |
| *Data de saída ou emissão (mesmo período ICMS)*	| ✅ |
| *Transportadora*	| ✅ |
| *Dados adicionais no rodapé*	| ✅ |
| *Quantidade, preço unitário, valor total*	| ❌ |
| *CNPJ, IE ou endereço do destinatário*	| ❌ |
| *Razão social do destinatário*	| ❌ |
| *Alíquota de ICMS/IPI/PIS/COFINS*	| ❌ |
--------------------------

✅ Transportadora 

A alteração da transportadora é permitida por meio da CC-e, desde que não haja mudança de valor do frete ou de regime tributário. A transportadora não é considerada dado essencial da operação, segundo o [`Manual de Orientação ao Contribuinte (MOC)`](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=LrBx7WT9PuA=).

📌 Exemplo válido de correção via CC-e:

- Correção do CNPJ ou nome da transportadora

- Inclusão da transportadora (quando faltante)

- Alteração do tipo de frete (CIF/FOB), desde que não altere os valores da nota

--------------------------

📅 **Prazos e limites**

- **Prazo:** até **720 horas** (30 dias corridos) após a autorização da NF-e

- **Limite de eventos:** até **20 CC-e por NF-e**

- **Consolidação:** a última CC-e deve conter todas as correções anteriores
--------------------------

🛠️ **Procedimento técnico**

- A CC-e é registrada como um **evento** da NF-e, com o **código 110110**

- Deve ser transmitida para a SEFAZ autorizadora

- O XML da CC-e deve conter:

  - Chave da NF-e

  - Descrição da correção

  - Sequência do evento

  - Assinatura digital do emitente
--------------------------

⚖️ **Base legal**

| **Documento**	| **Descrição** | **Link** |
|-----------|----------| ----------|
| *Ajuste SINIEF 13/2024* |	Define o uso e condições da CC-e a partir de 2024 | [Acesse site](https://www.confaz.fazenda.gov.br/legislacao/ajustes/2024/ajuste-sinef-13-24) |
| *Nota Técnica 2011/003*	| Especifica o layout e regras técnicas do evento | [Acesse site](https://www.nfe.fazenda.gov.br/portal/exibirArquivo.aspx?conteudo=hNJXbmu+l8Q%3D) |
| *Manual de Orientação ao Contribuinte (MOC)* |	Regras operacionais e técnicas da NF-e | [Acesse site](https://www.nfe.fazenda.gov.br/portal/listaConteudo.aspx?tipoConteudo=ndIjl+iEFdE%3D) |
| *Portal Nacional da NF-e*	| Documentação oficial da Receita Federal | [Acesse site](https://www.nfe.fazenda.gov.br) |
| *Resposta à consulta 29992/2024, de 12 de julho de 2024* | Dados cadastrais | [Acesse site](https://legislacao.fazenda.sp.gov.br/Paginas/RC29992_2024.aspx) |
| *Resposta à consultaA 30299/2024, de 23 de setembro de 2024* | Preenchimento incorreto | [Acesse site](https://legislacao.fazenda.sp.gov.br/Paginas/RC30299_2024.aspx) |
| *Resposta à consulta 31320/2025, de 18 de março de 2025* | Obrigações acessórias | [Acesse site](https://legislacao.fazenda.sp.gov.br/Paginas/RC31320_2025.aspx) |

**Ementa resumida das Resposta à consulta:**

- ☑️**Resposta à consulta 29992/2024:** Não é admitido o uso de CC-e para corrigir dados cadastrais que impliquem mudança na identidade/endereço do remetente/destinatário.
- ☑️**Resposta à consultaA 30299/2024:** A CC-e pode ser usada para sanar erros formais, desde que não alterem dados essenciais ou valores do imposto.
- ☑️**Resposta à consulta 31320/2025:** Reafirma limites legais do uso da CC-e conforme Ajuste SINIEF: proíbe alterações em valores ou variáveis tributárias.
--------------------------

### Conclusão

A **Carta de Correção Eletrônica (CC-e)** é uma ferramenta valiosa para corrigir **erros formais** em documentos fiscais, desde que **não alterem o conteúdo tributário ou elementos essenciais da operação**. Seu uso está claramente delimitado pela legislação vigente, especialmente o **Ajuste SINIEF 07/2005**, atualizado por normas posteriores, e por **entendimentos da SEFAZ-SP** consolidados em respostas recentes a consultas tributárias.

🔒 **Limites claros:** A CC-e **não pode** ser utilizada para corrigir valores, impostos, destinatário, remetente ou data de emissão/saída. Tentativas fora desses critérios podem invalidar o documento fiscal ou gerar autuação.

📌 **Importância do correto preenchimento:** Apesar da CC-e ser uma forma de regularização, sua aplicação deve ser vista como medida corretiva excepcional, e **não como solução para falhas recorrentes no processo de emissão da NF-e**.

🧭 **Orientação contínua**: Consulte sempre os manuais oficiais, notas técnicas, o **site do Portal Nacional da NF-e** e a **legislação estadual**, que pode trazer regras específicas ou entendimentos atualizados.

🖊️***Elaborado pelo colaborador:*** Wellington Daniel
