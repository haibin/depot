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
$ ./bin/rails generate migration add_quantity_to_line_items quantity:integer
$ ./bin/rails db:migrate
$ ./bin/rails generate migration combine_items_in_cart
$ ./bin/rails db:migrate
$ ./bin/rails db:rollback
$ ./bin/rails db:migrate:status
$ ./bin/rails test:controllers
$ ./bin/rails log:clear LOGS=test
$ ./bin/rails test:controllers
$ ./bin/rails generate channel products
$ ./bin/rails generate scaffold Order name address:text email pay_type:integer
$ ./bin/rails generate migration add_order_to_line_item order:references
$ ./bin/rails db:migrate
$ ./bin/rails dbconsole
$ curl --silent http://localhost:3000/products/3/who_bought.atom
$ bundle install
$ ./bin/rails webpacker:install
$ ./bin/rails webpacker:install:react
$ ./bin/rails test:system
$ ./bin/rails generate mailer Order received shipped
$ ./bin/rails generate job charge_order
$ ./bin/rails test test/system/orders_test.rb
$ ./bin/rails generate scaffold User name:string password:digest
$ ./bin/rails db:migrate
$ bundle install
$ sqlite3 -line db/development.sqlite3 "select * from users"
$ ./bin/rails generate controller Sessions new create destroy
$ ./bin/rails generate controller Admin index
$ ./bin/rails console
```

