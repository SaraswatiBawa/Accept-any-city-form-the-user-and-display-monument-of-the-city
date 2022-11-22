# Accept-any-city-form-the-user-and-display-monument-of-the-city

choice=str(input("Enter the city for the Monument:\n(1)Delhi(2)Agra(3)Jaipur: "))

if(choice=="Delhi"):
    print("RedFort")
elif(choice=="Agra"):
    print("Taj Mahal")
elif(choice=="Jaipur"):
    print("Jal Mahal")
else:
    print("City Not Exist.")
