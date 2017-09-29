# README

Token-based authentication with Ruby on Rails 5 API
Read more at https://www.pluralsight.com/guides/ruby-ruby-on-rails/token-based-authentication-with-ruby-on-rails-5-api#ha96xEYTyL51fBSY.99


Rails Commands 

    bundle install
    
    rails db:create
    
    rails db:migrate
    
    rails db:seed

    rails s



Testing API


    $ curl -H "Content-Type: application/json" -X POST -d '{"email":"alexishida@gmail.com","password":"123456"}' http://localhost:3000/authenticate


    $ curl -H "Authorization: <token>" http://localhost:3000/items