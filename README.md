# Guia Simplificado de Commits

Este guia foi elaborado com base em boas práticas adotadas em diversos projetos e equipes de desenvolvimento. Ele tem como objetivo padronizar as mensagens de commit para facilitar o entendimento do histórico de mudanças.

## Formato
As mensagens de commit devem seguir a estrutura abaixo, onde `<tipo>` é obrigatório e deve ser escolhido conforme a tabela de categorias. A `<descrição>` deve ser clara e objetiva sobre a alteração realizada.

```
<tipo>: <descrição>
```

## Tipos de Commit
A seguir, uma lista com os tipos de commit e seus respectivos significados:

| Tipo      | Descrição                    | Uso indicado |
|-----------|------------------------------|--------------|
| feat      | Nova funcionalidade          | Quando adicionar um novo recurso ao projeto |
| fix       | Correção de erro             | Para corrigir um bug identificado |
| docs      | Documentação                 | Alterações em arquivos de documentação |
| style     | Estilização                   | Mudanças que não afetam a lógica do código (espaçamento, formatação, etc.) |
| refactor  | Refatoração                   | Alterações no código sem impactar funcionalidade ou corrigir bugs |
| perf      | Otimização                    | Melhorias que impactam o desempenho do sistema |
| test      | Testes                        | Inclusão ou ajuste de testes automatizados |
| build     | Configuração de build         | Modificações em scripts de build ou dependências |
| ci        | Integração Contínua           | Ajustes em configurações e scripts de CI/CD |
| chore     | Tarefas diversas              | Outras mudanças que não afetam diretamente o código-fonte |
| revert    | Reversão de commit            | Desfazer um commit anterior |

Seguir essa estrutura ajuda a manter um histórico organizado e facilita a colaboração dentro da equipe.

✒️ Autor
Gustavo Araujo

