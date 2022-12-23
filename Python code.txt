print("\n","Welcome to the MOVIE QUESTER".center(50, "-"))
print("\n","Please Enter Your Name: ".rjust(35, " "), end=" ")
name = str(input())
print("\n",f'Welcome {name}!'.center(50, " "), end='\n\n')
print("Choose one of the Genre from the following:")
print("1. Comedy")
print("2. Romance")
print("3. Feel good")
print("4. Action")
print("5. Horror")
genre = int(input("Enter your Choice: "))
print("\n""Choose one of the language from the following:")
print("1. Telugu")
print("2. English")
print("3. Hindi")
lan = int(input("Enter your Choice: "))
print("")

Telugu = {"Comedy": ["Jathirathnalu", "Oh Baby!", "Bhimbisara", "F3", "Julayi"],
          "Romance": ["Bheeshma", "Sita Ramam", "Tholiprema", "Radhe Shyam", "Happy"],
          "Feel good": ["Rang De", "Bommarillu", "Happy Days", "Manam", "Majili"],
          "Action": ["Vikram", "Pushpa", "Bahubali", "KGF", "RRR"],
          "Horror": ["Avunu", "Kanchana", "Arundhathi", "Chandramukhi", "13B"]
          }
Hindi = {"Comedy": ["Chennai Express", "Darlings", "Fukrey", "HouseFull", "Welcome"],
         "Romance": ["Dilwale", "Kabir Singh", "Ashiqui 2", "Tamasha", "RamLeela"],
         "Feel good": ["Happy New Year", "Super 30", "Bhajrangi Bhaijan", "3 Idiots", "Dear Zindigi"],
         "Action": ["Bang Bang", "War", "Race", "Attack", "Dhoom"],
         "Horror": ["Chori", "Bhooth", "Bulbbul", "Bhool Bhulaiyya 2", "1920"]
         }
English = {"Comedy": ["The Dictator", "Jumanji", "Stuart Little", "Central Intelligence", "Rush hour"],
           "Romance": ["The Kissing Bhooth", "me before you", "La La Land", "Titanic", "Brooklyn"],
           "Feel good": ["The Terminal", "A Dog's way Home", "The Holiday", "Rescued by Ruby", "Life of Pi"],
           "Action": ["Avengers_Endgame", "Terminator", "Transformers", "StarWars_TheRiseOfSkywalker", "Real Steel"],
           "Horror": ["IT", "The Nun", "The Conjuring", "Alice", "The Orphan"]
           }
if lan == 1:
    lan = Telugu
elif lan == 2:
    lan = English
elif lan == 3:
    lan = Hindi
else:
    print("Invalid. Enter only 1 or 2 or 3")

Genre = {1: "Comedy", 2: "Romance", 3: "Feel good", 4: "Action", 5: "Horror"}
c = 1
diction={}
for i in lan[Genre[genre]]:
    print(f'{c}.', i)
    diction[c] = i
    c = c + 1
print("Now Enter the Choice of the Movie that you'd like to know about: ", end="")
m = int(input())
print("")
print(diction[m])

def Jathirathnalu_():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 7 March 2021")
    print("\t\t\tHero           : Naveen Polishetty")
    print("\t\t\tHeroine        : Faria Abdullah")
    print("\t\t\tDirector       : Anudeep Kv")
    print("\t\t\tMusic Director : Radhan")


def Oh_baby():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 5 july 2019")
    print("\t\t\tHero           : Naga Shaurya")
    print("\t\t\tHeroine        : Samantha Ruth Prabhu")
    print("\t\t\tDirector       : B.V.Nandhini Reddy")
    print("\t\t\tMusic Director : Mickey J Meyer")


def Bhimbisara():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 5 August 2022")
    print("\t\t\tHero           : Kalyan Ram")
    print("\t\t\tHeroine        : Samyuktha Menon")
    print("\t\t\tDirector       : Vasishta")
    print("\t\t\tMusic Director : M.M.Keeravani,Chirantan Bhatt")


def F2():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 12 January 2019")
    print("\t\t\tHero           : Venkatesh,Varun")
    print("\t\t\tHeroine        : Tamannaah,Mehreen")
    print("\t\t\tDirector       : Anil Ravipudi")
    print("\t\t\tMusic Director : Devi Sri Prasad")


