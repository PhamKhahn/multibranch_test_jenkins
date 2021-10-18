
pipeline {
    agent any
    environment {
        AGE = 15
        NAME = "Pham Quoc Khanh"
    }
    parameters {
        choice choices: ['a', 'b', 'c'], description: 'HI Hie', name: 'HI'
        string defaultValue: 'develop', description: 'Fill  your branch deploy', name: 'git branch', trim: true
}

    
    stages {
        stage('Test') {
            steps {
                /* `make check` returns non-zero on test failures,
                * using `true` to allow the Pipeline to continue nonetheless
                */
                sh 'printenv'
            }
        }


    }
}






































