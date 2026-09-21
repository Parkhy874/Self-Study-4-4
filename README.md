# Self-Study-4-4
AI언어 교재 문제 풀이

ss = '파이썬은완전재미있어요'

sslen = len(ss)
for i in range(0, sslen):
    if i %2 == 0:
        print(ss[i], end = "")
    else:
        print("#", end = "")        
