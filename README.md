# Elixir and Pheonix CRUD

### Install Elixir

Follow the Elixir install guide here: http://elixir-lang.org/install.html

### Install Phoenix

```bash
    $ mix archive.install https://github.com/phoenixframework/archives/raw/master/phx_new-1.3.0.ez
```

### PostgreSQL

Follow the instructions here: http://postgresguide.com/setup/install.html

Set up your database config by editing `config/dev.exs` and edit the username and password. 

### Other databases

If you choose to use another database provider, make sure you edit the configuration appropriately: https://phoenixframework.readme.io/docs/using-mysql

## Start Pheonix Server:

    ```bash
    $ mix phx.server
    ```

http://localhost:4000 from your browser.
