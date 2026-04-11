![eu](https://raw.githubusercontent.com/diogolang/diogolang/main/eu.jpg)

# 👋 Diogo Vasconcelos

### 🚀 Go Backend Engineer | Microsservices | Distributed Systems | High Performance APIs

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Backend](https://img.shields.io/badge/Backend-Engineering-0A0A0A?style=for-the-badge)
![Microservices](https://img.shields.io/badge/Microservices-Architecture-blue?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Status](https://img.shields.io/badge/Status-Open%20to%20Work-00C853?style=for-the-badge)

---

## 🧠 Sobre mim

Sou desenvolvedor focado em **backend com Go**, especializado em **microsserviços, concorrência e sistemas distribuídos**.

💡 Transformo problemas complexos em soluções simples, performáticas e escaláveis.

⚙️ Experiência com APIs robustas, mensageria, containers e arquitetura orientada a eventos.

---

## ⚙️ Who am I in Go?

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

#DesenvolvedorFullStack #React #Python #TailwindCSS #Node #Go #MachineLearning #SQL #Git #Docker #NestJS #NextJS

Here are some ideas to get you started:

- 👨‍🎓 Studying Computer Engineering (UNIVESP)
- 💻 I love programming
- 🔭 I’m currently working on ...
- 📕 I’m currently learning software engineering concepts
- ☕ I Love Coffee


<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=diogolang&show_icons=true&theme=dracula"/>
<img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=diogolang&theme=dracula"/>

</div>

 <!-- img height=200  src="https://github-readme-stats.vercel.app/api?username=diogolang&show_icons=true&theme=dracula" -->
   
##

<img align="center" alt="vasco-Python" src="https://repository-images.githubusercontent.com/521515652/d0a2676e-2a17-4ad1-8e2d-54dc08db0db7">

## 🚀 Tech Stack

### 🧠 Backend
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="Go"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="NodeJS">

### 🎨 Frontend
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" alt="Next.js"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" alt="TailwindCSS"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript">

### ⚙️ DevOps & Cloud
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-original.svg" alt="Kubernetes"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" alt="Terraform"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS">

### 🗄️ Databases & Messaging
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rabbitmq/rabbitmq-original.svg" alt="RabbitMQ">

### 🛠️ Tools
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" alt="GitHub"> &nbsp;&nbsp;&nbsp;&nbsp;
<img height="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux">
<div align="center">

  <a href="https://www.linkedin.com/in/diogolang" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  <a href="#" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
 <a href="https://discord.gg/diogolang" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a> 

</div>

---

## 🧠 Engineering Mindset

- 🧩 Design orientado a domínio (DDD)
- ⚡ Sistemas distribuídos e resilientes
- 🚀 Alta concorrência com Go (goroutines & channels)
- 📦 Arquitetura orientada a eventos
- 🔍 Observabilidade e performance

---

## 🏗️ Observability & Reliability Stack

> "If it’s not monitored, it’s not in production."

Eu projeto sistemas focados em transparência operacional, utilizando o padrão **OpenTelemetry (OTel)** para evitar vendor lock-in e garantir uma visão holística da saúde do sistema.

### 📊 Monitoring Strategy

* **Metrics (Prometheus & Grafana):** Implementação de métricas **RED** (Rate, Errors, Duration) para serviços e **USE** (Utilization, Saturation, Errors) para infraestrutura.
* **Distributed Tracing (Jaeger & Tempo):** Rastreamento de requisições cross-service para identificar gargalos de latência e falhas em cascatas em arquiteturas de microsserviços.
* **Structured Logging (Zap & Loki):** Logs estruturados (JSON) correlacionados com `trace_id` para depuração precisa e análise de causa raiz.

### 🛠️ Tooling
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-65D3E3?style=for-the-badge&logo=jaeger&logoColor=white)

---


<!--

## 💼 Projetos Recentes
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
<a href="https://github.com/diogolang/projeto1"><img src="https://img.shields.io/badge/Projeto1-Go%20Backend-00ADD8?style=for-the-badge" /></a>
<a href="https://github.com/diogolang/projeto2"><img src="https://img.shields.io/badge/Projeto2-React%20Frontend-61DAFB?style=for-the-badge" /></a>
<a href="https://github.com/diogolang/projeto3"><img src="https://img.shields.io/badge/Projeto3-NestJS%20API-E0234E?style=for-the-badge" /></a>
</div>

-->

---

## 📬 Let's build something great

💼 Open to opportunities  
🚀 Always working on scalable systems  

<div style="display: flex; gap: 10px;">
<a href="https://github.com/diogolang"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://linkedin.com/in/diogolang"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<!--<a href="https://discord.gg/diogolang"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" /></a> -->
</div>

<!-- ![Profile Views](https://komarev.com/ghpvc/?username=diogolang&style=for-the-badge&color=blue) -->

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

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/devsvasconcelos/devsvasconcelos/output/github-contribution-grid-snake-dark.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/devsvasconcelos/devsvasconcelos/output/github-contribution-grid-snake.svg">
</picture>
