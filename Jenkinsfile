node('built-in') {
    stage('continous download_master') {
		git 'https://github.com/msdeepak052/Maven_Project.git'
	}
	stage('continous build_master') {
		sh 'mvn package'
	}
}

