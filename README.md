<div align="center">

```
Hello!
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FF41&background=00000000&center=true&vCenter=true&width=600&lines=Systems+programmer+%7C+Driver+dev;C+%2B+Rust+%7C+Bare+metal+enjoyer;NixOS+%7C+Arch+%7C+FreeBSD;Writing+code+the+kernel+understands)](https://git.io/typing-svg)

</div>

---

## `$ whoami`

```c
typedef struct {
    char   *name;
    char   *role;
    char  **langs;
    char  **systems;
    bool    learning_rust;
} Developer;

Developer me = {
    .name        = "your_username",
    .role        = "Systems Programmer & Hobbyist Driver Dev",
    .langs       = (char*[]){"C", "Rust", "Shell", NULL},
    .systems     = (char*[]){"NixOS", "Arch Linux", "FreeBSD", NULL},
    .learning_rust = true,
};
```

---

## `$ cat /proc/skills`

<div align="center">

### Languages
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Systems
![NixOS](https://img.shields.io/badge/NixOS-5277C3?style=for-the-badge&logo=nixos&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![FreeBSD](https://img.shields.io/badge/FreeBSD-AB2B28?style=for-the-badge&logo=freebsd&logoColor=white)

### Tools
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-FF6600?style=for-the-badge&logo=gnu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D4C41?style=for-the-badge&logo=cmake&logoColor=white)

</div>

---

## `$ ls -la ~/projects`

```
drwxr-xr-x  driver-experiments/    → Hobby kernel modules & device drivers
                                     (NixOS, Arch, FreeBSD)
drwxr-xr-x  rust-learning/         → Rewriting my C habits in Rust, one
                                     borrow checker fight at a time
drwxr-xr-x  dotfiles/              → NixOS configs & reproducible setups
drwxr-xr-x  low-level-stuff/       → Pointers, memory, and regret
```

---

## `$ dmesg | grep interests`

```
[    0.000000] Kernel module development initialized
[    0.042000] Device driver subsystem: hobby mode enabled
[    0.108000] Memory management: manual (no GC allowed)
[    0.256000] Rust borrow checker: humbling me daily
[    0.512000] NixOS: because reproducibility matters
[    1.024000] FreeBSD: respecting the old ways
[    2.048000] Arch Linux: btw
```

---

## `$ cat ~/.config/currently_learning`

```rust
fn main() {
    let learning: Vec<&str> = vec![
        "Rust ownership model",
        "Writing safe abstractions over unsafe C",
        "FreeBSD driver model differences",
        "Async I/O at the kernel level",
    ];

    for topic in &learning {
        println!("[ IN PROGRESS ] {}", topic);  // lifetime: 'forever
    }
}
```
