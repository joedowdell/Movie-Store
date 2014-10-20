# Movie Store

Online shopping is a form of electronic commerce which allows customers to directly buy products or services like e-books, software, and streaming media over the Internet using a web browser. This kind of shopping is a part of our daily lives, used by many well-known sites, such as Amazon, E-bay, or various streaming sites.

## Technologies Used:

  + Ruby – Programming language
  + Rails – Back-end framework
  + Foundation 5 – Front-end css framework
  + Devise – User authentication
  + Redis – Key-value store

Next step to add Braintree or Stripe to accept payments.


### How to set it up
```sh
git clone git@github.com:joedowdell/Movie-Store.git
cd movie-store
bundle
bin/rake db:setup
```

### How to run it
```sh
cd movie-store
bin/rails s
```

open your browser and go to [localhost:3000](http://localhost:3000)