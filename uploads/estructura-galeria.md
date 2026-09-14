# Galería virtual Anímula — Estructura base
Ruta propuesta: `arkartech.com/animula` · Cada obra: `arkartech.com/animula/obra/<id>`
El chip NFC de cada pieza graba la URL corta `arkartech.com/a/<id>` → redirige a la ficha.

## Identidad visual (extraída del portafolio)
- Fondo: crema/hueso (≈ #FBF3E3)
- Texto y titulares: azul cobalto/primario (≈ #1E3FAE)
- Acento: naranja quemado (≈ #C87A1E) — el punto circular del logotipo "FLOW • STATE"
- Tipografía: serif clásica con tracking amplio en titulares (estilo Georgia/Cormorant), títulos en MAYÚSCULAS espaciadas, fichas técnicas en texto vertical/lateral
- Motivo gráfico: círculos (el punto naranja, la luna de "Tapiz Solar", óvalos de la portada)
- Paleta de obra (para acentos secundarios): verde esmeralda, amarillo primario, rojo vino, terracota, salmón, rosa palo, verde bosque, verde aqua, azul cobalto

## Textos clave extraídos
**Statement (portafolio, p. bio):**
"Mi proceso creativo nace de la intuición y de la necesidad profunda de expresar con colores y texturas lo que no cabe en las palabras. Para mí, el arte abstracto es una alquimia del alma... Autodidacta y salvaje de pensamiento, me gusta sentir que puedo ser un canal de creatividad; los símbolos y jeroglíficos que he creado vienen a mí como un viejo lenguaje del espíritu."

**Objetivo como artista visual:**
"Honrar el estado de trance 'flow state', ese momento donde no existen reglas; sólo emociones, movimiento, recuerdos y deseos manifestándose. Recordar la importancia del entorno como inspiración e instrumento. Deseo crear una experiencia inmersiva entre la artista y los visitantes."

**Manifiesto (poema "Flow State"):** disponible completo en el portafolio ("Ese momento sagrado donde el tiempo se disuelve...").

**Datos:** Artista emergente mexicana · Arte independiente y tatuaje abstracto desde hace 3 años · IG @animula.rtt_

## Catálogo (cruce portafolio × ficha técnica)

| ID | Obra | Técnica | Medidas | Precio venta | Estado | Imagen | Fuente |
|----|------|---------|---------|-------------|--------|--------|--------|
| 001 | Flow State | Acrílico sobre manta cruda | 2 m × 100 cm | $16,250 | Por confirmar en expo | portada (ilustr.) | Ficha |
| 002 | Certeza | Acrílico sobre manta cruda | 170 × 90 cm | $3,000 | Disponible | falta foto | Ficha |
| 003 | No Room for Form (serie) | Acrílico sobre manta cruda, suspendida | 2 m × 80 cm c/u | $2,000 c/u | Pendiente | no-room-for-form.png | Ambos |
| 004 | Es Amor | Acrílico sobre bastidor (manta) | 30 × 30 cm | — | VENDIDA | es-amor.jpg (+detalle) | Ambos |
| 005 | Rompe Olas | Acrílico sobre cartón | 20 × 12 cm | por definir | Disponible | rompe-olas.jpg (+detalle) | Portafolio |
| 006 | Sin Título (cartón) | Acrílico sobre cartón | 20 × 12 cm | por definir | Disponible | sin-titulo-carton.jpg | Portafolio |
| 007 | Canción Experimental | Acrílico sobre manta | 24 × 18 cm | por definir | Disponible | cancion-experimental.jpg | Portafolio |
| 008 | Loca | Acrílico y agua sobre manta cruda | 27 × 22 cm | por definir | Disponible | loca.jpg | Portafolio |
| 009 | Show Me Where You Fit | Acrílico sobre manta | 30 × 25 cm | por definir | Disponible | show-me-where-you-fit.png | Portafolio |
| 010 | Eterno Espiral | Acrílico sobre manta | 30 × 25 cm | por definir | Disponible | eterno-espiral.jpg | Portafolio |
| 011 | Girasol | — | — | por definir | Disponible | girasol.png | Portafolio |
| 012 | Tapiz Solar | — | — | por definir | Disponible | tapiz-solar.png | Portafolio |
| 013 | Paisaje Femenina | Acrílico sobre bastidor | 50 × 50 cm | $2,500 | Disponible | falta foto | Ficha |
| 014 | Estrías/Grietas | Acrílico sobre bastidor | 90 × 60 cm | $4,000 | Disponible | falta foto | Ficha |
| 015 | Sin Título (bastidor 80×80) | Acrílico sobre bastidor | 80 × 80 cm | $10,000 | Pendiente | falta foto | Ficha |
| 016 | Sin Título (madera) | Acrílico sobre madera | 150 × 100 cm | $10,000 | VENDIDA | falta foto | Ficha |
| 017 | Room to Breathe | Acrílico sobre bastidor | 30 × 40 cm | $3,000 | Disponible | falta foto | Ficha |
| 018 | Flor (título provisional) | Acrílico sobre bastidor | 50 × 50 cm | $3,000 | Disponible | falta foto | Ficha |
| 019 | Sin Título (30×30) | Acrílico sobre bastidor | 30 × 30 cm | — | VENDIDA | falta foto | Ficha |

⚠️ **Nota interna — NO publicar:** la "remuneración para la artista" de la ficha técnica es dato interno del acuerdo Arka↔Anímula. En la galería pública solo va el precio de venta (o "Vendida" / "Consultar").
⚠️ Los títulos marcados PULIR/PENDIENTE en la ficha pueden cambiar antes del registro y montaje.

## Estructura del sitio

### /animula (portada de la galería)
1. Hero: portada Flow State + "FLOW • STATE" en serif espaciada con el punto naranja + "Proyección artística · Anímula"
2. Grid de obras (imagen, título, técnica, medidas, estado) → clic a ficha
3. Manifiesto (fragmento del poema en itálica)
4. Bio + retrato + statement + @animula.rtt_
5. Sello Arka: "Colección con memoria — cada pieza cuenta con certificado phygital NFC" + CTA WhatsApp/contacto

### /animula/obra/<id> (ficha viva por pieza — destino del NFC)
- Imagen principal + detalle
- Título · técnica · medidas · año · estado (Disponible / Vendida / En exposición)
- Texto de la obra (descripción de la ficha técnica)
- Certificado: ID de pieza (slug), fecha de certificación, "Certificado por Arka Artech", historial (creación → exposición Lunario → venta)
- "Sin app: esta ficha se abre al acercar tu teléfono a la pieza"
- CTA: adquirir / consultar por WhatsApp

## Pendientes de contenido
- Fotos de las obras que solo están en la ficha técnica (002, 013–019)
- Precios de las obras que solo están en el portafolio (005–012)
- Confirmar títulos definitivos antes del montaje
- Año de creación de cada pieza (no aparece en ningún documento)
