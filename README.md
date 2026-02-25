Problemas Encontrados
Durante el desarrollo se presentaron los siguientes inconvenientes:

Error con AppCompatActivity Se presentó un error en la línea:
import androidx.appcompat.app.AppCompatActivity

Causa: El proyecto no tenía agregada la dependencia androidx.appcompat en el archivo build.gradle.

Solución aplicada: Se reemplazó AppCompatActivity por Activity, eliminando la necesidad de dependencias adicionales.
