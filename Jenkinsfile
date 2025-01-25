pipeline{
    agent{label 'Linux'}
    stages{
        stage('clone ggit '){
            steps{
             git 'https://github.com/Manikanta937/ans_jen.git'
            }
        }
        stage('executing playbook'){
          steps{
            sh 'ansible-playbook -i inventory.ini playbook.yml --vault-password-file vault.pass'
    }
}
}
}
