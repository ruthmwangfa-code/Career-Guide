# Career-Guide
web moderna y profesional de orientación para estudiantes y recién graduados.
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CareerGuide — Orientación para estudiantes y recién graduados</title>
  <meta name="description" content="Asesoría personalizada, recursos para búsqueda de empleo y consejos para el desarrollo profesional." />
  <!-- Tailwind Play CDN (útil para prototipos). En producción compilar Tailwind. -->
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Pequeños ajustes visuales */
    .brand-gradient { background: linear-gradient(135deg,#0ea5e9,#06b6d4); }
    .card { background: #ffffff; border-radius: 0.75rem; box-shadow: 0 4px 18px rgba(15,23,42,0.06); }
  </style>
</head>
<body class="antialiased bg-slate-50 text-slate-900">
  <header class="max-w-6xl mx-auto px-6 py-6 flex items-center justify-between">
    <div class="flex items-center gap-3">
      <div class="w-12 h-12 rounded-2xl brand-gradient flex items-center justify-center text-white font-bold">CG</div>
      <div>
        <h1 class="text-lg font-semibold">CareerGuide</h1>
        <p class="text-sm text-slate-500">Orientación profesional para estudiantes y recién graduados</p>
      </div>
    </div>
    <nav class="hidden md:flex gap-6 items-center text-sm">
      <a href="#services" class="hover:underline">Servicios</a>
      <a href="#resources" class="hover:underline">Recursos</a>
      <a href="#testimonials" class="hover:underline">Testimonios</a>
      <a href="#blog" class="hover:underline">Blog</a>
      <a href="#contact" class="px-4 py-2 rounded-lg bg-slate-900 text-white text-sm">Contactar</a>
    </nav>
  </header>

  <main class="max-w-6xl mx-auto px-6">
    <!-- Hero -->
    <section class="grid grid-cols-1 md:grid-cols-2 gap-10 items-center py-12">
      <div>
        <h2 class="text-3xl md:text-4xl font-extrabold">Tu carrera empieza aquí — guía cercana, resultados reales</h2>
        <p class="mt-4 text-slate-600">Asesoría personalizada, recursos prácticos y formación para que des tus próximos pasos con confianza.</p>

        <div class="mt-6 flex gap-3">
          <a href="#contact" class="inline-block px-5 py-3 rounded-lg bg-slate-900 text-white">Solicitar asesoría</a>
          <a href="#resources" class="inline-block px-5 py-3 rounded-lg border">Ver recursos</a>
        </div>

        <ul class="mt-8 grid grid-cols-1 sm:grid-cols-2 gap-4">
          <li class="flex items-start gap-3">
            <div class="p-3 rounded-xl bg-slate-100">✓</div>
            <div>
              <p class="font-semibold">Sesiones 1:1</p>
              <p class="text-sm text-slate-500">Planes adaptados a tu objetivo profesional.</p>
            </div>
          </li>

          <li class="flex items-start gap-3">
            <div class="p-3 rounded-xl bg-slate-100">✉️</div>
            <div>
              <p class="font-semibold">Material descargable</p>
              <p class="text-sm text-slate-500">CVs, cartas y plantillas listas para usar.</p>
            </div>
          </li>
        </ul>
      </div>

      <aside class="card p-6">
        <h3 class="text-lg font-semibold">¿Quieres una orientación rápida?</h3>
        <p class="text-sm text-slate-500 mt-1">Déjanos tus datos y te contactamos para una sesión inicial gratuita.</p>

        <form id="contactForm" class="mt-4 space-y-3">
          <input name="name" placeholder="Nombre" required class="w-full px-3 py-2 rounded-md border" />
          <input name="email" type="email" placeholder="Correo electrónico" required class="w-full px-3 py-2 rounded-md border" />
          <textarea name="message" placeholder="¿En qué te podemos ayudar?" rows="4" required class="w-full px-3 py-2 rounded-md border"></textarea>

          <div class="flex items-center justify-between">
            <button type="submit" class="px-4 py-2 rounded-lg bg-slate-900 text-white">Enviar mensaje</button>
            <small class="text-xs text-slate-500">Respuesta en menos de 48 horas</small>
          </div>
        </form>
      </aside>
    </section>

    <!-- Services -->
    <section id="services" class="py-10">
      <h3 class="text-2xl font-bold">Servicios</h3>
      <p class="text-slate-600 mt-2">Diseñados para estudiantes y recién graduados que buscan comenzar con el pie derecho.</p>

      <div class="mt-6 grid grid-cols-1 md:grid-cols-3 gap-6">
        <article class="card p-6">
          <h4 class="font-semibold">Asesoría personalizada</h4>
          <p class="text-sm text-slate-500 mt-1">Sesiones 1:1 con coaches expertos para definir objetivos, mejorar CV y preparar entrevistas.</p>
          <div class="mt-4"><a class="inline-block px-4 py-2 rounded border" href="#contact">Más información</a></div>
        </article>

        <article class="card p-6">
          <h4 class="font-semibold">Recursos para buscar empleo</h4>
          <p class="text-sm text-slate-500 mt-1">Plantillas de CV, cartas de presentación, guías por sectores y listas de empresas recomendadas.</p>
          <div class="mt-4"><a class="inline-block px-4 py-2 rounded border" href="#resources">Ver recursos</a></div>
        </article>

        <article class="card p-6">
          <h4 class="font-semibold">Desarrollo profesional</h4>
          <p class="text-sm text-slate-500 mt-1">Planes de carrera, formación en habilidades blandas y seguimiento a 3, 6 y 12 meses.</p>
          <div class="mt-4"><a class="inline-block px-4 py-2 rounded border" href="#contact">Solicitar plan</a></div>
        </article>
      </div>
    </section>

    <!-- Resources -->
    <section id="resources" class="py-10 bg-white">
      <h3 class="text-2xl font-bold">Recursos gratuitos</h3>
      <p class="text-slate-600 mt-2">Plantillas, checklists y mini-cursos para impulsar tu búsqueda.</p>

      <div class="mt-6 grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="card p-6">
          <h4 class="font-semibold">Plantillas de CV</h4>
          <p class="text-sm text-slate-500 mt-1">Descárgalas y adáptalas en minutos.</p>
          <div class="mt-4"><a class="inline-block px-4 py-2 rounded border" href="#">Descargar</a></div>
        </div>

        <div class="card p-6">
          <h4 class="font-semibold">Guía de entrevistas</h4>
          <p class="text-sm text-slate-500 mt-1">Estrategias y ejemplos prácticos.</p>
          <div class="mt-4"><a class="inline-block px-4 py-2 rounded border" href="#">Leer</a></div>
        </div>

        <div class="card p-6">
          <h4 class="font-semibold">Lista de empresas</h4>
          <p class="text-sm text-slate-500 mt-1">Empresas que suelen contratar recién graduados.</p>
          <div class="mt-4"><a class="inline-block px-4 py-2 rounded border" href="#">Explorar</a></div>
        </div>
      </div>
    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="py-10">
      <h3 class="text-2xl font-bold">Testimonios</h3>
      <p class="text-slate-600 mt-2">Historias reales de estudiantes y graduados que avanzaron en su carrera.</p>

      <div class="mt-6 grid grid-cols-1 md:grid-cols-2 gap-6">
        <div class="card p-6 flex gap-4 items-start">
          <div class="w-12 h-12 rounded-full bg-slate-100 flex items-center justify-center font-semibold">ML</div>
          <div>
            <p class="font-semibold">María López <span class="text-slate-500 font-normal">— Recién graduada, Marketing</span></p>
            <p class="text-slate-600 mt-2">"Gracias a la asesoría encontré mi primer trabajo en 2 meses. El proceso fue claro y cercano."</p>
          </div>
        </div>

        <div class="card p-6 flex gap-4 items-start">
          <div class="w-12 h-12 rounded-full bg-slate-100 flex items-center justify-center font-semibold">CJ</div>
          <div>
            <p class="font-semibold">Carlos Jiménez <span class="text-slate-500 font-normal">— Ingeniero de software</span></p>
            <p class="text-slate-600 mt-2">"Las simulaciones de entrevista me dieron la confianza que necesitaba. Muy recomendable."</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Blog -->
    <section id="blog" class="py-10 bg-white">
      <h3 class="text-2xl font-bold">Blog</h3>
      <p class="text-slate-600 mt-2">Artículos útiles para tu desarrollo profesional.</p>

      <div class="mt-6 grid grid-cols-1 md:grid-cols-3 gap-6">
        <article class="card p-6">
          <h4 class="font-semibold">Cómo adaptar tu CV a cada oferta</h4>
          <p class="text-xs text-slate-400 mt-1">10 Sep 2025</p>
          <p class="text-sm text-slate-600 mt-3">Consejos prácticos para que tu CV pase los filtros automáticos y humanos.</p>
          <div class="mt-4"><a class="inline-block px-4 py-2 rounded border" href="#">Leer artículo</a></div>
        </article>

        <article class="card p-6">
          <h4 class="font-semibold">Preguntas frecuentes en entrevistas técnicas</h4>
          <p class="text-xs text-slate-400 mt-1">21 Ago 2025</p>
          <p class="text-sm text-slate-600 mt-3">Cómo preparar respuestas claras y estructuradas para preguntas difíciles.</p>
          <div class="mt-4"><a class="inline-block px-4 py-2 rounded border" href="#">Leer artículo</a></div>
        </article>

        <article class="card p-6">
          <h4 class="font-semibold">Networking para recién graduados</h4>
          <p class="text-xs text-slate-400 mt-1">05 Jul 2025</p>
          <p class="text-sm text-slate-600 mt-3">Estrategias sencillas para empezar a construir tu red profesional desde la universidad.</p>
          <div class="mt-4"><a class="inline-block px-4 py-2 rounded border" href="#">Leer artículo</a></div>
        </article>
      </div>
    </section>

    <!-- Contact / Footer -->
    <section id="contact" class="py-12">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div>
          <h3 class="text-2xl font-bold">Contacto</h3>
          <p class="text-slate-600 mt-2">¿Tienes dudas? Escríbenos y te responderemos lo antes posible.</p>

          <div class="mt-6">
            <p class="text-sm"><strong>Teléfono:</strong> +34 600 000 000</p>
            <p class="text-sm mt-2"><strong>Email:</strong> hola@careerguide.example</p>
          </div>
        </div>

        <form class="card p-6" onsubmit="event.preventDefault(); alert('Mensaje enviado — gracias!');">
          <input required class="w-full px-3 py-2 rounded-md border" placeholder="Nombre" />
          <input required type="email" class="w-full px-3 py-2 rounded-md border mt-3" placeholder="Correo" />
          <textarea required class="w-full px-3 py-2 rounded-md border mt-3" rows="4" placeholder="Mensaje"></textarea>
          <div class="mt-4 text-right">
            <button class="px-4 py-2 rounded-lg bg-slate-900 text-white">Enviar</button>
          </div>
        </form>
      </div>
    </section>

    <footer class="py-8 text-sm text-slate-500">
      <div class="flex flex-col md:flex-row md:justify-between md:items-center gap-4">
        <div>© 2025 CareerGuide. Todos los derechos reservados.</div>
        <div class="flex gap-4">
          <a href="#">Términos</a>
          <a href="#">Privacidad</a>
        </div>
      </div>
    </footer>
  </main>

  <script>
    // Pequeño manejo del formulario de contacto del hero
    document.getElementById('contactForm')?.addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Gracias — hemos recibido tu mensaje. Te contactaremos pronto.');
      this.reset();
    });
  </script>
</body>
</html>
