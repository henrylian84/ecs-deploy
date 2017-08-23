node {
    stage "Hello world"
    echo "Hello World"

    stage "build"
    build "BuildJob"

    stage "test"
    build "TestJob"

    stage "deploy"
    build "DeployJob"

    stage 'Goodbye world'
    echo "Goodbye world"
}