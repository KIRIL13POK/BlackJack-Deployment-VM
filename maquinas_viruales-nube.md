# Las máquinas virtuales (MV)

![Las máquinas virtuales (MV)](https://ingenierobinario.com/wp-content/uploads/2021/02/sistemvirtual.jpg)

Las máquinas virtuales (MV) son réplicas virtuales de equipos físicos como PCs, teléfonos inteligentes o servidores. Están definidas por software dentro de servidores físicos y existen solo como código. Cuentan con CPU, memoria y pueden conectarse a internet. Los recursos de una MV provienen de la máquina física donde se realiza la virtualización. Por ejemplo, si una PC física tiene 1 TB de almacenamiento y se asignan 500 GB a una MV, esta última solo podrá usar esos 500 GB​.


Estas máquinas están en particiones separadas del sistema principal, lo que evita interferencias con el sistema operativo del equipo anfitrión​. Funcionan sobre un software especial llamado **hipervisor o VMM (Virtual Machine Monitor)**, que crea una capa de abstracción del hardware físico para ofrecérsela al sistema operativo de la MV​.

Existen dos tipos principales:

* **Las máquinas virtuales de sistema** - utilizadas en la virtualización de hardware, permiten que una máquina física funcione como varias MV, cada una con su propio sistema operativo.
* **Las máquinas virtuales de proceso** - que sirven de enlace entre un lenguaje de programación y el sistema operativo, como la máquina virtual de Java​.

Las MV tienen varias ventajas, como facilidad de manejo y mantenimiento, la capacidad de ejecutar múltiples sistemas operativos en una sola computadora física, y soportar aplicaciones de versiones anteriores. No obstante, pueden ser menos eficientes y más lentas que las computadoras físicas, y su rendimiento puede ser inestable si no se cumplen ciertos requisitos de infraestructura

[Máquina virtual en WikipediA](https://es.wikipedia.org/wiki/M%C3%A1quina_virtual)


# Las máquinas virtuales en la nube

![Las máquinas virtuales (MV) en la nube](https://www.muycomputer.com/wp-content/uploads/2018/08/Maquinas_virtuales.jpg)

En cuanto a las máquinas virtuales en la nube, estas te permiten ejecutar aplicaciones y cargas de trabajo similares a las MV tradicionales, pero sin usar tu propio hardware, lo que ahorra recursos y dinero. Utilizan también un hipervisor para virtualizar el hardware físico​.

Hay varios proveedores de MV en la nube, como Azure Virtual Machine de Microsoft, que ofrece MV de Windows Server o Linux en sus centros de datos; Google Compute Engine, que permite a los clientes usar MV en la nube con hardware de Google; Amazon WorkSpaces, un servicio de escritorio como servicio (DaaS); IBM Cloud, que ofrece configuración y ejecución de MV online; y Tencent Cloud Virtual Machine, un servicio escalable que reduce los costos de hardware y software​​.

[5 mejores máquinas virtuales en la nube](https://www.ardilu.com/webs/maquina-virtual-nube)