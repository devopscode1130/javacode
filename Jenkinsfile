pipeline {

    agent any

    stages {

        stage('get the code') {

            steps {

                sh 'echo "this will get me the code"'

                git 'https://github.com/devopscode1130/javacode'

            }

        }

        stage('second stage') {

            steps {

				sh 'echo "stage 2"'

               sh 'javac hellojava.java'

            }

        }

        stage('third stage') {

            steps {

				sh 'echo "stage 2"'

		sh 'java hellojava'

            }

        }

    }

}