def Julayi():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 9 August 2012")
    print("\t\t\tHero           : Allu Arjun")
    print("\t\t\tHeroine        : Ileana")
    print("\t\t\tDirector       : Trivikram")
    print("\t\t\tMusic Director : Devi Sri Prasad")


def Bheeshma():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 3 March 2022")
    print("\t\t\tHero           : Nithin")
    print("\t\t\tHeroine        : Rashmika")
    print("\t\t\tDirector       : Venky Kudumula")
    print("\t\t\tMusic Director : Sagar Mahati")


def sita_Ramam():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 5 August 2022")
    print("\t\t\tHero           : Dulquer Salman")
    print("\t\t\tHeroine        : Mrunal Thakur")
    print("\t\t\tDirector       : Hanu Raghavapudi")
    print("\t\t\tMusic Director : Vishal Chandrasekhar")


def Tholiprema():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 10 February 2018")
    print("\t\t\tHero           : Varun Tej")
    print("\t\t\tHeroine        : Rashi Khanna")
    print("\t\t\tDirector       : Venky Atluri")
    print("\t\t\tMusic Director : S.Thaman")


def Radhe_Shyam():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 11 March 2022")
    print("\t\t\tHero           : Prabhas")
    print("\t\t\tHeroine        : Pooja Hegde")
    print("\t\t\tDirector       : Radha Krishna Kumar")
    print("\t\t\tMusic Director : S.Thaman")


def Happy():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 27 January 2006")
    print("\t\t\tHero           : Allu Arjun")
    print("\t\t\tHeroine        : Genelia")
    print("\t\t\tDirector       : Karunakaran")
    print("\t\t\tMusic Director : Yuvan Shankar Raja")


def Rang_De():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 26 March 2021")
    print("\t\t\tHero           : Nithin")
    print("\t\t\tHeroine        : Keerthi Suresh")
    print("\t\t\tDirector       : Venky Atluri")
    print("\t\t\tMusic Director : Devi Sri Prasad")


def Bommarillu():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 9 August 2006")
    print("\t\t\tHero           : Siddharth")
    print("\t\t\tHeroine        : Genelia")
    print("\t\t\tDirector       : Bhaskar")
    print("\t\t\tMusic Director : Devi Sri Prasad")


def Happy_Days():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 2 October 2007")
    print("\t\t\tHero           : Varun Sandesh")
    print("\t\t\tHeroine        : Tamannaah")
    print("\t\t\tDirector       : Sekhar Kammula")
    print("\t\t\tMusic Director : Micky J Meyer")


def Manam():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 23 May 2014")
    print("\t\t\tHero           : Akkineni Family")
    print("\t\t\tHeroine        : Samantha,Shreya")
    print("\t\t\tDirector       : Vikram Kumar")
    print("\t\t\tMusic Director : Anup Rubens")


def Majili():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 5 April 2019")
    print("\t\t\tHero           : Naga Chaitanya")
    print("\t\t\tHeroine        : Samantha")
    print("\t\t\tDirector       : Shiva Nirvana")
    print("\t\t\tMusic Director : Gopi SUndar,S.Thaman")


def Vikram():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 3 June 2022")
    print("\t\t\tHero           : Kamal Haasan")
    print("\t\t\tHeroine        : -----")
    print("\t\t\tDirector       : Lokesh Kanagaraj")
    print("\t\t\tMusic Director : Anirudh Ravichandran")


def Pushpa():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 17 December 2021")
    print("\t\t\tHero           : Allu Arjun")
    print("\t\t\tHeroine        : Rashmika")
    print("\t\t\tDirector       : Sukumar")
    print("\t\t\tMusic Director : Devi Sri Prasad")


def Bahubali():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 10 July 2015")
    print("\t\t\tHero           : Prabhas")
    print("\t\t\tHeroine        : Tamannaah")
    print("\t\t\tDirector       : S.S.Rajamouli")
    print("\t\t\tMusic Director : M.M.Keeravani")


def KGF():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 21 December 2018")
    print("\t\t\tHero           : Yash")
    print("\t\t\tHeroine        : Srinidhi Setty")
    print("\t\t\tDirector       : Prashnath Neel")
    print("\t\t\tMusic Director : Ravi Barsur")


