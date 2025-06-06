# Backend

Spring Boot REST API for coastal change prediction.

## Build & Run

```bash
cd backend
./gradlew build
java -jar build/libs/*.jar
```

## API Docs

Javadoc is generated with:

```bash
cd backend
./gradlew javadoc
```

Docs output: `build/docs/javadoc/index.html`

## Diagnostics

- Uses SLF4J for logging (see logs for errors/warnings).
- Helper libraries: Apache Commons Lang, Lombok (for code clarity).
