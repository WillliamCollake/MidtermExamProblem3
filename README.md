# MidtermExamProblem3
Problem Number 3 Midterm

def evalQuadratic(a, b, c, x):
  '''
  a, b, c: numerical values for the coefficients of a quadratic equation
  x: numerical value at which to evaluate the quadratic.
  '''
  
  return a*x*x + b*x +c
  
def twoQuadratics(a1, b1, c1, x1, a2, b2, c2, x2):
  '''
  a1, b1, c1: one set of coefficients of a quadratic equation
  a2, b2, c2: another set of coefficients of a quadratic equation
  x1, x2: values at which to evaluate the quadratics
  '''
  x= evalQuadratic(a1, b1, c1, x1)
  y= evalQuadratic(a2, b2, c2, x2)
  
  print (x+y)
