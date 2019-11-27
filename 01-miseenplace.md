---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
id: miseenplace
title: Mise en Place
layout: page
---

# Mise en Place

## Tripulación de Cocineros

{% for colaborador_hash in site.data.colaboradores %}
{% assign colaborador = colaborador_hash[1] %}

  <div class="col-sm-4 col-xs-6 colaborador" >
    {% if colaborador.foto %}
      <img class="img-responsive " src="{{colaborador.foto}}" alt="{{colaborador.nombre}}" title="{{colaborador.nombre}}">
    {% else %}
      <img class="img-responsive " src="https://robohash.org/{{colaborador.nombre | url_encode}}" alt="{{colaborador.nombre}}" title="{{colaborador.nombre}}">
    {% endif %}
    <div class="pull-left">
    {{colaborador.nombre | upcase }}<br>
    {{colaborador.descripcion}}
    {{colaborador.role}}<br>
    </div>
    <div class="pull-right">
    {% if colaborador.url %}
      <a href="{{colaborador.url}}" target="_blank"><i class="fa fa-home"></i></a>
    {% endif %}
    {% if colaborador.twitter %}
      <a href="https://twitter.com/{{colaborador.twitter}}" target="_blank"><i class="fa fa-twitter"></i></a>
    {% endif %}
    {% if colaborador.facebook %}
      <a href="{{colaborador.facebook}}" target="_blank"><i class="fa fa-facebook"></i></a>
    {% endif %}
    {% if colaborador.linkedin %}
      <a href="{{colaborador.linkedin}}" target="_blank"><i class="fa fa-linkedin"></i></a>
    {% endif %}
    </div>
  </div>
{% endfor %}

## Ingredientes

- 10 kilos de empatía
- 1 tonelada de arte
- 500 gr de deriva
- 10 galones de Juego
- 10 cucharadas de interdependencia
- 10 tazas de crítica propositiva
- 10 gr de observación
- 50 gr de tecnología
- Todos los sentidos despiertos

## Preparación

1. Convocar y conformar una tripulación interdisciplinaria dispuesta a lanzarse en busca de nuevas experiencias bajo los designios del juego y del azar, entregados al intercambio y así crear conocimiento desde el empirismo colectivo y horizontal, bajo el lema “juntos pero no revueltos”.
2. Presentación de la artista y el equipo, confraternización para el florecimiento de la empatía por los intereses comunes, el reconocimientos de los potenciales de cada uno de los miembros de la tripulación y creación de lazos afectivos.
3. Tomar la deriva como método de investigación, creación, aprendizaje y conocimiento. Establecer la táctica de juego colectiva, una vez lista, vierta la mezcla compuesta de observar, absorber, compartir y crear.
   Identificar las cualidades creativas de los tripulantes para organizar frentes de trabajo flexibles a la permeabilidad y simbiosis.
4. Desarrollamos un método de trabajo colaborativo, rizomático (en red) dividido en células, horizontal, simbiótico, puntualizado, flexible a los cambios y la simultaneidad basados en el método Scrum.
