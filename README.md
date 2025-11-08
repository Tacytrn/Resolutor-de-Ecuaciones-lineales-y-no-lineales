# Resolutor-de-Ecuaciones-lineales-y-no-lineales
Es un proyecto basado en Python que implimineta 6 metodos para encontrar raíces de ecuaciones no lineales como:

-a) Métodos de Bracketing:
  1. Bisección.
  2. Falsa posicipon
  3. Brent

b) Métodos abiertos:
  1. Punto Fijo
  2. Newton-Raphson
  3. Secante

.
├─ README.md
└─ Trabajo2Final.ipynb   # Notebook con el código y la demo


----Como usar el código----
En el último bloque, el numero 7, tenemos la demo, cual podemos editar para cambiar la función que los métodos evaluan. 

En nuestra celda de DEMO, solo cambiamos estas partes:
1. La función objetivo f(x).
2. La derevida df(x).
3. La transformación g(x) //ACLARACIÓN: Solo para punto fijo, ya que se necesita cumplir x = g(x).
4. Los parametros de inicio como f(a)*¨f(b) < 0.

Un ejemplo extra que se podría poner en la DEMO.
f(x)=x3+4x2−10

def f(x): return x**3 + 4*x**2 - 10
def df(x): return 3*x**2 + 8*x
g = lambda x: (10 - 4*x**2)**(1/3)

a, b = 1, 2
x0 = 1.5
x0_fp = 1.0


---Requisitos---
Pyton 3.9 o Python3
También un editor de codigo de preferencia.


---Aclaraciones---
El proyecto tuvo ayuda con IA tales como ChatGPT con fines de correción e implementación de mejoras. El código fue verificado, leído y documentado por los integrantes del grupo. 


