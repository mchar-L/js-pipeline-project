 pipeline {

 agent any

 stages {

 stage("build") {

 steps {

 echo 'building the applicaiton...'

 }

 }

 stage("test") {

 steps {

 echo 'testing the applicaiton...'

 }

 }

 stage("deploy") {

 steps {

 echo 'deploying the applicaiton...'

 }

 }

}

 post {

 }

 }

 git push

 always {

 echo 'building..'

 }

 success {

            echo 'success'

 }

 failure {

            echo 'failure'

 }

 }

}
