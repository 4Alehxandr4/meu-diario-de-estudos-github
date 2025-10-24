# Resumo do Domínio 1: Introdução ao Git

O Git é um Sistema de Controle de Versão (VCS), uma ferramenta cujo objetivo é rastrear e gerenciar o histórico de alterações nos arquivos de um projeto. Ele permite que equipes colaborem de forma segura e organizada.

O fluxo de trabalho básico do Git segue três estágios:

1. Diretório de Trabalho (Working Directory): É a pasta local do projeto, onde os desenvolvedores modificam os arquivos.

2. Área de Preparação (Staging Area): Uma área intermediária. Depois de modificar os arquivos, usamos o comando git add para selecionar quais alterações específicas queremos incluir no próximo ponto de salvamento.

3. Repositório (Repository): Onde o histórico do projeto é salvo permanentemente. Usamos o comando git commit para pegar tudo o que está na Staging Area e criar um "save point" (um snapshot) no histórico, sempre com uma mensagem descritiva.

Para facilitar a colaboração, o Git usa branches (ramos). Uma branch é uma linha de trabalho independente que permite desenvolver novas funcionalidades ou corrigir bugs sem afetar a linha principal (main). Cada colaborador pode trabalhar em sua própria branch e, quando o trabalho estiver pronto, ele pode ser integrado de volta à branch principal.