def RRR():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 24 March 2022")
    print("\t\t\tHero           : NTR,Ram Charan")
    print("\t\t\tHeroine        : Alia Bhatt,Olivia Morris")
    print("\t\t\tDirector       : Rajamouli")
    print("\t\t\tMusic Director : M.M.Keeravani")


def Avunu():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 21 September 2012")
    print("\t\t\tHero           : Harshvardhan")
    print("\t\t\tHeroine        : Shamna Kasim")
    print("\t\t\tDirector       : Ravi Babu")
    print("\t\t\tMusic Director : Sekhar Chandra")


def Kanchana():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 15 July 2011")
    print("\t\t\tHero           : Raghava Lawrence")
    print("\t\t\tHeroine        : Laxmi Raai")
    print("\t\t\tDirector       : Raghava Lawrence")
    print("\t\t\tMusic Director : S.Thaman")


def Arundhathi():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 16 January 2009")
    print("\t\t\tHero           : -----")
    print("\t\t\tHeroine        : Anushka")
    print("\t\t\tDirector       : Ramakrishna Kodi")
    print("\t\t\tMusic Director : Koti")


def Chandramukhi():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 14 April 2005")
    print("\t\t\tHero           : Rajinikanth")
    print("\t\t\tHeroine        : Nayanathara,Jyothika")
    print("\t\t\tDirector       : P.Vasu")
    print("\t\t\tMusic Director : Vidyasagar")


def _13B():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 6 March 2009")
    print("\t\t\tHero           : Madhavan")
    print("\t\t\tHeroine        : Neetu Chandra")
    print("\t\t\tDirector       : Vikram Kumar")
    print("\t\t\tMusic Director : Loy Mendonsa,Sankar,Ehsaan")


def Chennai_Express():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 8 August 2013")
    print("\t\t\tHero           : Shah Rukh Khan")
    print("\t\t\tHeroine        : Deepika Padukone")
    print("\t\t\tDirector       : Rohit Shetty")
    print("\t\t\tMusic Director : Yo Yo Honey Singh")


def Darlings():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 5 August 2022")
    print("\t\t\tHero           : -----")
    print("\t\t\tHeroine        : Alia Bhatt")
    print("\t\t\tDirector       : Jasmeet K.Reen")
    print("\t\t\tMusic Director : Prasanth Pillai")


def Fukrey():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 14 June 2013")
    print("\t\t\tHero           : Ali Fazal,Pulkit Samrat,Varun Sharma")
    print("\t\t\tHeroine        : Richa Chadha")
    print("\t\t\tDirector       : Mrigdeep Singh Lamba")
    print("\t\t\tMusic Director : Ram Sampath")


def HouseFull():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 30 April 2010")
    print("\t\t\tHero           : Akshay Kumar")
    print("\t\t\tHeroine        : Jacqueline,Deepika Padukone")
    print("\t\t\tDirector       : Sajid Khan,Farhad Khan")
    print("\t\t\tMusic Director : Shankar-Ehsaan-Loy")


def Welcome():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 21 December 2007")
    print("\t\t\tHero           : Akshay Kumar")
    print("\t\t\tHeroine        : Katrina Kaif")
    print("\t\t\tDirector       : Anees Bazmee")
    print("\t\t\tMusic Director : Anand Raaj")


def Dilwale():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 18 December 2015")
    print("\t\t\tHero           : Shah Rukh Khan,Varun Dhawan")
    print("\t\t\tHeroine        : Kajol,Kriti Sanon")
    print("\t\t\tDirector       : Rohit Shetty")
    print("\t\t\tMusic Director : Pritam Chakraborty")


def Kabir_Singh():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 21 June 2019")
    print("\t\t\tHero           : Shahid  Kapoor")
    print("\t\t\tHeroine        : Kiara Advani")
    print("\t\t\tDirector       : Sandeep Reddy Vanga")
    print("\t\t\tMusic Director : Mithoon")


def Ashiqui_2():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 26 April 2013")
    print("\t\t\tHero           : Aditya Roy Kapoor")
    print("\t\t\tHeroine        : Shraddha Kapoor")
    print("\t\t\tDirector       : Mohith Suri")
    print("\t\t\tMusic Director : Ankit Tiwari")


