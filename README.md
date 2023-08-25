<h1 align="center"> 👨🏻‍💻 Java RESTful API 👨🏻‍💻 </h1>

📝 Descrição
Java RESTful API criado para o BootCamp Santander 2023
## Diagrama de Classes

```mermaid
classDiagram
    class User {
        - name: String
        - account: Account
        - features: List<Feature>
        - card: Card
        - news: List<News>
    }

    class Account {
        - number: String
        - agency: String
        - balance: Float
        - limit: Float
    }

    class Feature {
        - icon: String
        - description: String
    }

    class Card {
        - number: String
        - limit: Float
    }

    class News {
        - icon: String
        - description: String
    }

    User "1" *-- "1" Account
    User "1" *-- "N" Feature
    User "1" *-- "1" Card
    User "1" *-- "N" News
```

## 🔧 Tecnologias utilizadas
* Java;
* API REST;
* Spring;
* Git & GitHub;
* Railway

## :soon: Implementação futura
* Null

## :handshake: Colaboradores
<table>
  <tr>
    <td align="center">
      <a href="http://github.com/marioslazaro">
        <img src="https://avatars.githubusercontent.com/u/111144236?v=4" width="100px;" alt="Foto de Mario Lazaro no GitHub"/><br>
        <sub>
          <b>marioslazaro</b>
        </sub>
      </a>
    </td>
  </tr>
</table>



## :dart: Status do projeto
Null






