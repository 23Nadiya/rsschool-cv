NADEZHDA YANUSHEVICH
Junior Frontend Developer

CONTACT
Phone: +375336610771
E-mail: macyoka23@gmail.com
Discord: Nadezhda#7111
GitHub: 23Nadiya
Location: Minsk, Belarus

SKILLS
HTML
CSS
JavaScript

LANGUAGES
English: Pre-intermediate/Intermediate
French: Beginner

SUMMARY
Medical doctor intrested in evidence-based pediatrics. Having a good ability for growth but there is no way to fully implement my knowledge and experience without leaving the country. A strong beliver than our success is in our hands! Trying to make every effort to improve the wealth. My goal is to become a full-stack JavaScript developer and to get the growth opportunities. Front End attracted me by the possibility to see the result of the work. I really like the process of acquiring deep specialist knowledge and getting the satisfactory to see the great result of your work. I'm good as a team member, responsible and well organized.

EXPERIENCE
2015 - Present: HI "9 children's polyclinic". Pediatrician. April 2019: after successfully passing the exam for the first category at the request of the health committee sent to leadership courses.
2014 - April 2015: Salon "Skvirel". Designer-consultant.
2011 - July 2014: HI "36 children's polyclinic". District pediatrician. April 2013: acting head of department.
2009 – June 2012г: LLC "Tibetray". Commercial organization, part of a large RTL holding. Sales economist.

EDUCATION
University
2005 - 2011: Belarusian State Medical University
Courses
2021: Harvard CS50 lectures
RS School
2021: JavaScript/Front-end. Stage 0.

PROJECTS

CODE EXAMPLE
Task: Add all the numbers included in it until there is one digit left.
const square = (num) => {
if (num < 0) {
return "Введите положительное число.";
} else if (num < 10) {
return num;
}
let str = String(num);
const numSum = (newStr) => {
let sum = 0;
for (let i = 0; i < newStr.length; i += 1) {
sum = sum + Number(newStr[i]);
}
if (sum < 10) {
return sum;
} else {
numSum(String(sum));
const y = numSum(String(sum));
if (y < 10) {
return y;
}
}
};
const x = numSum(str);
return x;
};
