# 02 — Incremento 2: chamar na ordem correta

- **Data:** 2026-09-28
- **Autoria:** Thalisson Viana Moura
- **Ferramenta:** GitHub Copilot no VS Code
- **Trilha:** local, workspace aberto no VS Code
- **Requisito ou critério alvo:** RF-03 e RF-04

## O que foi pedido

```text
Agora implemente somente chamarProxima em labs/lab-02-fila-facil/src/fila.js.
Cumpra RF-03 e RF-04: atender FIFO, retirar da espera, atualizar a senha atual e
contar chamadas efetivas. Fila vazia retorna null e preserva todo o estado.
Preserve emitirSenha, a interface, reiniciarFila e os testes. Verifique pelo caminho
disponível e explique como tratou o caso vazio. Não acrescente prioridade ainda.
```

## Contexto fornecido

O estado inicial de `fila.js`, as instruções do repositório e do laboratório, a
especificação e os testes foram consultados. O restante do código e a interface deveriam
ser preservados.

## O que veio

`chamarProxima` foi implementada com remoção FIFO, atualização da senha atual e do
contador. A fila vazia retorna `null` antes de qualquer mutação.

## O que eu fiz com isso

A suíte JavaScript foi executada. Resultado observado: 20 aprovados, 4 falhas; as quatro
falhas eram de RF-05, ainda pendente naquele incremento.