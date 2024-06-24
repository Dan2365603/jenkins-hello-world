pipeline {
          agent any
          environment {
                PYTHON_HOME = 'C:\Users\a7200\AppData\Local\Programs\Python\Python312' 
                PATH = "${env.PYTHON_HOME}\\;${env.PATH}"
          }
          stages {
              stage('Build') {
                  steps {
                      script {
                          // Choisissez la commande en fonction de votre script
                          bat 'python hello.py' // Pour Python
                          // sh 'javac HelloWorld.java && java HelloWorld' // Pour Java
                      }
                  }
              }
          }
      }
