# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


# Toy-App
A toy demo application to show off some of the power of Rails.


### FEATURE 01 - Criar um endpoint <code>/users/new</code> para o cadastro de pessoas usuárias.

### FEATURE 02 - Criar um endpoint <code>/users</code> para listar todas as pessoas usuárias.

### FEATURE 03 - Criar um endpoint <code>/users/:id</code> para exibir o usuário com o id correspondente.

### FEATURE 04 - Criar um endpoint <code>/users/:id/edit</code> para editar o usuário com o id correspondente.

### FEATURE 05 - Criar um endpoint <code>/users/:id</code> em que seja possível deletar o usuário com o id correspondente.

### FEATURE 06 - Criar um endpoint <code>/microposts/new</code> para o cadastro de posts.

### FEATURE 07 - Criar um endpoint <code>/microposts</code> para listar todas os posts.

### FEATURE 08 - Criar um endpoint <code>/microposts/:id</code> para exibir o post com o id correspondente.

### FEATURE 09 - Criar um endpoint <code>/microposts/:id/edit</code> para editar o post com o id correspondente.

### FEATURE 10 - Criar um endpoint <code>/microposts/:id</code> para deletar o post com o id correspondente.

<br />

<hr>

# SETUP

## Sumário
- [1 - Iniciando o ambiente Ruby](#1---iniciando-o-ambiente-ruby)


<br />

<hr>

### <strong>1 - Iniciando o ambiente Ruby</strong>

  ```sh
    rails new Toy_App
  ```

  ```sh
    cd Toy_App
  ```

  ```sh
    bundle install --without production
  ```


 <br />

 ### <strong>2 - Sincronizando com o repositório remoto</strong>

  ```sh
    git init
  ```

  ```sh
    git add -A
  ```

  ```sh
    git commit -m 'Initialize repository'
  ```

  ```sh
    git remote add origin <endereço SSH>
  ```

  ```sh
    git branch -M main
  ```
  ```sh
    git push -u origin main
  ```

 <br />


