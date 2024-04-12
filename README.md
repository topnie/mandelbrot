# Mandelbrot
Program używający C oraz asemblera nasm, aby generować na żywo zbiór Mandelbrota.
Program używa bibliotek OpenGL oraz glwf.
Część w C zbiera input użytkownika i wywołuje funkcję w asemblerze, która oblicza wyświetlaną bitmapę.
W otwartym okienku można poruszać widokiem strzałkami, oraz przybliżać i oddalać widok scrollem.

Program można skompilować używając make, a następnie wywołać komendą `./display width`, gdzie width jest wielkością
okna programu w pikselach.
