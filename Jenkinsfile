node {
    stage('Example') {
        if (env.BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'
        } else {
            echo 'I execute elsewhere'
        }
    }
}
/*pipeline {
    agent any
    stages {
        stage('Example') {
            input {
                message "Can we Proceed?"
                ok "Yes"
                parameters {
                    string(name: 'PERSON', defaultValue: 'SEF20', description: 'Member')
                }
            }
            steps {
                echo "${PERSON}, is proceeding..."
            }
        }
    }
}*/
