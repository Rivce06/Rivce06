#  👋 Hi there! I'm Andres

I'm an **Junior DevOps Engineer** with 2+ years of experience in Technical Support and a strong passion for automation, cloud infrastructure, and modern software delivery.

``` _      _ _         __        __         _     _ 
 | | | | ___| | | ___     \ \      / /__  _ __| | __| |
 | |_| |/ _ \ | |/ _ \     \ \ /\ / / _ \| '__| |/ _` |
 |  _  |  __/ | | (_) |     \ V  V / (_) | |  | | (_| |
 |_| |_|\___|_|_|\___( )     \_/\_/ \___/|_|  |_|\__,_|
                     |/           Junior DevOps 🛠️      

```

` #!/usr/bin/env python3`

`import time`

```
def typewriter(text, delay=0.02):
    for char in text:
        print(char, end='', flush=True)
        time.sleep(delay)
    print()
```
```
def separator():
    print("\n" + "=" * 50 + "\n")

def intro():
    separator()
    typewriter(3"👋 Hi there! I'm Andres")
    typewriter("🚀 Junior DevOps Engineer with 2+ years in Technical Support")
    typewriter("🔧 Passionate about automation, cloud infrastructure & modern DevOps workflows")
    separator()
```
```
def install_command():
    typewriter("💻 Installing profile...")
    typewriter("➜  $ sudo apt install andres-devops", 0.04)
    separator()
```
```
def tech_stack():
    typewriter("🛠️ Tech Stack:")
    stack = {
        "☁️ Cloud": "AWS (EC2, IAM, S3)",
        "📦 IaC": "Terraform",
        "🐳 Containers": "Docker",
        "☸️ Orchestration": "Kubernetes",
        "🔁 CI/CD": "GitHub Actions",
        "💻 Scripting": "Bash, Python"
    }
    for k, v in stack.items():
        typewriter(f"  {k}: {v}")
    separator()
```
```
def learning_focus():
    typewriter("🎯 Currently focused on:")
    focus = [
        "🚧 Building a mini DevOps pipeline (Terraform + AWS + GitHub Actions)",
        "📦 Running containers and learning Helm charts",
        "🔐 Studying IAM roles and policies",
        "⚙️ Automating infrastructure with IaC"
    ]
    for item in focus:
        typewriter(f"  - {item}")
    separator()
```
```
def courses():
    typewriter("📚 Courses & Learning:")
    courses = {
        "AWS Cloud Practitioner": False,
        "Docker & Kubernetes (Udemy)": True,
        "Terraform Basics (Udemy)": True,
        "Git & GitHub (freeCodeCamp)": True
    }
    for name, completed in courses.items():
        status = "[x]" if completed else "[ ]"
        typewriter(f"  {status} {name}")
    separator()
```
```
def connect():
    typewriter("🌍 Let's connect:")
    links = {
        "🔗 LinkedIn": "https://www.linkedin.com/in/andres-rivera0608",
        "🐙 GitHub": "https://github.com/Rivce06",
        "📧 Email": "mailto:gvenegas7978@gmail.com"
    }
    for label, url in links.items():
        typewriter(f"  {label}: {url}")
    separator()
```
```
if __name__ == "__main__":
    intro()
    install_command()
    tech_stack()
    learning_focus()
    courses()
    connect()
```