def Tamasha():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 27 November 2015")
    print("\t\t\tHero           : Ranbir Kapoor")
    print("\t\t\tHeroine        : Deepika Padukone")
    print("\t\t\tDirector       : Imtiaz Ali")
    print("\t\t\tMusic Director : A.R.Rahman")


def RamLeela():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 15 November 2013")
    print("\t\t\tHero           : Ranveer Singh")
    print("\t\t\tHeroine        : Deepika Padukone")
    print("\t\t\tDirector       : Sanjay Leela Bhansali")
    print("\t\t\tMusic Director : Monty Sharma,Sanjay Leela Bhansali")


def Happy_New_Year():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 24 October 2014")
    print("\t\t\tHero           : Shah Rukh Khan")
    print("\t\t\tHeroine        : Deepika Padukone")
    print("\t\t\tDirector       : Farhan Khan")
    print("\t\t\tMusic Director : Vishal Dadlani")


def Super_30():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 12 july 2019")
    print("\t\t\tHero           : Hrithik Roshan")
    print("\t\t\tHeroine        : Mrunal Thakur")
    print("\t\t\tDirector       : Vikas Bahi")
    print("\t\t\tMusic Director : Ajay,Atul")


def Bhajrangi_Bhaijan():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 17 April 2015")
    print("\t\t\tHero           : Salman Khan")
    print("\t\t\tHeroine        : Kareena Kapoor")
    print("\t\t\tDirector       : Kabir Khan")
    print("\t\t\tMusic Director : Pritam Chakraborty")


def _3_idiots():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 25 December 2009")
    print("\t\t\tHero           : Aamir Khan")
    print("\t\t\tHeroine        : Kareena Kapoor")
    print("\t\t\tDirector       : Rajkumar Hirani")
    print("\t\t\tMusic Director : Sanjay Wandrekar")


def Dear_Zindigi():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 25 November 2016")
    print("\t\t\tHero           : Shah Rukh Khan")
    print("\t\t\tHeroine        : Alia Bhatt")
    print("\t\t\tDirector       : Gauri Shinde")
    print("\t\t\tMusic Director : Amit Trivedi")


def Bang_Bang():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 2 October 2014")
    print("\t\t\tHero           : Hrithik Roshan")
    print("\t\t\tHeroine        : Katrina Kaif")
    print("\t\t\tDirector       : Siddharth Anand")
    print("\t\t\tMusic Director : Vishal Shekhar")


def War():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 2 October 2019")
    print("\t\t\tHero           : Hrithik Roshan,Tiger Shroff")
    print("\t\t\tHeroine        : Vaani Kapoor")
    print("\t\t\tDirector       : Siddharth Anand")
    print("\t\t\tMusic Director : Sanchith,Vishal")


def Race():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 21 March 2008")
    print("\t\t\tHero           : Saif Ali Khan")
    print("\t\t\tHeroine        : Katrina Kaif,Sameera Reddy")
    print("\t\t\tDirector       : Mustan,Abbas")
    print("\t\t\tMusic Director : Pritam Chakraborty")


def Attack():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 1 April 2022")
    print("\t\t\tHero           : John Abraham")
    print("\t\t\tHeroine        : Rakul Preet Singh")
    print("\t\t\tDirector       : Lakshya Raj Anand")
    print("\t\t\tMusic Director : Shashwat Sachdev")


def Dhoom():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 27 August 2004")
    print("\t\t\tHero           : Abhisekh Bachan")
    print("\t\t\tHeroine        : Aishwarya Rai Bachan")
    print("\t\t\tDirector       : Sanjay Gadhvi")
    print("\t\t\tMusic Director : Pritam Chakraborty")


def Chori():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 26 November 2021")
    print("\t\t\tHero           : -----")
    print("\t\t\tHeroine        : Nushrratt Bharuccha,Mita Vashisht")
    print("\t\t\tDirector       : Vishal Furia")
    print("\t\t\tMusic Director : Shankar,Jaikishan")


