print("*** TorKham HanSaa ***")
ip = input("Enter Input : ").split(",")
index = 0
cindex = 0
colec = []
while ip[index][0] != "X" and index < len(ip) :
    if ip[index][0] == "P" :
        colec.append(ip[index][2:len(ip[index])])
        cindex = len(colec) - 1
        if len(colec) == 1 :
            print(f"'{colec[cindex]}' -> {colec}")
        else :
            if colec[cindex][0:2].upper() == colec[cindex-1][-2:len(colec[cindex-1])].upper() :
                print(f"'{colec[cindex]}' -> {colec}")
            else : print(f"'{colec[cindex]}' -> game over")

    elif ip[index][0] == "R" :
        colec = []
        checkindex = 0
        print("game restarted")
    else :
        print(f"'{ip[index]}' is Invalid Input !!!")
        exit()
    index += 1
