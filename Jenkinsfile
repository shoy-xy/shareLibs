@Library('tools')

def tools = new org.devops.tools()

pipeline {
    agent { node { label "master"}}

    stages {
    	stage("test") {
            steps {
	        tools.printStr("aaa")
            }

        }
    }
}
