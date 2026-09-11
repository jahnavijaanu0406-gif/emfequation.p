# emfequation.p
emf equation calculation in python 
P = int(input("Enter number of poles (P): "))
phi = float(input("Enter flux per pole in Weber (Φ): "))
Z = int(input("Enter total armature conductors (Z): "))
N = float(input("Enter speed in RPM (N): "))
A = int(input("Enter number of parallel paths (A): "))

Eg = (P * phi * Z * N) / (60 * A)

print("Generated EMF = {:.2f} V".format(Eg))