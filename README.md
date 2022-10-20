# INTRODUCTION #


This document provides the instructions for using / interacting with the Hello Demo Application developed by ***Dieuveille BOUSSA ELLENGA***. 


<br>
<br>


## Basic Introduction to Elixir and Phoenix framework 

<br>

For this project we also need PostgreSQL 

<br>

### We clone the project 

```
git clone https://github.com/DieuveilleWebH3/hello-younzee.git
```

### We make sure to have Elixir and Phoenix on our locall machine, else 

- [Installing Elixir](https://elixir-lang.org/install.html)

<br>

- [Installing Phoenix](https://hexdocs.pm/phoenix/installation.html)

<br>

- [Installing PostgreSQL](https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql/) 

<br>

### We open our cloned project in our favorite IDE

<br>

### We add the database configuration   

We open config/dev.exs and fill the information 

```

# Configure your database
config :hello, Hello.Repo,
  # This should be the username of our database server, by default it usually is  "postgres"
  username: "**********",  
  
  # This should be the password of our database server, the one used when PostgreSQL was installed 
  password: "**********",  

  # This should be the hostname of our database server, running on local it is "localhost" 
  hostname: "**********",  

  database: "hello_dev",
  stacktrace: true,
  show_sensitive_data_on_connection_error: true,
  pool_size: 10

```


## Hello

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix
