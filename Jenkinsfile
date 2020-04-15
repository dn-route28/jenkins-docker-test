pipeline {
    agent {
        docker {
            image 'centos'
            label 'generic'
        } //docker
    } //agent
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