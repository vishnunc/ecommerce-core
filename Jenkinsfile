node('any'){
  checkout scm
  def a=load ('sample.groovy')
  a.prep()
}
node('any'){
  checkout scm
  def a=load ('sample.groovy')
  a.build()
}