def Bhooth():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 21 February 2020")
    print("\t\t\tHero           : Ajay Devgn")
    print("\t\t\tHeroine        : Urmila Matondkr")
    print("\t\t\tDirector       : Ram Gopal Varma")
    print("\t\t\tMusic Director : Salim,Sulaiman")


def Bulbbul():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 24 June 2020")
    print("\t\t\tHero           : Avinash Tiwary")
    print("\t\t\tHeroine        : Tripti Dimri")
    print("\t\t\tDirector       : Anvita Dutt")
    print("\t\t\tMusic Director : V.Hari Krishna")


def Bhool_Bhulaiyya_2():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 20 May 2022")
    print("\t\t\tHero           : Karthik Aaryan")
    print("\t\t\tHeroine        : Kiara Advani")
    print("\t\t\tDirector       : Anees Bazmee")
    print("\t\t\tMusic Director : Sandeep Shirodkar")


def _1920():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 12 September 2008")
    print("\t\t\tHero           : Rajneesh Duggal")
    print("\t\t\tHeroine        : Adah Sharma")
    print("\t\t\tDirector       : Vikram Bhatt")
    print("\t\t\tMusic Director : Adnan Sami")


def The_Dictator():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 16 May 2012")
    print("\t\t\tHero           : Sacha Baron Cohen")
    print("\t\t\tHeroine        : Anna Faris")
    print("\t\t\tDirector       : Larry Charles")
    print("\t\t\tMusic Director : Erran Baron Cohen,Khaled")


def Jumanji():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 20 December 2017")
    print("\t\t\tHero           : Dwayne Johnson,Kevin Hart,Jack Black,Nick Jonas")
    print("\t\t\tHeroine        : Karen Gillan,Madison Iseman")
    print("\t\t\tDirector       : Jake Kasdan")
    print("\t\t\tMusic Director : Henry Jackman")


def Stuart_Little():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 5 December 1999")
    print("\t\t\tHero           : Michael J.Fox,Hugh Laurie")
    print("\t\t\tHeroine        : Geena Davis")
    print("\t\t\tDirector       : Rob Minkoff")
    print("\t\t\tMusic Director : Alan Silvestri")


def Central_Intelligence():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 10 June 2016")
    print("\t\t\tHero           : Kevin Hart,Dwayne Johnson")
    print("\t\t\tHeroine        : Amy Ryan")
    print("\t\t\tDirector       : Rawson Marshall Thurber")
    print("\t\t\tMusic Director : Theodore Shapiro")


def Rush_Hour():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 18 September 1998")
    print("\t\t\tHero           : Jackie Chan,Chris Tucker")
    print("\t\t\tHeroine        : Julia Hsu")
    print("\t\t\tDirector       : Brett Ratner")
    print("\t\t\tMusic Director : Ira Hearshen")


def The_Kissing_Bhooth():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 11 May 2018")
    print("\t\t\tHero           : Jacob Elordi")
    print("\t\t\tHeroine        : Joey King")
    print("\t\t\tDirector       : Vince Marcello")
    print("\t\t\tMusic Director : Patrick Krist,Rostam Batmanglij")


def Me_Before_You():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 3 June 2016")
    print("\t\t\tHero           : Sam Claflin")
    print("\t\t\tHeroine        : Emilia Clarke")
    print("\t\t\tDirector       : Thea Sharrock")
    print("\t\t\tMusic Director : Craig Armstrong")


def La_La_Land():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 9 December 2016")
    print("\t\t\tHero           : Ryan Gosling")
    print("\t\t\tHeroine        : Emma Stone")
    print("\t\t\tDirector       : Damien Chazelle")
    print("\t\t\tMusic Director : Justin Hurwitz")


def Titanic():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 19 December 1997")
    print("\t\t\tHero           : Leonardo DiCaprio")
    print("\t\t\tHeroine        : Kate Winslet")
    print("\t\t\tDirector       : James Cameron")
    print("\t\t\tMusic Director : James Horner")


def Brooklyn():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 20 November 2015")
    print("\t\t\tHero           : Emory Cohen")
    print("\t\t\tHeroine        : Saoirse Ronan")
    print("\t\t\tDirector       : John Crowley")
    print("\t\t\tMusic Director : Michael Brook")


