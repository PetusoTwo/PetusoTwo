
# 👋 ¡Hola! Soy Pedro

```java
public class Desarrollador {
    private String nombre = "Pedro";
    private String especialidad = "Next.js, React, TypeScript, Tailwind CSS";
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
