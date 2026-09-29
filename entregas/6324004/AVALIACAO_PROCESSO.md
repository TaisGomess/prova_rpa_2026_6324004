# Ficha de Avaliação de Processo (PDD) — Questão 5

> Cenário escolhido para esta avaliação: A.

**Cenário escolhido:** A

1. **Nome do processo e descrição resumida:**
   Renomeação e arquivamento de comprovantes em PDF. O processo identifica a
   data e o número do documento no nome de cada arquivo, aplica o padrão fixo
   de nomenclatura e arquiva o PDF no destino definido.

2. **Volume / frequência estimados:**
   Execução diária, em dias úteis. Como estimativa inicial, considera-se um
   volume de 20 a 100 arquivos por dia; esse intervalo deve ser confirmado
   com o histórico real da operação.

3. **As entradas são estruturadas?** (sim/não + justificativa)
   Sim, desde que os nomes dos arquivos sigam um padrão consistente que
   contenha a data e o número do documento em posições ou formatos
   identificáveis. O processo utiliza esses dados do nome, sem depender de
   interpretar o conteúdo visual dos PDFs.

4. **As regras são claras e determinísticas?** (sim/não + justificativa)
   Sim. A regra de nomenclatura é fixa e permite determinar o nome final a
   partir da data e do número do documento. Arquivos sem esses dados válidos
   ou com nomes duplicados devem ser separados para tratamento manual.

5. **Veredito — o processo é elegível a RPA?** (justifique com base em regras
   claras, dados estruturados e repetibilidade)
   Sim. A atividade é repetitiva e diária, usa dados estruturados no nome dos
   arquivos e segue regras determinísticas para renomear e arquivar. Um robô
   pode executar o fluxo padrão e encaminhar exceções, como nomes inválidos
   ou duplicados, para revisão humana.
