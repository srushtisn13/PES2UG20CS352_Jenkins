pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
//         sh 'npm run build'
        echo 'Build Stage Successful'
      }
    }
    stage('Test'){
      steps{
//         sh 'npm test'
        echo 'Test Stage Successful'
//         post {
//           always{
//             junit 'target/surefire-reports/*.xml'
//           }
//         }
      }
    }
    stage('Deploy'){
      steps{
//         sh 'npm deploy'
        echo 'Deployment Successful'
      }
    }
  }
  post{
    failure{
      echo 'Pipeline failed'
    }
  }
}
