

## Run `Quick_Skill` Locally
1. Make sure you have Docker, Docker Compose, NodeJS and vite installed on your machine.

2. Clone the repository:
    ```bash
    git clone  https://github.com/Dhanvin-Murkute/Quick_Skill.git

    ```

3. Change the directory:
    ```bash
    cd Quick_Skill
    ```

4. Run the following command to start the backend:
    ```bash
    docker-compose up [-d]
    ```
    The -d flag is optional and it runs the containers in the background. 
    Backend should be now available at `http://localhost:4444`.

5. Change the directory to the frontend:
    ```bash
    cd frontend
    ```

6. Install the dependencies:
    ```bash
    npm install
    ```

7. Start the frontend:
    ```bash
    vite
    ```

8. Open your browser and go to `http://localhost:5173`.

9. You can use the following credentials to log in:
    - user:
        - username: user
        - password: user1234
    - admin:
        - username: admin
        - password: admin1234
