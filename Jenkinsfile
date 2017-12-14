node('master'){
  checkout scm
  git url: 'https://github.com/vishnunc/pipelines.git'
  def a=load ('sample.groovy')
  parallel(
  a.prep(),
    a.build())
}
