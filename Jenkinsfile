pipeline {
    agent {
        docker {
            image 'centos'
            label 'generic'
        }
    }
    stages {
        stage("Check hostname of docker contaniner") {
            step {
                sh """
                    cat /etc/hostname
                """    
            } //steps
        } //stage
    } //stages
} //pipeline