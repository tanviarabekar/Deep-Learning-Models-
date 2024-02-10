# Deep-Learning-Models-
Scalars Vectors Tensor Matrix Properties Implementation Using Different Libraries
import numpy as np

# Creating Scalars in NumPy
scalar_np1 = np.array(5)
scalar_np2 = np.array(3)

# Addition
result_add_np = scalar_np1 + scalar_np2
print("Addition using NumPy:", result_add_np)

# Subtraction
result_sub_np = scalar_np1 - scalar_np2
print("Subtraction using NumPy:", result_sub_np)
import numpy as np

# Scalars in NumPy
scalar_np1 = np.array(5)
scalar_np2 = np.array(3)
scalar_np3 = np.array(2)

# Associativity of Addition
result_associativity_np = (scalar_np1 + scalar_np2) + scalar_np3

# Commutativity of Addition
result_commutativity_np = scalar_np1 + scalar_np2

# Distributivity of Addition
result_distributivity_np = scalar_np1 * (scalar_np2 + scalar_np3)

# Identity Element of Addition
identity_element = np.array(0)
result_identity_np = scalar_np1 + identity_element

print("Associativity of Addition (NumPy):", result_associativity_np)
print("Commutativity of Addition (NumPy):", result_commutativity_np)
print("Distributivity of Addition (NumPy):", result_distributivity_np)
print("Identity Element of Addition (NumPy):", result_identity_np)
