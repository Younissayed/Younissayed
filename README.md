## السلام عليكم، أنا [Younis Elsayyed](https://github.com/youniselsayyed)

[![YouTube Badge](https://img.shields.io/badge/-@YounisElSayyed-c4302b?style=flat-square&labelColor=c4302b&logo=youtube&logoColor=white&link=https://www.youtube.com/@YounisElSayyed)](https://www.youtube.com/@YounisElSayyed)
[![Twitter Badge](https://img.shields.io/badge/-@younis_elsayyed-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/younis_elsayyed)](https://twitter.com/younis_elsayyed)
[![Instagram Badge](https://img.shields.io/badge/-@younis.elsayyed-F44747?style=flat-square&labelColor=F44747&logo=instagram&logoColor=white&link=https://instagram.com/younis.elsayyed)](https://instagram.com/younis.elsayyed)
[![LinkedIn Badge](https://img.shields.io/badge/-Younis%20Elsayyed-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/younis-elsayyed)](https://www.linkedin.com/in/younis-elsayyed)
[![Gmail Badge](https://img.shields.io/badge/-younis.elsayyed@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:younis.elsayyed@gmail.com)](mailto:younis.elsayyed@gmail.com)

---

### 👨‍💻 من أنا؟
- 💻 Flutter Developer
- 🎥 Content Creator on YouTube
- 🎯 مهتم بتطوير تطبيقات الهاتف باستخدام Flutter ودائمًا أشارك معرفتي على اليوتيوب
- 📚 حاليًا بتعلم تقنيات متقدمة في Flutter + Backend (Firebase / Node.js)

---

### 📈 GitHub Stats
![GitHub stats](https://github-readme-stats.vercel.app/api?username=youniselsayyed&show_icons=true&theme=radical)

---

### 📹 جديد على القناة
🎥 شاهد أحدث فيديوهات البرمجة على [YouTube](https://www.youtube.com/@YounisElSayyed)

---

### ✍️ أكتب أيضًا مقالات برمجية على:
[مدونتي قيد الإنشاء](https://youniselsayyed.dev)

## مشروع في مسابقة كرة القدم في لغه بايثون 

the_player=input("What is the player's name? ") 
print("Welcome " , the_player)
Terms = ("To be able to enter the competition, you must choose 25 players with you on the list ")
competition= input ("would you like to enter the competition with us , (Yes or No):") 
if competition == "Yes":
    print(Terms)
    play= input("Do you agree these terms? (Yes or No) ")
    if play == "Yes":
        print("I will contact you within the first seven weeks before the competition")
    else:
        print("Good luck, you can enter the competition with us next season if you like")
        
elif competition == "No":
    print("Good luck, you can enter the competition with us next season if you like")
else: 
    print("Sorry, you must choose the Yes or No")

# مشروع الالة حاسبة في لغه بايثون 
Name= float(input ("What is your name : "))
print("Welcome to the calculator : " + Name)
Num1= float(input ("Enter the first number : "))
operation = input ("Choose to end process ( +, -, *, /, % ) : ")
Num2= float(input ("Enter the second number: "))
if operation == "+" :
    result= (Num1 + Num2)
    print("is result = " result)
elif operation== "-" :
    result=(Num1 - Num2)
    print("is result = " result)
elif operation== "*" :
    result=(Num1 * Num2)
    print("is result = " result)
elif operation== "/" :
    result=(Num1 / Num2)
    if Num2 != 0 :
        print("sorry ")
    print("is result = " result)
elif operation== "%" :
    result=(Num1 % Num2)
    print("is result = " result)
else :
    print("sorry ")

 # برنامج حساب العمر المستخدم في لغه بايثون 
name =str(input ("What is your name : "))
print("Welcom to Knowing age " + name )
year_now= int(input("How old are we? "))
year= int(input ("What year were you born? "))
age= (year_now - year)
print("Your age now is  " + str(age))

# مشروع في لغه بايثون والمشروع هو لعبه التخمين 
import random

name = input("What is your name: ")
print("Hello", name)

computer_number = random.randint(1, 100)
attempts = 0
max_attempts = 5

while attempts < max_attempts:
    guess = int(input(f"Attempt {attempts + 1}: Enter your guess (1-100): "))
    attempts += 1

    if guess > computer_number:
        print("Too high! Try again.")
    elif guess < computer_number:
        print("Too low! Try again.")
    else:
        print(f"🎉 Congratulations, {name}! You guessed it right in {attempts} attempt(s).")
        break
else:
    print(f"❌ Sorry, {name}. You've used all {max_attempts} attempts.")
    print(f"The correct number was: {computer_number}")
    




# مشروع معرفة الاسم و العمر و الوزن و الطول و BMI

# المستخدم في لغه جافا 


import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
		Scanner input = new Scanner (System.in);
	
		System.out.print("Enter your name ");
		String name= input.nextLine();
		
		System.out.print("Enter your age ");
		int age= input.nextInt();
		
	    System.out.print("Enter your weight (Kg) ");	
        double weight= input.nextDouble();
		
        System.out.print("Enter your height ");	
        double height= input.nextDouble();
		
		
		double BMI = weight/(height*height);
   System.out.printf("Name : %s%n", name);
	 System.out.printf("Age : %d%n", age);
   System.out.printf("weight : %.2f%n", weight);
	 System.out.printf("height : %.2f%n", height);
   System.out.printf("BMI : %.2f%n", BMI);
	
	
	}
}



## اضيف مستخدم في لغه بايثون 

users = []

def add_user():
    first_name = input("Enter first name: ")
    last_name = input("Enter last name: ")
    email = input("Enter email: ")
    password = input("Enter password: ")


    for user in users:
        if user["Email"] == email:
            print("This email is already registered!\n")
            return

    user = {
        "First Name": first_name,
        "Last Name": last_name,
        "Email": email,
        "Password": password,
        "Status": "inactive"
    }

    users.append(user)
    print("User added successfully! Account status: inactive\n")


def display_users():
    print("Displaying all users...\n")
    for user in users:
        print("First Name:", user["First Name"])
        print("Last Name:", user["Last Name"])
        print("Email:", user["Email"])
        print("Status:", user["Status"])
        print("-----------------------")


def activate_account():
    email = input("Enter your email to activate your account: ")
    for user in users:
        if user["Email"] == email:
            user["Status"] = "active"
            print("Account activated successfully!\n")
            return
    print("Email not found!\n")


def login():
    email = input("Enter your email: ")
    password = input("Enter your password: ")

    for user in users:
        if user["Email"] == email and user["Password"] == password:
            if user["Status"] == "active":
                print(f"Welcome {user['First Name']}! You have successfully logged in.\n")
            else:
                print("Your account is inactive. Please activate it first.\n")
            return

    print("Invalid email or password.\n")



while True:
    print("Welcome to User Management System")
    print("Choose an Action:\n")
    print("1. Add new user")
    print("2. Display all users")
    print("3. Activate account")
    print("4. Login")
    print("5. Exit\n")

    choice = input("Enter your choice: ")

    if choice == "1":
        add_user()
    elif choice == "2":
        display_users()
    elif choice == "3":
        activate_account()
    elif choice == "4":
        login()
    elif choice == "5":
        print("Exiting the program. Goodbye!")
        break
    else:
        print("Invalid choice. Please try again.\n")
