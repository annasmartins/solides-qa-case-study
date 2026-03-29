# Bug Report 02 - Tela de login aparece para usuário autenticado

## Título
Tela de login é exibida momentaneamente ao abrir uma nova página, mesmo com usuário autenticado.

## Ambiente
Plataforma web de recrutamento

## Pré-condição
Usuário já autenticado na plataforma.

## Passos para reproduzir
1. Fazer login na plataforma com sucesso
2. Navegar para uma nova página interna da área logada
3. Observar a interface durante o carregamento da nova página

## Resultado atual
A tela de login aparece por uma fração de segundos antes da página correta ser exibida.

## Resultado esperado
O usuário autenticado deve visualizar diretamente a página interna correspondente, sem exibição temporária da tela de login.

## Impacto
Médio. O comportamento gera confusão, transmite instabilidade e prejudica a experiência do usuário.

## Severidade
Média

## Prioridade
Média
