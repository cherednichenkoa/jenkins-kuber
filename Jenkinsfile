node {
  def appName = 'jk8s'
  checkout scm
  stage 'Build image'
  sh("docker build -t 'version-1' .")
}
