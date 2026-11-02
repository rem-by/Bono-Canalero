# Bono Canalero

Calcula tu salario bruto, horas extra, bonificaciones, deducciones de ley.

Calculadora web de salario bisemanal según la legislación panameña. Funciona completamente en el navegador: no se guarda información personal y los cálculos no se envían a ningún lado.

## Qué calcula

- **Salario base:** 80 horas básicas × rata por hora.
- **Horas extra:** cada hora extra se paga a 1.5 veces la rata.
- **Bonificaciones anuales** (se marcan si se cobran en la bisemana actual):
  - Bono por ausentismo: 80 horas básicas.
  - Bono de Índice de Desempeño Corporativo: 0, 3, 4 o 5 % del salario anual (80 h × rata × 26 pagos).
  - Bono extraordinario: horas ganadas × rata.
  - Bono en Vale General: monto en dólares, sin deducciones.
- **Deducciones:**
  - Seguro Social: 9.75 %
  - Seguro Educativo: 1.25 %
  - Impuesto sobre la Renta según la tabla anual de la DGI (exento hasta B/. 11,000; 15 % hasta B/. 50,000; B/. 5,850 + 25 % sobre el excedente).
  - Préstamos y otros descuentos que ingrese el usuario.

Los resultados son estimados. El ISR no considera los sobretiempos y diferenciales del resto del año ni las deducciones personales de la declaración anual.

## Cómo publicarla con GitHub Pages

1. Sube `index.html` y `README.md` a la raíz del repositorio.
2. En el repositorio, entra a **Settings → Pages**.
3. En **Source**, elige **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`. Guarda.
4. En unos minutos la página estará en `https://<tu-usuario>.github.io/<nombre-del-repositorio>/`.

## Tecnología

HTML, CSS y JavaScript sin librerías. Las fuentes se cargan desde Google Fonts.

## Autoría

Creado por **R. Delmar**.

© 2026 R. Delmar. Todos los derechos reservados. No se permite copiar, modificar ni distribuir este código sin autorización del autor.
