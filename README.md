# Hello Rails-React (Back-end)
> This app works as an API that gets data from a database and manages other back-end aspects for a separate hello-react-rails front-end project. Built with Ruby on Rails.

## 🛠️ Built With

- Ruby on Rails
- PostsgreSQL

## [Hello Rails-React (Front-end)](pending)

## 🧮 Prerequisites

### Install
- Node.js
- Yarn
- Ruby
- Ruby on Rails

### Setup

Follow these steps on your console to properly clone this repository on your desktop:

```
$ cd desktop
$ git clone 'repo_path'
$ cd 'repo_name'
$ code .
Run 'ruby file_name' to see outputs in the console.
Run 'rubocop' to check linter offenses.
```

If you create a new rails application you can create the app with the following command:
```
rails new my_new_rails_app --api --git --database=postgresql -T
```
If you already have a rails application you can setup the app with the following command:
```
rails new . --api --git --database=postgresql -T
```

Create database for the project with `bin/rails db:create`, otherwise create databases manually in PostgreSQL.

If necessary, add username and password in `config/database.yml` for development and test:
```
development:
  <<: *default
  database: hello-react-rails-backend_development
  host: ''
  username:
  password:
  
  test:
  <<: *default
  database: hello-react-rails-backend_test
  username:
  password:
```

## 👤 Author

### Mike Martínez

- GitHub: [@mikemtzp](https://github.com/mikemtzp)
- Twitter: [@mikemtzp](https://twitter.com/mikemtzp)
- LinkedIn: [Mike Martínez](https://www.linkedin.com/in/mike-mart%C3%ADnez/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](https://github.com/mikemtzp/hello-react-rails-backend/issues).

## ⭐️ Show your support

Give a ⭐️ if you like this project!

## 🥇 Acknowledgments

- This README.md was elaborated with the [Microverse readme-template](https://github.com/microverseinc/readme-template)

## 📝 License

[MIT License](https://github.com/mikemtzp/hello-react-rails-backend/blob/dev/LICENSE)
