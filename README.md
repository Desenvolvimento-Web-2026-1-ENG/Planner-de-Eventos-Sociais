
##  Planner de Eventos Sociais
O Planner de Eventos Sociais é um sistema desenvolvido para auxiliar na organização de eventos como aniversários e casamentos. A aplicação tem como foco principal a gestão de convidados, controle de confirmações (RSVP) e acompanhamento de fornecedores e tarefas.
Com uma interface simples e funcional, o sistema permite ao organizador ter controle total do evento e proporciona uma melhor experiência aos convidados.

graph TD

    A["Frontend (Web/App)"]
    B[Backend API]
    C[Banco de Dados]

    D[Serviço RSVP]
    E[Módulo de Tarefas e Fornecedores]
    F["Mural (Fotos e Mensagens)"]

    A --> B
    B --> C

    B --> D
    B --> E
    B --> F

    D --> C


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Authors

- [@Fernanda](https://www.github.com/octokatherine)

