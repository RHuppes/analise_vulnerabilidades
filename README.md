# Desafio: Criação de Cenários Controlados para Simulação de Vulnerabilidades

## 📖 Descrição
Este projeto foi desenvolvido como parte do desafio da DIO, com o objetivo de criar **cenários controlados** para estudar e simular vulnerabilidades em aplicações, aplicando os conceitos de segurança aprendidos no curso.

## 🎯 Objetivos
- Criar ambientes práticos de simulação de vulnerabilidades.
- Aplicar conceitos de segurança em cenários controlados.
- Documentar todo o processo de forma clara.
- Utilizar o GitHub para versionamento e compartilhamento da documentação.

## 🛠️ Tecnologias Utilizadas
- [VirtualBox](https://www.virtualbox.org/) / [VMware] ou [Azure](https://portal.azure.com/)  
- [Kali Linux](https://www.kali.org/) (máquina atacante)  
- [DVWA](http://www.dvwa.co.uk/) - Damn Vulnerable Web Application (máquina vulnerável)  
- Git e GitHub para documentação  

## 🚀 Cenário Montado
1. **Máquina Atacante**: Kali Linux, configurada para realizar testes de penetração.  
2. **Máquina Vulnerável**: DVWA instalada em servidor Apache + MySQL.  
3. **Rede Virtual**: As VMs foram configuradas em rede interna para isolar os testes.  

## 🔍 Vulnerabilidades Simuladas
- SQL Injection
- Cross-Site Scripting (XSS)
- Brute Force Authentication
- File Upload inseguro

## 📸 Evidências
As capturas de tela do ambiente e dos testes estão disponíveis na pasta `/images`.

## 📂 Estrutura do Repositório
├── README.md
├── /images
│ ├── vm-setup.png
│ ├── dvwa-login.png
│ └── sql-injection-test.png

## 📑 Conclusão
Este projeto proporcionou a criação de um **laboratório de segurança controlado**, permitindo praticar ataques comuns e compreender como corrigi-los.  
A experiência reforçou a importância da segurança desde o desenvolvimento até a implantação de sistemas.  

---
👨‍💻 Autor: Rafael Huppes  
📌 Projeto desenvolvido para o **Desafio DIO**
