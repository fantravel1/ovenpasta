---
layout: default
title: Contact Us
description: "Get in touch with the OvenPasta team. Share recipes, report issues, or just say hello."
permalink: /contact/
---

<section class="py-16 md:py-20">
  <div class="container-narrow">
    <h1 class="text-4xl md:text-5xl font-display font-bold text-warm-900 mb-6 text-center">
      Contact Us
    </h1>
    <p class="text-xl text-warm-600 text-center max-w-2xl mx-auto mb-12">
      We'd love to hear from you. Whether you have a recipe to share, found an error, or just want to talk pasta.
    </p>

    <div class="card p-8 md:p-10">
      <form action="#" method="POST" class="space-y-6">
        <div class="grid md:grid-cols-2 gap-6">
          <div>
            <label for="name" class="block text-sm font-ui font-medium text-warm-700 mb-2">Name</label>
            <input type="text" id="name" name="name" required class="w-full px-4 py-3 rounded-lg border border-warm-300 focus:border-tomato-500 focus:ring-2 focus:ring-tomato-200 outline-none transition-colors">
          </div>
          <div>
            <label for="email" class="block text-sm font-ui font-medium text-warm-700 mb-2">Email</label>
            <input type="email" id="email" name="email" required class="w-full px-4 py-3 rounded-lg border border-warm-300 focus:border-tomato-500 focus:ring-2 focus:ring-tomato-200 outline-none transition-colors">
          </div>
        </div>

        <div>
          <label for="subject" class="block text-sm font-ui font-medium text-warm-700 mb-2">Subject</label>
          <select id="subject" name="subject" class="w-full px-4 py-3 rounded-lg border border-warm-300 focus:border-tomato-500 focus:ring-2 focus:ring-tomato-200 outline-none transition-colors">
            <option value="">Select a topic...</option>
            <option value="recipe">Share a Recipe</option>
            <option value="correction">Report an Error</option>
            <option value="question">General Question</option>
            <option value="partnership">Partnership Inquiry</option>
            <option value="other">Other</option>
          </select>
        </div>

        <div>
          <label for="message" class="block text-sm font-ui font-medium text-warm-700 mb-2">Message</label>
          <textarea id="message" name="message" rows="6" required class="w-full px-4 py-3 rounded-lg border border-warm-300 focus:border-tomato-500 focus:ring-2 focus:ring-tomato-200 outline-none transition-colors resize-none"></textarea>
        </div>

        <div class="text-center">
          <button type="submit" class="btn-primary px-8 py-3 text-lg">
            Send Message
          </button>
        </div>
      </form>
    </div>

    <div class="mt-12 text-center text-warm-600">
      <p>You can also reach us at <a href="mailto:hello@ovenpasta.com" class="text-tomato-600 hover:text-tomato-700">hello@ovenpasta.com</a></p>
    </div>
  </div>
</section>
