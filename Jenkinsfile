node ('docker'){
    stage ("Build"){
    checkout scm

    sh """
        docker build -t iljailz/flaskex .
    """
    }
}