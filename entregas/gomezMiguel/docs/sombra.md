# Reto 001 — Modelado: Una sombra

## 1. Una sombra

Una sombra se forma cuando algo se interpone con la  trayectoria de la luz antes de que llegue al suelo  . El modelo busca representar esa situación con la menor cantidad de conceptos posible, sin perder la idea de que la sombra depende de otros elementos para existir.

### Supuestos
* La sombra es un fenómeno que surge de una situación concreta, no un objeto con existencia propia e independiente.
* Para que aparezca deben coincidir tres elementos al mismo tiempo: una fuente de luz, un cuerpo que la bloquee y una superficie donde se proyecte. Si falta alguno, no hay sombra visible.
* Si existen varias fuentes de luz, un mismo cuerpo puede proyectar varias sombras a la vez, una por cada fuente.
* Se asume que el cuerpo es opaco, es decir, que bloquea por completo el paso de la luz.

### Glosario
* **Fuente de luz**: Todo aquello que emite algo de luz, como el sol, una lámpara o una vela. Es el origen del proceso.
* **Objeto**: Cualquier cuerpo opaco que se interpone y evita que la luz continúe su camino.
* **Sombra**: Superficie que se genera cuando un objeto se interpone contra la luz lo que genera un contraste de luz ocntra otras partes expuestas al sol.
* **Superficie**: Lugar donde la sombra se hace visible, como el suelo, una pared o una mesa.
 
### Decisiones discutibles
* **`Sombra` como concepto propio**: Podría pensarse que la sombra es simplemente algo que un objeto tiene o no tiene, como un atributo. Sin embargo, la sombra no pertenece al objeto: nace de la relación entre la luz, el objeto y la superficie. Por eso se representa como un concepto independiente en el diagrama.
* **Sin relación directa `Fuente de luz -> Sombra`**: A primera vista parece lógico que la luz cause la sombra, pero sin un objeto que la bloquee no existiría ninguna. El objeto es un paso obligatorio de la cadena, así que el diagrama sigue el recorrido `Fuente de luz -> Objeto -> Sombra`, que describe mejor lo que ocurre en la realidad.
* **Fenómenos descartados**: Se dejaron fuera la penumbra, la refracción y otros efectos ópticos para mantener el modelo centrado en lo esencial. Incluirlos añadiría complejidad sin cambiar la idea central de cómo se origina una sombra.