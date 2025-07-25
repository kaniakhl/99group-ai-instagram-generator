# 99group-ai-instagram-generator

## Overview
A lightweight, repeatable AI-based workflow to generate Instagram content for Gen-Z and millennial property seekers in Indonesia. Built using ChatGPT GPT-4.0 and DALL·E, with manual supervision.

## Objectives
- Generate weekly Instagram posts based on trending property news
- Maintain relevance for Gen-Z and millennial segments
- Optimize captions for SEO & engagement

## Tools Used
- **GPT-4.0 (via ChatGPT)**: Generate news headlines and captions  
- **DALL·E 3**: Create accompanying images  
- **Canva (optional)**: Layout final design  
- **GitHub**: Documentation repository (no custom code)

## Workflow

1. **Fetch Latest Property News**  
   Source: RSS feed (e.g., Kompas Properti, Detik Properti) or web scrape via n8n / Make
   Optional: Use Google News API

2. **Filter Top 5 News for Gen Z/Millennial**
   Use GPT-4 API or Flowise to filter for news that is:
      - Easy to relate to (e.g., rent, tiny homes, KPR, green living)
      - Emotionally engaging (e.g., problems, aspirations, tips)

3. **Generate Instagram caption for each**  
   Prompt:  
   > “Write a catchy, Gen Z-style Instagram caption with emojis, hook, and hashtags based on this news: [insert news]”

5. **Generate an image with DALL·E**  
   Prompt:  
   > “Modern Indonesian house for young and millenial, bright daylight, tropical setting, Instagram aesthetic, no text.”

6. **Auto-Schedule Post**  
   Tools: Buffer, Metricool, Later, or manual upload

7. **Save to Repo or Airtable**
   Store generated image, caption, and source link for archive or review

## Sample Output
- **Caption example**:  
  > "🏡 “Penasaran kenapa harga rumah hampir stagnan, tapi tetap jadi peluang emas?”

Di Q1 2025, indeks harga properti residensial nasional naik hanya 1,1% YoY — inflasi disesuaikan, naik 0,5% saja 
globalpropertyguide.com
.
Tapi justru ini jadi momen bagus buat beli rumah: harga belum melonjak, KPR mulai normal, dan permintaan properti kompak meningkat 0,7% YoY!

✍️ Saatnya jadi pemilik properti muda tanpa bikin kantong bolong, apalagi kalau kamu pertama kali beli rumah.

#GenZMelekProperti #InvestasiMuda #RenovasiCerdas #Properti2025"

- **Image example**: *(https://drive.google.com/file/d/1_4Yx3cTPTx6WXqbK6PM7pGCRoMgDLKkY/view?usp=sharing)*


## How to Use
1. Clone the repo  
2. Manually run prompts in ChatGPT + DALL·E weekly  
3. Copy outputs into Canva or directly upload to Instagram  
4. Repeat each week with fresh headlines

## Credits
Built for 99 Group AI Challenge (Option A)  
Workflow: Hybrid AI-human approach – no programming required
