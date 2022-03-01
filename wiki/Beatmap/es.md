---
outdated: true
---

# Beatmap

Un **beatmap** o mapa es un conjunto de niveles ([dificultades](#dificultad)) que están formados por varios [hit objects](/wiki/Hit_object/es.md) y casi siempre representan a una sola canción. También incluye otros componentes, todos empaquetados en un archivo con la extensión `.osz`:

- la canción, en formato MP3 u Ogg.
- [imagen de fondo](/wiki/Beatmap/Background/en.md), o un vídeo.
- [hitsounds personalizados](/wiki/Beatmapping/Hitsound/en.md) para acompañar a la canción (opcional).
- [storyboard](/wiki/Storyboard/es.md) con gráficos en movimiento y efectos especiales, que sirven como historia de fondo o tema para la canción (opcional).
- [skin personalizada](/wiki/Skinning/es.md), que cambia la apariencia de los elementos de juego e interfaz (opcional).

# Dificultad

*Véase: [Dificultad](/wiki/Beatmap/Difficulty/es.md)*

Una **dificultad** es un archivo con la extensión `.osu` que representa la posición de los *hit objects*, los *hitsounds* y efectos especiales como el [kiai](/wiki/Gameplay/Kiai_time/es.md). También contiene los [ajustes de dificultad](/wiki/Client/Beatmap_editor/Song_Setup/en.md#difficulty) y otros parámetros que afectan directamente a la jugabilidad. Las dificultades tienen estructuras diferentes y a veces solo pueden ser jugadas en un solo [modo de juego](/wiki/Game_mode/es.md). El sistema de [star rating](/wiki/Beatmapping/Star_rating/en.md) es usado para visualizar el requisito de habilidad de una dificultad.

## Subir mapas

*Véase: [Subir mapas](/wiki/Submission/en.md)*

Los autores de mapas pueden [subir sus mapas](/wiki/Submission/en.md) a la [lista de mapas públicos](https://osu.ppy.sh/beatmapsets). Aunque cada mapa tiene un [único dueño](/wiki/Beatmap/Beatmap_host/en.md), es a menudo un esfuerzo conjunto: algunas dificultades pueden estar mapeadas [en colaboración](/wiki/Beatmap/Beatmap_collaborations/en.md) o [separadas](/wiki/Beatmap/Guest_difficulty/en.md).

Cuando el mapa está subido, éste gana campos de metadatos adicionales como; idioma, género y el marcador de contenido explícito.

### Identificación

A cada mapa subido se le asigna un número identificativo (`BeatmapSetID`), que puede ser rastreada en la web o con la [api de osu](/wiki/osu!api/es.md). Cada dificultad también tiene su propio número de identificación (`BeatmapID`).La URL que apunta a una dificultad específica incluye ambos identificadores y tiene el siguiente formato:

```
https://osu.ppy.sh/beatmapsets/{BeatmapSetID}#{GameMode}/{BeatmapID}`
```

### Categoría

*Véase: [Categoría](/wiki/Beatmap/Category/es.md)*

Un mapa subido pertenece a una de las siguientes categorías, la cual puede cambiar con el paso del tiempo:

- [Abandonado](Category/es.md#abandonado)
- [Pendientes/WIP](Category/es.md#pendiente)
- [Calificado](Category/es.md#mapas-calificados)
- [Rankeado](Category/es.md#beatmaps-rankeados)
- [Aprobado](Category/en.md#approved)
- [Loved](Category/es.md#loved)

Algunas categorías tienen [criterios de subida](/wiki/Ranking_Criteria) y permite a los mapas tener [tablas de clasificación](#tablasdeclasificación). La manera más popular de conseguirlo es mediante el [proceso de rankeo](/wiki/Beatmap_ranking_procedure/en.md), mientras que la segunda opción es conseguir que el mapa esté [loved](Category/es.md#loved).