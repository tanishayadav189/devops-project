pipeline {
agent any

```
stages {

    stage('Build Docker Image') {
        steps {
            bat 'docker build -t devops-project:v1 .'
        }
    }

    stage('Push Docker Image') {
        steps {
            withCredentials([usernamePassword(
                credentialsId: 'dockerhub-creds',
                usernameVariable: 'DOCKER_USER',
                passwordVariable: 'DOCKER_PASS'
            )]) {
                bat 'docker login -u %DOCKER_USER% -p %DOCKER_PASS%'
                bat 'docker tag devops-project:v1 %DOCKER_USER%/devops-project:v1'
                bat 'docker push %DOCKER_USER%/devops-project:v1'
            }
        }
    }

}
```

}

```
