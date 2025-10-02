pipeline{
  agent any
  stages{
    stage('Build'){steps{echo 'Task: Compile & package | Tool: Maven'}}
    stage('Unit & Integration Tests'){steps{echo 'Task: Run unit+integration tests | Tool: JUnit/Jest'}}
    stage('Code Analysis'){steps{echo 'Task: Static analysis | Tool: SonarQube'}}
    stage('Security Scan'){steps{echo 'Task: Dependency & SAST scan | Tool: npm audit'}}
    stage('Deploy to Staging'){steps{echo 'Task: Deploy app to staging | Tool: Docker/K8s'}}
    stage('Integration Tests on Staging'){steps{echo 'Task: Run integration tests | Tool: Postman/newman'}}
    stage('Deploy to Production'){steps{echo 'Task: Deploy app to production | Tool: Kubernetes'}}
  }
}
