# Hello World!

### ... I'm Martin, nice to meet you! 👀


```go

type Person struct {
	Name        string
	Age         int
	Nationality string
	Company     string
	Student     bool
}

func (p *Person) SayHello() {
	fmt.Println("Hello world!")
	firstName := strings.Split(p.Name, " ")[0]
	fmt.Println("... I'm " + firstName + ", nice to meet you! 👀")
}

func main() {
	me := Person{
		Name:        "Martin Pech",
		Age:         25,
		Nationality: "Czechia",
		Company:     "Simplo s.r.o",
		Student:     true,
	}
	me.SayHello()
}
```
I'm a passionate _Backend developer_ and freelance _Software engineer_ from Brno, Czechia. In 2016 I made my first steps in the world of software development and since then I have been part of many interesting projects.

- Are you dreaming of any kind of software application? [Tell me abour your idea!](https://mpech.net/projectStarter)! 

- Do you want to find out more? Visit my [website](https://mpech.net/developer)!

<h3 align="center">Languages and Tools</h3>

<p align="center">
  <a href="https//mpech.net">
    <img src="https://skillicons.dev/icons?i=laravel,php,mysql,docker,sentry,bash,regex,vim,unity,blender,html,css,bootstrap,js,electron" />
  </a>
</p>

<p align="center">
  <a href="https//mpech.net">
    <img src="https://skillicons.dev/icons?i=py,cpp,cs,lua,java,powershell,visualstudio,git,github,figma,materialui,latex,mongodb" />
  </a>
</p>

<h3 align="center">Stay in touch</h3>


<p align="center">
  <a href="mailto:dev@mpech.net" target="_blank">
    <img src="https://github.com/martafonekVOLE/images/blob/main/email.png?raw=true" height="50px" />
  </a>
  
  <a href="https://www.linkedin.com/in/pechmar/" target="_blank">
    <img src="https://skillicons.dev/icons?i=linkedin" />
  </a>
    
  <a href="https://mpech.net" target="_blank">
    <img src="https://github.com/martafonekVOLE/images/blob/main/world-wide-web.png?raw=true", height="50px">
  </a>
</p>


<!---
martafonekVOLE/martafonekVOLE is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
