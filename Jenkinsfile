@Library('jenkins-shared-lib')
pipeline {
    agent any

    stages{

        stage('Git Checkout'){
            gitCheckout(
                branch: "master",
                url: "https://github.com/yogeshk04/hello-springboot.git"
            )
        }
    }
}