
# NameLess Chat

This is a Full Stack MERN Project.

### 1. Client : 
Visit [NameLess Chat](https://nameless-chat.vercel.app/). This Front-end is made with React and Material UI. In here we can send messages anonymously.


### 2. Server : 
At the Back-end, we have an API made with Node, Express, Mongoose. This API is hosted on Heroku.





### API Reference
Base Url - https://hello-memo-api.herokuapp.com/

#### Get all memos

```http
  GET /api/memos
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `none` | `-----` | No parameters are required. |

#### Create a memo

```http
  POST /api/memos
```

_The Body should contain these parametes while sending a request._

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `title`      | `string` | **Required**. Title of the Memo |
| `details`      | `string` | **Required**. Message of the Memo |
| `category`      | `string` | **Required**. Category of the Memo |

