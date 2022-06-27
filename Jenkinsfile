//@Library('piper-lib-os') _

//node() {
  //stage('init') {
    //deleteDir()
    //checkout scm
  //}
  //stage('integrationArtifactDownload Command') {
	
	//  integrationArtifactDownload script: this
  //}
//}
@Library('piper-lib-os') _

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
  stage('integrationArtifactDownload Command') {
	
	  integrationArtifactDownload script: this
  }

  stage('uploadIntegrationArtifact Command') {
       integrationArtifactUpload script: this
  }

}
