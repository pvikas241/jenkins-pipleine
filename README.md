# jenkins-pipleine

This repository contains a simple Jenkins pipeline (`Jenkinsfile`) demonstrating multiple stages, each echoing a different message.

## Pipeline Stages

1. **Hello**: Prints "Hello, World!"
2. **Greeting**: Prints "Greetings from Jenkins!"
3. **Message**: Prints a custom message.
4. **Farewell**: Prints "Goodbye from Jenkins!"

## Post Actions

- **Always**: Executes after all stages, regardless of success or failure.
- **Success**: Executes only if the pipeline succeeds.
- **Failure**: Executes only if the pipeline fails.

## Usage

1. Clone this repository to your local machine or Jenkins server.
2. Create a new pipeline job in Jenkins.
3. Point the job to the `Jenkinsfile` in this repository.
4. Run the job to see the pipeline in action.

Enjoy exploring Jenkins pipelines!
::contentReference[oaicite:5]{index=5}
 
