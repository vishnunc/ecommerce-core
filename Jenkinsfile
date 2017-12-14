node('master'){
  checkout scm
  git url: 'https://github.com/vishnunc/pipelines.git'
  def a=load ('sample.groovy')
  a.prep()
  a.build()
}
