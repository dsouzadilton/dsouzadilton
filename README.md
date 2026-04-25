<img src="https://quotefancy.com/media/wallpaper/3840x2160/20574-Anonymous-Quote-I-need-a-six-month-vacation-twice-a-year.jpg"/>

```java
class Me{
    private String name;
    private String location;
    private String[] interests;
    private String[] hobbies;
    private String portfolio;

    Me(){
        this.name="Dilton";
        this.location="Mumbai, India";
        this.interests = new String[] {"Software Development", "IoT", "Machine Learning", "Performance Engineering"};
        this.hobbies = new String[] {"Coding", "Cycling", "Swimming", "Skating", "Kickboxing"};
        this.portfolio="https://dsouzadilton.github.io/";
    }
    
    public void introduce(){
        System.out.println("Hey there! I'm "+this.name+".");
        
    }
}

class Main{
    public static void main (String[] args) {
        Me me = new Me();
        me.introduce();
    }

}
```

