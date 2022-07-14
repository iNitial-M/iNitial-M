# Profile

<h1 align="center">
  Hello Fellow < Developers/ >! <img src = "https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width = 30px>
</h1>

![Profile views](https://visitor-badge.glitch.me/badge?page_id=iNitialM503.iNitialM503)
[![Github](https://img.shields.io/github/followers/iNitialM503?label=Follow&style=social)](https://github.com/iNitialM503)
[![Twitter](https://img.shields.io/twitter/follow/initial_m503?style=social)](https://twitter.com/initial_m503)

Hello, My name is <strong>M Lukman</strong>, Currently Working at IT Consultant (<strong>Java Developer</strong>) Jakarta Selatan, Indonesia.

I'm learning programming through small projects on the side.

---

## Skill's

<p>
<div align="center">
<br>
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E">
  <img src="https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white">
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white">
  <img src="https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white">
  <img src="https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37">
  <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB">
  <img src="https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white">
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB">
  <img src="https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB">
  <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white">
  <img src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/-ElasticSearch-005571?style=for-the-badge&logo=elasticsearch">
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Android%20Studio-3DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white">
</div>
</p>

---

## Entity

```java
package com.github.profile.entity;

import lombok.AllArgsConstructor;
import lombok.Data;
import lombok.NoArgsConstructor;
import org.springframework.data.jpa.repository.JpaRepository;

import javax.persistence.Entity;
import javax.persistence.GeneratedValue;
import javax.persistence.GenerationType;
import javax.persistence.Id;

@Entity
@Data
@NoArgsConstructor
@AllArgsConstructor
public class Profile {
    @Id
    private String Name;
    private String email;
    private String location;
}

public interface ProfileRepository extends JpaRepository<Profile, String>{
}

public class Definition {
    private Profile profile;
    public Profile setData(Profile profile) {
        Profile = new Profile();
        profile.setName("M Lukman");
        profile.setEmail("initial.m503@gmail.com");
        profile.setLocation("Jakarta Selatan, Indonesia");
    }
}
```

---

## My Statistics

<br/>
<p align="left">
  <img width="49.5%" src="https://github-readme-stats.vercel.app/api?username=iNitialM503&show_icons=true&theme=gruvbox&hide_border=true" />
    <img width="49.5%" src="https://github-readme-streak-stats.herokuapp.com/?user=iNitialM503&theme=gruvbox&hide_border=true" />
</p>
<br>

![M Lukman' Activity Graph](https://activity-graph.herokuapp.com/graph?username=iNitialM503&custom_title=M%20Lukman%20Contribution%20Graph&theme=gruvbox&bg_color=282828&hide_border=true&line=d1a01f&point=c58545)

---

## Connect With Me

[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/initial_m503)
[![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)](https://www.facebook.com/5t1ll4l1v3)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/intial-m503/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto://initial.m503@gmail.com)

---

Credit: [iNitialM503](https://github.com/iNitialM503)

Last Edited on: 14/07/2022
