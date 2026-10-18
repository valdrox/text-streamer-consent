# text-streamer consent page

The OAuth consent page of [text-streamer](https://github.com/valdrox/text-streamer)'s account service: when Claude (or another app) asks to connect, Supabase Auth sends you here to sign in and allow it.

Built from `apps/consent` in the main repo (`npm run build -w @text-streamer/consent` with `SUPABASE_URL` and `SUPABASE_PUBLISHABLE_KEY`). The key in it is the project's publishable key, which is public by design.
