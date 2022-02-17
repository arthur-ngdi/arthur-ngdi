# ArthurFerreira

<h2> Hey, buddy! I'm Arthur Ferreira!</h2>
<img align='right' src="https://media.giphy.com/media/ule4vhcY1xEKQ/giphy.gif" width="230">
<p>Student of Computer Enginneering at  <em><a href="https://inatel.br/home/" target="_blank">INATEL</a></em> and trying Hard to be a Web Developer
</p></br>

[![Linkedin: Arthur Ferreira](https://img.shields.io/badge/-ArthurFerreiraSilva-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ArthurFerreiraSilva/)]( www.linkedin.com/in/ArthurFerreiraSilva)
[![GitHub Arthur Ferreira](https://img.shields.io/github/followers/arthur-ngdi?label=follow&style=social)](https://github.com/arthur-ngdi)


### A little more about me...  

```Java

public class Arthur extends Developer{

    private int energy;
    private String[] knowledge ;

    public Arthur() {
        this.knowledge = new String[]{"Java", "SQL", "DataBase", "Python", "JavaScript", "C++", "C" ,"Arduino",
        "HTML5", "CSS3", "MQTT Protocol ", "GIT"};
    }

    public String[] getKnowledge() {
        return knowledge;
    }

    public void setknowledge(String[] knowledge) {
        System.out.println("Alura?");
        this.knowledge = knowledge;
    }

    public int getEnergy() {
        return energy;
    }

    public void setEnergy(int energy) {
        this.energy = energy;
    }

    public  void drinkCoffee (){
        if(this.energy < 100) {
            System.out.print("let's go!");
            this.energy = 100;
        } else {
             System.out.print("I'm not in need of energy, but every time is a good time for a little coffee!");
        }
    }
}
```
