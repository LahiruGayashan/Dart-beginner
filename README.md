# Dart-beginner

  // Variables
  int age = 9;
  //print(age);
  
  String name = "Lahiru Gayashan";
  //print(name);
  
  // concatanation
  print("$name is $age years Old!");
  
  //Conditional statements
  if (age>10){  
    print("$name is $age years Old!");
  }
  
  
  // calling Example-(1)function
  int sum = addition(7,6);
  print(sum);
  
  // calling Example-(2)function
  int mine =subtraction(11,12);
  print(mine);
  
  // calling Example-(3)function
  print (isGrater(age));
  
  
  
  //list
  
  List numbers = [1,2,3,4,5];
  List names =["harry","henrey","alponmsu"];
  
  print(names);
  print(numbers);
  
  print(names + numbers);
  
  //add names
  names.add("Lahiru");
  print(names);
  
  //add numbers
  numbers.add(11);
  print(numbers);
  
  //remove name
  names.remove("henrey");
  print(names);
  
  //length
  print(names.length);
  print(numbers.length);
  
  
  
  //create objectes using the Student class
  print("----classes and objects----");
  
  
  Student studentOne = Student();
  studentOne.name ="Lahiru";
  studentOne.age = 25;
  studentOne.login();
  studentOne.logout(7);
    
    
  Student studentTwo =Student();
  studentTwo.name ="Saman Kumara";
  studentTwo.age =26;
  studentTwo.login();
  studentOne.logout(17);
  
  
  
  
  
  
}
