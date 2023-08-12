npx create-next-app@latest --ts --use-npm supabase-nextjs

cd supabase-nextjs

npm install @supabase/supabase-js


Create .env.local

NEXT_PUBLIC_SUPABASE_URL=YOUR_SUPABASE_URL

NEXT_PUBLIC_SUPABASE_ANON_KEY=YOUR_SUPABASE_ANON_KEY


npm install @supabase/auth-helpers-nextjs @supabase/supabase-js

npm install @supabase/auth-ui-react @supabase/auth-ui-shared

npm run dev
