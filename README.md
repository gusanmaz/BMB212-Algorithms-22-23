## NKÜ Bilgisayar Mühendisliği Veri Yapıları (BMB212) 2022-2023 Bahar Donemi Dersi Uygulama Not ve Duyuruları

Bu repo'da uygulama derslerine ait materyallere (ders notlari, odev bilgileri, proje bilgileri, duyurular vb.) ulasabilirsiniz.

### Iletisim

Ars. Gor. Güvenç Usanmaz

Oda: B207

Bolum: Bilgisayar Muhendisligi

Email: gusanmaz <att< nku nokta edu nokta tr

### Onerilen Kaynaklar

* [CS50](https://cs50.harvard.edu/college/2022/spring/)
* [Introduction to Programming in Java](https://introcs.cs.princeton.edu/java/home/)
* [Algorithms, 4th Edition by Robert Sedgewick and Kevin Wayne](https://algs4.cs.princeton.edu/home/)
* [Algoritmalar, Robert Sedgewick, NOBEL AKADEMİK YAYINCILIK](https://www.kitapyurdu.com/kitap/algoritmalar/498451.html)
* [Introduction to Algorithms, Fourth Edition](https://www.amazon.com/Introduction-Algorithms-fourth-Thomas-Cormen/dp/026204630X)
* [Coding Train](https://www.youtube.com/channel/UCvjgXvBlbQiydffZU7m1_aw)
* [2021-2022 Bahar Donemi BMB212 Ders Sayfasi](https://github.com/gusanmaz/BMB212_Algorithms)
* [Python Tutor](https://pythontutor.com/)


**Algorithm Visualisation - Algoritma Gorsellestirme**

* [https://visualgo.net/en](https://visualgo.net/en)
* [https://algorithm-visualizer.org/](https://algorithm-visualizer.org/)
* [https://www.cs.usfca.edu/~galles/visualization/Algorithms.html](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)

### Git

![Git vs Renaming](https://github.com/gusanmaz/BMB212_Algorithms/blob/main/images/git_vs_renaming.jpg)

* [Pro Git book](https://git-scm.com/book/en/v2)
* [Turkce Git 101](https://aliozgur.gitbooks.io/git101/content/)
* [Git Basit Rehber](https://rogerdudler.github.io/git-guide/index.tr.html)
* [Yeni Baslayanlar icin Git 101](https://medium.com/@muratcanbur/yeni-ba%C5%9Flayanlar-i%C3%A7in-git-101-ff7ea5b3eff9)
* [Git Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)
* [Git Github Kullanim Rehberi](https://www.enesonmez.com/git-github-nedir-kullanim-rehberi/)
* [Introduction to Git - talk by Scott Chacon](https://youtu.be/xbLVvrb2-fY)
* [Introduction to Git with Scott Chacon of GitHub](https://youtu.be/ZDR433b0HJY)
* [Git 101 | Git, GitHub nedir?](https://youtu.be/nyIdgGD74c4)
* [Git, GitHub ve GitLab Kullanımı Playlist](https://www.youtube.com/playlist?list=PLPrHLaayVkhnNstGIzQcxxnj6VYvsHBHy)

### Terminal Kullanimi

* [Linux Tutorial for Beginners - Learn Linux and the Bash Command Line](https://ryanstutorials.net/linuxtutorial/)
* Windows? [Cygwin](https://www.cygwin.com/)

### Debugging - Hata Ayiklama

![Debugging Cat](https://github.com/gusanmaz/BMB212_Algorithms/blob/main/images/debug_cats.jpeg)

* Break points
* Step into vs. Step over
* Step out
* Variable values
* [IntelliJ IDEA Debugging](https://www.jetbrains.com/help/idea/debugging-code.html)

### Command Line Arguments

* [Command Line Arguments](https://docs.oracle.com/javase/tutorial/essential/environment/cmdLineArgs.html)
* [Java Ornek Kodu - Github Gist](https://gist.github.com/gusanmaz/49dae8ffd1b1511e7c394a259dae785d)
* [Replit Ornek Kodu](https://replit.com/@GuvencUsanmaz/CommandLineArgsJavaExample1)

![Linux CLI Power](https://github.com/gusanmaz/BMB212_Algorithms/blob/main/images/linux_cli.jpg)

Komut satirindan alinan iki tam sayinin toplamini ekrana yazdiran kod:

```java
public class Main {
  public static void main(String args[]) {
    int num1 = Integer.parseInt(args[0]);
    int num2 = Integer.parseInt(args[1]);
    System.out.println(num1 + num2);
  }
}
```

Main.java isimli dosyada saklanabilecek yukarida verilen kodun derlenmesi icin calistirilmasi gereken terminal komutu:

```bash
javac Main.java
```

javac programinin derleme sonrasi olusturdugu calistirilabilir program Main.class'in calistirilmasi:

```bash
java Main 4 5 
```

Calistirilan programin ciktisi:

```bash
9
```

# 



