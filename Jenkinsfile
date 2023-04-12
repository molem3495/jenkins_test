node {
    stage('Clone') {
         git branch: 'main', url: 'https://github.com/molem3495/jenkins_test.git'
    }
    stage('Build') {
    sh '''javac Main.java
       '''
    }
    stage('Run') {
    sh '''java Main
       '''
    }
}
