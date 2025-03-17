
<!-- Imagen de texto animado -->
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?color=02D9F7FF&size=35&center=true&vCenter=true&width=1000&lines=Welcome!;I'm+from+Perú;Software+Developer" alt="Typing SVG" />
</div>

```java
public class Desarrollador {
    private String nombre = "Pedro";
    private String especialidad = "Next.js, React, TypeScript, Tailwind CSS, Python, PHP";
    private String[] intereses = {"Machine Learning", "Análisis de Datos", "NLP", "IA"};
    
    public void mostrarPerfil() {
        System.out.println("🚀 " + nombre + " - Especialista en " + especialidad);
        System.out.println("📊 Intereses: " + String.join(", ", intereses));
    }

    public static void main(String[] args) {
        Desarrollador yo = new Desarrollador();
        yo.mostrarPerfil();
    }
}
