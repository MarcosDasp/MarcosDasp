##  Sobre mim

```java

public class Student {

    private String name;
    private String role;
    private String[] languageSpoken;

    public Student() {
        this.name = "Marcos";
        this.role = "Informática para Negócios";
        this.languageSpoken = new String[] {"pt_BR", "en_US"};
    }

    public void sayHi() {
        System.out.println("Obrigado por visitar, espero que ache interessante o meu perfil :)");
    }

    public static void main(String[] args) {
        Student me = new Student();
        me.sayHi();
    }
}

```
