# CRM

simple customer relation manager built with rails.

- customers with name, phone, email, notes and an image
- admin panel at /admin (activeadmin)
- pages: / , /customers/alphabetized , /customers/missing_email

run it:

bundle install
rails db:migrate
rails db:seed
rails s