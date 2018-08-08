node{
    stage('scm'){
        git 'https://github.com/phani9398/game-of-life.git'
    }
    stage('package'){
        sh '/opt/apache-maven-3.5.3/bin/mvn clean package install'
    }
}     
