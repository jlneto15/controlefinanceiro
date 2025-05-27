# Funcionalidades do Controle Financeiro

## Visão Geral

O Controle Financeiro é uma aplicação web que permite gerenciar suas finanças pessoais de forma eficiente e organizada. Abaixo está a documentação detalhada de todas as funcionalidades disponíveis.

## Filtros

### Filtros de Período
- **De/Até**: Filtra transações por período específico
- Útil para visualizar gastos em um mês ou período específico

### Filtros de Categoria
- **Categoria**: Filtra por categoria específica
- Opção "Sem Categoria" para transações não categorizadas
- Lista todas as categorias cadastradas

### Filtros de Texto
- **Título**: Busca por texto no título da transação
- Busca case-insensitive
- Funciona com partes do texto

### Filtros de Status
- **Apenas não pagas**: Mostra apenas transações pendentes
- Útil para acompanhar dívidas e recebimentos pendentes

### Filtros de Recorrência
- **Recorrência**: Filtra por tipo de recorrência
- Opção "Sem Recorrência" para transações únicas
- Lista todas as recorrências cadastradas

## Transações

### Criação de Transação
- **Título**: Nome/descrição da transação
- **Data de Vencimento**: Data limite para pagamento
- **Data de Pagamento**: Data em que foi pago (opcional)
- **Tipo**: Entrada (receita) ou Saída (despesa)
- **Categoria**: Categorização da transação
- **Valor**: Valor monetário
- **Recorrência**: Configuração de repetição (opcional)

### Transações Parceladas
- Marque "Compra parcelada" ao criar
- Defina parcela atual e total de parcelas
- Sistema gera automaticamente todas as parcelas futuras
- Mantém histórico de parcelas pagas

### Transações Recorrentes
- Configure recorrências (mensal, semanal, etc.)
- Defina dia do vencimento
- Sistema gera automaticamente as próximas ocorrências
- Mantém histórico de recorrências

### Pagamentos Parciais
- Marque "Devolver" para habilitar pagamentos parciais
- Registre pagamentos parciais com data e valor
- Acompanhe valor restante
- Histórico completo de pagamentos
- Marca como quitado quando valor restante chega a zero

### Transações Prioritárias
- Marque transações como prioritárias
- Aparecem em seção separada
- Útil para contas importantes
- Pode ser despriorizada a qualquer momento

## Categorias

### Gerenciamento
- Crie, edite e exclua categorias
- Organize suas transações
- Categorias ordenadas alfabeticamente
- Validação para evitar duplicatas

## Recorrências

### Configuração
- Crie recorrências com ID único
- Defina nome e dia do vencimento
- Aplique em transações
- Sistema gera automaticamente próximas ocorrências

## Sincronização

### Firebase
- Sincronização opcional com Firebase
- Mantém dados atualizados entre dispositivos
- Backup automático na nuvem
- Configuração via interface

### Armazenamento Local
- Dados salvos no navegador
- Funciona offline
- Exportação/importação de dados
- Backup manual

## Interface

### Painel Principal
- Filtros rápidos
- Totais e saldos
- Lista de transações
- Ações rápidas

### Transações Prioritárias
- Seção dedicada
- Total prioritário
- Ações específicas

### Extrato
- Lista completa de transações
- Seleção múltipla
- Cálculo de totais
- Filtros avançados

## Totais e Saldos

### Saldo Atual
- Campo para saldo atual
- Influencia cálculos de totais
- Atualização manual

### Totais
- Total vencido não pago
- Total prioritário
- Total selecionado
- Cores indicativas (verde/vermelho)

## Ações

### Transações
- Criar nova transação
- Editar transação existente
- Excluir transação
- Marcar como paga
- Priorizar/despriorizar
- Registrar pagamento parcial

### Categorias
- Gerenciar categorias
- Editar categorias
- Excluir categorias

### Recorrências
- Gerenciar recorrências
- Editar recorrências
- Excluir recorrências

### Dados
- Exportar dados
- Importar dados
- Backup manual
- Configurar Firebase

## Dicas de Uso

1. **Organização**
   - Use categorias de forma consistente
   - Mantenha títulos descritivos
   - Configure recorrências para contas fixas

2. **Priorização**
   - Marque contas importantes como prioritárias
   - Acompanhe total prioritário
   - Mantenha saldo atualizado

3. **Pagamentos Parciais**
   - Use para empréstimos e devoluções
   - Mantenha histórico de pagamentos
   - Acompanhe valor restante

4. **Sincronização**
   - Configure Firebase para backup
   - Faça backup manual regularmente
   - Mantenha dados atualizados

5. **Filtros**
   - Use filtros para análises específicas
   - Combine filtros para visões detalhadas
   - Acompanhe períodos específicos 