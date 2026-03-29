# Bug Report 01 - Expiração de sessão com perda de dados

## Título
Usuário é deslogado durante o preenchimento do cadastro e perde os dados inseridos.

## Ambiente
Plataforma web de recrutamento

## Pré-condição
Usuário autenticado na plataforma e com formulário de cadastro em andamento.

## Passos para reproduzir
1. Acessar a plataforma com login válido
2. Iniciar o preenchimento dos dados cadastrais
3. Permanecer alguns minutos preenchendo as informações
4. Tentar continuar o processo após algum tempo

## Resultado atual
O sistema desloga o usuário rapidamente e os dados preenchidos são perdidos.

## Resultado esperado
A sessão deve permanecer ativa por tempo suficiente durante o preenchimento ou o sistema deve salvar automaticamente os dados inseridos.

## Impacto
Alto. O problema compromete a conclusão do cadastro e causa retrabalho e frustração ao usuário.

## Severidade
Alta

## Prioridade
Alta
