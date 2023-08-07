print("WELCOME TO KBC(KAUN BANEGA CROREPATI)")

print("\n \nYOU WILL GET 4 OPTIONS AND IF YOU ANSWER THE CORRECT OPTION YOU WILL MOVE TO THE NEXT QUESTION, BUT IF YOU GIVE THE WRONG ANSWER YOU WILL BE DISQUALIFIED")

print("\nSO LETS BEGIN WITH THE GAME")

i=0
money_won=0

# def money_win(a):
  # sum= money_won+ a
  # print(sum)

while i==0:
  print("\nQ1- WHAT IS THE CAPITAL OF INDIA")
  print("    a- PUNJAB         b- DELHI")
  print("    c- HARYANA        d- UTTAR PRADESH")

  
  option= input("ENTER THE ANSWER: ")
  
  if option=="b" or option=="2" or option=="B":
    print("\nCORRECT ANSWER")


    money_won= money_won+ 10000
    print("\nYOU WON ", money_won, "RUPEES")

    # money_win(10000)
    # print("\nYOU WON ", money_win, "RUPEES")
    

    print("\nLETS MOVE ON TO THE NEXT QUESTION")
    # money_won= money_won+ 10000
    # print("\nYOU WON ", money_won, "RUPEES")
    i=i+1

  else: 
    print("YOU ARE WRONG")
    print("\nTHE CORRECT ANSWER IS DELHI")
    print("\nBETTER LUCK NEXT TIME")

    break

  print("\nQ2- WHO IS THE PRESIDENT OF INDIA? ")
  print("    a- DROUPADI MURMU         b- NARENDRA MODI")
  print("    c- RAM NATH KOVIND        d- PRANAB MUKHERJEE")

  option= input("ENTER THE ANSWER: ")


  if (option=="A" or option=="1" or option=="a"):
    print("\nCORRECT ANSWER")


    # print("\nYOU WON 50,000 RUPEES")
    money_won= money_won + (40000)
    print("\nYOU WON ", money_won, "RUPEES")  


    print("\nLETS MOVE ON TO THE NEXT QUESTION")
    # money_won= money_won + (40000)
    # print("\nYOU WON ", money_won, "RUPEES")  

  
  
  else:
    print("YOU ARE WRONG")
    print("\nTHE CORRECT ANSWER IS DROUPADI MURMU")
    print("\nBETTER LUCK NEXT TIME")
    break

# print("Q3- WHAT IS THE NATIONAL BIRD OF INDIA?    \na- PIEGON     b-WOODPECKER    \nc- PEACOCK    d- OWL")

  print("Q3- WHAT IS THE NATIONAL BIRD OF INDIA?")
  print("    a- PIEGON         b- WOODPECKER")
  print("    c- PEACOCK        d- OWL")

  option= input("ENTER THE ANSWER: ")

  if (option=="c" or option=="2" or option=="C"):
    print("\nCORRECT ANSWER")
    money_won= money_won+ 100000
    print("\nYOU WON ", money_won, "RUPEES")
    print("\nLETS MOVE ON TO THE NEXT QUESION")

  else:
    print("YOU ARE WRONG")
    print("\nTHE CORRECT ANSWER IS PEACOCK")
    print("\nBETTER LUCK NEXT TIME")
    break

      

print("\nTHANKS FOR PLAYING THIS GAME")
    
