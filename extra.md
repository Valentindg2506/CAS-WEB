#Formulario de contacto:
```        
        <!-- Contacto -->
        <section id="contacto" class="contact reveal">
            <h2 class="section-title center">Contacto</h2>
            <p class="section-subtitle center">
                Escrbinos tu consulta y te llamamos.
            </p>
            <form class="contact-form" action="https://formsubmit.co/TU_CORREO_AQUI" method="POST">
            
                <label for="nombre">Nombre</label>
                <input type="text" id="nombre" name="nombre" placeholder="Tu nombre" required>
            
                <label for="email">Email</label>
                <input type="email" id="email" name="email" placeholder="tu@correo.com" required>
                
                <label for="movil">Móvil (opcional)</label>
                <input type="tel" id="movil" name="movil" placeholder="Tu número de móvil">
            
                <label for="mensaje">Mensaje</label>
                <textarea id="mensaje" name="mensaje" placeholder="Cuéntanos en qué podemos ayudarte" required></textarea>
            
                <!-- Opcionales -->
                <input type="hidden" name="_subject" value="Nuevo mensaje desde CAS RS">
                <input type="hidden" name="_captcha" value="false">

                <input type="submit" value="Enviar mensaje" class="btn-primary btn-full">
            </form>
        </section>
```

---
