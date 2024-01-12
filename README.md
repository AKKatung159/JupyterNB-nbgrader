# Jupyter Notebook with nbgrader Docker Setup using Docker Compose

This repository provides a Docker Compose setup for running Jupyter Notebook with nbgrader installed.

## Installation

To set up the Jupyter Notebook environment with nbgrader using Docker Compose, follow the steps below:

### Prerequisites

- Docker and Docker Compose installed on your machine. If not installed, you can download and install Docker Desktop which includes Docker Compose from [Docker's official website](https://www.docker.com/products/docker-desktop).

### Steps

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```

    Navigate to the cloned repository:

    ```bash
    cd your-repository
    ```

2. Build and run the Docker containers using Docker Compose:

    ```bash
    docker-compose up -d --build
    ```

3. Once the containers are up and running, open your web browser and navigate to:

    ```
    http://localhost:8888/
    ```

    You should see the Jupyter Notebook interface.
## Additional Information
For more information on using nbgrader, refer to the [nbgrader documentation](https://nbgrader.readthedocs.io/en/stable/).

---
### By. AK KATUNG