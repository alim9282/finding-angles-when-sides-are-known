# finding-angles-when-sides-are-known
import math
a = float(input("lenath of a:"))
b = float(input("length of b:"))
c = float(input("length of c:"))

angelc = math.acos((c*c-a*a-b*b)/(-2*a*b))
angelc = angelc*(180/math.pi)
angela = math.acos((a*a-c*c-b*b)/(-2*c*b))
angela = angela*(180/math.pi)
angelb = math.acos((b*b-a*a-c*c)/(-2*a*c))
angelb = angelb*(180/math.pi)
print(angelc)
print(angela)
print(angelb)
total = angela+angelb+angelc
print(total)
