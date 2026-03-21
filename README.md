Descripcion:

Este proyevto ayudara a una micro empresa de pays,este proyecto estara echo para poder ayudar tanto en la interaccion de cliente y vendedor,tanmbien a los vendedores al poder llevar un mejor orden en sus pedidos 

Motivacion:

Este proyecto surge con la finalidad de ayudar a una micro empresa que es de mi familia para ayudarnos a facilitarnos el trabajo diario 

Normalizacion:

La base de datos fue normalizada con el objetivo de organizar adecuadamente la información, evitar redundancias y mejorar la integridad de los datos. Este proceso permitió estructurar de manera eficiente las entidades y sus relaciones, facilitando su mantenimiento y actualización.

Se normalizó para eliminar datos repetidos, reducir inconsistencias y mantener una organización clara de la información.

La información se separó en entidades como Cliente, Pedido y Pay, además de la relación Incluye (Detalle_Pedido), que permite manejar correctamente la relación entre pedidos y productos.

Se eliminaron atributos innecesarios o derivados, como el total del pedido, ya que este puede calcularse a partir de los subtotales.

Se definieron relaciones adecuadas entre las entidades, evitando duplicidad de datos mediante el uso de una estructura intermedia para la relación muchos a muchos.

Formas normales aplicadas:
Se aplicó la Primera Forma Normal (1FN) al asegurar que todos los atributos sean atómicos y sin repeticiones.
La Segunda Forma Normal (2FN) se cumplió al eliminar dependencias parciales, especialmente al separar la relación entre Pedido y Pay.
La Tercera Forma Normal (3FN) se logró al eliminar redundancias y dependencias transitivas, dejando únicamente los datos necesarios en cada entidad.

Gracias a este proceso, la base de datos quedó correctamente estructurada, consistente y fácil de mantener, permitiendo un mejor manejo de la información y evitando errores en su almacenamiento.
