[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=18375442)
# ICS3U ⇢ Unit #X-YY

[![Mr Coxall's Super Linter](https://github.com/<OWNER>/<REPOSITORY>/workflows/Mr%20Coxall's%20Super%20Linter/badge.svg)](https://github.com/<OWNER>/<REPOSITORY>/actions)

[![CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-blue.svg)](./LICENSE)

---

**Python**
- to interpret your python program
```console
  python main.py
```
- to run black to lint your python code
```console
  black --check --diff ./*.py
```

**C**
- to compile and run your C program
```console
  gcc ./Main.c -o ./ Main.app
  ./Main.app
```
- if you are using CS50's C Library then
```console
  gcc ./Main.c -o ./ Main.app -lcs50
  ./Main.app
```
- to run cpplint to lint your C code
```console
  cpplint ./*.c
```

**GitHub**
- ensure you commit your code after every major change, to keep your history and not loose anything
```console
  git add -A
  git commit -m "𝑐𝑜𝑚𝑚𝑖𝑡 𝑚𝑒𝑠𝑠𝑎𝑔𝑒"
  git push origin main
```
