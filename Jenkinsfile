pipeline{
    agent{
        label "windows"
    }
    options{
        buildDiscarder logRotater(artifactDaysToKeepStr:'',artifactNumToKeepStr:'5',daysToKeepStr:'',numToKeepStr:'5')
        disableConcurrentBuilds()
    }
    stages{
        stage('Hello'){
            steps{
                echo "hello"
            }
        }
    }
}