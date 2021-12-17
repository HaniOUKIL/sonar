node {
        stage('Clone') {
            git 'https://github.com/HaniOUKIL/sonar.git'
        }
        stage('Build') {
            sh label: '', script: 'mvn clean package'
        }
        stage('Run') {
            sh label: '', script: 'mvn clean run'
        }
}

