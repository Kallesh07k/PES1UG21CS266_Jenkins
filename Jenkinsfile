pipeline {
  agent any
  stages {
//
          stage('Clone repository') {
//
            steps {
                    checkout([$class: 'GitSCM,
//                  
                    branches: [[name: '*/main']],
//
                    userRemoteConfigs: [[url: 'https://github.com/Kallesh07k/PES1UG21CS266_Jenkins.git']]])
//

}
//
}
stage('Build') {
steps {
build 'PES2UG19CS266-1'
sh 'g++ main.cpp-o output'
}
}
stage('Test') {
steps {
sh./output'
}
}
stage('Deploy') {
steps {
echo 'deploy'
}
}
}
post{
failure{
error 'Pipeline failed
}
}
}
