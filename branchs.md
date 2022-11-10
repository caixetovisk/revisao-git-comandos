# Branchs
São ramificações do projeto, o qual permite vários desenvolvedores, trabalharem em diferentes funcionalidades, sem bugar a versão estável.

## Principais branchs
Branch main -> que é a branch principal, ou seja, a branch estável da aplicação. Versão que é disponibilizada aos clientes.

Branch developer -> é branch utilizada pelos testers. Os quais vão testar as novas funcionalidades, correções de bugs, etc.

## Outras branchs
Para cada nova funcionalidade ou correção de bugs é criada uma nova branch

### Padrões para criar nomes de branchs
!IMPORTANTE! Nomes de branchs não tem acentos nem Ç

Para correção de bugs: fix_identicacao_do_bug
Exemplo: fix_botao_de_login, fix_cor_do_cabecalho

Para novas funcionalidades: feat_identificao_da_novo_funcionalidade
Exemplo: feat_integracao_com_google, feat_nova_tela_de_contato

Para atualizar documentação: doc_identificao_da_alteracao
Exemplo: doc_adicionada_nova_imagem

Para criação/alteração de tarefas que não interfere no código:
chore_identificacao_da_modificacao
Exemplo: chore_atualizada_a_versao_do_banco

## Comandos para trabalhar com branchs
### Criação de novas branchs
git checkout -b nome_da_nova_branch
Exemplo: git checkout -b fix_botao_da_tela_login
Obs: O ideal é sempre criar as branchs a partir da main.

### Listar as branchs existentes
git branch list

### Trocar de branch
git switch nome_da_branch_que_deseja_entrar
Exemplo 01: git switch fix_botao_da_tela_login
Exemplo 02: git switch main

### Excluir uma branch 
git branch -D nome_da_branch_que_deseja_excluir
Exemplo: git branch -D fix_botao_da_tela_login

