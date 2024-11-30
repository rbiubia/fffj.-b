# fffj.-b
git clone <URL_DO_REPOSITÓRIO>
cd <NOME_DO_REPOSITÓRIO>
touch README.md
# Nome do Projeto

## Objetivo
Descreva brevemente o propósito do projeto.  
Exemplo: "Este projeto é um aplicativo de lista de tarefas simples para ajudar na organização do dia a dia."  

## Funcionalidades
- Adicionar tarefas.  
- Marcar tarefas como concluídas.  
- Excluir tarefas.  

## Cronograma
| Etapa             | Descrição                       | Prazo        |
|-------------------|---------------------------------|--------------|
| Planejamento      | Criar o README e estrutura      | DD/MM/AAAA   |
| Interface (UI)    | Criar o design da aplicação     | DD/MM/AAAA   |
| Backend           | Desenvolver a lógica da aplicação | DD/MM/AAAA |
| Testes e Finalização | Realizar ajustes e testes finais | DD/MM/AAAA |
git add README.md
git commit -m "Adiciona README com planejamento inicial"
git push origin main
git checkout -b interface-ui
# Trabalhe na interface
git add .
git commit -m "Implementa a interface básica"
git push origin interface-ui
git checkout main
git merge interface-ui
git push origin main
