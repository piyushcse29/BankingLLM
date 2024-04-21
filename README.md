# BankingLLM


## Getting Started

1. Clone the repository:
    ```
    git clone git@github.com:piyushcse29/BankingLLM.git
    ```

2. Navigate to the project directory:
    ```
    cd prototype
    ```

3. Install the required Python packages:
    ```
    pip install -r requirements.txt
    ```

## Running the Docker File

1. Build the Docker image. Replace `<image-name>` with the name you want to give to your Docker image:
    ```
    docker build -t <image-name> .
    ```

2. Run the Docker container. Replace `<image-name>` with the name of your Docker image:
    ```
    docker run -p 7860:7860 <image-name>
    ```

The application should now be running at `http://localhost:7860`.