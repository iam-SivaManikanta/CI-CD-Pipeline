pipeline{
    agent{label 'Linux'}
    stages{
        stage('clone git '){
            steps{
             git 'https://github.com/Manikanta937/ans_jen.git'
            }
        }
        stage('executing playbook'){
          steps{
            sh 'ansible-playbook playbook.yml'
    }
}
}
}
