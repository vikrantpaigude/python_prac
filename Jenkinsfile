pipeline{
    agent any
    //options{
       // skipDefaultCheckout()
    //}
    stages{
        stage('Build'){
            when{
                buildingTag()
            }
            steps{
                echo "In build zone"
            }
        }
    }
}