def The_Terminal():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 18 June 2004")
    print("\t\t\tHero           : Tom Hanks")
    print("\t\t\tHeroine        : Catherine")
    print("\t\t\tDirector       : Steven Soielberg")
    print("\t\t\tMusic Director : John Williams")


def A_Dogs_Way_Home():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 11 January 2019")
    print("\t\t\tHero           : -----")
    print("\t\t\tHeroine        : Bryce Dallas Howard")
    print("\t\t\tDirector       : Charles Martin Smith")
    print("\t\t\tMusic Director : Mychael Danna")


def The_Holiday():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 9 February 2007")
    print("\t\t\tHero           : Jude Law")
    print("\t\t\tHeroine        : Cameron Diaz")
    print("\t\t\tDirector       : Nancy Meyers")
    print("\t\t\tMusic Director : Hans Zimmer")


def Rescued_By_Ruby():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 17 March 2022")
    print("\t\t\tHero           : Grant Gustin")
    print("\t\t\tHeroine        : -----")
    print("\t\t\tDirector       : Katt Shea")
    print("\t\t\tMusic Director : Joy Ngiaw")


def Life_Of_Pi():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 23 November 2012")
    print("\t\t\tHero           : Irrfan Khan,Suraj Sharma")
    print("\t\t\tHeroine        : Tabu")
    print("\t\t\tDirector       : Ang Lee")
    print("\t\t\tMusic Director : Mychael Danna")


def Avengers_Endgame():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 26 April 2019")
    print("\t\t\tHero           : Robert Downey Jr.,Chris Evans,Chris Hemsworth,Tom Holland,Mark Ruffalo,Jeremy Renner")
    print("\t\t\tHeroine        : Scarlet Johansson,Brie Larson")
    print("\t\t\tDirector       : Anthony Russo,Joe Russo")
    print("\t\t\tMusic Director : Alan Silvestri")


def Terminator():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 26 October 1984")
    print("\t\t\tHero           : Arnold Schwarzenegger")
    print("\t\t\tHeroine        : Linda Hamilton")
    print("\t\t\tDirector       : James Cameron")
    print("\t\t\tMusic Director : Brad Fiedel,Tane McClure,Joe Dolce")


def Transformers():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 4 August 2007")
    print("\t\t\tHero           : Shia LeBeouf")
    print("\t\t\tHeroine        : Megan Fox")
    print("\t\t\tDirector       : Michel Bay")
    print("\t\t\tMusic Director : Steve Jablonsky")


def StarWars_TheRiseOfSkywalker():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 20 December 2019")
    print("\t\t\tHero           : Mark Hamill")
    print("\t\t\tHeroine        : Carrie Fisher")
    print("\t\t\tDirector       : J.J.Abrams")
    print("\t\t\tMusic Director : John Williams")


def Real_Steel():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 7 October 2011")
    print("\t\t\tHero           : Hugh Jackman")
    print("\t\t\tHeroine        : Evangeline Lilly")
    print("\t\t\tDirector       : Shawn Levy")
    print("\t\t\tMusic Director : Danny Elfman")


def IT():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 8 September 2017")
    print("\t\t\tHero           : Bill Skarsgard,Jaeden Martell,Finn,Jack Dylan..")
    print("\t\t\tHeroine        : Sophia Lillis..")
    print("\t\t\tDirector       : Andres Muschietti")
    print("\t\t\tMusic Director : Benjamin Wallfisch")


def The_Nun():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 7 September 2018")
    print("\t\t\tHero           : Jonas Bloquet")
    print("\t\t\tHeroine        : Taissa Farmiga,Bonnie Aarons")
    print("\t\t\tDirector       : Corin Hardy")
    print("\t\t\tMusic Director : Abel Korzeniowski")


def The_Conjuring():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 2 August 2013")
    print("\t\t\tHero           : Patrick Wilson,Ron Livingston")
    print("\t\t\tHeroine        : Vera Farmiga,Lili Taylor")
    print("\t\t\tDirector       : James Wan")
    print("\t\t\tMusic Director : Joseph Bishara,Mark Isham")


def Alice():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 23 January 2022")
    print("\t\t\tHero           : -----")
    print("\t\t\tHeroine        : Keke Palmer")
    print("\t\t\tDirector       : Krystin Ver Linden")
    print("\t\t\tMusic Director : Common")


