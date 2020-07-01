pipeline {
    agent any
    stages {
         stage('Lint HTML') {
              steps {
                  sh 'tidy -q -e *.html'
        }
         }
         stage('Upload to AWS') {
                 sh 'echo "Hello World"'
                 sh '''
                     echo "Multiline shell steps works too"
                     ls -lah
                 '''
          }
        }
}
