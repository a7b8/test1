node {
    stage("Checkout") {
        deleteDir()
        git "https://github.com/a7b8/test1.git"
    }
    
    stage("Build") {
        sh "echo Building ${BUILD_ID} build"
    }
    
    stage("Testing") {
        sh "echo Testing on ${NODE_NAME}"
    }
    
    stage("Delivery") {
        sh "echo Pulling on registry......."
    }
    
}
