# Marketizo CRM MVP Starter

Ovo je početni paket za pravi web CRM koji može da se hostuje na Vercel-u.

## Šta je uključeno

- Next.js frontend
- Lead dashboard
- Filteri: mesec, godina, tag, status, izvor
- Ručni unos leadova
- API endpoint za unos leadova iz Meta / Make / budućeg Marketizo funnel-a
- Supabase SQL šema za bazu
- Placeholder za instant notifikacije
- Dugme za poziv
- Dugme za WhatsApp

## Kako se pokreće lokalno

```bash
npm install
npm run dev
```

Otvori:

```bash
http://localhost:3000
```

## Kako ide dalje

1. Napraviti Supabase projekat
2. Pokrenuti `supabase/schema.sql`
3. Dodati env varijable iz `.env.example`
4. Deploy na Vercel
5. Povezati Make scenario: Meta Lead Ads -> Webhook URL
6. Povezati WhatsApp klik preko `wa.me`
7. Kasnije dodati pravi WhatsApp Cloud API i push notifikacije
