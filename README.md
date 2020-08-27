# Desafio RoR

Este repositório contém uma aplicação usando o Rails 6.

# Iniciando

1. `bundle install`
2. `rails db:create`
3. `rails s`

# Objetivo

O objetivo desse exercício é criar um calendário para agendamento de eventos. Os critérios estão listados abaixo:

1. Eventos podem ser criados, editados e apagados
2. Eventos devem estar associado com um único usuário
3. Eventos devem conter nome, descrição, data e horário
    -   Exemplo: se houver um evento agendado para o dia 27/09/2020 iniciando as 08:00 e terminando as 10:00,
    apenas poderão ser marcados eventos antes das 08:00 ou depois das 10:00 do dia 27/09/2020
4. Eventos não podem ser marcado na mesma faixa horário
5. Você pode utilizar o FullCalendar (https://fullcalendar.io/) para apresentação do calendário
6. Deve ser possível navegar pelos meses visualizando os eventos de cada mês isoladamente

Extras:
 
 1. Usar a gem Devise para gerenciar o acesso do usuário
 2. Arquivo de seeds.rb com código ruby para popular o banco


    
# Entregáveis
- Link do repositório do GitHub

 
 Obs: 
- Iremos analisar principalmente o Back-End da aplicação, não sendo necessário apresentar um Front-End bem elaborado. 


----------
