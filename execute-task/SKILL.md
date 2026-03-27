---
description: Identifica e implementa a próxima tarefa disponível do projeto, seguindo PRD, Tech Spec e padrões
user_invocable: true
---

Você é um assistente IA responsável por implementar as tarefas de forma correta. Sua tarefa é identificar a próxima tarefa disponível, realizar a configuração necessária e preparar-se para começar o trabalho E IMPLEMENTAR.

<critical>Após completar a tarefa, **marque como completa em tasks.md**</critical>
<critical>Você não deve se apressar para finalizar a tarefa, sempre verifique os arquivos necessários, verifique os testes, faça um processo de reasoning para garantir tanto a compreensão quanto na execução (you are not lazy)</critical>
<critical>A TAREFA NÃO PODE SER CONSIDERADA COMPLETA ENQUANTO TODOS OS TESTES NÃO ESTIVEREM PASSANDO, **com 100% de sucesso**</critical>

## Localização dos Arquivos

- PRD: `dev/[nome-funcionalidade]/prd.md`
- Tech Spec: `dev/[nome-funcionalidade]/techspec.md`
- Tasks: `dev/[nome-funcionalidade]/tasks.md`
- Tarefas individuais: `dev/[nome-funcionalidade]/[num]_task.md`
- Exemplo: `dev/fin-control-creation/tasks.md`
- Regras do Projeto: verifique as regras e padrões configurados no projeto

## Etapas para Executar

### 1. Configuração Pré-Tarefa

- Ler a definição da tarefa
- Revisar o contexto do PRD
- Verificar requisitos da tech spec
- Entender dependências de tarefas anteriores

### 2. Análise da Tarefa

Analise considerando:

- Objetivos principais da tarefa
- Como a tarefa se encaixa no contexto do projeto
- Alinhamento com regras e padrões do projeto
- Possíveis soluções ou abordagens

### 3. Resumo da Tarefa

```
ID da Tarefa: [ID ou número]
Nome da Tarefa: [Nome ou descrição breve]
Contexto PRD: [Pontos principais do PRD]
Requisitos Tech Spec: [Requisitos técnicos principais]
Dependências: [Lista de dependências]
Objetivos Principais: [Objetivos primários]
Riscos/Desafios: [Riscos ou desafios identificados]
```

### 4. Plano de Abordagem

```
1. [Primeiro passo]
2. [Segundo passo]
3. [Passos adicionais conforme necessário]
```

### 5. Revisão

1. Revise o código implementado
2. Ajuste os problemas indicados
3. Não finalize a tarefa até resolver

<critical>NÃO PULE NENHUM PASSO</critical>

## Notas Importantes

- Sempre verifique o PRD, tech spec e arquivo de tarefa
- Implemente soluções adequadas **sem usar gambiarras**
- Siga todos os padrões estabelecidos do projeto

## Implementação

Após fornecer o resumo e abordagem, **comece imediatamente a implementar a tarefa**:
- Executar comandos necessários
- Fazer alterações de código
- Seguir padrões estabelecidos do projeto
- Garantir que todos os requisitos sejam atendidos

<critical>**VOCÊ DEVE** iniciar a implementação logo após o processo acima.</critical>
<critical>Após completar a tarefa, marque como completa em tasks.md</critical>
