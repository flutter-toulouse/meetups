---
theme : "night"
transition: "slide"
highlightTheme: "monokai"
logoImg: "img/logo.png"
slideNumber: false
title: "Flutter Toulouse - 22/10"
---

![alt text](img/logo.png "Flutter Toulouse")

---

## Début de l'aventure !

![alt text](img/fun.gif "fun")

&#x2713; Groupe Meetup ( ~= **60 membres** )

&#x2713;  Twitter  ( ~= **90 followers** )

---

## Who Am I ? 

- Boris-Wilfried : @bwnyasse

- Dart Enthusiast / Flutter Technical Trainer 

- Cloud Architect 

---

## La cible :

Faire aussi des **workshops** / **codelabs**

![alt text](img/workshop.gif)


---

## Merci !

![alt text](img/santetis.png)
![alt text](img/kooloc.jpg "Kooloc")


---

## Agenda 

1. **Episode #1 :** What's up Flutter ? 

2. **Flutter is all platform** : 
    
    **Le Beurre et l'argent du Beurre !**

    👨‍💻 Kévin Segaud ( **GDE Flutter**  )


---

## What's up Flutter ?  #1

![alt text](img/wassup.gif "Wassup")

---

###### What's up Flutter ?  #1

### Current is Dart SDK v2.5.2


- Born in October 2011 

![alt text](img/dart2.5.2_2.gif "Verified Pub" )

---

###### What's up Flutter ?  #1

### [dart2native](https://dart.dev/tools/dart2native)


AOT compiling Dart programs to native, 

self-contained executables.


---

###### What's up Flutter ?  #1

### Spread Operator ...

Without Spread &#8658;

    List<Widget> americanCountries = [
        Text('USA'),
        Text('Canada')
    ];

    List<Widget> europeanCountries = [
        Text('France'),
        Text('Italy'),
        Text('Germany')
    ];

    List<Widget> asianCountries = [
        Text('India'),
        Text('China'),
    ];

    Row(
        children: americanCountries
                   ..addAll(europeanCountries)
                   ..addAll(asianCountries),
    )


---

###### What's up Flutter ?  #1

### Spread Operator ...

With Spread &#8658;

    Row(
        children: [
                ...americanCountries
                ...europeanCountries
                ...asianCountries
                ]         
    )


---

###### What's up Flutter ?  #1

### Use `if` in your Collection

With Spread &#8658;

    List<Widget> countriesToShow = [
                ...americanCountries
                ...europeanCountries
                if(isAsian)
                    ...asianCountries
    ]      

---


###### What's up Flutter ?  #1

### Who published the [package](https://pub.dev/) ?

![alt text](img/22_10_verified_pub.png "Verified Pub" )

---

###### What's up Flutter ?  #1

Do miss the [Show](https://www.youtube.com/results?search_query=%23BoringShow) !
![alt text](img/boringshow.jpg "Verified Pub" )

---

###### What's up Flutter ?  #1

&#x2713; Git-based : **AWS CodeCommit**, **GitLab** ...

&#x2713;  **Build** / **Sign** / **Publish** iOS apps without a Mac

&#x2713; Test your apps on **real devices**

![alt text](img/codemagic.png "Verified Pub" )

---

###### What's up Flutter ?  #1

VsCode is cool with Flutter Extensions

<img src="img/vscodeflutter.gif" width="800" height="500"></img>

---

###### What's up Flutter ?  #1

[Supernova](https://supernova.io/features/platform-export) 

**Sketch mobile app designs** &#8658;  **native UI code**

![alt text](img/supernova-mb-final.png "Verified Pub" )