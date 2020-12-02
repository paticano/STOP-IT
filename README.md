# STOP-IT

def main():
    print('Welcome! YOU ARE NOT ALONE\n')
    print('\nSign in if you want to stop bullying')
    userdict={}
    mail = input('\nenter you email')
    password = input('\nenter you password')
    userdict[mail]=password
    print('\nChoose from the following options: \n1. You need to contact immediate help.'
          '\n2. Information \n3. You are witness of bullying'
          ' \n4. You suffer bullying ')
    option = input('\nPlease enter the option number: ')
    useroption=[]
    useroption.append(option)
    try:
        option = int(option)
        if 0 < option < 5:
            if option ==1:
                print('\nWe are here to help you!')
                print('\nYou are not alone!')
                print('\n Please call this number as soon as possible and someone will assist you : '
                      '1-800-273-TALK (8255)')
            elif option == 2:
                print('\nYou will receive information about bullying')
                print('\nWhich type of bullying do you want to have information about')
                print('ºnChoose from the following options: \n1. Sexual Bullying'
                      ' \n2. Prejudicial Bullying \n3. Verbal Bullying \n4. Relational Agressive \n5. Physical Bullying'
                      '\n6. Cyberbullying ')
                type = int(input('\nPlease enter the option number: '))
                useroption.append(type)
                if type == 1:
                    print('Sexual bullying consists of repeated, harmful, and humiliating actions that target a person sexually. '
                          'Examples include sexual name-calling, crude comments, vulgar gestures, uninvited touching, sexual propositioning, and pornographic materials.'
                          ' A bully might make a crude comment about a peers appearance, attractiveness, sexual development, or sexual activity')
                elif type == 2:
                    print('Prejudicial bullying is based on prejudices tweens and teens have toward people of different races, religions, or sexual orientation.'
                          ' This type of bullying can encompass all the other types of bullying.'
                          ' When prejudicial bullying occurs, kids are targeting others who are different from them and singling them out.')
                elif type == 3:
                    print('Perpetrators of verbal bullying use words, statements, and name-calling to gain power and control over a target. '
                          'Typically, verbal bullies will use relentless insults to belittle, demean, and hurt another person. '
                          'They choose their targets based on the way they look, act, or behave. It’s also common for verbal bullies to target kids with special needs.')
                elif type == 4:
                    print('Relational bullying is a sneaky and insidious type of bullying that often goes unnoticed by parents and teachers. '
                          'Sometimes referred to as emotional bullying, '
                          'relational aggression is a type of social manipulation where tweens and teens try to hurt their peers or sabotage their social standing.')
                elif type == 5:
                    print('Physical bullying is the most obvious form of bullying. It occurs when kids use physical actions to gain power and control over their targets. '
                          'Physical bullies tend to be bigger, stronger, and more aggressive than their peers. '
                          'Examples of physical bullying include kicking, hitting, punching, slapping, shoving, and other physical attacks.')
                elif type == 6:
                    print('When a tween or a teen uses the Internet, a smartphone, or other technology to harass, threaten, embarrass, or target another person, it is cyberbullying. '
                          'If an adult is involved in the harassment, it is called cyber-harassment or cyberstalking.')
                else:
                    print('Invalid Input. You have entered a number outside the range')

            elif option == 3:
                print('\nYou will receive help on how to help the person who is suffering bullying')
                print('\nWhich type of bullying have you witnessed')
                print('\nChoose from the following options: \n1. Sexual Bullying'
                      ' \n2. Prejudicial Bullying \n3. Verbal Bullying \n4. Relational Bullying \n5. Physical Bullying'
                      '\n6. Cyberbullying ')
                type = int(input('\nPlease enter the option number: '))
                useroption.append(type)
                if type == 1:
                    print('This type of bullying can evolve into more serious problems for which we recommend '
                          'contacting superior authorities such as the police or trained professionals.')

                elif type == 2:
                    print('We recommend to take immediate action by telling your family the problem and contacting the '
                          'principal of the school you are attending to and have them deal with the problem trough'
                          'talks and intense methods.')

                elif type == 3:
                    print('Research has shown that verbal bullying and name-calling has serious consequences and '
                          'can leave deep emotional scars. For this reason we strongly recommend you to get '
                          'professional help form different psychologist and contact the school in order to stop'
                          'and take action to stop the bullies. ')

                elif type == 4:
                    print('This type of bullying usually goes unnoticed but it does not matter it is less'
                          'harmful, in order to stop this you have to tell your family and even try to talk to'
                          'the bullies to make them understand your situation.')

                elif type == 5:
                    print('Since this type of bullying is the most obvious one because of the visible scars it leaves,'
                          'people would have probably noticed it and in case they have not taken action you have to'
                          'do it, contact the police and have them move to your school and contact the bullies since'
                          'physical damage can be reported and criminalized in many ways.')

                elif type == 6:
                    print('Cyberbullies often say things that they do not have the courage to say face-to-face. '
                          'Technology makes them feel anonymous, insulated, and detached from the situation. They may '
                          'go under the radar since they do not act in person but it does not make them less '
                          'dangerous. This type of bullying has caused many suicides and it has to be reported to the'
                          'authorities as soon as possible to stop it.')
                else:
                    print('\nInvalid Input. You have entered a number outside the range')

            elif option == 4:
                victimInfo=[]
                print('\nWe are here to help you!')
                print('\nYou are not alone!')
                print('\nDo you wanna share more detailed information with us therefore we can help you? \n1.Yes \n2.No')
                help=int(input("Please enter the option number:"))
                useroption.append(help)
                if help==1:
                    print("We are happy to help you:) \nThen could you please tell us that which type of bullying have you suffered?")
                    print('\nChoose from the following options: \n1. Sexual Bullying'
                      ' \n2. Prejudicial Bullying \n3. Verbal Bullying \n4. Relational Bullying \n5. Physical Bullying'
                      '\n6. Cyberbullying ')
                    type = int(input('\nPlease enter the option number: '))
                    if type == 1:
                        print('This type of bullying can evolve into more serious problems for which we recommend '
                              'contacting superior authorities such as the police or trained professionals.')
                        help2=('If you want us to contact with superior authorities for you, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2==0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2==1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            addr=input("Please enter your address, therefore we will find the closest superior authorities for you:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to the superior authorities:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele,addr,situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')

                    elif type == 2:
                        print('We recommend to take immediate action by telling your family the problem and contacting the '
                              'principal of the school you are attending to and have them deal with the problem trough'
                              'talks and intense methods.')
                        help2=('If you want us to contact with your family and principal of school, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2==0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2==1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            parentTele=input("Please enter your parents' telephone number:")
                            school=input("Please enter the name of your school:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to your family and school:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele,parentTele,school,situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')

                    elif type == 3:
                        print('Research has shown that verbal bullying and name-calling has serious consequences and '
                              'can leave deep emotional scars. For this reason we strongly recommend you to get '
                              'professional help form different psychologist and contact the school in order to stop'
                              'and take action to stop the bullies. ')
                        help2=('If you want us to contact with the psychologist and principal of school, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2==0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2==1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            addr=input("Please enter your address, therefore we can find the appropriate psychologist for you:")
                            school=input("Please enter the name of your school:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to the school and psychologist:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele,addr,school,situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')

                    elif type == 4:
                        print('This type of bullying usually goes unnoticed but it does not matter it is less'
                              'harmful, in order to stop this you have to tell your family and even try to talk to'
                              'the bullies to make them understand your situation.')
                        help2=('If you want us to contact with your family and the bullies, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2==0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2==1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            buName=input("Please enter the bullies' name:")
                            buTele=input("Please enter the bullies' telephone number:")
                            parentTele=input("Please enter your parents' telephone number:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to your family:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele,buName,buTele,parentTele,situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')

                    elif type == 5:
                        print('Since this type of bullying is the most obvious one because of the visible scars it leaves,'
                              'people would have probably noticed it and in case they have not taken action you have to'
                              'do it, contact the police and have them move to your school and contact the bullies since'
                              'physical damage can be reported and criminalized in many ways.')
                        help2=('If you want us to contact with the police and the bullies, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2 == 0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2 == 1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            addr=input("Please enter your address, therefore we can find the police office for you:")
                            schoolAddr=input("Please enter the address of your school, therefore the police can move to your school as soon as possible")
                            buName=input("Please enter the bullies' name:")
                            buTele=input("Please enter the bullies' telephone number:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to the police:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele,addr,schoolAddr,buName,buTele,situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')

                    elif type == 6:
                        print('Cyberbullies often say things that they do not have the courage to say face-to-face. '
                              'Technology makes them feel anonymous, insulated, and detached from the situation. They may '
                              'go under the radar since they do not act in person but it does not make them less '
                              'dangerous. This type of bullying has caused many suicides and it has to be reported to the'
                              'authorities as soon as possible to stop it.')
                        help2=('If you want us to contact with authorities, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2==0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2==1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            addr=input("Please enter your address, therefore we will find the appropriate authorities for you:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to the authorities:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele, addr, situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')
                    else:
                        print('\nInvalid Input. You have entered a number outside the range')

                elif help==2:
                    print("It's okay~ But please notice that it's not your fault at all. To be honest, you don't deserve this."
                          "If you want any help in the future, feel free to come to us. We are always here for you 😉")
                else:
                    print('\nInvalid Input. You have entered a number outside the range')

        else:
            print('Invalid Input. You have entered a number outside the range')
    except ValueError:
        print('You have entered a non numeric character')


main()
