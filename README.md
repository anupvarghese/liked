#### Git 
- [Git tips](https://github.com/git-tips/tips)

#### Functional Programming
- [Functional Programming introduction](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536#.v75g0i6xk)

#### Javascript

- ##### Docs
  - [Functional Programming](https://github.com/hemanth/functional-programming-jargon)
  - [javascriptallongesix](https://leanpub.com/javascriptallongesix/read)
  - [Yarn vs npm](https://shift.infinite.red/npm-vs-yarn-cheat-sheet-8755b092e5cc#.zan26kdby)
  - [JS from scratch](https://github.com/verekia/js-stack-from-scratch)
  - [ES6](https://github.com/DrkSephy/es6-cheatsheet)
  - [More ES6](https://engineering.haus.com/dumb-es6-tricks-53ecadd1b29f#.i3ggpwde9)

- ##### Videos
  - [Monads](https://www.youtube.com/watch?v=cB0vpg9-YMQ)
  - [Code for Humans](https://www.youtube.com/watch?v=loj3CLHovt0)

#### React

- ##### Docs
  - [Binding & Arrow Functions](https://medium.com/@machnicki/handle-events-in-react-with-arrow-functions-ede88184bbb#.xfxboxcln)

- ##### Videos
  - [React Style Components](https://www.youtube.com/watch?v=gNeavlJ7lNY)

#### Rust
- [Book](https://doc.rust-lang.org/book)

#### Docker
- Remove all exited containers `❯❯❯ docker rm $(docker ps -a -q -f "status=exited")`
- [Private NPM with docker](https://blog.risingstack.com/private-npm-with-docker/)
- Connect to a docker container `❯❯❯ docker exec -it CONTAINER_ID bash`

#### Postgres
- [Faster JSON with postgresql](https://hashrocket.com/blog/posts/faster-json-generation-with-postgresql)
- [JSON filtering & aggregation in postgresql](http://stormatics.com/howto-use-json-functionality-in-postgresql/)

#### CURL helpers
- Sample post request `❯❯❯ curl -X POST -H 'Content-Type: application/json' -d '{"username":"a@ab.com","password":"abc"}' http://localhost:8080/auth`

#### Mongo
- Mongo restore `❯❯❯ mongorestore --db db_name ../db_dump_folder`

#### Free e-books
- [Oreilly](http://www.oreilly.com/programming/free/)

#### CSS
- [Refactoring CSS](https://speakerdeck.com/csswizardry/refactoring-css-without-losing-your-mind)

#### Cloud
- [AWS](https://github.com/open-guides/og-aws)

#### Kubernetes
- [Kubernetes kubectl installation](https://code.google.com/p/google-cloud-sdk/issues/detail?id=336#c8)
- Show master credentials `gcloud alpha container clusters describe example-cluster`

#### Elasticsearch
- [Introduction](https://www.hakkalabs.co/articles/introduction-to-elasticsearch-by-radu-gheorghe/)

#### Commands
- Kill app using a port - `lsof -i tcp:3004`
