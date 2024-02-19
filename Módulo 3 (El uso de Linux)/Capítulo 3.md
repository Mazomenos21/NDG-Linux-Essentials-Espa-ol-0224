# Modo Gráfico vs. No Gráfico en Linux

Linux ofrece dos modos de operación: gráfico y no gráfico, cada uno adaptado a diferentes necesidades y preferencias. 

## Modo Gráfico

En el modo gráfico, las aplicaciones se ejecutan en ventanas que pueden ser redimensionadas y movidas. Se disponen de menús y herramientas que facilitan la búsqueda y el uso de aplicaciones, como navegadores web, editores de gráficos y correo electrónico. A continuación, se muestra un ejemplo de escritorio gráfico con una barra de menús de aplicaciones populares y un documento de LibreOffice con un navegador web de fondo.

![Escritorio Gráfico](https://ndg-content-dev.s3.amazonaws.com/media/images/3.3_1.png)

Es posible tener varios shells abiertos, lo que resulta útil para realizar tareas en múltiples equipos remotos. Incluso puedes iniciar sesión con tu usuario y contraseña a través de una interfaz gráfica, como se ilustra en la siguiente figura.

![Inicio de Sesión Gráfico](https://ndg-content-dev.s3.amazonaws.com/media/images/3.3_2.png)

## Modo No Gráfico

En el modo no gráfico, la sesión comienza con una interfaz basada en texto. Solo se solicita el nombre de usuario y la contraseña. Si el inicio de sesión tiene éxito, se accede directamente al shell. Aunque no hay ventanas, se pueden utilizar editores de texto, navegadores web y clientes de correo electrónico, todos en formato de texto. Este modo es común en servidores, donde una interfaz gráfica podría ser innecesaria y consumir recursos. La siguiente imagen muestra la pantalla de inicio de sesión en modo no gráfico.

![Inicio de Sesión No Gráfico](https://ndg-content-dev.s3.amazonaws.com/media/images/3.3_3.png)

Durante el inicio de sesión, podrías ver mensajes del día (MOTD), que brindan información del administrador de sistemas a los usuarios. La terminal mantiene un historial de comandos introducidos, permitiendo desplazarse hacia arriba para revisarlos. En Linux, la interfaz es todo lo que se muestra en pantalla, sin ventanas para navegar.

![Ejemplo de Terminal No Gráfica](https://ndg-content-dev.s3.amazonaws.com/media/images/3.3_4.png)

En resumen, Linux ofrece flexibilidad con sus modos gráfico y no gráfico, adaptándose a diversas necesidades y entornos de uso.


---------------------
# Línea de Comandos

La línea de comandos es una entrada de texto simple que permite ingresar desde comandos de una sola palabra hasta scripts complicados. Si inicias la sesión en modo de texto, accedes directamente a la consola. En el caso de una sesión gráfica, necesitarás iniciar un shell gráfico, que es básicamente una consola de texto con una ventana que puedes redimensionar y mover.

Dado que cada escritorio de Linux puede ser diferente, es necesario buscar en el menú una opción llamada terminal o x-term, ambas son shells gráficos, diferenciándose más en aspectos estéticos que en funcionalidad. Si cuentas con una herramienta de búsqueda como Ubuntu Dash, puedes buscar un terminal como se muestra aquí.

![Búsqueda de Terminal en Ubuntu Dash](https://ndg-content-dev.s3.amazonaws.com/media/images/3.4_1.png)

Estas herramientas te permiten buscar de manera eficiente en tu sistema, facilitando la ejecución precisa de lo que necesitas en lugar de perderse en los menús.



---------------------
# Virtualización y Cloud Computing

La virtualización y el Cloud Computing son conceptos esenciales en el campo de la informática, transformando la forma en que gestionamos recursos y servicios. Aquí se explora cómo Linux desempeña un papel crucial en estas tecnologías.

## Virtualización: Optimizando Recursos

Linux, como sistema operativo multiusuario, permite la colaboración simultánea de varios usuarios, pero enfrenta desafíos en la distribución equitativa de recursos. La virtualización resuelve este problema al permitir que un host ejecute múltiples copias de un sistema operativo, denominadas invitados, mediante un hipervisor. A través de esta técnica, se optimiza el uso de recursos, aunque la memoria sigue siendo una limitación.


En un entorno virtualizado, un host puede ejecutar numerosos sistemas operativos invitados, cada uno con sus propios recursos y red. Esto reduce la necesidad de servidores físicos, proporcionando flexibilidad para ejecutar diferentes sistemas operativos.

## Cloud Computing: Acceso Remoto Eficiente

El Cloud Computing lleva la virtualización al siguiente nivel, permitiendo el acceso a máquinas virtuales en centros de datos remotos. Los usuarios pagan solo por los recursos utilizados, aprovechando las economías de escala de los proveedores de servicios en la nube. Esta aproximación se extiende más allá de servidores virtuales, incluyendo almacenamiento, bases de datos y software, con la ventaja de pagar por el uso en lugar de adquirir y mantener hardware y software.


Linux desempeña un papel central en el Cloud Computing, siendo la base de la mayoría de los servidores virtuales y la elección común para alojar aplicaciones detrás de los servicios en la nube. En resumen, la virtualización y el Cloud Computing ofrecen eficiencia, flexibilidad y ahorro de costos en comparación con las infraestructuras tradicionales basadas en servidores físicos.


***
# Utilizar Linux para el Trabajo

En entornos de oficina, Linux se destaca como una opción eficiente para llevar a cabo tareas comunes utilizando herramientas esenciales. Las principales herramientas utilizadas en la mayoría de las oficinas incluyen:

- Procesador de textos
- Hoja de cálculo
- Paquete de presentación
- Navegador web

OpenOffice y, más activamente, LibreOffice, se encargan de las tres primeras funciones. El procesador de texto se utiliza para editar documentos como informes y memos. Las hojas de cálculo son útiles para trabajar con números, como resumir datos de ventas y hacer predicciones. El paquete de presentación se utiliza para crear diapositivas con texto, gráficos y vídeos incrustados, para compartir con una audiencia mediante impresión o proyección.

A continuación, se muestra la hoja de cálculo y el editor de documentos de LibreOffice. Observa cómo LibreOffice Calc no se limita a filas y columnas de números; puede utilizar números como fuente para gráficos y escribir fórmulas para calcular valores basados en información, como tasas de interés y cantidades.

![LibreOffice](https://ndg-content-dev.s3.amazonaws.com/media/images/3.6_1.png)

LibreOffice puede trabajar con otros formatos de archivo, como Microsoft Office o Adobe Portable Document Format (PDF). Además, mediante el uso de extensiones, se puede integrar LibreOffice con el software Wiki para ofrecer una potente solución de intranet.

Linux es compatible con los navegadores Firefox y Google Chrome, lo que garantiza acceso a software actualizado y correcciones de errores de manera oportuna. Aunque algunos complementos, como Adobe Flash, pueden presentar problemas debido a dependencias con otras compañías y prioridades diferentes.


***
# Proteger tu Equipo Linux

Linux no discrimina si estás frente al teclado de un equipo o conectado a través de Internet, por lo que es crucial tomar precauciones básicas para garantizar la seguridad de tus datos.

La primera medida es emplear una contraseña sólida y única en todas tus interacciones, especialmente en tu máquina local. Una buena contraseña debe tener al menos 10 caracteres y contener una combinación de números, letras (mayúsculas y minúsculas) y símbolos. Herramientas como KeePassX pueden generar contraseñas seguras, simplificando el proceso al requerir solo una contraseña de inicio de sesión y otra para abrir el archivo de KeePassX.

Adicionalmente, es fundamental crear periódicamente puntos de control de actualizaciones. En la configuración de actualización de software de Ubuntu, visible en el menú de Configuración, puedes establecer la frecuencia de búsqueda de actualizaciones. Si hay actualizaciones de seguridad, se te pedirá instalarlas de inmediato; de lo contrario, recibirás actualizaciones periódicas.

![Configuración de Actualización en Ubuntu](https://ndg-content-dev.s3.amazonaws.com/media/images/3.7_1.png)

Por último, es necesario proteger tu equipo contra conexiones entrantes mediante un firewall. Linux incluye uno integrado, y si usas Ubuntu, gufw proporciona una interfaz gráfica para el "Uncomplicated firewall". Puedes bloquear todo el tráfico entrante cambiando el estado a "on", permitiendo selectivamente ciertas conexiones haciendo clic en el signo más.

![Gufw - Interfaz gráfica para Firewall en Ubuntu](https://ndg-content-dev.s3.amazonaws.com/media/images/3.7_2.png)

Aunque gufw facilita la construcción de una política efectiva desde el escritorio, utiliza iptables bajo el capó. Esto te permite establecer reglas detalladas sin la necesidad de introducir complicados comandos iptables, brindando un equilibrio entre accesibilidad y funcionalidad avanzada.

***

# Protegerte a tí Mismo
Cuando navegas por Internet, dejas una huella digital. Mucha de esta información viene ignorada, pero alguna viene reunida para recopilar estadísticas de publicidad y otra puede ser utilizada para propósitos maliciosos.

Como regla general, no deberías confiar en los sitios con los que interactúas. Usa contraseñas diferentes en cada sitio de Internet para que si tal sitio web estuviera hackeado, la contraseña no podría utilizarse para obtener acceso a otros sitios. Usando anteriormente mencionado KeePassX es la forma más fácil de hacerlo. De la misma forma, limita la información que proporcionas a los sitios, sólo lo imprescindible. Mientras que dar el nombre de tu madre y fecha de nacimiento podría ayudarte a desbloquear tus credenciales para la red social en caso de que pierdas tu contraseña, la misma información puede utilizarse para suplantar la identidad de tu banco.

Las cookies son el mecanismo principal que los sitios web utilizan para darte seguimiento. A veces este seguimiento es bueno, por ejemplo para dar seguimiento de lo que está en tu cesta de compras o para mantenerte conectado cuando regreses al sitio.

Cuando navegas por la web, un servidor web puede devolver la cookie que es un pequeño trozo de texto junto con la página web. Tu navegador lo almacena y envía con cada solicitud al mismo sitio. No envías cookies para ejemplo.com a sitios en ejemplo.org.

Sin embargo, muchos sitios han incrustado scripts que provienen de terceros, como un mensaje emergente de anuncio o un píxel de analítica. Si ejemplo.com y ejemplo.org tienen un píxel de analítica, por ejemplo de un anunciante, entonces esa misma cookie se enviará al navegar por ambos sitios. El anunciante se entera entonces que has visitado ejemplo.com y ejemplo.org.

Con un alcance suficientemente amplio, como los "Likes" y botones parecidos, un sitio web puede obtener un entendimiento de cuáles sitios web visitas y averiguar tus intereses y datos demográficos.

Existen diversas estrategias para tratar este asunto. Uno es ignorarlo. La otra es limitar los píxeles de seguimiento que aceptas, ya sea por bloqueo completo o vaciarlos periódicamente. A continuación abajo se muestra la configuración de cookies para Firefox. En la parte superior, verás que el usuario ha optado que Firefox no de permiso al sitio para el seguimiento. Esta es una etiqueta voluntaria enviada en la petición que algunos sitios distinguirán. A continuación, el navegador recibe una instrucción de no recordar nunca las cookies de terceros y eliminar cookies regulares (por ejemplo, desde el sitio navegando) después de haber cerrado el Firefox.

Afinando la configuración de privacidad puede hacerte más anónimo en Internet, pero también puede causar problemas con algunos sitios que dependen de cookies de terceros. Si esto sucede, probablemente tengas que permitir explícitamente que se guarden algunas cookies.

<img src="https://ndg-content-dev.s3.amazonaws.com/media/images/3.8_1.png" alt="Evolución de Linux" width="200"/>


Aquí también tendrás la posibilidad de olvidar el historial de búsqueda o no seguirlo. Con el historial de búsqueda eliminado no habrá ningún registro en el equipo local de los sitios que hayas visitado.

Si te preocupa mucho ser anónimo en Internet, puedes descargar y utilizar el Navegador Tor. Tor es el nombre corto para "The Onion Router" que es una red de servidores públicamente ejecutados que rebotan tu tráfico para ocultar el origen. El navegador que viene con el paquete es una versión básica que no ejecuta ni siquiera las secuencias de comandos, por lo que algunos sitios probablemente no funcionarán correctamente. Sin embargo, es la mejor manera de ocultar tu identidad si es lo que deseas hacer.