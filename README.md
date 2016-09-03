Run and experiment with the [IBM Swift Kitura Sample](https://github.com/IBM-Swift/Kitura-Sample) in Docker.

Clone this repository, cd into the root directory, and run `docker-compose up`.

Connect to the Kitura Sample at http://127.0.0.1:38090.

The local src folder will be mapped to the Docker container.
Changes to the code in the src folder will be monitored by the Docker process, re-compiled, and the process restarted.
