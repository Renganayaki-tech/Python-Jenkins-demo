node {

    stage('Checkout') {
        checkout scm
    }

    stage('Show Files') {
        bat 'dir'
    }

    stage('Run Python') {
        bat '"C:\\Users\\DELL\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" app.py'
    }

}
