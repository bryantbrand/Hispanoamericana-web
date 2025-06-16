import { Button } from "@/components/ui/button"
import { Card, CardContent, CardDescription, CardHeader, CardTitle } from "@/components/ui/card"
import { Input } from "@/components/ui/input"
import { Textarea } from "@/components/ui/textarea"
import { Badge } from "@/components/ui/badge"
import { GraduationCap, Users, BookOpen, Award, MapPin, Phone, Mail, Star, Clock, Globe } from "lucide-react"
import Image from "next/image"
import Link from "next/link"

export default function Component() {
  return (
    <div className="flex flex-col min-h-screen">
      {/* Header */}
      <header className="bg-white shadow-sm border-b">
        <div className="container mx-auto px-4 lg:px-6 h-16 flex items-center justify-between">
          <div className="flex items-center space-x-2">
            <GraduationCap className="h-8 w-8 text-emerald-600" />
            <div>
              <h1 className="text-xl font-bold text-gray-900">Institución Educativa</h1>
              <p className="text-sm text-emerald-600 font-medium">Hispanoamericana</p>
            </div>
          </div>
          <nav className="hidden md:flex items-center space-x-6">
            <Link href="#inicio" className="text-gray-700 hover:text-emerald-600 transition-colors">
              Inicio
            </Link>
            <Link href="#nosotros" className="text-gray-700 hover:text-emerald-600 transition-colors">
              Nosotros
            </Link>
            <Link href="#programas" className="text-gray-700 hover:text-emerald-600 transition-colors">
              Programas
            </Link>
            <Link href="#instalaciones" className="text-gray-700 hover:text-emerald-600 transition-colors">
              Instalaciones
            </Link>
            <Link href="#contacto" className="text-gray-700 hover:text-emerald-600 transition-colors">
              Contacto
            </Link>
          </nav>
          <Button className="bg-emerald-600 hover:bg-emerald-700">Admisiones</Button>
        </div>
      </header>

      <main className="flex-1">
        {/* Hero Section */}
        <section id="inicio" className="bg-gradient-to-r from-emerald-50 to-teal-50 py-20">
          <div className="container mx-auto px-4 lg:px-6">
            <div className="grid lg:grid-cols-2 gap-12 items-center">
              <div className="space-y-6">
                <Badge className="bg-emerald-100 text-emerald-800 hover:bg-emerald-100">
                  Excelencia Educativa desde 1985
                </Badge>
                <h1 className="text-4xl lg:text-6xl font-bold text-gray-900 leading-tight">
                  Formando líderes del <span className="text-emerald-600">futuro</span>
                </h1>
                <p className="text-xl text-gray-600 leading-relaxed">
                  En la Institución Educativa Hispanoamericana, brindamos una educación integral que combina excelencia
                  académica, valores sólidos y desarrollo personal para preparar a nuestros estudiantes para los
                  desafíos del mañana.
                </p>
                <div className="flex flex-col sm:flex-row gap-4">
                  <Button size="lg" className="bg-emerald-600 hover:bg-emerald-700">
                    Conoce más
                  </Button>
                  <Button
                    size="lg"
                    variant="outline"
                    className="border-emerald-600 text-emerald-600 hover:bg-emerald-50"
                  >
                    Solicitar información
                  </Button>
                </div>
              </div>
              <div className="relative">
                <Image
                  src="/placeholder.svg?height=500&width=600"
                  alt="Estudiantes de la Institución Educativa Hispanoamericana"
                  width={600}
                  height={500}
                  className="rounded-lg shadow-2xl"
                />
              </div>
            </div>
          </div>
        </section>

        {/* Stats Section */}
        <section className="py-16 bg-white">
          <div className="container mx-auto px-4 lg:px-6">
            <div className="grid grid-cols-2 lg:grid-cols-4 gap-8">
              <div className="text-center">
                <div className="text-3xl lg:text-4xl font-bold text-emerald-600 mb-2">38+</div>
                <p className="text-gray-600">Años de experiencia</p>
              </div>
              <div className="text-center">
                <div className="text-3xl lg:text-4xl font-bold text-emerald-600 mb-2">1,200+</div>
                <p className="text-gray-600">Estudiantes activos</p>
              </div>
              <div className="text-center">
                <div className="text-3xl lg:text-4xl font-bold text-emerald-600 mb-2">95%</div>
                <p className="text-gray-600">Tasa de graduación</p>
              </div>
              <div className="text-center">
                <div className="text-3xl lg:text-4xl font-bold text-emerald-600 mb-2">50+</div>
                <p className="text-gray-600">Docentes calificados</p>
              </div>
            </div>
          </div>
        </section>

        {/* About Section */}
        <section id="nosotros" className="py-20 bg-gray-50">
          <div className="container mx-auto px-4 lg:px-6">
            <div className="grid lg:grid-cols-2 gap-12 items-center">
              <div>
                <Image
                  src="/placeholder.svg?height=400&width=500"
                  alt="Campus de la institución"
                  width={500}
                  height={400}
                  className="rounded-lg shadow-lg"
                />
              </div>
              <div className="space-y-6">
                <h2 className="text-3xl lg:text-4xl font-bold text-gray-900">Nuestra Historia y Misión</h2>
                <p className="text-lg text-gray-600 leading-relaxed">
                  Fundada en 1985, la Institución Educativa Hispanoamericana ha sido pionera en brindar educación de
                  calidad que trasciende las fronteras tradicionales del aprendizaje.
                </p>
                <div className="space-y-4">
                  <div className="flex items-start space-x-3">
                    <Award className="h-6 w-6 text-emerald-600 mt-1" />
                    <div>
                      <h3 className="font-semibold text-gray-900">Excelencia Académica</h3>
                      <p className="text-gray-600">Programas educativos reconocidos a nivel nacional</p>
                    </div>
                  </div>
                  <div className="flex items-start space-x-3">
                    <Users className="h-6 w-6 text-emerald-600 mt-1" />
                    <div>
                      <h3 className="font-semibold text-gray-900">Comunidad Diversa</h3>
                      <p className="text-gray-600">Estudiantes de diferentes culturas y backgrounds</p>
                    </div>
                  </div>
                  <div className="flex items-start space-x-3">
                    <Globe className="h-6 w-6 text-emerald-600 mt-1" />
                    <div>
                      <h3 className="font-semibold text-gray-900">Perspectiva Global</h3>
                      <p className="text-gray-600">Preparamos ciudadanos del mundo</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>

        {/* Programs Section */}
        <section id="programas" className="py-20 bg-white">
          <div className="container mx-auto px-4 lg:px-6">
            <div className="text-center mb-16">
              <h2 className="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">Nuestros Programas Académicos</h2>
              <p className="text-xl text-gray-600 max-w-3xl mx-auto">
                Ofrecemos una amplia gama de programas diseñados para desarrollar el potencial completo de cada
                estudiante
              </p>
            </div>
            <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
              <Card className="hover:shadow-lg transition-shadow">
                <CardHeader>
                  <BookOpen className="h-12 w-12 text-emerald-600 mb-4" />
                  <CardTitle>Educación Primaria</CardTitle>
                  <CardDescription>Fundamentos sólidos para el desarrollo integral de los más pequeños</CardDescription>
                </CardHeader>
                <CardContent>
                  <ul className="space-y-2 text-sm text-gray-600">
                    <li>• Metodología lúdica y participativa</li>
                    <li>• Desarrollo de habilidades básicas</li>
                    <li>• Formación en valores</li>
                    <li>• Actividades extracurriculares</li>
                  </ul>
                </CardContent>
              </Card>

              <Card className="hover:shadow-lg transition-shadow">
                <CardHeader>
                  <Users className="h-12 w-12 text-emerald-600 mb-4" />
                  <CardTitle>Educación Secundaria</CardTitle>
                  <CardDescription>Preparación integral para la vida universitaria y profesional</CardDescription>
                </CardHeader>
                <CardContent>
                  <ul className="space-y-2 text-sm text-gray-600">
                    <li>• Bachillerato académico</li>
                    <li>• Énfasis en ciencias y humanidades</li>
                    <li>• Preparación para pruebas ICFES</li>
                    <li>• Orientación vocacional</li>
                  </ul>
                </CardContent>
              </Card>

              <Card className="hover:shadow-lg transition-shadow">
                <CardHeader>
                  <Award className="h-12 w-12 text-emerald-600 mb-4" />
                  <CardTitle>Programas Especiales</CardTitle>
                  <CardDescription>Actividades complementarias para el desarrollo integral</CardDescription>
                </CardHeader>
                <CardContent>
                  <ul className="space-y-2 text-sm text-gray-600">
                    <li>• Bilingüismo (Inglés-Español)</li>
                    <li>• Deportes y recreación</li>
                    <li>• Arte y cultura</li>
                    <li>• Tecnología e innovación</li>
                  </ul>
                </CardContent>
              </Card>
            </div>
          </div>
        </section>

        {/* Facilities Section */}
        <section id="instalaciones" className="py-20 bg-gray-50">
          <div className="container mx-auto px-4 lg:px-6">
            <div className="text-center mb-16">
              <h2 className="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">Nuestras Instalaciones</h2>
              <p className="text-xl text-gray-600 max-w-3xl mx-auto">
                Espacios modernos y equipados para brindar la mejor experiencia educativa
              </p>
            </div>
            <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
              <div className="relative group">
                <Image
                  src="/placeholder.svg?height=250&width=400"
                  alt="Aulas modernas"
                  width={400}
                  height={250}
                  className="rounded-lg shadow-md group-hover:shadow-lg transition-shadow"
                />
                <div className="absolute inset-0 bg-black bg-opacity-40 rounded-lg flex items-end p-6">
                  <div className="text-white">
                    <h3 className="text-xl font-semibold mb-2">Aulas Inteligentes</h3>
                    <p className="text-sm">Equipadas con tecnología de punta</p>
                  </div>
                </div>
              </div>
              <div className="relative group">
                <Image
                  src="/placeholder.svg?height=250&width=400"
                  alt="Laboratorios"
                  width={400}
                  height={250}
                  className="rounded-lg shadow-md group-hover:shadow-lg transition-shadow"
                />
                <div className="absolute inset-0 bg-black bg-opacity-40 rounded-lg flex items-end p-6">
                  <div className="text-white">
                    <h3 className="text-xl font-semibold mb-2">Laboratorios</h3>
                    <p className="text-sm">Ciencias, informática y idiomas</p>
                  </div>
                </div>
              </div>
              <div className="relative group">
                <Image
                  src="/placeholder.svg?height=250&width=400"
                  alt="Biblioteca"
                  width={400}
                  height={250}
                  className="rounded-lg shadow-md group-hover:shadow-lg transition-shadow"
                />
                <div className="absolute inset-0 bg-black bg-opacity-40 rounded-lg flex items-end p-6">
                  <div className="text-white">
                    <h3 className="text-xl font-semibold mb-2">Biblioteca</h3>
                    <p className="text-sm">Amplio acervo bibliográfico</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>

        {/* Testimonials Section */}
        <section className="py-20 bg-white">
          <div className="container mx-auto px-4 lg:px-6">
            <div className="text-center mb-16">
              <h2 className="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">Lo que dicen nuestras familias</h2>
            </div>
            <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
              <Card>
                <CardContent className="pt-6">
                  <div className="flex items-center mb-4">
                    {[...Array(5)].map((_, i) => (
                      <Star key={i} className="h-5 w-5 text-yellow-400 fill-current" />
                    ))}
                  </div>
                  <p className="text-gray-600 mb-4">
                    "La educación que recibe mi hija en Hispanoamericana es excepcional. Los maestros son dedicados y el
                    ambiente es muy acogedor."
                  </p>
                  <div className="flex items-center">
                    <div className="w-10 h-10 bg-emerald-100 rounded-full flex items-center justify-center mr-3">
                      <span className="text-emerald-600 font-semibold">MG</span>
                    </div>
                    <div>
                      <p className="font-semibold text-gray-900">María González</p>
                      <p className="text-sm text-gray-600">Madre de familia</p>
                    </div>
                  </div>
                </CardContent>
              </Card>

              <Card>
                <CardContent className="pt-6">
                  <div className="flex items-center mb-4">
                    {[...Array(5)].map((_, i) => (
                      <Star key={i} className="h-5 w-5 text-yellow-400 fill-current" />
                    ))}
                  </div>
                  <p className="text-gray-600 mb-4">
                    "Mis hijos han desarrollado no solo conocimientos académicos, sino también valores y habilidades
                    para la vida."
                  </p>
                  <div className="flex items-center">
                    <div className="w-10 h-10 bg-emerald-100 rounded-full flex items-center justify-center mr-3">
                      <span className="text-emerald-600 font-semibold">CR</span>
                    </div>
                    <div>
                      <p className="font-semibold text-gray-900">Carlos Rodríguez</p>
                      <p className="text-sm text-gray-600">Padre de familia</p>
                    </div>
                  </div>
                </CardContent>
              </Card>

              <Card>
                <CardContent className="pt-6">
                  <div className="flex items-center mb-4">
                    {[...Array(5)].map((_, i) => (
                      <Star key={i} className="h-5 w-5 text-yellow-400 fill-current" />
                    ))}
                  </div>
                  <p className="text-gray-600 mb-4">
                    "La preparación que recibí me permitió ingresar a la universidad de mis sueños. Siempre estaré
                    agradecida."
                  </p>
                  <div className="flex items-center">
                    <div className="w-10 h-10 bg-emerald-100 rounded-full flex items-center justify-center mr-3">
                      <span className="text-emerald-600 font-semibold">AS</span>
                    </div>
                    <div>
                      <p className="font-semibold text-gray-900">Ana Sofía</p>
                      <p className="text-sm text-gray-600">Egresada 2023</p>
                    </div>
                  </div>
                </CardContent>
              </Card>
            </div>
          </div>
        </section>

        {/* Contact Section */}
        <section id="contacto" className="py-20 bg-emerald-50">
          <div className="container mx-auto px-4 lg:px-6">
            <div className="grid lg:grid-cols-2 gap-12">
              <div>
                <h2 className="text-3xl lg:text-4xl font-bold text-gray-900 mb-6">Contáctanos</h2>
                <p className="text-lg text-gray-600 mb-8">
                  Estamos aquí para resolver todas tus dudas y acompañarte en el proceso de admisión. ¡Contáctanos hoy
                  mismo!
                </p>

                <div className="space-y-6">
                  <div className="flex items-center space-x-4">
                    <MapPin className="h-6 w-6 text-emerald-600" />
                    <div>
                      <p className="font-semibold text-gray-900">Dirección</p>
                      <p className="text-gray-600">Calle 123 #45-67, Bogotá, Colombia</p>
                    </div>
                  </div>
                  <div className="flex items-center space-x-4">
                    <Phone className="h-6 w-6 text-emerald-600" />
                    <div>
                      <p className="font-semibold text-gray-900">Teléfono</p>
                      <p className="text-gray-600">+57 (1) 234-5678</p>
                    </div>
                  </div>
                  <div className="flex items-center space-x-4">
                    <Mail className="h-6 w-6 text-emerald-600" />
                    <div>
                      <p className="font-semibold text-gray-900">Email</p>
                      <p className="text-gray-600">info@hispanoamericana.edu.co</p>
                    </div>
                  </div>
                  <div className="flex items-center space-x-4">
                    <Clock className="h-6 w-6 text-emerald-600" />
                    <div>
                      <p className="font-semibold text-gray-900">Horario de atención</p>
                      <p className="text-gray-600">Lunes a Viernes: 7:00 AM - 5:00 PM</p>
                    </div>
                  </div>
                </div>
              </div>

              <Card>
                <CardHeader>
                  <CardTitle>Solicitar Información</CardTitle>
                  <CardDescription>Completa el formulario y nos pondremos en contacto contigo</CardDescription>
                </CardHeader>
                <CardContent className="space-y-4">
                  <div className="grid grid-cols-2 gap-4">
                    <div>
                      <label className="text-sm font-medium text-gray-700 mb-2 block">Nombre</label>
                      <Input placeholder="Tu nombre" />
                    </div>
                    <div>
                      <label className="text-sm font-medium text-gray-700 mb-2 block">Apellido</label>
                      <Input placeholder="Tu apellido" />
                    </div>
                  </div>
                  <div>
                    <label className="text-sm font-medium text-gray-700 mb-2 block">Email</label>
                    <Input type="email" placeholder="tu@email.com" />
                  </div>
                  <div>
                    <label className="text-sm font-medium text-gray-700 mb-2 block">Teléfono</label>
                    <Input placeholder="Tu número de teléfono" />
                  </div>
                  <div>
                    <label className="text-sm font-medium text-gray-700 mb-2 block">Mensaje</label>
                    <Textarea placeholder="Cuéntanos en qué podemos ayudarte..." rows={4} />
                  </div>
                  <Button className="w-full bg-emerald-600 hover:bg-emerald-700">Enviar mensaje</Button>
                </CardContent>
              </Card>
            </div>
          </div>
        </section>
      </main>

      {/* Footer */}
      <footer className="bg-gray-900 text-white py-12">
        <div className="container mx-auto px-4 lg:px-6">
          <div className="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
            <div>
              <div className="flex items-center space-x-2 mb-4">
                <GraduationCap className="h-8 w-8 text-emerald-400" />
                <div>
                  <h3 className="text-lg font-bold">Institución Educativa</h3>
                  <p className="text-emerald-400 font-medium">Hispanoamericana</p>
                </div>
              </div>
              <p className="text-gray-400 text-sm">
                Formando líderes del futuro con excelencia académica y valores sólidos.
              </p>
            </div>

            <div>
              <h4 className="font-semibold mb-4">Enlaces rápidos</h4>
              <ul className="space-y-2 text-sm text-gray-400">
                <li>
                  <Link href="#inicio" className="hover:text-emerald-400 transition-colors">
                    Inicio
                  </Link>
                </li>
                <li>
                  <Link href="#nosotros" className="hover:text-emerald-400 transition-colors">
                    Nosotros
                  </Link>
                </li>
                <li>
                  <Link href="#programas" className="hover:text-emerald-400 transition-colors">
                    Programas
                  </Link>
                </li>
                <li>
                  <Link href="#contacto" className="hover:text-emerald-400 transition-colors">
                    Contacto
                  </Link>
                </li>
              </ul>
            </div>

            <div>
              <h4 className="font-semibold mb-4">Programas</h4>
              <ul className="space-y-2 text-sm text-gray-400">
                <li>Educación Primaria</li>
                <li>Educación Secundaria</li>
                <li>Bilingüismo</li>
                <li>Actividades Extracurriculares</li>
              </ul>
            </div>

            <div>
              <h4 className="font-semibold mb-4">Contacto</h4>
              <div className="space-y-2 text-sm text-gray-400">
                <p>Calle 123 #45-67</p>
                <p>Bogotá, Colombia</p>
                <p>+57 (1) 234-5678</p>
                <p>info@hispanoamericana.edu.co</p>
              </div>
            </div>
          </div>

          <div className="border-t border-gray-800 mt-8 pt-8 text-center text-sm text-gray-400">
            <p>
              &copy; {new Date().getFullYear()} Institución Educativa Hispanoamericana. Todos los derechos reservados.
            </p>
          </div>
        </div>
      </footer>
    </div>
  )
}
