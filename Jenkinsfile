pipline{
    agent any 
    stages{
        steps("compile"){
            sh 'javac Test.java'
        }
    }
    stages{
        steps("run"){
            sh 'java Test'
        }
    }
}