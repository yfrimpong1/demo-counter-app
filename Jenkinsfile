pipeline{
    agent any
        stages{

            stage('Git Checkout'){
                steps{
                    git branch: 'main', url: 'https://github.com/yfrimpong1/demo-counter-app.git'
                }
            }

            stage('UNIT TEST'){
                steps{
                    sh 'mvn test'
                }
            }

        }
}