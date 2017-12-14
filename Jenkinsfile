node('master'){
  checkout scm
  git url: 'https://github.com/vishnunc/pipelines.git'
  def a=load ('pipelines/sample.groovy')
  a.prep()
  a.build()
  a.unittest()
}
