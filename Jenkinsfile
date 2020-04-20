pipeline{
    agent any
    stages{
        stage ("Build"){
            when{
               tag "Release-to-Prod" 
            }
            steps{
                echo "Building tags To Prod"
            }
        }
    }
}
