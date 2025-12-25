# architecture-tp29

A project containing a pricing microservice and related resources.

## Project Structure

```
architecture-tp29/
│
├── .idea/                   # IDE config files
│   ├── vcs.xml
│   └── workspace.xml
│
├── Screans/                 # Screenshots and images for documentation
│   ├── 1.png
│   └── 2.png
│
├── pricing-service/         # Main microservice: Pricing
│   ├── .gitattributes
│   ├── .gitignore
│   ├── Dockerfile
│   ├── mvnw
│   ├── mvnw.cmd
│   ├── pom.xml              # Maven project definition
│   ├── .mvn/                # Maven Wrapper files
│   └── src/                 # Java source code (not listed here)
│
```

## Pricing Service

The `pricing-service` directory contains a microservice for pricing operations, likely built in Java with Maven based on the presence of `pom.xml` and Maven Wrapper files. 

* To build the service:
  ```bash
  cd pricing-service
  ./mvnw clean package
  ```
* To run the service (locally or via Docker):
  ```bash
  # Using Docker
  docker build -t pricing-service .
  docker run -p 8080:8080 pricing-service
  ```

## Screans

The `Screans` folder contains images (`1.png`, `2.png`) which can be utilized for documentation, UI demonstration, or architectural diagrams.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/RadouaneAitSaid123/architecture-tp29.git
   ```
2. Refer to the `pricing-service/README.md` for service-specific details (if it exists, otherwise consult `pom.xml` and the source code).

## Contributions

Feel free to open issues or submit pull requests.

## License

Specify your project license here!