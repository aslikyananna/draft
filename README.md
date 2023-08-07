# def replace(string, old, new):
#     new_string = ""
#     for old in string:
#         if old in string:
#             new_string= string.index(old)
#     return new_str
#
# print(replace("anna", "a", "b"))
# def isDigit(string):
#    x = string.encode()
#    for i in x:
#        if i in range(48,58):
#           return True
#        else:
#           return False
# print(isDigit("123"))

# def append(t, val):
#     t +=val,
#     return t
#
# t = (1,2,3)
# print(append(t,4))
#

#
#
# def insert(t, val, index):
#      dict = {}
#      for i in range(len(t)):
#         dict[i] = t[i]
#      print(dict)
#
# insert((1,2), 2,3)
#

# n = [1,2,6]
# n.extend([1,2,3],[7,8])
# print(n)
#
# def extend(t, iterable):
#     if not hasattr(iterable,"_iter_"):
#         raise ValueError("No")
# # help(extend())
#
# def sort(t):
#     tmp =  tuple()
#     for i in range(len(ls)-1):
#         for j in range(i,len(ls)):
#             if ls[i]>ls[j]:
#                tmp =tmp + ((ls[i+1],) + (ls[i],))
#             else:
#                 tmp += ((ls[i],) +(ls[i+1],))
#     return tmp
# ls = (7,8,9)
# print(sort((ls)))
#
#
# def bayt(number):
#     count = 0
#     while number!=0:
#         if number%2==1:
#             count+=1
#         number=number//2
#     return count
# print(bayt())
