"# leap" 
Equipo:

Ernesto Alvarez
Eduardo Antolin
Javier Contreras
Karla Jaime
David Preciado
Deni Alfaro
Lizbeth Báez


Documentacion:
Para empezar se ubicaron los modelos de las manos para la simulación. 


El script está conformado por dos transform, uno de cada mano y de condicionales. 
La condicional dice que si la distancia de esos dos es menor a ClapDistance, (ClapDistance es una variable y es el mínimo de distancia para registrarlo como clap) después, se hizo otra condición (ClapReady) para que movimiento Clap solo se active una vez, de forma que si se quiere hacer otra vez se tendrá que separarlos otra vez y pegarlos.


El script “clap” se le asigna al prefab de las manos.

Referencias:

*Unity. (2022, 22 enero). Unity - Manual: Transforms. Unity Documentation. Recuperado 31 de enero de 2022, de https://docs.unity3d.com/Manual/class-Transform.html 

*Unity. (2022b, enero 22). Unity - Scripting API: Vector3.Distance. Unity Documentation. Recuperado 31 de enero de 2022, de https://docs.unity3d.com/ScriptReference/Vector3.Distance.html 

*Unity. (2014, 30 abril). how to get the palm, finger position in Leap Motion. Unity Forum. Recuperado 31 de enero de 2022, de https://forum.unity.com/threads/how-to-get-the-palm-finger-position-in-leap-motion.245050/ 
