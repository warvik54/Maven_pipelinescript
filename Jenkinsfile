pipeline {
        agent any
        stages {
 	stage ("Compile"){
	steps {
		sh "mvn compile"
	}
	}
	stage ("Unit Test"){
	steps {
		sh "mvn test"
	}
	}
	}
	}
