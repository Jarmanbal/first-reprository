# first-reprository
it is a python code
"""regular expression set is the set of experssion kept inside the square braces with special meanings
(a)[arn] it returns the match where one of the specified character has a match"""
import re
s="India is a Asian Country"
x=re.findall("[arn]",s)
print(x)

#(b)[a-n] it returns the match for any lowercase letter alphabetically between a to n
s="India is a Asian Country"
x=re.findall("[a-n]",s)
print(x)
#C)[^arn] it will returns all characters except arn
s="India is a Asian Country"
x=re.findall("[^arn]",s)
print(x)
#(d)[0123]it returns the match where any of the specified digits are present
s="India is a Asian Country hosting G20 nation meeting"
x=re.findall("[0123]",s)
print(x)
#(E)[0-9]:return all the ,match specified in digits from 0-9
s="099454855476244"
x=re.findall("[0-9]",s)
print(x)
