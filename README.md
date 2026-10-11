# Blink

A Snapchat and Telegram-style web app with sign-up and sign-in on Supabase.

## Setup
1. In Supabase, open SQL Editor and run `supabase/schema.sql`.
2. In Supabase → Authentication → Providers, keep Email enabled. Email confirmation is on by default.
3. In this repo → Settings → Pages, set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Open the Pages URL shown there.

The Supabase URL and publishable key are in `index.html`. The publishable key is designed to be public. Never put the service_role key in this repo.
