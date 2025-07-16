![eu](https://raw.githubusercontent.com/diogolang/diogolang/main/eu.jpg)

# 👋 Olá, sou Diogo Vasconcelos

Sou aquele desenvolvedor que adora transformar ideias em **código vivo e funcional**. Minha jornada no desenvolvimento web me levou a explorar e dominar várias tecnologias e ferramentas modernas.

---

## ⚙️ Sobre mim em forma de código Go

```go
package main

import (
	"fmt"
        "sync"
	"time"
)

// Developer representa um desenvolvedor apaixonado por tecnologia e boas práticas.
type Developer struct {
	Name        string
	Languages   []string
	Frameworks  []string
	Databases   []string
	Tools       []string
	Expertise   []string
	Passions    []string
        GitHub      string
        LinkedIn    string
	Available   bool
}

// Code transforma ideias em software funcional.
func (d Developer) Code() {
	fmt.Println("💡 Transformando ideias em código funcional e elegante.")
}

// Learn mostra o compromisso com aprendizado contínuo.
func (d Developer) Learn(newTech string) {
	fmt.Printf("🔍 Explorando %s para entregar soluções cada vez melhores.\n", newTech)
}

// Build representa a construção de soluções completas.
func (d Developer) Build() {
	fmt.Println("🏗️ Construindo aplicações web do front ao banco de dados.")
}

func (d Developer) Focus(area string) {
	fmt.Printf("🔭 Aprofundando conhecimentos em %s para construir soluções de alta qualidade.\n", area)
}

// DeployService simula o deploy de um serviço específico em paralelo.
func (d Developer) DeployService(service string, wg *sync.WaitGroup) {
	defer wg.Done()
	fmt.Printf("🚀 Iniciando o deploy de %s...\n", service)
	time.Sleep(time.Second * 1 + time.Duration(len(service))*time.Millisecond*200) // Simula tempo de deploy variável
	fmt.Printf("✅ %s foi deployado com sucesso!\n", service)
}

func (d Developer) ShowcaseParallelDeploy() {
	fmt.Println("\n⚙️ Demonstrando o deploy paralelo de serviços:")

	services := []string{"Frontend", "Backend API", "Banco de Dados", "Serviços de Cache"}
	var wg sync.WaitGroup

	for _, service := range services {
		wg.Add(1)
		go d.DeployService(service, &wg)
	}

	wg.Wait() // Espera todos os serviços serem deployados
	fmt.Println("\n🎉 Todos os serviços foram deployados em paralelo!")
}

func (d Developer) Connect() {
	fmt.Printf("\n🤝 Conecte-se comigo no GitHub: %s ou LinkedIn: %s para explorarmos juntos o futuro da tecnologia!\n", d.GitHub, d.LinkedIn)
}

func main() {
	diogo := Developer{
		Name: "Diogo Vasconcelos",
		Languages: []string{
			"Go", "PHP", "Python", "TypeScript",
		},
		Frameworks: []string{
			"Laravel", "NestJS", "Next.js", "React", "Tailwind CSS",
		},
		Databases: []string{
			"PostgreSQL",
		},
		Tools: []string{
			"Docker",
		},
		Expertise: []string{
			"APIs RESTful e seguras",
			"Arquitetura de microsserviços",
			"Desenvolvimento Back-end escalável",
			"Front-end responsivo",
			"SEO",
		},
		Passions: []string{
			"Código limpo e bem documentado",
			"Performance e escalabilidade",
			"Resolução de problemas complexos",
                        "Cultura de aprendizado e colaboração",
		},
                GitHub: "github.com/DioGolang"
                LinkedIn:  "linkedin.com/in/diogolang",
		Available: true,
	}

	fmt.Printf("👋 Olá, eu sou %s!\n", diogo.Name)
	diogo.Code()
	diogo.Build()
        diogo.ShowcaseParallelDeploy()
	diogo.Learn("as melhores práticas do futuro")

	fmt.Println("\n✨ Minhas principais áreas de especialidade incluem:")
	for _, expertise := range diogo.Expertise {
		fmt.Printf("🚀 %s\n", expertise)
	}

	fmt.Println("\n💡 No meu dia a dia, sou movido por:")
	for _, passion := range diogo.Passions {
		fmt.Printf("🔥 %s\n", passion)
	}

	diogo.Focus("Arquiteturas escaláveis e performantes")

	if diogo.Available {
		fmt.Println("\n✅ Atualmente disponível para novos desafios e oportunidades!")
	} else {
		fmt.Println("\n⏳ No momento, estou focado em projetos existentes, mas aberto a conversas futuras.")
	}

        diogo.Connect()
        time.Sleep(time.Hour * 24 * 365) // ⏳ Sempre aprendendo, sempre evoluindo...
}
```

## O que o código acima significa?

Meu foco é projetar arquiteturas de microsserviços escaláveis e resilientes (como demonstrado na função ShowcaseParallelDeploy), aplicando princípios de Domain-Driven Design (DDD) e Clean Architecture. Sou apaixonado por código limpo, performance e por resolver problemas complexos, sempre buscando as melhores ferramentas para o trabalho, como Go, TypeScript, Docker e PostgreSQL.

---

- 💡 Transformando ideias em código funcional e elegante
- 🏗️ Construindo aplicações web do front ao banco de dados
- 🔍 Explorando novas tecnologias para entregar soluções cada vez melhores
- 🔭 Focado em arquiteturas escaláveis e performantes

---

## 🚀 Tecnologias e ferramentas

Utilizo Go para construir microsserviços performáticos e com alta concorrência. Adoto TypeScript com NestJS para criar APIs robustas e escaláveis com princípios de DDD. Orquestro tudo com Docker e Kubernetes para garantir resiliência e escalabilidade, e uso RabbitMQ para a comunicação assíncrona em arquiteturas orientadas a eventos.

---

## ✨ Especialidades

    APIs RESTful e seguras

    Arquitetura de microsserviços

    Desenvolvimento Back-end escalável

    Front-end responsivo

    Otimização para SEO
---

## 🌟 Paixões

- Código limpo e bem documentado
- Performance e escalabilidade
- Resolução de problemas complexos
- Cultura de aprendizado e colaboração

---

## ⚙️ Deploy Paralelo de Serviços (Simulado)

```bash

🚀 Iniciando o deploy de Frontend...
🚀 Iniciando o deploy de Backend API...
🚀 Iniciando o deploy de Banco de Dados...
🚀 Iniciando o deploy de Serviços de Cache...
✅ Frontend foi deployado com sucesso!
✅ Banco de Dados foi deployado com sucesso!
✅ Backend API foi deployado com sucesso!
✅ Serviços de Cache foi deployado com sucesso!

🎉 Todos os serviços foram deployados em paralelo!

```

## 📬 Conecte-se comigo

- 🤝 Vamos explorar juntos o futuro da tecnologia!
- 🔗 GitHub
- 🔗 LinkedIn

---

## ✅ Disponível para novos desafios!

⏳ Sempre aprendendo, sempre evoluindo...

```go
for {
    Learn("novas tecnologias")
    Build()
    ShareKnowledge()
}
```

---

### 🤝 Vamos construir algo incrível juntos?

#DesenvolvedorFullStack #CientistaDeDados #React #Python #TailwindCSS #Node #Go #MachineLearning #SQL #Git #Docker #NestJS #NextJS

Here are some ideas to get you started:

- 👨‍🎓 Studying Computer Engineering (UNIVESP)
- 💻 I love programming
- 🔭 I’m currently working on ...
- 📕 I’m currently learning software engineering concepts
- ☕ I Love Coffee


<div style="display: inline_block">
    <img height=200  src="https://github-readme-stats.vercel.app/api/top-langs/?username=diogolang&layout=compact&theme=dracula&langs_count=10">
    <img height=200  src="https://github-readme-streak-stats.herokuapp.com/?user=diogolang&theme=dracula&hide_border=false">
</div>

 <!-- img height=200  src="https://github-readme-stats.vercel.app/api?username=diogolang&show_icons=true&theme=dracula" -->
   
##

<img align="center" alt="vasco-Python" src="https://repository-images.githubusercontent.com/521515652/d0a2676e-2a17-4ad1-8e2d-54dc08db0db7">

##
### ❤️‍🔥 I love these technologies and I use them 
<div style="display: inline_block">    
  <br>
<img align="center" alt="vasco-Python" height="70" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
<img align="center" alt="vasco-Js" height="70" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg">
<img align="center" alt="vasco-Csharp" height="80" width="100" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg">
<img align="center" alt="vasco-Ts" height="80" width="100"src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg">
<img align="center" alt="vasco-Ts" height="50" width="60"src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
<img align="center" alt="vasco-Ts" height="50" width="60"src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg">
<img align="center" alt="vasco-React" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nestjs/nestjs-original.svg">
<img align="center" alt="nextjs-original" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg">
<img align="center" alt="express-original" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg">
<img align="center" alt="laravel-original." height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-original.svg">
<!--img align="center" alt="react-original" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" -->
<img align="center" alt="docker-original" height="90" width="77" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg">
<img align="center" alt="kubernetes" height="65" width="57" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kubernetes/kubernetes-original.svg" />      
<img  align="center" alt="terraform-original" height="60" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/terraform/terraform-original.svg" />
<img align="center" alt="yaml-original" height="50" width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/yaml/yaml-original.svg">
<img align="center" alt="git-original" height="70" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg">
<img align="center" alt="vasco-React" height="70" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg">
<img align="center" alt="amazonwebservices" height="80" width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg">
<img align="center" alt="googlecloud" height="80" width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/googlecloud/googlecloud-original.svg">
<img align="center" alt="linux-original" height="60" width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg">
<img align="center" alt="fedora" height="60" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fedora/fedora-original.svg" />
<img align="center" alt="linux-original" height="60" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redhat/redhat-original.svg" />          
<img align="center" alt="postgresql-original" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg">
<img align="center" alt="vasco-React" height="80" width="100" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg">
<img align="center" alt="mongodb" height="72" width="81" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg" />
<img align="center" alt="mongoose" height="72" width="81" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongoose/mongoose-original.svg" />      
<img align="center" alt="rabbitmq-original" height="50" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rabbitmq/rabbitmq-original.svg" />
<img align="center" alt="vasco-HTML" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
<img align="center" alt="tailwindcss" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg">
<img align="center" alt="bootstrap-original" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-original.svg">
<img align="center" alt="vasco-CSS" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
<img align="center" alt="pycharm-original" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pycharm/pycharm-original.svg">
<img align="center" alt="goland" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/goland/goland-original.svg">
<img align="center" alt="datagrip" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/datagrip/datagrip-original.svg">
<img align="center" alt="dataspell" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dataspell/dataspell-original.svg">
<img align="center" alt="phpstorm-original" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/phpstorm/phpstorm-original.svg">
<img align="center" alt="webstorm" height="50" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/webstorm/webstorm-original.svg">

</div>

##

<div align="center">

  <a href="https://www.linkedin.com/in/diogolang" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  <a href="#" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
 <a href="https://discord.gg/diogolang" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a> 

</div>
 
##

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/devsvasconcelos/devsvasconcelos/output/github-contribution-grid-snake-dark.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/devsvasconcelos/devsvasconcelos/output/github-contribution-grid-snake.svg">
</picture>

##
### Number of visitors

<img src="https://profile-counter.glitch.me/%7Bdiogolang%7D/count.svg">

<!-- ![visitors](https://visitor-badge.laobi.icu/badge?page_id=diogolang) -->

##

<!--

<div align="center">
  
  [![github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=diogolang&bg_color=0d1117&color=c535d0&line=d1056c&point=d1056c&area=true&area_color=d1056c&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)
</div>

-->

<!--

<div align="center">
  <img src="https://streak-stats.demolab.com?user=diogolang&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5&order=3" height="150" alt="streak graph"  />
  <img src="https://github-profile-trophy.vercel.app?username=diogolang&theme=dracula&column=-1&row=1&margin-w=8&margin-h=8&no-bg=false&no-frame=false&order=4" height="150" alt="trophy graph"  />
</div>

-->

<!--

<div align="center" style="width: 100%">
  <a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@diogo.vasconcelos/0">
    <img style="width: 100%" src="https://github-readme-medium-recent-article.vercel.app/medium/@diogo.vasconcelos/0" alt="Medium post 1"  />
  </a>
  <a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@diogo.vasconcelos/1">
    <img style="width: 100%" src="https://github-readme-medium-recent-article.vercel.app/medium/@diogo.vasconcelos/1" alt="Medium post 2"  />
  </a>
  <a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@diogo.vasconcelos/2">
    <img style="width: 100%" src="https://github-readme-medium-recent-article.vercel.app/medium/@diogo.vasconcelos/2" alt="Medium post 3"  />
  </a>
</div>

-->

