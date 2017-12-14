node('master'){
  checkout scm
  dir('scripts') {
  git url: 'https://github.com/vishnunc/pipelines.git'
  }
  def a=load ('scripts/sample.groovy')
  a.prep()
  a.build()
  a.unittest()
}
