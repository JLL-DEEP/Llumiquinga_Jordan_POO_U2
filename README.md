# Tarea U2 - Programación Orientada a Objetos
**Universidad Politécnica Salesiana**  
**Estudiante:** Llumiquinga Jordan

## Descripción
Sistema de gestión de contenido audiovisual implementando 
herencia, asociación, agregación y composición en Java.

## Clases implementadas
- `ContenidoAudiovisual` - clase base abstracta
- `Pelicula` → ASOCIACION con `Actor`
- `SerieDeTV` → COMPOSICION con `Temporada`
- `Documental` → AGREGACION con `Investigador`
- `VideoYouTube` - nueva subclase
- `Cortometraje` - nueva subclase

## Cómo ejecutar
1. Clonar repositorio
2. Importar en Eclipse: File → Import → Existing Projects
3. Ejecutar `PruebaAudioVisual.java`

## Relaciones implementadas
- **Herencia**: todas las subclases extienden ContenidoAudiovisual
- **Asociacion**: Pelicula tiene Actores externos
- **Composicion**: SerieDeTV crea sus propias Temporadas
- **Agregacion**: Documental referencia Investigadores externos
