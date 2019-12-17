# depot

```bash
$ rails new .
$ ./bin/rails generate scaffold Product title:string description:text image_url:string price:decimal
$ ./bin/rails db:migrate
$ ./bin/rails server
$ ./bin/rails test
$ ./bin/rails db:seed
$ ./bin/rails test:models
$ ./bin/rails generate controller Store index
$ ./bin/rails test:controllers
$ ./bin/rails dev:cache # turn it on
$ ./bin/rails dev:cache # turn it off
$ ./bin/rails generate scaffold Cart
$ ./bin/rails generate scaffold LineItem product:references cart:belongs_to
$ ./bin/rails db:migrate
$ ./bin/rails test test/controllers/line_items_controller_test.rb
```