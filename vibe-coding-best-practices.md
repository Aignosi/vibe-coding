# Guia de Vibe Coding para Windsurf/Cursor
=====================================

Neste guia, reunimos dicas práticas para maximizar as melhores práticas e resultados.

## Como usar este guia

Insira este documento em uma pasta com um nome sugestivo, tipo: project-guidelines e configure o Cursor ou Windsurf para entender isso como um documento contexto do seu projeto.

### 1. Começando com Vibe Coding

*   Se nunca programou antes, você pode dar um passo atrás e começar usando ferramentas como Replit ou Lovable para prototipagem visual rápida.
*   Se já tem experiência com programação, prefira ferramentas como Windsurf, Cursor ou Claude Code.
*   Antes de começar a programar, avalie o projeto e crie um plano detalhado e documente esse plano em um arquivo Markdown dentro do projeto (preferencialmente na pasta docs).
*   Trabalhe seção por seção, marcando o progresso conforme avança.

## 2. Ferramentas e Estratégias

#### Controle de Versão

*   Use Git religiosamente.
*   Antes de uma nova feature, faça um commit limpo para facilitar reverts.
*   Em caso de problemas, precisaremo usar o git reset --hard e recomece em um estado limpo. Me consulte sempre antes de fazer esse comando.

## 3. Testes e Qualidade

#### Escreva Testes

*   Crie testes de alto nível (integração), simulando ações de usuários reais, não apenas unit tests.
*   Valide cada funcionalidade antes de prosseguir para a próxima.

#### Monitorando

*   Se você começar a gerar códigos inconsistentes, vou precisar de interromper e reavaliar o contexto.
*   Evite múltiplas tentativas no mesmo código defeituoso: iremos resetar e tentar novamente.

## 4. Dicas Avançadas

#### Gestão de Documentação

*   Vou Baixar e armazenar localmente a documentação de APIs que pretendo usar.
*   Consulte esses arquivos antes de tentar implementar algo.

#### Corrigindo Bugs

*   Colarei diretamente as mensagens de erro.
*   Para bugs complexos, pense em várias hipóteses antes de propor uma correção.
*   Sempre aplique correções em um código base limpo.

#### Revisão de Código

*   Sempre abra PRs com no mínimo 2 revisores.
*   Documente alterações com descrições claras.

#### Mensagens de Commit

*   Adote Conventional Commits para mensagens de commit.

#### CI/CD

*   Configure integração contínua usando GitHub Actions, GitLab CI ou similar.
*   Inclua linting e testes automatizados na pipeline de CI.

## 5. Otimização e Aprendizado

#### Refatoração Contínua

*   Refatore após implementar e testar.
*   Mantenha arquivos pequenos e modulares.
*   Modularidade facilita tanto o entendimento humano quanto o seu.

## 6. Docs, Docstrings e type hinting

*   Crie arquivos de documentação para explicar o que cada arquivo faz.
*   Use docstrings claros e explicativas para explicar o que cada método faz.
*   Use type hints para melhorar a legibilidade do código.

## 7. Linting

*   Use ferramentas de linting para identificar e corrigir erros de sintaxe e estilo.

## 8. Logging

*   Use ferramentas de logging para adicionar logs ao código.
*   Use logs para depuração e monitoramento.

## 9. Estilo de programação

*   Use um estilo de programação orientado a objeto, criando classes.
*   Use um estilo de programação procedural, criando funções que fazem uma coisa de cada vez.

## 10. Prototipação

*   Os arquivos que for gerando de prototipagem, devem ser armazenados em uma pasta chamada "prototipagem", nunca no root principal do projeto.
*   O código gerado, aí sim, deve ser armazenado no src ou na pasta recomendada pelo user.
