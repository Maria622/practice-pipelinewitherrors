pipeline {
  agent any
  stages {
    stage("Build") {
      steps {
        echo "Compilando..."
        sh 'gcc main.c -o main' // Pero no existe main.c
      }
    }
    stage("Test") {
      steps {
        sh 'chmod +x test.sh'
        sh './test.sh' // test.sh no es ejecutable
      }
    }
  }
}
