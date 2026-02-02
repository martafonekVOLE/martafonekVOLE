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
#### About me
I am a Software Engineer with a strong focus on backend development and system architecture. I combine hands-on experience in Laravel with familiarity in Rust, Java, and Go, along with a deep understanding of APIs, databases, and containerized environments. My work bridges clean software design and practical implementation, ensuring efficient and maintainable systems.

🏫 - Master's student @ MUNI FI

👨‍💼 - Laravel developer @ Simplo s.r.o.

Checkout my work here 👉 [mpech.net](https://mpech.net/)

---

#### Do you have project of any kind in mind? Tell me more, I might be the right person to help you 🤠
Share your ideas 👉 [Send me an email!](mailto:dev@mpech.net)

---

<h3 align="center">Tech Stack</h3>

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
