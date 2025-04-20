# Fundamentos de Ciberseguridad

## La Triada CIA

La **triada CIA** es un concepto fundamental en ciberseguridad que abarca tres pilares clave:  
`Confidentiality, Integrity and Availability`

### 1. **Confidencialidad**  
La información debe ser accesible únicamente por personas autorizadas. Es esencial evitar el acceso no autorizado para proteger la privacidad y la seguridad de los datos.

### 2. **Integridad**  
La información no debe ser modificada de forma no autorizada. Este pilar garantiza que los datos se mantengan correctos, completos y confiables.

### 3. **Disponibilidad**  
La información y los sistemas deben estar disponibles cuando se necesiten. Esto implica mantener la operatividad, prevenir interrupciones y asegurar la recuperación ante fallos.

### Otros principios clave

Además de la triada CIA, existen dos principios adicionales que también son fundamentales en ciberseguridad:

### 4. **No repudio**  
Este principio garantiza que una persona no pueda negar que realizó una acción, como enviar un mensaje, realizar una transacción o firmar un documento.  
**Ejemplo:** Si firmas un contrato digital con tu certificado digital, ese documento contiene tu firma única. Gracias al no repudio, no puedes negar legalmente que tú lo firmaste, ya que existe evidencia técnica que lo demuestra.

### 5. **Autenticación**  
Aunque no forma parte directa de la triada CIA, la autenticación se basa en poder demostrar, mediante varios factores, la autenticidad de un usuario para poder autenticarse en un activo. Estos factores suelen basarse en:

1. Lo que el usuario sabe (Ej. contraseña)
2. Lo que el usuario tiene (Ej. llave de acceso física)
3. Lo que el usuario es (Ej. huella dactilar)

---

## Exploit, Payload y 0day

### **Exploit**  
Es un fragmento de código que puede estar escrito en cualquier lenguaje de programación o scripting, y que contiene una serie de instrucciones que permiten alterar el comportamiento normal de un software para aprovechar una vulnerabilidad detectada. Es decir, el exploit interrumpe el funcionamiento correcto del software y abre una puerta para introducir otro código que continuará con la explotación: el **payload**.

### **Payload**  
Es la acción que se ejecuta una vez que el exploit ha explotado la vulnerabilidad. No se puede ejecutar un payload sin un exploit previo, aunque sí se pueden lanzar exploits que no incluyan un payload.

### **0day**  
Se refiere a vulnerabilidades que son conocidas por muy pocas personas (incluso solo una), y que, sobre todo, **no han sido parcheadas** por el fabricante. Son especialmente peligrosas por su carácter desconocido y la falta de solución disponible.

---

## Malware y tipos

### **Malware**  
Es cualquier tipo de código malicioso que busca aprovecharse de una vulnerabilidad y adicionalmente causar daño. La palabra *malware* es el acrónimo de *Malicious Software* y fue acuñada por el analista de ciberseguridad Yisrael Radai en 1990.

No todos los softwares maliciosos son virus, y en base a su comportamiento podemos clasificarlos en varios tipos. Los principales tipos son: **troyanos, virus, gusanos, rogues, adware, spyware y ransomware**.

#### 1. **Virus**  
Los virus buscan siempre un huésped donde puedan añadir parte de su código malicioso para infectarlo. Para completar la infección o propagarse, requieren la acción del usuario, como ejecutar un archivo.

#### 2. **Gusanos**  
A diferencia de los virus, los gusanos no necesitan la acción del usuario para propagarse. Se replican de manera autónoma y pueden infectar dispositivos y propagarse a través de la red, lo que pone en riesgo a otros dispositivos conectados.

#### 3. **Adware y Spyware**  
Normalmente, uno puede usar al otro. El **adware** es un software legítimo cuya función principal es mostrar anuncios, los cuales pueden ser legítimos o maliciosos, y se presentan de forma nativa dentro del sistema.  
Los **adwares** suelen estar integrados en programas gratuitos que se financian mostrando publicidad. Sin embargo, cuando un adware comienza a recopilar o monitorear información del sistema, aunque sea con fines comerciales, pasa a considerarse **spyware**.

#### 4. **Rogue**  
Es un tipo de malware que **finge ser un software legítimo**, como por ejemplo un antivirus, con el objetivo de engañar al usuario. Su propósito es inducir a la víctima a descargar e instalar voluntariamente el propio malware, creyendo que está protegiendo su sistema.

#### 5. **Troyano**  
Es un tipo de malware que se disfraza como un software legítimo. A diferencia del **rogue**, el troyano abarca una mayor variedad de estrategias para hacer creer al usuario que está instalando un programa confiable y libre de amenazas. Es muy común encontrarlo en software pirateado, tanto en aplicaciones como en videojuegos.

#### 6. **Ransomware**  
La mayoría de los ataques a infraestructuras informáticas son realizados por ciberdelincuentes utilizando algún tipo de **ransomware**. Este malware funciona cifrando toda la información del dispositivo que infecta, bloqueando así el acceso a los datos.  
A partir de ahí, los atacantes exigen a la víctima (normalmente una empresa) el pago de un **rescate** a cambio de una clave que, en teoría, permitirá descifrar los datos. Este modelo se ha convertido en una forma lucrativa de cibercrimen.  
Sin embargo, incluso si la empresa paga, no hay garantía de que los ciberdelincuentes devuelvan el acceso a la información. Por eso, contar con **copias de seguridad** actualizadas y almacenadas fuera de la infraestructura principal es una práctica esencial de prevención.

---

Estos tipos de malware pueden combinarse entre sí. Por ejemplo, un **troyano** puede tener características de **spyware**, o un **gusano** puede replicarse mientras incluye elementos propios de **adware**.

---

## Vulnerabilidad, amenaza y riesgo

### **Vulnerabilidad**  
En seguridad informática, una vulnerabilidad es un fallo en la configuración, el diseño o la implementación de un sistema. Se refiere a un defecto dentro de un activo de información, ya sea lógico o físico, que puede poner en riesgo dicho activo en determinadas circunstancias. Este fallo afecta negativamente a los pilares fundamentales de la ciberseguridad.

### **Amenaza**  
Una amenaza es cualquier circunstancia o evento que pueda ocurrir y que, al aprovechar una vulnerabilidad, ponga en riesgo la seguridad de la información. Las amenazas pueden ser de naturaleza **física** o **lógica**.

### **Riesgo**  
El riesgo es la probabilidad de que una amenaza se materialice y afecte a un activo, aprovechando una vulnerabilidad existente.

---
 
He añadido subtítulos, y he estructurado mejor los apartados para facilitar su lectura. La idea es que cada tema quede claramente separado, con los puntos destacados para que el texto sea más accesible. ¡Espero que te guste!
