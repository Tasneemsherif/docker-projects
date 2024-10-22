
# Basic Dockerfile Project

This project contains a Dockerfile that builds a Docker image, which prints "Hello, Captain!" to the console when run.

## Project Structure

- **Dockerfile**: Contains the instructions to build the Docker image.

## How to Build and Run the Docker Image

1. **Clone the repository** (or navigate to your project directory where the Dockerfile is located).

2. **Build the Docker Image**:
   - Open a terminal and run the following command to build the image:
     ```bash
     docker build -t hello-captain .
     ```

3. **Run the Docker Image**:
   - After building, run the image with:
     ```bash
     docker run hello-captain
     ```
   This will print:
   ```
   Hello, Captain!
   ```

## project url
https://roadmap.sh/projects/basic-dockerfile

## License

This project is open-source and available under the MIT License.