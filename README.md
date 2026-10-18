# 🎓 42 — Rank 02

Rank 02 of the 42 curriculum: stack sorting, UNIX signal communication, 2D graphics, and a programming exam.

![Rank](https://img.shields.io/badge/42%20Rank-02-5c6ac4?style=for-the-badge)
![Time](https://img.shields.io/badge/Estimated%20time-160%20hours%20%2B%20exam-007ec6?style=for-the-badge)

---

## 📚 Projects

| Project | Grade | Time | Main topic |
|---|---:|---:|---|
| 📚 [push_swap](https://github.com/MariaBarreiro/42_Push_Swap) | **84/100** | ~50 h | Sorting stacks with limited operations |
| 📡 [minitalk](https://github.com/MariaBarreiro/42_Minitalk) | **125/125** | ~50 h | UNIX signals and data exchange |
| 🎮 [so_long](https://github.com/MariaBarreiro/42_So_Long) | **100/100** | ~60 h | 2D game development with MiniLibX |
| ⏱️ [Exam Rank 02](https://projects.intra.42.fr/projects/exam-rank-02) | **100/100** | 7 days reported | Programming assessment |

**Total: 409/425 · about 160 project hours, plus the exam**

---

## 📚 push_swap

> Sort integers using two stacks and a limited set of operations, aiming to minimize moves.

![Grade](https://img.shields.io/badge/Grade-84%2F100-orange?style=flat-square)
![Time](https://img.shields.io/badge/Time-~50%20hours-blue?style=flat-square)

**What I learned**
- How to represent and manipulate stacks
- How to compare sorting strategies and optimize operation counts
- How to handle input validation and edge cases

**Compile and run**

```sh
make
./push_swap 2 1 3 6 5 8
```

The program prints the operations needed to sort the input.

---

## 📡 minitalk

> Send a message between a client and server using UNIX signals.

![Grade](https://img.shields.io/badge/Grade-125%2F125-brightgreen?style=flat-square)
![Time](https://img.shields.io/badge/Time-~50%20hours-blue?style=flat-square)

**What I learned**
- How to send and handle UNIX signals
- How to encode and decode characters as bits
- How to coordinate communication between processes

**Compile and run**

```sh
make
```

In one terminal, start the server and note its PID:

```sh
./server
```

In another terminal, send it a message:

```sh
./client <server_pid> "Hello from minitalk"
```

---

## 🎮 so_long

> Build a small 2D game: collect every item, then reach the exit.

![Grade](https://img.shields.io/badge/Grade-100%2F100-brightgreen?style=flat-square)
![Time](https://img.shields.io/badge/Time-~60%20hours-blue?style=flat-square)

**What I learned**
- How to render a map with textures and sprites
- How to handle player movement and window events
- How to parse and validate a map, including checking for a valid path

**Compile and run**

```sh
make
./so_long Maps/map.ber
```

The repository includes MiniLibX, Libft, and sample maps.

---

## ⏱️ Exam Rank 02

> A timed assessment of programming ability and knowledge.

![Grade](https://img.shields.io/badge/Grade-100%2F100-brightgreen?style=flat-square)
![Time](https://img.shields.io/badge/Time-7%20days%20reported-lightgrey?style=flat-square)

This exam is completed in the 42 exam environment. The tasks are compiled and evaluated there; no GitHub repository was included in this Rank 02 list.
