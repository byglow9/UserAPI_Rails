# User Registration API

This API is built with Rails for user registration. It allows creating, viewing, updating, and deleting users.

## Technologies Used

- **Ruby version:** 3.2.2
- **Rails version:** 7.1.3.4
- **Database:** PostgreSQL


## Configuration

To set up the system on your computer, you need to have Ruby and Rails configured.

Follow the steps below to set up the system on your computer:



1. Clone the repository:
    ```sh
    git clone https://github.com/byglow9/UserAPI_Rails.git
    cd UserAPI_Rails
    ```

2. Install all Rails dependencies (gems):
    ```sh
    bundle install
    ```

3. Configure the `database.yml` file in the `config` folder with your username and password.

4. With the database configured, create the database:
    ```sh
    rails db:create
    ```

5. Run the migrations:
    ```sh
    rails db:migrate
    ```

6. Install Action Text and Active Storage:
    ```sh
    rails action_text:install
    rails active_storage:install
    rails db:migrate
    ```

