---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Mahad Berkah Ilmu
      text: Sinergi Antara Ilmu Bashirah dan Amal Shalih
      primary_action:
        text: Pelajari Lebih Lanjut
        url: https://hugoblox.com/templates/
        icon: rocket-launch
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "1M+"
          description: |
            Santri
        - statistic: "10k+"
          description: |
            Tenaga Pengajar
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Keunggulan
          text: As easy as 1, 2, 3!
          feature_icon: check
          features:
            - "Talaqqi bacaan al Qur'an sesuai panduan para ulama tajwid"
            - "Materi pelajaran langsung merujuk pada kitab-kitab turats karya para ulama ahlus-sunnah wal-jama'ah"
            - "Penekanan dalam adab (etika) pergaulan Islami, dengan harapan santri terlindungi dari pergaulan bebas"
            - Para pengajar yang berkompeten di bidangnya, lulusan ma'had dan perguruan tinggi Islam
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Get Started
            url: #features
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
- block: features
    id: features
    content:
      title: Materi Pelajaran
      text: yang Dipelajari di Mahad Berkah Ilmu
      items:
        - name: Talaqqi Al Qur'an
          icon: magnifying-glass
          description: Talaqqi Iqro, Talaqqil Al Qur'an
        - name: Tajwid & Tahfizh
          icon: bolt
          description: Tajwid (Tuhfathul-Athfal), Tahfizh juz 'Amma
        - name: Tatacara Ibadah
          icon: sparkles
          description: Fiqh Ibadah Safinatun-Najah
        - name: Tahfizh Dzikir dan Do'a
          icon: code-bracket
          description: Dari kitab Hishnul-Muslim
        - name: Kisah Nabi dan Rasul
          icon: star
          description: Dari kitab Qashashul Anbiya'
        - name: Bahasa Arab
          icon: rectangle-group
          description: Dari kitab al-Mumtaz
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Hugo Smith"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Build your future-proof website
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
