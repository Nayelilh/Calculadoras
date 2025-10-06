# Proyecto: Calculadoras Android

## Descripción General

Este repositorio contiene tres versiones de una aplicación de calculadora para Android, desarrolladas con el objetivo de aplicar distintos niveles de complejidad en la evaluación de expresiones matemáticas.

Cada versión corresponde a un proyecto independiente:

1. SE_CalculadoraBasicaa  
2. SE_CalculadoraJerarquica  
3. SE_CalculadoraEditable  

---

## Descripción de Cada Versión

### 1. SE_CalculadoraBasicaa
Calculadora simple que permite realizar operaciones básicas como suma, resta, multiplicación y división.  
Utiliza una interfaz con botones numéricos y operadores, y muestra el resultado en un TextView.

### 2. SE_CalculadoraJerarquica
Versión mejorada que permite el uso de paréntesis y respeta la jerarquía de operaciones.  
Hace uso de un evaluador de expresiones como ScriptEngine o ExpressionBuilder para interpretar las fórmulas ingresadas.

### 3. SE_CalculadoraEditable
Versión más completa que permite editar directamente la fórmula antes de calcular.  
Por ejemplo, el usuario puede modificar:
(8*(2*2))/(3+6)
a:
(8*(2+2))/(3+6)

sin tener que borrar toda la expresión.  
Esta versión integra una interfaz editable con EditText y validación de entrada.

---

## Teoría Utilizada

1. **Evaluación de expresiones matemáticas:**  
   Se emplea la teoría de expresiones infijas para evaluar fórmulas con paréntesis y operadores, utilizando librerías como ExpressionBuilder o ScriptEngine.

2. **Interfaz de usuario (UI):**  
   - Diseñada en XML utilizando LinearLayout y GridLayout.  
   - Botones numéricos y de operadores configurados con eventos onClickListener.  
   - Uso de EditText para permitir edición directa en la versión editable.

3. **Gestión de eventos:**  
   Se emplean listeners para cada botón que insertan texto en el campo de entrada o ejecutan la evaluación.

4. **Manejo de errores:**  
   Se controlan errores comunes como paréntesis desbalanceados, operadores duplicados o divisiones por cero mediante bloques try-catch.

---

## Instrucciones de Ejecución

1. Descargar y descomprimir el archivo **SE_Calculadoras.zip**.  
2. Abrir el proyecto deseado en **Android Studio**.  
3. Conectar un dispositivo físico o iniciar un emulador Android.  
4. Ejecutar la aplicación con el botón **Run**.

---

## Evidencia del Funcionamiento

- Capturas de pantalla en la carpeta `/images` de cada versión.  
- Video demostrativo del funcionamiento general disponible en el enlace correspondiente.

---

## Conversación de Referencia

El desarrollo de este trabajo se basó en la conversación mantenida con ChatGPT, donde se explicó el proceso de creación de cada versión.  
Enlace a la conversación:  https://chatgpt.com/c/68aca8e4-9ae4-8329-9eb9-5ac942de72f6

---

## Autora

Nombre: Nayeli Constantina Labra Huaita  
Curso: Sistemas Embebidos 
Fecha: Setiembre 2025
