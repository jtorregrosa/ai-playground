# AI-Playground

This project is developed in the scope of Jorge Torregrosa Master's Thesis.
 
## Summary

```
Design and implementation of an application that helps to understand the functioning of a neural network. For this purpose, the application will allow the graphical display of the network with the different values ​​that the weights acquire during their training.
The system will allow configuring different parameters of the network: inputs, outputs, activation function, minimum error, etc. The objective is that at any moment of the training process, the current values ​​of the network can be paused and displayed.
You should also see graphics at the end that indicate how the error has evolved during the process.
```

## Goals

```
- Allow to enter the training, validation and test sets by uploading files.
- Configure the parameters of the network.
- Show evolution of the training process.
- Save the architecture of a network.
- Load the architecture of a network.
```

## About the project

[TODO]

## Running

**Step 1**: clone the project with git

```sh
$ git clone https://github.com/jtorregrosa/ai-playground.git
```

**Step 2**: go into the `ai-playground` folder and run composer
```sh
$ cd ai-playground
$ composer install
```

**Step 2.1**: if you want to get the last vendor versions, run composer update
```sh
$ composer update
```

**Step 3**: install node modules with [yarn](https://yarnpkg.com/) or npm
```sh
# with yarn
$ yarn
# with npm 
$ npm install
```

**Step 3.1**: if you want to upgrade to the last module versions, do it with yarn or npm
```sh
# with yarn
$ yarn upgrade
# with npm 
$ npm update
```

**Step 4**: if you want a fresh start for the project, remove the `.git` folder


## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, yet powerful, providing tools needed for large, robust applications. A superb combination of simplicity, elegance, and innovation give you tools you need to build any application with which you are tasked.

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](http://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell at taylor@laravel.com. All security vulnerabilities will be promptly addressed.

## License

The AI-Playground is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
