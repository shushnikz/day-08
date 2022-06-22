# day-08
https://github.com/rvsp/typescript-oops/blob/master/Practice/Movie.md

class movie{
constructor(title,studio,rating){
this.title=title;
this.studio=studio;
this.rating=rating;
}
getPG(movie){
var arr=new movie[movie.length];
var newarrindex=0;
for (var i = 0; i < movie.length; i++) {
 if (movie[i].rating==PG) {
 arr[newarrindex]=movie[i];
 newarrindex++;
}
}
return arr;
}
}
var c1=new movie("Casino Royale","Eon Productions","PG13");
console.log(c1.rating);
  

Write a “person” class to hold all the details.

class person{
constructor(name,age,country,company,employeeid,salary){
this.name=name;
this.age=age;
this.country=country;
this.company=company;
this.employeeid=employeeid;
this.salary=salary;
}
}
var c1=new person("jon",23,"India","guvi",1,30000);
var c2=new person("doe",25,"India","guvi",2,35000);

write a class to calculate uber price.

class uberPrice{
constructor(perkm,distance){
this.perkm=perkm;
this.distance=distance;
}
get calcUberprice(){
return this.calcalcUberprice();
}
calcalcUberprice(){
return this.perkm * this.distance;
}
}
var c1=new uberPrice(20,23);
console.log(c1.calcUberprice);
