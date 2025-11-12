# 📝 Blog en Ruby on Rails

<img width="1918" height="954" alt="image" src="https://github.com/user-attachments/assets/13dd1495-cdfc-41dc-af00-5483976a9157" />
<img width="1903" height="1034" alt="image" src="https://github.com/user-attachments/assets/7b05da82-3055-4748-855d-a63224336128" />
<img width="1916" height="1035" alt="image" src="https://github.com/user-attachments/assets/ee0fbc85-992c-43d9-bf36-50aacf7863d9" />


Este proyecto es un **blog** desarrollado con **Ruby on Rails**, creado con el objetivo de aprender los fundamentos del framework y aplicar buenas prácticas de desarrollo web.  

## 🚀 Objetivos de aprendizaje

Durante la construcción de este proyecto, aprendí y apliqué varios conceptos fundamentales:

### 🧩 Patrón MVC (Modelo - Vista - Controlador)
Comprendí cómo **Rails organiza el código en tres capas**:
- **Modelo:** gestiona la lógica de negocio y la comunicación con la base de datos.  
- **Vista:** maneja la presentación de la información al usuario.  
- **Controlador:** actúa como intermediario entre el modelo y la vista, controlando el flujo de la aplicación.

### 🧱 Plantillas y ERB
Aprendí a **utilizar plantillas HTML con código Ruby embebido** mediante **ERB (Embedded Ruby)**.  
Esto me permitió:
- Generar contenido dinámico en las vistas.  
- Mostrar datos del modelo directamente en las páginas.  
- Reutilizar componentes a través de **layouts** y **partials**.

### 🧩 Separación de responsabilidades y vistas parciales
Implementé el concepto de **separación de responsabilidades**, manteniendo el código organizado y limpio.  
Además, usé **plantillas parciales** (`_partial.html.erb`) para reutilizar secciones comunes, como formularios o encabezados, en distintas partes de la aplicación.

### 🗃️ Active Record (ORM)
Descubrí lo poderoso que es **Active Record** como **ORM (Object-Relational Mapping)** para interactuar con la base de datos.  
Gracias a él, pude:
- Definir modelos como clases Ruby.  
- Manipular registros de la base de datos sin escribir SQL directamente.  
- Usar asociaciones (`has_many`, `belongs_to`), validaciones y migraciones con facilidad.

## ⚙️ Tecnologías utilizadas
- **Ruby on Rails**
- **Ruby**
- **SQLite3** (base de datos de desarrollo)
- **HTML / ERB**
- **CSS (opcionalmente con Bootstrap o Tailwind)**

## 💡 Ejecución del proyecto
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/blog-rails.git

2. Instala las dependencias:
   ```bash
   bundle install

3. Crea la base de datos y aplica las migraciones:
   ```bash
   rails db:create db:migrate
   
4. Inicia el servidor::
   ```bash
   rails server   

   
