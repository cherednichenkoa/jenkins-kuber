node {
  def appName = 'jk8s'
  checkout scm
  stage 'Build image'
  def image = docker.build("my-image:${env.BUILD_ID}")
}
