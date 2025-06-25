# Java Gradle DevOps

## Build & Test

To build the project:
```sh
./gradlew build
```

To run tests:
```sh
./gradlew test
```

## CI/CD

This project uses [GitHub Actions](.github/workflows/gradle.yml) to automatically build and test the project on every push and pull request to the `main` branch.

## Dependency Management

Dependencies are managed using Gradle and a version catalog (`gradle/libs.versions.toml`).

## DevOps Principles Applied
- **Automation:** Builds and tests are automated with Gradle and GitHub Actions.
- **Continuous Integration:** Every change is validated by CI before merging.
- **Version Control:** All code and configuration are tracked in Git.
- **Documentation:** This README explains setup and DevOps practices. 
