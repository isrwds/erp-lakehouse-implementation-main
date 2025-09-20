# Workshop de Descoberta - Operações & Logística

## 📌 Metadados da Sessão
- **Data:** `YYYY-MM-DD`
- **Horário:** `HH:MM` às `HH:MM`
- **Facilitador:** `[Seu Nome]`
- **Participantes:**
    - `Nome do Participante 1 - Cargo`
    - `Nome do Participante 2 - Cargo`

## 🎯 Objetivo da Sessão
Mapear processos operacionais e logísticos para identificar oportunidades de otimização através do Data Lakehouse.

---

## ❓ Perguntas & Respostas

1. Qual é o nível de visibilidade em tempo real do estoque em todos os armazéns/pontos?

Resposta:
“Ainda é parcial. Temos o WMS que dá visibilidade por armazém, mas a integração com os pontos de venda nem sempre é automática. Muitas vezes precisamos confirmar com planilhas ou ligações.”

Insights/Observações:

Palavras-chave: WMS, ERP, integração incompleta, planilhas manuais, visibilidade parcial.

2. Como é calculado e monitorado o indicador OTIF (On Time In Full)?

Resposta:
“Hoje calculamos OTIF a partir de relatórios do TMS e feedback dos clientes. O acompanhamento não é em tempo real, geralmente consolidamos no fim do mês. Isso dificulta corrigir desvios durante o processo.”

Insights/Observações:

Palavras-chave: OTIF, TMS, relatórios mensais, feedback de clientes, ausência de monitoramento em tempo real.

3. Qual é o processo de planejamento de rotas de entrega? É otimizado dinamicamente?

Resposta:
“O planejamento ainda é feito de forma semi-manual, considerando regiões e volume. Algumas ferramentas sugerem rotas, mas não recalculam dinamicamente quando há imprevistos como trânsito ou atraso no carregamento.”

Insights/Observações:

Palavras-chave: roteirização manual/semi-automática, sistemas de TMS básicos, sem otimização dinâmica, impacto de trânsito e imprevistos.

4. Como são gerenciadas as devoluções e as não conformidades?

Resposta:
“Registramos as devoluções no sistema, mas o processo é demorado: precisa abrir chamado, gerar nota de devolução e ajustar estoque. Muitas vezes a análise da causa da não conformidade não é aprofundada.”

Insights/Observações:

Palavras-chave: notas de devolução, chamados internos, ajuste de estoque manual, falta de análise de causa raiz.

5. Existem gargalos no processo de recebimento, separação (picking) e expedição?

Resposta:
“Sim, principalmente no recebimento, onde há conferência manual das notas. No picking, quando não temos sistema com coletores, a separação gera erros. Já na expedição, o gargalo é a fila para carregamento.”

Insights/Observações:

Palavras-chave: recebimento manual, picking sem coletores RF, fila na expedição, erros humanos.

6. Como é feito o controle de qualidade na operação?

Resposta:
“É amostral. Fazemos conferência de parte das cargas, mas não conseguimos checar 100% por falta de tempo e equipe. Em alguns casos, só descobrimos falhas depois que o cliente reclama.”

Insights/Observações:

Palavras-chave: controle de qualidade amostral, checagem parcial, dependência de reclamações de clientes.

7. Quais dados de fornecedores (performance, prazo) são críticos e como são acompanhados?

Resposta:
“O principal é prazo de entrega e taxa de conformidade dos pedidos. Monitoramos via planilhas ou relatórios do ERP, mas raramente temos dashboard consolidado.”

Insights/Observações:

Palavras-chave: SLA de fornecedores, prazo de entrega, taxa de conformidade, ERP sem dashboard integrado.

8. Quais informações de outros departamentos são necessárias para melhorar a eficiência?

Resposta:
“Precisamos de previsões de vendas mais precisas do comercial e informações sobre campanhas de marketing. Muitas vezes a falta de alinhamento gera excesso ou falta de estoque.”

Insights/Observações:

Palavras-chave: previsão de demanda, alinhamento com vendas e marketing, impacto direto no estoque/logística.

9. Se pudessem rastrear um único item em tempo real na cadeia, o que seria?

Resposta:
“Gostaríamos de rastrear a localização exata dos veículos em rota com status de cada pedido. Isso reduziria chamadas de clientes e permitiria prever atrasos antes de acontecerem.”

Insights/Observações:

Palavras-chave: rastreamento em tempo real, telemetria/frota conectada, status do pedido, previsão de atrasos.

10. Qual é o maior desperdício de tempo ou recurso na operação logística hoje?

Resposta:
“O maior desperdício está no retrabalho: reprocessamento de notas, ajustes de estoque e filas de carregamento. Além disso, a falta de integração entre sistemas gera muito trabalho manual.”

Insights/Observações:

Palavras-chave: retrabalho, ajustes manuais, filas de carregamento, falta de integração de sistemas.