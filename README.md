# Buo.Readme
# Define a class called Square
class Square:
  # Define a constructor method that takes an optional size parameter
  def __init__(self, size=0):
    # The same code as before
    ...

  # Define a method called area that takes no parameters
  def area(self):
    """This is a method that returns the area of the square

    Returns:
      The area of the square as an integer
    """
    # Calculate the area by multiplying the size attribute by itself
    area = self.size * self.size
    # Return the area
    return area
