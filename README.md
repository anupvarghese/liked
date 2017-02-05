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
- [modular CSS](https://medium.engineering/simple-style-sheets-c3b588867899#.cmmi61to0)
- [CSS-reference](http://cssreference.io/)
- [New friend Felxbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Flexbox complete](https://medium.freecodecamp.com/understanding-flexbox-everything-you-need-to-know-b4013d4dc9af#.xvhiqtrhh)

#### Cloud
- [AWS](https://github.com/open-guides/og-aws)
- [Jump server and tunneling](https://blog.remibergsma.com/2013/05/28/creating-a-multi-hop-ssh-tunnel-by-chaining-ssh-commands-and-using-a-jump-host/)

#### Kubernetes
- [Kubernetes kubectl installation](https://code.google.com/p/google-cloud-sdk/issues/detail?id=336#c8)
- Show master credentials `gcloud alpha container clusters describe example-cluster`
- [Deploy using kubernetes from DockerHub](http://blog.wercker.com/deploying-a-microservice-to-kubernetes)

#### Elasticsearch
- [Introduction](https://www.hakkalabs.co/articles/introduction-to-elasticsearch-by-radu-gheorghe/)

#### Commands
- Kill app using a port - `lsof -i tcp:3004`

#### Snippets
- [Moment Timezone](http://jsfiddle.net/91zmpneh/)

#### Editors
- [Mac Key Bindings for VS Code](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)

#### Briantree test cards
- [Test credit card numbers](https://developers.braintreepayments.com/reference/general/testing/ruby#credit-card-numbers)

#### 2017
- [for 2017](https://medium.com/@sapegin/what-to-learn-in-2017-if-youre-a-frontend-developer-b6cfef46effd#.akm9ll6b9)

#### Kafka
- List kafka topics  `/opt/kafka_<version>/bin/kafka-topics.sh --zookeeper zk01.example.com:2181 --list`
- Create new kafka topics  `/opt/kafka_<version>/bin/kafka-topics.sh --topic TOPIC_NAME --create --zookeeper zk01.example.com:2181 --partitions 1 --replication-factor 1`

#### SSH
- [teleconsole](http://gravitational.com/blog/instant-ssh-github/)

