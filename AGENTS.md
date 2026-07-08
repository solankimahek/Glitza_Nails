# Glitza Nails — Agent Notes

This is a **Vite + TanStack Router + Supabase** project for Glitza Nails, a luxury handmade press-on nail brand.

## Key Conventions
- Routes live in `src/routes/`. File-based routing via TanStack Router.
- Admin routes are under `src/routes/_authenticated/admin/`.
- Admin access is gated by Supabase RLS + `has_role()` function.
- The admin email `solankimahek2511@gmail.com` is auto-promoted to admin on signup via a DB trigger.
- Styles use Tailwind CSS utility classes + custom design tokens (see `src/styles.css`).
- Supabase client is at `src/integrations/supabase/client.ts`.
