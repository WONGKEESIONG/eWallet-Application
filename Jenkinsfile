pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('C:/Users/sqkswong/Downloads/build.bat'){
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqkswong/Downloads/build.bat'
            }
        }
        stage('Test') {
            steps {
                dir('C:/Users/sqkswong/Downloads/test.bat'){
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqkswong/Downloads/test.bat'
            }
        }
        stage('Package') {
            steps {
                dir('C:/Users/sqkswong/Downloads/package.bat'){
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqkswong/Downloads/package.bat'
            }
        }
        stage('Deploy') {
            steps {
                dir('C:/Users/sqkswong/Downloads/deploy.bat'){
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqkswong/Downloads/deploy.bat'
            }
        }
    }
}
