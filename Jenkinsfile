pipeline {
    agent {
        node {
            label 'int-jenkins02.dc1.lan'
        }
    }

    stages {
        stage('Detect') {
            steps {
                synopsys_detect '--detect.tools.excluded=POLARIS'
            }
        }
    }
}
