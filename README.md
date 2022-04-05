
# Netflix Clone

It is developed by using Nodejs and  design look like Netflix app



## Author

- [@gopimudumal](https://www.github.com/gopimudumal99)


## Features

- Responsive
- sliding 
- Individual page for particular movie
- all are dynamic 
- youtube vedios are apended


## 🛠 Skills
Javascript, HTML, CSS, Node.js...

## Tech Stack

**Server:** Node, Express


## Screenshots

![App Screenshot](https://i.postimg.cc/4xg5k9j2/1.png)

![2.png](https://i.postimg.cc/pXYjj11k/2.png)

![3.png](https://i.postimg.cc/SKwR3WvJ/3.png)





## API Reference

#### Get all items

```http
  GET https://api.themoviedb.org/3/genre/movie/list?<api_key>
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /https://api.themoviedb.org/3/movie/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |




## Run Locally

Clone the project

```bash
  git clone https://github.com/gopimudumal99/netflix-app.git
```

Go to the project directory

```bash
  cd netflix-app
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