def The_Orphan():
    print("-".center(75, "-"))
    print("")
    print("\t\t\tRelease Date   : 24 July 2009")
    print("\t\t\tHero           : Peter Sarsgaard")
    print("\t\t\tHeroine        : Jamie Young")
    print("\t\t\tDirector       : Jaume Collet-Serra")
    print("\t\t\tMusic Director : John Ottman")

dict_ = {"JATHIRATHNALU": "Jathirathnalu_()","OH BABY!": "Oh_baby()","BHIMBISARA":"Bhimbisara()",
    "F2": 'F2()', "JULAYI": 'Julayi()', "BHEESHMA": 'Bheeshma()', "SITA RAMAM": 'sita_Ramam()',
    "THOLIPREMA": 'Tholiprema()', "RADHE SHYAM": 'Radhe_Shyam()', "HAPPY": 'Happy()', "RANG DE": 'Rang_De()',
    "BOMMARILLU": 'Bommarillu()', "HAPPY DAYS": 'Happy_Days()', "MANAM": 'Manam()', "MAJILI": 'Majili()',
    "VIKRAM": 'Vikram()', "PUSHPA": 'Pushpa()', "BAHUBALI": 'Bahubali()', "KGF":'KGF()', "RRR":'RRR()',
    "AVUNU": 'Avunu()', "KANCHANA": 'Kanchana()', "ARUNDHATHI": 'Arundhathi()', "CHANDRAMUKHI": 'Chandramukhi()',
    "13B":'_13B()', "CHENNAI EXPRESS": 'Chennai_Express()', "DARLINGS": 'Darlings()', "FUKREY": 'Fukrey()',
    "HOUSEFULL": 'HouseFull()', "WELCOME": 'Welcome()', "DILWALE": 'Dilwale()', "KABIR SINGH": 'Kabir_Singh()',
    "ASHIQUI 2": 'Ashiqui_2()', "TAMASHA": 'Tamasha()', "RAMLEELA": 'RamLeela()', "HAPPY NEW YEAR": 'Happy_New_Year()',
    "SUPER 30": 'Super_30()', "BHAJARANGI BHAIJAN": 'Bhajrangi_Bhaijan()', "3 IDIOTS": '_3_idiots()',
    "DEAR ZINDIGI": 'Dear_Zindigi()', "BANG BANG": 'Bang_Bang()', "WAR": 'War()', "RACE": 'Race()', "ATTACK": 'Attack()',
    "DHOOM":'Dhoom()', "CHORI": 'Chori()', "BHOOTH": 'Bhooth()', "BULBBUL": 'Bulbbul()', "BHOOL BHULAIYYA 2": 'Bhool_Bhulaiyya_2()',
    "1920": '_1920()', "THE DICTATOR": 'The_Dictator()', "JUMANJI": 'Jumanji()', "STUART LITTLE": 'Stuart_Little()',
    "CENTRAL INTELLIGENCE": 'Central_Intelligence()', "RUSH HOUR": 'Rush_Hour()', "THE KISSING BHOOTH": 'The_Kissing_Bhooth()',
    "ME BEFORE YOU": 'Me_Before_You()', "LA LA LAND": 'La_La_Land()', "TITANIC": 'Titanic()', "BROOKLYN":'Brooklyn()',"THE TERMINAL":'The_Terminal()',
    "A DOG'S WAY HOME":'A_Dogs_Way_Home()', "The HOLIDAY":'The_Holiday()', "RESCUED BY RUBY":'Rescued_By_Ruby()',"LIFE OF PI":'Life_Of_Pi()',
    "AVENGERS_ENDGAME":'Avengers_Endgame()', "TERMINATOR":'Terminator()', "TRANSFORMERS":'Transformers()', "STARWARS THERISEOFSKYWALKER":'StarWars_TheRiseOfSkywalker()', "REAL STEEL":'Real_Steel()',
    "IT":'IT()', "THE NUN":'The_Nun()', "THE CONJURING":'The_Conjuring()', "ALICE":'Alice()', "THE ORPHAN":'The_Orphan()'}

print(eval(dict_[(diction[m]).upper()]))