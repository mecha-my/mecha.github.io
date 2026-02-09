<script setup>
import { Button } from '@/components/ui/button'
import { Card, CardContent, CardDescription, CardHeader, CardTitle } from '@/components/ui/card'

const openEmail = () => {
  window.location.href = 'mailto:hello@ray.computer?subject=%5BmechaCraft%5D%20I%20have%20an%20enquiry'
}
</script>

<template>
  <div class="min-h-screen bg-stone-50">
    <!-- Hero Section -->
    <section class="relative overflow-hidden bg-white">
      <div class="container mx-auto px-4 py-16 md:py-20">
        <div class="mx-auto text-center space-y-4">
          <div class="text-xs font-medium tracking-widest text-stone-500 uppercase">mecha.my</div>
          <p class="text-base text-stone-600 max-w-2xl mx-auto leading-relaxed">
            At mechaCraft, we build revenue-generating SaaS products, <br>
            AI-powered systems engineered for scale, automation, and growth.
          </p>
          <div class="pt-2">
            <Button @click="openEmail" class="rounded-full">Start a Conversation</Button>
          </div>
        </div>
      </div>
    </section>

    <!-- What We Do Section -->
    <section class="py-16">
      <div class="container mx-auto px-4">
        <div class="text-center mb-10">
          <h2 class="text-2xl font-semibold text-stone-900 mb-2">What We Do</h2>
          <p class="text-sm text-stone-600 mx-auto">
            Production-ready SaaS platforms that generate revenue from day one
          </p>
        </div>
        
        <div class="grid md:grid-cols-3 gap-4 mx-auto">
          <Card class="rounded-2xl border-stone-200 hover:shadow-md transition-shadow">
            <CardHeader class="pb-3">
              <div class="w-10 h-10 rounded-xl bg-stone-100 flex items-center justify-center mb-3">
                <span class="text-xl">🚀</span>
              </div>
              <CardTitle class="text-base font-semibold text-stone-900">SaaS Development</CardTitle>
            </CardHeader>
            <CardContent class="space-y-3">
              <p class="text-sm text-stone-600 leading-relaxed">
                Multi-tenant systems for performance and scalability.
              </p>
              <ul class="space-y-1.5 text-xs text-stone-500">
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>Subscription & billing</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>License & plan controls</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>Multi-tenant architecture</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>Payment integrations</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>Production infrastructure</span>
                </li>
              </ul>
            </CardContent>
          </Card>

          <Card class="rounded-2xl border-stone-200 hover:shadow-md transition-shadow">
            <CardHeader class="pb-3">
              <div class="w-10 h-10 rounded-xl bg-stone-100 flex items-center justify-center mb-3">
                <span class="text-xl">🤖</span>
              </div>
              <CardTitle class="text-base font-semibold text-stone-900">AI & Automation</CardTitle>
            </CardHeader>
            <CardContent class="space-y-3">
              <p class="text-sm text-stone-600 leading-relaxed">
                AI integrated into workflows as productivity multipliers.
              </p>
              <ul class="space-y-1.5 text-xs text-stone-500">
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>Workflow automation</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>LLM integrations</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>Data pipelines</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>Process automation</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>AI-native features</span>
                </li>
              </ul>
            </CardContent>
          </Card>

          <Card class="rounded-2xl border-stone-200 hover:shadow-md transition-shadow">
            <CardHeader class="pb-3">
              <div class="w-10 h-10 rounded-xl bg-stone-100 flex items-center justify-center mb-3">
                <span class="text-xl">🏢</span>
              </div>
              <CardTitle class="text-base font-semibold text-stone-900">Retail & Property</CardTitle>
            </CardHeader>
            <CardContent class="space-y-3">
              <p class="text-sm text-stone-600 leading-relaxed">
                Systems that power real-world operations.
              </p>
              <ul class="space-y-1.5 text-xs text-stone-500">
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>POS integrations</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>Loyalty systems</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>Retail CRM</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>Property management</span>
                </li>
                <li class="flex items-start gap-2">
                  <span class="text-stone-400 mt-0.5">•</span>
                  <span>Operations workflows</span>
                </li>
              </ul>
            </CardContent>
          </Card>
        </div>
      </div>
    </section>

    <!-- Products Section -->
    <section class="py-16 bg-white text-center">
      <div class="container mx-auto px-4">
        <div class="mb-10">
          <h2 class="text-2xl font-semibold text-stone-900 mb-2">Our Products</h2>
          <p class="text-sm text-stone-600 max-w-xl mx-auto">
            Production platforms serving real customers
          </p>
        </div>

        <div class="grid md:grid-cols-2 gap-4 max-w-4xl mx-auto">
          <a href="https://housemonkey.co" target="_blank" rel="noopener noreferrer" class="group">
            <Card class="h-full text-left rounded-2xl border-stone-200 hover:shadow-md transition-all hover:border-stone-300">
              <CardHeader class="space-y-3 pb-3">
                <div class="flex items-center gap-3">
                  <div class="w-10 h-10 rounded-xl bg-stone-100 flex items-center justify-center flex-shrink-0">
                    <img src="https://housemonkey.co/images/logo.svg" alt="HouseMonkey" class="w-6 h-6" />
                  </div>
                  <div>
                    <CardTitle class="text-base font-semibold text-stone-900">HouseMonkey</CardTitle>
                    <CardDescription class="text-xs">Property Management</CardDescription>
                  </div>
                </div>
              </CardHeader>
              <CardContent>
                <p class="text-sm text-stone-600 leading-relaxed">
                  Rental and property management for landlords, investors, and agencies. Tools for tenant screening, rent collection, and maintenance.
                </p>
                <div class="mt-3 flex items-center text-xs text-stone-500 group-hover:text-stone-900 transition-colors">
                  <span>housemonkey.co</span>
                  <span class="ml-1.5 group-hover:translate-x-0.5 transition-transform">→</span>
                </div>
              </CardContent>
            </Card>
          </a>

          <a href="https://rewardlah.com" target="_blank" rel="noopener noreferrer" class="group">
            <Card class="h-full text-left rounded-2xl border-stone-200 hover:shadow-md transition-all hover:border-stone-300">
              <CardHeader class="space-y-3 pb-3">
                <div class="flex items-center gap-3">
                  <div class="w-10 h-10 rounded-xl bg-stone-100 flex items-center justify-center text-xl flex-shrink-0">
                    🛍️
                  </div>
                  <div>
                    <CardTitle class="text-base font-semibold text-stone-900">RewardLah</CardTitle>
                    <CardDescription class="text-xs">Loyalty & Retail CRM</CardDescription>
                  </div>
                </div>
              </CardHeader>
              <CardContent>
                <p class="text-sm text-stone-600 leading-relaxed">
                  Loyalty points and CRM for SMEs. Retain customers and drive repeat purchases through intelligent reward systems and insights.
                </p>
                <div class="mt-3 flex items-center text-xs text-stone-500 group-hover:text-stone-900 transition-colors">
                  <span>rewardlah.com</span>
                  <span class="ml-1.5 group-hover:translate-x-0.5 transition-transform">→</span>
                </div>
              </CardContent>
            </Card>
          </a>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="py-16 bg-white">
      <div class="container mx-auto px-4">
        <div class="max-w-2xl mx-auto text-center space-y-4">
          <h2 class="text-2xl font-semibold text-stone-900">Work With Us</h2>
          <p class="text-sm text-stone-600">
            We partner with founders, SMEs, and operators building scalable systems.
          </p>
          <div class="pt-2">
            <Button @click="openEmail" class="rounded-full">Get In Touch</Button>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-stone-200 bg-stone-50">
      <div class="container mx-auto px-4 py-10">
        <div class="text-center space-y-2">
          <h4 class="text-xs font-semibold tracking-widest text-stone-900">MECHACRAFT SDN. BHD.</h4>
          <p class="text-xs text-stone-500">(Company No. 202501021879 (1623292-T))</p>
          <p class="text-xs text-stone-500 leading-relaxed">
            1-19-03, Menara Bangkok Bank, Laman Sentral Berjaya,<br>
            No. 105, Jalan Ampang, 50450 Kuala Lumpur, W.P. Kuala Lumpur.
          </p>
          <p class="text-xs text-stone-500">TIN: C60102050020</p>
        </div>
      </div>
    </footer>
  </div>
</template>