# python-lessons-N-3
   "Das-4"
            "N-1"
                "variant-1"
                def hashvich_for_string(bar):
                     a = len(bar)
                     print(a)
                hashvich_for_string("aytsexjyur")

                "variant-2"
                def hashvich_2(bar):
                    count = 0
                    for a in bar:
                        count += 1
                    print(count)
                hashvich_2("hashvich")


            "N-2"
                 def control_for_hashvich(symbols):
                     stop = int(input("input stop point: "))
                     i = 0
                     while i <= stop:
                         i += 1
                         a = symbols % 10
                         print(a)
                         symbols = symbols // 10
                     return symbols
                control_for_hashvich(157468952357468521457)

            "N-3"
                def fact(tiv):
                    count = 1
                    for i in range(1, tiv+1):
                        count *= i
                    print(count)
                fact(int(input("input the num: ")))


            "N-4"
                def stugum(tiv):
                    if tiv % 2 == 0:
                        a = True
                        print(a)
                    else:
                        a = False
                        print(a)
                    return tiv




                def stugman_stugum(tiv):
                    stugum_2 = stugum(tiv)
                    avelacum = tiv ** 3
                    print(avelacum)
                stugman_stugum(int(input("input num: ")))
