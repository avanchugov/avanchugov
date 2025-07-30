<p align="center">
    <img src="s.png" alt="image">
</p>

## 🧾 About Me

Distributed systems engineer / Back-End developer. Work with MySQL, PostgreSQL, microservice architecture, distributed systems, RESTful APIs and other tech. I have SaaS project (with HMAC, tokens, HWID, etc.), experience in bot development, commercial projects, development in C. Commercial experience, Joint development (TypeScript&Java), Contributing in Open-Source, CS/DS knowledge.

I'm interested in neuropsychology and psychoanalysis.

Open to collaboration.

```assembly
section .data
  name db "Artemy Vanchugov", 0xA
  age db 15
  music db "According to my mood", 0xA
  telegram db "https://t.me/a_vanchugov", 0xA
  msg db "Someone in the world is having fun, someone is feeling good. Everyone`s had some luck in life - but I wasn`t lucky."
  message_len equ $ - msg

section .text
  global _start

_start:
  mov rax, 1
  mov rdi, 1
  mov rsi, msg
  mov rdx, message_len
  syscall

_end:
  mov rax, 60
  syscall
```

<br>

## 📁 My Projects

<table>
  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/ModularORM">ModularORM</a></b><br/>
      Lightweight and modular ORM for TypeScript with built-in query builder.<br/>
      <sub><code>TypeScript</code> • <code>MySQL</code> • <code>npm</code></sub>
    </td>
  </tr>
  
  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/Time">Time</a></b><br/>
      Library focused on time formatting and convenient manipulation<br/>
      <sub><code>TypeScript</code> • <code>Datetime</code> • <code>npm</code></sub>
    </td>
  </tr>
  
  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/FineHTTP">FineHTTP</a></b><br/>
      Simple library that will help you type standard fetch and automate some actions.<br/>
      <sub><code>TypeScript</code> • <code>fetch</code> • <code>npm</code></sub>
    </td>
  </tr>

  
  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/ctest">cTEST</a></b><br/>
      This is a simple and lightweight C library that will allow you to test your application and see the test results right in the console.<br/>
      <sub><code>C</code> • <code>tests</code> • <code>lightweight</code></sub>
    </td>
  </tr>

  
  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/docker-cli-tool">DockerCLI</a></b><br/>
      A console utility that allows you to easily create Dockerfile and docker-compose with a single command.<br/>
      <sub><code>C</code> • <code>cli</code> • <code>docker</code></sub>
    </td>
  </tr>

  <tr>
    <td valign="top">
      <b><a href="https://github.com/KoP3YkA/mysql-c-driver">MySQL C Driver</a></b><br/>
      This is an unfinished project that was supposed to be a mysql driver in C, with which you could send SQL queries through a single function, directly in C.<br/>
      <sub><code>C</code> • <code>mysql</code> • <code>driver</code></sub>
    </td>
  </tr>
</table>

<br>

<br>

## ⚙️ My Stack
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,js,nodejs,git,github,gitlab,discordjs,mysql,sqlite,nestjs,redis,npm,jest,java,python,docker,c" />
  </a>
</p>


