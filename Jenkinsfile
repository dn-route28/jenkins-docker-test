pipeline {
    agent {
        docker {
            image 'centos'
            label 'generic'
        } //docker
    } //agent
    stages {
        stage("Check hostname of docker container") {
            step {
                sh """
                    cat /etc/hostname
                """    
            } //steps
        } //stage
    } //stages
} //pipeline