# Key Commands:

## Docker Commands & Process

### Fell free to clone the repo

1. **Create Project Folder:**
    ``` sh
    mkdir devops_demo
    cd devops_demo
    ```
<b><i>Create the files needed in project</i></b>

2. **Create & Activate Virtual Env.:**
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```
3. **Installing Packages:**
    ```sh 
    touch requirements.txt
    pip install <package_name>
    pip freeze > requirements.txt
    ```
4. **Running Pytest (Local):**
    ```sh
    pytest
    ```

5. **Building Docker:**
    ```sh
    docker build -t <image_name> .
    docker run <image_name>
    ```

6. **Running Pytest (Docker):**
    ```sh
    docker run <image_name> -m pytest
    ```

7. **Pushing to Docker:**
1. Create Docker repository on https://hub.docker.com/ 
    ```sh 
    docker build -t <docker_username>/<repository_name> .
    docker push <docker_username>/<repository_name>
    ```

8. **Github Secrets:**
- Located in Github repository
    - Settings > Environments > Environment secrets

9. **Docker Tokens:**
- Located in Docker account 
    - My Profile > Edit profile > Security > New Access Token


## Command Line Commands:

1. **Installation:**
    ```sh
    pip3 install virtualenv
    ```

2. **Activating Virtual Environment:**
    ```sh
    source venv/bin/activate
    ```

3. **Installing Dependencies:**
    ```sh
    pip3 install -r requirements.txt
    ```

4. **Updating Requirements File:**
    ```sh
    pip3 freeze > requirements.txt
    ```
