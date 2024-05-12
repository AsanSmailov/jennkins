pipeline{
    agent any
    stages{
        stage('Print Info'){
            steps{
                sh 'echo "Branch: $(git rev-parse --abbrev-ref HEAD)"'
                sh 'echo "Hash: $(git rev-parse HEAD)"'
                sh 'echo "g++ version: $(g++ --version)"'
            }
        }
      }
}
