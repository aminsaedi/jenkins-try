pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                echo "========executing A========"
                echo "Amin Saedi"
            }
        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}