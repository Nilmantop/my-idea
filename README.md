I am Nilmadhab I am going to show you my trigonometric calcultor here
def main():
    import math
    trig = input('do cos sine tan ')
    if trig == 'si' or trig == 'sin':
        a = eval(input('what?'))
        result = math.sin(math.radians(a))
        print('answer ' +str(round(result,3)))
        main()
    elif trig == 'cos' or trig == 'cosine':
        a = eval(input('what?'))
        result = math.cos(math.radians(a))
        print('answer ' +str(round(result,3)))
        main()
    elif trig == 'tan' or trig == 'tang':
        a = eval(input('what?'))
        result = math.tan(math.radians(a))
        print('answer ' +str(round(result,3)))
        main()
    else:
        print('fuck')
        main()
        
main()
