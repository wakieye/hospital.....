full_name= 'John smith'
age= 20
is_new_patient= False
is_not_new_patient=True
if is_new_patient :
    print(full_name)
    print(age )
    print("welcome to santa maria hospital")
    print("thank you for choosing this hospital,you have been served by")
    print(input('name of doctor assigned'))
    print('we wish you a quick recovery ')
    print('have a nice day ahead of you')
    print('in case of any emergency contact us , our emergency contact number is' + input('enter phone number'))
elif is_not_new_patient:
    print("welcome back " + full_name)
    print("age")
    print("have our services satisfied you")
    print(input('name of doctor assigned' + "has been happy working with you sir"))
    print('we wish you a quick recovery ')
    print('have a nice day ahead of you')
    print('in case of any emergency contact us , our emergency contact number is' + input('enter phone number'))
else:
    print('we wish you a quick recovery ')
    print('have a nice day ahead of you')
    print('in case of any emergency contact us , our emergency contact number is' + input('enter phone number'))
