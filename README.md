<h1 align="center">👋 Hello! I'm Carlos</h1>

<p align="center">   
I'm a currently studying to be a Software Engineer. Right now i'm learning Java, and my dream is to live a peacefull life working in tech.
</p>
<p align="center">
I like reading, listening to music, and drinking matcha 💚.
</p>

<h3>This is me...</h3>

 ```c
 #include <stdbool.h>
#include <stdio.h>
#include <stdlib.h>

struct Me {
  char *name;
  int age;
  char *hobbies[4];
  bool happy;
  char *location;
};

struct Me *meSetUp() {
  char *name = "Carlos Reyes";
  int age = 19;
  char *hobbies[4] = {"Coding", "Reading", "Coffe shops", "Sushi"};
  bool happy = true;
  char *location = "México";

  struct Me *Carlos = malloc(sizeof(struct Me));
  Carlos->name = name;
  Carlos->age = age;
  for (int i = 0; i < 4; i++) {
    Carlos->hobbies[i] = hobbies[i];
  }
  Carlos->happy = happy;
  Carlos->location = location;

  return Carlos;
}

void currentlyDoing() {
  char *studying[] = {"C", "Data structures", "web", "Java"};
  char *reading[] = {"¿Por dónde se sale?", "Data structures in C"};
  char *doing[] = {"Probably listening to music", "Eating",
                   "Doing my duolingo streak"};
}

int main() {
  struct Me *myInfo = meSetUp();
  printf("My name is ^^ %s\n", myInfo->name);

  free(myInfo);

  return 0;
}

 ```
 
<br>

### My most used tools :D
<p> 
  <img src="assets/java.png" alt="java-logo">
  <img src="assets/js.png" alt="js-logo">
  <img src="assets/linux.png" alt="linux-logo">
  <img src="assets/mysql.png" alt="mysql-logo">
  <img src="assets/python.png" alt="python-logo">
  <img src="assets/c.png" alt="c-logo" style="height: 64px; width: 64px">
</p>
