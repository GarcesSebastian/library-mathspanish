# MathSpanish Library

La librería MathSpanish proporciona una colección de operaciones matemáticas y trigonométricas, así como conversiones y cálculos de áreas y perímetros.

## Características

- **Operaciones Matemáticas:** Potenciación, raíz cuadrada, factorial.
- **Operaciones Geométricas:** Cálculos de áreas y perímetros de triángulos, círculos, cuadrados y rectángulos.
- **Operaciones Trigonométricas:** Cálculo del seno, coseno, tangente, secante, cotangente y cosecante.

## Uso

A continuación se muestra un ejemplo básico de cómo usar la librería en tu proyecto:

```java
import com.mathspanish.operaciones;
import com.mathspanish.opTrigonometricas;
import com.mathspanish.conversor;

public class Main {
    public static void main(String[] args) {
        double area = operaciones.areaTriangulo(5, 7);
        System.out.println("Área del triángulo: " + area);

        double senoValue = opTrigonometricas.seno(30);
        System.out.println("Seno de 30 grados: " + senoValue);

        String binario = conversor.convertirDecABin(10);
        System.out.println("Decimal 10 en binario: " + binario);
    }
}

```
Instalación
Descarga la librería MathSpanish desde el enlace de releases.
Agrega el archivo JAR a tu proyecto.
Importa las clases necesarias en tu código.
Documentación
La documentación detallada de cada clase y método se encuentra en la carpeta docs. Puedes consultarla para obtener más información sobre cómo utilizar la librería.

Contribuciones
¡Las contribuciones son bienvenidas! Si encuentras algún error, tienes ideas para nuevas funciones o mejoras, no dudes en abrir un issue o enviar un pull request.

Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo [MIT License](LICENSE.txt) para más detalles.
