# Áudio:

~~~html
<audio controls autoplay loop src="musica.mp3">
  <!--mp3, ogg, wav -->
  Seu navegador não suporta este áudio.
</audio> <br />
<audio controls src="musica.mp3">
  <!--modo 2 -->
  <source src="musica.ogg" type="audio/ogg"> <!-- tenta esse ou o outro -->
  <source src="musica.mp3" type="audio/mpeg">
</audio>
~~~
