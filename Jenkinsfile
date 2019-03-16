node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval to deploy to QA'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
stage('Get approval to deploy to Dev'){
    input "Deploy to Dev?"
}
node {
    stage('deploy to dev'){
        echo "deploying"
    }
}
