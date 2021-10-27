pipeline{
    agent any
    triggers {
      pollSCM '* * * * *'
    }
    stages{
        stage("SCM"){
            steps{
               echo "job ran..only 1 time"
            }
        }
    }
}
