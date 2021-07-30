node("worker1") {
	def APPNAME = "sample-c";
	def SONAR_URL = "192.168.122.214:9000";

	stage("Checkout code") {
        checkout scm
	}
	stage("Run a CPP Check") {
			sh """
				cppcheck --xml --xml-version=2 . 2> cppcheck.xml
			"""
			    echo "Checked Successfully - Please see output for Results"
			}

	stage("Run Twistlock") {
#        twistlockPublish(
#            dockerAddress: "unix:///var/run/docker.sock",
#            ignoreImageBuildTime: true,
#            image: "${NEXUS_URL}/${DOCKER_IMAGE}:latest",
#            logLevel: "true",
#            timeout: 10)
	}
}
