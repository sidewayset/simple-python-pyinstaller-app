pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                docker {
                    image 'python:2-alpine' 
                }
            }
            steps {
                sh 'python -m py_compile C:\Users\vahmad01\Documents\Jenkins-Shnenigans\git-project\simple-python-pyinstaller-app\sources C:\Users\vahmad01\Documents\Jenkins-Shnenigans\git-project\simple-python-pyinstaller-app\sources\calc.py' 
            }
        }
    }
}