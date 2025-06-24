<template>
  <div>
    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-blue-600 to-indigo-700">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-24">
        <div class="text-center">
          <Icon name="heroicons:user-circle" class="w-20 h-20 text-white mx-auto mb-8" />
          <h1 class="text-4xl sm:text-5xl md:text-6xl font-bold text-white mb-6">
            Bo Clifton
            <span class="block text-blue-200">Software Developer & Architect</span>
          </h1>
          <p class="text-xl text-blue-100 mb-8 max-w-3xl mx-auto">
            Over a decade of experience in modern AI software and solution design. 
            Passionate about building innovative, scalable solutions that drive business value.
          </p>
          <div class="flex flex-col sm:flex-row gap-4 justify-center">
            <a 
              href="#contact"
              class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md text-blue-600 bg-white hover:bg-gray-50 transition-colors"
            >
              <Icon name="heroicons:envelope" class="w-5 h-5 mr-2" />
              Get In Touch
            </a>
            <a 
              href="#experience"
              class="inline-flex items-center px-6 py-3 border border-white text-base font-medium rounded-md text-white hover:bg-white hover:bg-opacity-10 transition-colors"
            >
              <Icon name="heroicons:briefcase" class="w-5 h-5 mr-2" />
              View Experience
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-24 bg-white">
      <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
          <h2 class="text-3xl font-bold text-gray-900 mb-4">
            About Me
          </h2>
          <p class="text-lg text-gray-600 max-w-2xl mx-auto">
            Passionate about creating intelligent solutions that transform how businesses operate
          </p>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
          <div>
            <h3 class="text-2xl font-semibold text-gray-900 mb-6">
              Driving Innovation Through Technology
            </h3>
            <p class="text-gray-600 mb-6">
              As a software developer and architect with over a decade of experience, I specialize in designing and implementing 
              cutting-edge AI solutions that solve complex business challenges. My expertise spans the full software development 
              lifecycle, from initial concept to production deployment.
            </p>
            <p class="text-gray-600 mb-6">
              I'm passionate about leveraging modern technologies to create scalable, maintainable solutions that drive real 
              business value. Whether it's architecting cloud-native applications, implementing machine learning models, or 
              leading development teams, I bring a strategic approach to every project.
            </p>
            <div class="flex flex-wrap gap-2">
              <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-sm font-medium">AI & Machine Learning</span>
              <span class="bg-green-100 text-green-800 px-3 py-1 rounded-full text-sm font-medium">Cloud Architecture</span>
              <span class="bg-purple-100 text-purple-800 px-3 py-1 rounded-full text-sm font-medium">Solution Design</span>
              <span class="bg-orange-100 text-orange-800 px-3 py-1 rounded-full text-sm font-medium">Team Leadership</span>
            </div>
          </div>
          <div class="bg-gray-50 rounded-lg p-8">
            <h4 class="text-lg font-semibold text-gray-900 mb-4">Core Expertise</h4>
            <ul class="space-y-3">
              <li class="flex items-center">
                <Icon name="heroicons:check-circle" class="w-5 h-5 text-green-500 mr-3" />
                <span class="text-gray-700">Modern AI & Machine Learning Solutions</span>
              </li>
              <li class="flex items-center">
                <Icon name="heroicons:check-circle" class="w-5 h-5 text-green-500 mr-3" />
                <span class="text-gray-700">Enterprise Software Architecture</span>
              </li>
              <li class="flex items-center">
                <Icon name="heroicons:check-circle" class="w-5 h-5 text-green-500 mr-3" />
                <span class="text-gray-700">Cloud-Native Application Design</span>
              </li>
              <li class="flex items-center">
                <Icon name="heroicons:check-circle" class="w-5 h-5 text-green-500 mr-3" />
                <span class="text-gray-700">Cross-Functional Team Leadership</span>
              </li>
              <li class="flex items-center">
                <Icon name="heroicons:check-circle" class="w-5 h-5 text-green-500 mr-3" />
                <span class="text-gray-700">Strategic Technology Planning</span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-24 bg-gray-50">
      <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
          <h2 class="text-3xl font-bold text-gray-900 mb-4">
            Professional Experience
          </h2>
          <p class="text-lg text-gray-600 max-w-2xl mx-auto">
            Over a decade of delivering innovative solutions across diverse industries
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <!-- AI Solutions -->
          <div class="bg-white rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow">
            <div class="w-12 h-12 bg-blue-100 rounded-lg flex items-center justify-center mb-4">
              <Icon name="heroicons:cpu-chip" class="w-6 h-6 text-blue-600" />
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-3">
              AI & Machine Learning
            </h3>
            <p class="text-gray-600 mb-4">
              Designing and implementing intelligent systems that automate complex processes and provide actionable insights.
            </p>
            <ul class="text-sm text-gray-600 space-y-1">
              <li>• Natural Language Processing</li>
              <li>• Computer Vision Solutions</li>
              <li>• Predictive Analytics</li>
              <li>• Model Deployment & MLOps</li>
            </ul>
          </div>

          <!-- Software Architecture -->
          <div class="bg-white rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow">
            <div class="w-12 h-12 bg-green-100 rounded-lg flex items-center justify-center mb-4">
              <Icon name="heroicons:building-library" class="w-6 h-6 text-green-600" />
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-3">
              Software Architecture
            </h3>
            <p class="text-gray-600 mb-4">
              Creating scalable, maintainable architectures that support business growth and technological evolution.
            </p>
            <ul class="text-sm text-gray-600 space-y-1">
              <li>• Microservices Design</li>
              <li>• API Strategy & Development</li>
              <li>• Database Architecture</li>
              <li>• Performance Optimization</li>
            </ul>
          </div>

          <!-- Cloud Solutions -->
          <div class="bg-white rounded-lg p-6 shadow-sm hover:shadow-md transition-shadow">
            <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center mb-4">
              <Icon name="heroicons:cloud" class="w-6 h-6 text-purple-600" />
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-3">
              Cloud Solutions
            </h3>
            <p class="text-gray-600 mb-4">
              Leveraging cloud platforms to build resilient, scalable solutions with optimal cost-efficiency.
            </p>
            <ul class="text-sm text-gray-600 space-y-1">
              <li>• Cloud Migration Strategy</li>
              <li>• Infrastructure as Code</li>
              <li>• DevOps & CI/CD</li>
              <li>• Security & Compliance</li>
            </ul>
          </div>
        </div>

        <!-- Years of Experience -->
        <div class="mt-16 bg-white rounded-lg p-8 shadow-sm">
          <div class="text-center">
            <h3 class="text-2xl font-bold text-gray-900 mb-4">10+ Years of Excellence</h3>
            <p class="text-lg text-gray-600 mb-8">
              Consistently delivering high-impact solutions that drive business transformation
            </p>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
              <div class="text-center">
                <div class="text-3xl font-bold text-blue-600 mb-2">50+</div>
                <div class="text-gray-600">Projects Delivered</div>
              </div>
              <div class="text-center">
                <div class="text-3xl font-bold text-green-600 mb-2">25+</div>
                <div class="text-gray-600">AI Solutions Deployed</div>
              </div>
              <div class="text-center">
                <div class="text-3xl font-bold text-purple-600 mb-2">100%</div>
                <div class="text-gray-600">Client Satisfaction</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-24 bg-white">
      <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
          <h2 class="text-3xl font-bold text-gray-900 mb-4">
            Let's Build Something Amazing Together
          </h2>
          <p class="text-lg text-gray-600 max-w-2xl mx-auto">
            Ready to discuss your next project? I'd love to hear about your vision and explore how we can bring it to life.
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <div class="bg-gray-50 rounded-lg p-8">
            <h3 class="text-xl font-semibold text-gray-900 mb-6">Get In Touch</h3>
            <div class="space-y-4">
              <div class="flex items-center">
                <Icon name="heroicons:envelope" class="w-5 h-5 text-blue-600 mr-3" />
                <a href="mailto:bo@boclifton.com" class="text-gray-700 hover:text-blue-600 transition-colors">
                  bo@boclifton.com
                </a>
              </div>
              <div class="flex items-center">
                <Icon name="simple-icons:linkedin" class="w-5 h-5 text-blue-600 mr-3" />
                <a href="https://linkedin.com" target="_blank" rel="noopener noreferrer" class="text-gray-700 hover:text-blue-600 transition-colors">
                  LinkedIn Profile
                </a>
              </div>
              <div class="flex items-center">
                <Icon name="simple-icons:github" class="w-5 h-5 text-blue-600 mr-3" />
                <a href="https://github.com" target="_blank" rel="noopener noreferrer" class="text-gray-700 hover:text-blue-600 transition-colors">
                  GitHub Portfolio
                </a>
              </div>
            </div>
          </div>

          <div class="bg-blue-50 rounded-lg p-8">
            <h3 class="text-xl font-semibold text-gray-900 mb-6">What I Can Help With</h3>
            <ul class="space-y-3">
              <li class="flex items-start">
                <Icon name="heroicons:check-circle" class="w-5 h-5 text-green-500 mr-3 mt-0.5" />
                <span class="text-gray-700">AI strategy and implementation consulting</span>
              </li>
              <li class="flex items-start">
                <Icon name="heroicons:check-circle" class="w-5 h-5 text-green-500 mr-3 mt-0.5" />
                <span class="text-gray-700">Software architecture design and review</span>
              </li>
              <li class="flex items-start">
                <Icon name="heroicons:check-circle" class="w-5 h-5 text-green-500 mr-3 mt-0.5" />
                <span class="text-gray-700">Technology leadership and team mentoring</span>
              </li>
              <li class="flex items-start">
                <Icon name="heroicons:check-circle" class="w-5 h-5 text-green-500 mr-3 mt-0.5" />
                <span class="text-gray-700">Cloud migration and modernization</span>
              </li>
              <li class="flex items-start">
                <Icon name="heroicons:check-circle" class="w-5 h-5 text-green-500 mr-3 mt-0.5" />
                <span class="text-gray-700">Full-stack development projects</span>
              </li>
            </ul>
          </div>
        </div>

        <div class="mt-12 text-center">
          <a 
            href="mailto:bo@boclifton.com"
            class="inline-flex items-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-blue-600 hover:bg-blue-700 transition-colors"
          >
            <Icon name="heroicons:envelope" class="w-5 h-5 mr-2" />
            Start a Conversation
          </a>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
// Set page meta for SEO
definePageMeta({
  title: 'Bo Clifton - Software Developer & Architect',
  description: 'Bo Clifton is a software developer and architect with over a decade of experience in modern AI software and solution design.'
})

// Set head for SEO
useHead({
  title: 'Bo Clifton - Software Developer & Architect',
  meta: [
    { 
      name: 'description', 
      content: 'Bo Clifton is a software developer and architect with over a decade of experience in modern AI software and solution design. Specializing in AI solutions, cloud architecture, and team leadership.' 
    },
    {
      name: 'keywords',
      content: 'software developer, software architect, AI solutions, machine learning, cloud architecture, technology leadership'
    },
    {
      property: 'og:title',
      content: 'Bo Clifton - Software Developer & Architect'
    },
    {
      property: 'og:description',
      content: 'Over a decade of experience in modern AI software and solution design. Passionate about building innovative, scalable solutions.'
    },
    {
      property: 'og:type',
      content: 'website'
    }
  ]
})
</script>
