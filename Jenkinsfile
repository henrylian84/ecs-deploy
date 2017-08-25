node {
    stage("clone repo"){
        echo "clone repo"
        checkout scm
    }

    stage("compile"){
        echo "compiling the source code"
        sh 'gradlew build'
    }

    stage("build docker"){
        echo "building docker"
    }

    stage("deploy"){
        echo "deploying to aws_ass2"
    }
    
}