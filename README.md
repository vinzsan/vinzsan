<h2 align="center">🌸 Vin's GitHub Config 🌸</h2>
<h2 align="center">tiny femboys -w-</h2>
<h3 align="center">gym for my thigs >:3</h3>
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?center=true&vCenter=true&lines=Hi+there~+I'm+Vin!;+C+lover+with+a+bit+of+pink+code~+🩷;I+build+lowlevel+tools+and+write+bare-metal+stuff!">
</p>

---

### 💫 About Me
- 🧠 High school student, deeply in love with **C**, **assembly**, and **low-level systems**.
- 🔧 I make simple tools using **syscalls**, sometimes without any libc.
- 🌐 Currently experimenting with **barebone networking**, **direct I/O**, and **game rendering** using **Raylib** or **SDL**.
- 🎀 Occasionally I sprinkle some aesthetics into my code. Who says low-level can't be a little cute? >w<

---

### 🛠️ Tech Skill Overview
| Language      | Experience % | Description |
|---------------|--------------|-------------|
| 🧠 C          | **50%**       | My main playground — from system calls to embedded apps. |
| ⚙️ Assembly   | **50%**       | Mostly x86 (32-bit & 64-bit), writing syscalls and boot code. |
| 💻 C++        | **10%**       | Used in certain structured projects (Raylib, OOP-style logic). |

---

## Still Learn!

---

### 🌷 Favorite Syntax -w-
```c
int main() {
      char *str = "UwU~";
      unsigned long length = 5;
     __asm__ __volatile__(
		       "movq $1,%%rax\n\t"
		       "movq $1,%%rdi\n\t"
		       "movq %0,%%rsi\n\t"
		       "movq %1,%%rdx\n\t"
		       "syscall"
		       :
		       :"r"(str),"r"(length)
		       :"rax","rdi","rsi","rdx"
		);
    return 0;
}
