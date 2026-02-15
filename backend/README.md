# Project Planner Backend

Spring Boot application for generating project boards using OpenAI and Jira.

## Structure

```
backend/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── noelnp/
│   │   │           └── projectplanner/
│   │   │               ├── ProjectPlannerApplication.java
│   │   │               ├── config/
│   │   │               ├── controller/
│   │   │               ├── service/
│   │   │               ├── model/
│   │   │               ├── exception/
│   │   │               └── util/
│   │   └── resources/
│   │       ├── application.yml
│   │       ├── application-dev.yml
│   │       ├── application-prod.yml
│   │       └── prompts/
│   └── test/
│       └── java/
│           └── com/
│               └── noelnp/
│                   └── projectplanner/
│                       ├── service/
│                       └── integration/
├── build.gradle
└── .env.example
```

## Setup

1. Copy `.env.example` to `.env` and fill in your API keys
2. Build the project: `./gradlew build`
3. Run the application: `./gradlew bootRun`

## Configuration

See `application.yml` for application configuration.
