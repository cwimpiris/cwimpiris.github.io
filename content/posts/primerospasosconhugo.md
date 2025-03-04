+++
date = '2025-03-04T12:22:32+01:00'
draft = false
title = 'Primeros pasos con Hugo'
categories = 'desarrollo'
tags = 'hugo'
+++

## Crear un post en hugo.

    hugo new content [path] [flags]

## Crear arquetipos y posts

Para crear un arquetipo editamos el fichero en la carpeta archetypes

Para crear un post del arquetipo que queremos, escribimos

    hugo new content --kind libros ./content/posts/nombrequesea.md
