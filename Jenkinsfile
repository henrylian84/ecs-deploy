node {
    stage("clone repo"){
        echo "clone repo"
        checkout scm
    }

    stage("compile"){
        echo "compiling the source code"
        sh './gradlew clean build'
    }

    stage("build docker"){
        echo "building docker"
        def app = docker.build "henrylian/springbootdemo:${env.BUILD_NUMBER}"
        app.push 'latest'
    }

    stage("deploy"){
        echo "deploying to aws_ass2"
    }
    
}