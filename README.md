# python_work
# list
# Basic Template for List Iteration (whil
def list_template(L: list):
  answer = 0
  while L != []:
    ## work involving L[0] and updating answer
    L = L[1:]
  return answer
  # Basic Template for List Iteration (for loop)
  def list_template(L: list):
  answer = 0
  for val in L:
    ## work involving val and updating answer
  return answer
  import check

def my_sum(L: list[int]):
  """
  Returns the sum of elements in L
  
  Examples:
     my_sum([]) => 0
     my_sum([1,2,3]) => 6
  """
  answer = 0 
  while L != []:
    answer += L[0]
    L = L[1:]
  return answer
    
check.expect("Test1", my_sum([1, 2, 3]), 6)
