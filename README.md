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

## مشروع الالة حاسبة في لغه بايثون 
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

    ## مشروع حساب عمر المستخدم في لغه بايثون 
name = print("What is your name : ")
print("Welcom to Knowing age " + name )
year= int(input ("WWhat year were you born? "))
age= (2025 - year)
print("Your age now is  " + str(age))


مشروع معرفة الاسم و العمر و الوزن و الطول و BMI المستخدم في لغه جافا 


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
