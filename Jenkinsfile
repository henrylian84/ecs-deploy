node {
    stage("clone repo"){
        echo "clone repo starts"
        checkout scm
        sh 'git submodule update --init --recursive'
    }

    stage("compile"){
        echo "compiling starts"

    }

    stage("build docker"){
        echo "building docker"
    }

    stage("pushing to ecs"){

    }

}