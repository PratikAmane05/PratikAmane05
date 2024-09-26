def swap_case(string):
    a=[]
    for i in s:
        if(i.islower()):
            a.append(i.upper())
        else:
            a.append(i.lower())
    return ''.join(a)
