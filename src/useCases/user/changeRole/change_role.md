# Alterar cargo

> ## Dados

1. Id do usuário a receber cargo
2. Novo cargo

> ## Fluxo Primário

1. Receber dados do usuário
2. Buscar usuário a ser alterado
3. Verificar se pode fazer alteração
4. fazer alteração

> ## Fluxo Secundário: Usuário tenta trocar própria função

3. Retornar erro informando que não pode executar alteração

> ## Fluxo Secundário: Usuário tenta trocar função de superior

3. Retornar erro informando que não pode executar alteração

> ## Fluxo Secundário: Usuário tenta trocar para função atual

3. Retornar erro informando que não pode executar alteração