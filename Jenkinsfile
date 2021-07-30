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

#	stage("Run Stage2") {
#			sh """
#				cppcheck --xml --xml-version=2 . 2> cppcheck.xml
#			"""
#			    echo "Checked Successfully - Please see output for Results"
#			}

}
