pipeline {
agent any
stages {
  stage('Build') {
    steps {
      echo 'Démarrage du build...'
    }
  }
  stage('test') {
    steps {
      script {
         if(fileExists 'index.html') {
            echo 'Le fichier HTML existe bien...'
          } else {
             echo 'Le fichier est manquant...'
         }
      }
    }
  }
}
}
